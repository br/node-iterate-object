<!---------------------------------------------------------------------------->
<!-- STOP, LOOK & LISTEN!                                                   -->
<!-- ====================                                                   -->
<!-- Do NOT edit this file directly since it's generated from a template    -->
<!-- file, using https://github.com/IonicaBizau/node-blah                   -->
<!--                                                                        -->
<!-- If you found a typo in documentation, fix it in the source files       -->
<!-- (`lib/*.js`) and make a pull request.                                  -->
<!--                                                                        -->
<!-- If you have any other ideas, open an issue.                            -->
<!--                                                                        -->
<!-- Please consider reading the contribution steps (CONTRIBUTING.md).      -->
<!-- * * * Thanks! * * *                                                    -->
<!---------------------------------------------------------------------------->

# iterate-object [![Donate now][donate-now]][paypal-donations]

A convenient way to iterate objects.

## Installation

```sh
$ npm i iterate-object
```

## Example

```js
// Dependencies
var IterateObject = require("iterate-object");

// Iterate this object
IterateObject({
    name: "Bob"
  , age: 42
}, function (name, value) {
    console.log(name, value);
});
// => "name", "Bob"
// => "age", 42

```

## Documentation

### `IterateObject(obj, fn)`
Iterates an object. Note the object field order may differ.

#### Params
- **Object** `obj`: The input object.
- **Function** `fn`: A function that will be called with the current name and value.

#### Return
- **Function** The `IterateObject` function.

## How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].

## License
[KINDLY][license] © [Ionică Bizău][website]–The [LICENSE](/LICENSE) file contains
a copy of the license.

[license]: http://ionicabizau.github.io/kindly-license/?author=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica@gmail.com%3E&year=2015
[contributing]: /CONTRIBUTING.md
[website]: http://ionicabizau.net
[docs]: /DOCUMENTATION.md
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=MG98D7NPFZ3MG
[donate-now]: http://i.imgur.com/jioicaN.png