# clone-date [![Support this project][donate-now]][paypal-donations]

Clone date objects.

## Installation

```sh
$ npm i --save clone-date
```

## Example

```js
const cloneDate = require("clone-date");

var d = new Date(1989, 11, 21);

// Clone the d object
var c = cloneDate(d);

console.log(d);
// => Thu Dec 21 1989 00:00:00 GMT+0200 (EET)

console.log(c);
// => Thu Dec 21 1989 00:00:00 GMT+0200 (EET)

console.log(c === d);
// => false
```

## Documentation

### `cloneDate(date)`
Clones a date object.

#### Params
- **Date** `date`: The date object to clone.

#### Return
- **Date** The cloned date object.

## How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].

## Where is this library used?
If you are using this library in one of your projects, add it in this list. :sparkles:

## License

[MIT][license] © [Ionică Bizău][website]

[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(http%3A%2F%2Fionicabizau.net)&year=2015#license-mit
[website]: http://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md