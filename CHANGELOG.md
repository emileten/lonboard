# Changelog

## [0.3.0] - 2023-11-07

### New Features

- Save widget to standalone HTML file by @kylebarron in https://github.com/developmentseed/lonboard/pull/199
- Support for rendering inside Visual Studio Code
- Allow customized picking radius by @kylebarron in https://github.com/developmentseed/lonboard/pull/212
- New example notebooks
- Automatically downcast data types in `from_geopandas` by @kylebarron in https://github.com/developmentseed/lonboard/pull/195

### Fixed

- Allow pandas series as accessor to FloatAccessor by @kylebarron in https://github.com/developmentseed/lonboard/pull/208
- Raise error when creating class with unknown keyword argument by @kylebarron in https://github.com/developmentseed/lonboard/pull/209
- fix tooltip rendering when not hovering over an object by @kylebarron in https://github.com/developmentseed/lonboard/pull/215

**Full Changelog**: https://github.com/developmentseed/lonboard/compare/v0.2.0...v0.3.0

## [0.2.0] - 2023-11-01

### Breaking Changes

- Layers no longer render a map object. Instead, pass one or more layer instances into a `lonboard.Map` and display that.

### New Features

- Support multiple layers on a single map.
- Tooltip with data information on hover.
- Allow hex string color input to ColorAccessor.
- Versioned documentation website
- New examples
- Experimental API to change map height

### Fixed

- Fix handling of 3d coordinates by @kylebarron in https://github.com/developmentseed/lonboard/pull/160
- Improved validation error messages by @kylebarron in https://github.com/developmentseed/lonboard/pull/161

### New Contributors

- @chrisgervang made their first contribution in https://github.com/developmentseed/lonboard/pull/150

**Full Changelog**: https://github.com/developmentseed/lonboard/compare/v0.1.2...v0.2.0

## [0.1.2] - 2023-10-24

- _Actually_ update `@geoarrow/deck.gl-layers` to version 0.2.0, whoops 😅

## [0.1.1] - 2023-10-23

- Updates to `@geoarrow/deck.gl-layers` version 0.2.0:
  - Fixed MultiPolygon rendering
  - Fixed rendering of polygons with holes.
  - Polygon rendering is roughly 35% faster.

## [0.1.0] - 2023-10-17

- Initial public release.
- Initial support for `ScatterplotLayer`, `PathLayer`, and `SolidPolygonLayer`.
