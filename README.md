# ember-cli-one-script

**[ember-cli-one-script is built and maintained by DockYard, contact us for expert Ember.js consulting](https://dockyard.com/ember-consulting)**.

## Installation
`ember install ember-cli-one-script`

## Usage

This addon combines your `vendor.js` and `<your-app-name>.js` into a single
file called `app.js`.

You also need to update your `app/index.html`:

```html
<!-- change the following -->
<script src="{{rootURL}}assets/vendor.js"></script>
<script src="{{rootURL}}assets/my-project.js"></script>
<!-- to -->
<script async src="{{rootURL}}assets/app.js"></script>
```

## Want to help?

Please do! We are always looking to improve this library. Please see our
[Contribution Guidelines](https://github.com/dockyard/ember-cli-one-script/blob/master/CONTRIBUTING.md)
on how to properly submit issues and pull requests.

## Legal

[DockYard](http://dockyard.com/), Inc. &copy; 2016

[@dockyard](http://twitter.com/dockyard)

[Licensed under the MIT license](http://www.opensource.org/licenses/mit-license.php)
