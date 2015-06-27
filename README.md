# primitive-quad

[![stable](http://badges.github.io/stability-badges/dist/stable.svg)](http://github.com/badges/stability-badges)

Creates an indexed quad mesh (two triangles), with normals and UVs. It sits on the XY plane with `Z=0`, and positions ranging from `-1.0` to `1.0`.

## Usage

[![NPM](https://nodei.co/npm/primitive-quad.png)](https://www.npmjs.com/package/primitive-quad)

#### `mesh = quad([scale])`

Creates a new indexed quad along the XY plane, with an optional `scale` number (defaults to 1).

`scale` can also be an `[x, y]` array to scale each axes independently.

The vertices are in counter-clockwise order, the UV origin is top-left (0 - 1 range), and the normals are negative along the Z axis.

## License

MIT, see [LICENSE.md](http://github.com/glo-js/primitive-quad/blob/master/LICENSE.md) for details.
