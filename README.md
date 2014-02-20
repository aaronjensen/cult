# cult [![NPM version](https://badge.fury.io/js/cult.png)](http://badge.fury.io/js/cult)

cult is a no-brainer tool that detects `gulpfile` extension and calls your local `gulp` with the corresponding `--require` option.

It supports `gulpfile.js`, `gulpfile.coffee` and `gulpfile.ls`.

## Usage

Use cult as you would use gulp.

## Example

```bash
# gulpfile.coffee
$ cult <task> <othertask>
```

Will call:

```bash
$ gulp <task> <othertask> --require coffee-script/register
```

## Install

```bash
$ npm install -g gulp cult
```

## Contribute

Missing a language? Fork and create a pull request.

## See also

[Using CoffeeScript for gulpfile](https://github.com/gulpjs/gulp/blob/master/docs/recipes/using-coffee-script-for-gulpfile.md)

## License

MIT


