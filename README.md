# Tilelive Download Example

An example showing how we can use tilelive to copy from a TileJSON source to an MBTiles database

## To Use

1) Install [Node.js](http://nodejs.org).

2) Clone the `tilelive-download-example` repository OR download and extract the zip file.

3) In a command prompt or terminal window, `cd` to the `tilelive-download-example` directory.

4) Run `npm install` to install the dependencies.

5) Run `node index.js` to run the download script.

## Customize

Use the example TileJSON file `aerialImagery2013.tilejson` as a template for using a different tiled map service. Rename the `src` and `dst` variables in `index.js` to your new filenames.

## Don't Be Evil

* Adhere to map service usage restrictions and licenses.

* Limit `bounds` and `maxzoom` settings in your TileJSON file to only the areas you need.

## Licensing
Copyright 2015 Nick Peihl

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [license.txt](https://raw.githubusercontent.com/npeihl/tilelive-download-example/master/LICENSE.txt) file.
