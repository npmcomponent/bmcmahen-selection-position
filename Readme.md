*This repository is a mirror of the [component](http://component.io) module [bmcmahen/selection-position](http://github.com/bmcmahen/selection-position). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/bmcmahen-selection-position`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# selection-position

  small wrapper to determine the current position of the window selection

## Installation

  Install with [component(1)](http://component.io):

    $ component install bmcmahen/selection-position

## Example

```javascript
var position = require('selection-position');
var rect = position();
// rect.top, rect.height, etc.
```

## License

  MIT
