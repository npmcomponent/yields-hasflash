*This repository is a mirror of the [component](http://component.io) module [yields/hasflash](http://github.com/yields/hasflash). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yields-hasflash`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# hasflash

  Whether or not the browser has flash plugin enabled.

## Installation

    $ component install yields/hasflash

## API

#### hasflash()

checks the navigator plugins, navigator mime types and
then tries to construct a new `ActiveXObject` with `ShockwaveFlash`.

if all above fail the function returns `false`.

```javascript
hasflash();
// > boolean
```


## License

  MIT
