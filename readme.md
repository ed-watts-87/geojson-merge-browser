# geojson-merge-browser
Allows use of Mapbox [geojson-merge](https://github.com/mapbox/geojson-merge) in the browser.

# Install #
#### Dependencies

* Browserify: `$ npm install -g browserify`

**_You can:_**
1. Use geojson-merge.js from the repo :smile:
2. Build
  * Clone this repo
  * `$ npm install`
  * `$ npm run build`
  * The latest version of gejson-merge for the browser is ready to use!

# Usage #
1. Include the source via HTML ```<script>``` tags
```html
<script src='path/to/geojson-merge.js'></script>
```
2. In your JavaScript
```javascript
var merged = merge([featureCollection1, featureCollection2...])
```
