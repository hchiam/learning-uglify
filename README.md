# Learning UglifyJS

Just one of the things I'm learning. <https://github.com/hchiam/learning>

`uglify-js`: <https://github.com/mishoo/UglifyJS2#uglifyjs-3>

`uglify-es` for ES6: <https://github.com/mishoo/UglifyJS2/tree/harmony#uglify-es>

```bash
npm install uglify-es -g
uglifyjs input.js -o output.js -m -c
```

You can set this in your .bash_profile:

```bash
function ugly() { uglifyjs "$1" -o "$2" -m -c; }
```

And then you can type less in CLI:

```bash
ugly input.js output.js
```
