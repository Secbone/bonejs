# Cabjs

[![Build Status][travis-image]][travis-url]

A framework to draw canvas with Babel

## Usage

```
var ret = CabJS.RectClass.extend({
    x: 0,
    y: 0,
    width: 20,
    height: 100,
    color: "#000",
    keyframe: function() {
        this.x += 1;
        this.y += 0.5;
    }
});
CabJS.start("mycanvas");
```

## License

MIT

[travis-image]: https://travis-ci.org/Secbone/cabjs.svg?branch=master
[travis-url]: https://travis-ci.org/Secbone/cabjs
