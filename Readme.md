*This repository is a mirror of the [component](http://component.io) module [component/select](http://github.com/component/select). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-select`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# select

  Select utility

## Installation

    $ component install component/select

## API

### select(array, fn)

  Filter `array` returning a new array:

```js
users = select(users, function(user){
  return user.age > 20;
});
```

# License

  MIT
