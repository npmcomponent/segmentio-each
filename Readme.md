*This repository is a mirror of the [component](http://component.io) module [segmentio/each](http://github.com/segmentio/each). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/segmentio-each`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# each

  Array / object / string iteration utility.

## Installation

    $ component install component/each

## API

### each(array, fn[, ctx])

  Iterate an array:

```js
each([1,2,3], function(num, i){
  
})
```

  Optionally pass a context object:

```js
each([1,2,3], function(num, i){

}, this)
```

### each(object, fn[, ctx])

  Iterate an object's key / value pairs:

```js
each(conf, function(key, val){
  
})
```

  Iterate an array-ish object (has numeric `.length`):

```js
each(collection, function(val, i){
  
})
```

### each(string, fn[, ctx])

  Iterate a string's characters:

```js
each('hello', function(c, i){
  
})
```

# License

  MIT
