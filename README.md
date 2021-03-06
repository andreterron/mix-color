# mix-color

## Install

```sh
$ npm install --save mix-color
```

## Use

```js
import mix from 'mix-color';

mix('#fff', '#000', 0.5);
mix('#ff0000', 'rgba(0,0,0,0.3)', 0.2);
mix('#ff0000', '#ffffff88', 0.1);
```

## build and publish npm

```sh
node scripts/build.lib.js && cd dist && npm publish --access public
```

## Test List

```snap
// Jest Snapshot v1, https://goo.gl/fbAQLP

exports[`alphaColor to alphaColor: mix('#336699', '#ff880000') 1`] = `"rgba(255, 136, 0, 0)"`;

exports[`alphaColor to alphaColor: mix('#336699', '#ff880000', 0.5) 1`] = `"rgba(153, 119, 76, 0.5)"`;

exports[`alphaColor to alphaColor: mix('#336699', 'rgba(255,128,0,0.5)', 0.5) 1`] = `"rgba(153, 115, 76, 0.25)"`;

exports[`alphaColor to alphaColor: mix('#33669988', '#ff880000') 1`] = `"rgba(255, 136, 0, 0)"`;

exports[`alphaColor to alphaColor: mix('#33669988', '#ff880000', 0.5) 1`] = `"rgba(153, 119, 76, 0.2667)"`;

exports[`alphaColor to alphaColor: mix('#33669988', 'rgba(255,128,0,0.5)', 0.5) 1`] = `"rgba(153, 115, 76, 0.1333)"`;

exports[`alphaColor to alphaColor: mix('mix('rgba(255,128,0,1)', 'rgba(128,128,0,0.8)', 0.2) 1`] = `"rgba(229, 128, 0, 0.64)"`;

exports[`alphaColor to alphaColor: mix('rgba(255,128,0,0)', 'rgba(0,128,0,1)', 0.2) 1`] = `"rgba(204, 128, 0, 0.8)"`;

exports[`alphaColor to alphaColor: mix('rgba(255,128,0,0.5)', 'rgba(0,128,0,0.5)', 1) 1`] = `"rgba(0, 128, 0, 0.25)"`;

exports[`alphaColor to alphaColor: mix('rgba(255,128,0,1)', 'rgba(0,128,0,-0.3)', 0.2) 1`] = `"rgba(255, 128, 0, 0)"`;

exports[`alphaColor to alphaColor: mix('rgba(255,128,0,1)', 'rgba(0,128,0,0)', 0.2) 1`] = `"rgba(204, 128, 0, 0.8)"`;

exports[`alphaColor to alphaColor: mix('rgba(255,128,0,1)', 'rgba(0,128,0,0.3)', 0.2) 1`] = `"rgba(204, 128, 0, 0.24)"`;

exports[`alphaColor to alphaColor: mix('rgba(255,128,0,1)', 'rgba(0,128,0,0.3)', 0.2) 2`] = `"rgba(0, 128, 0, 1)"`;

exports[`alphaColor to alphaColor: mix('rgba(255,128,0,1)', 'rgba(0,128,0,0.3)', 0.2) 3`] = `"rgba(255, 128, 0, 0.3)"`;

exports[`alphaColor to alphaColor: mix('rgba(255,128,0,1)', 'rgba(255,128,0,0.5)', 0.5) 1`] = `"rgba(255, 128, 0, 0.25)"`;

exports[`alphaColor to alphaColor: mix('rgba(255,128,0,1)', 'rgba(255,128,0,3)', 4) 1`] = `"rgba(255, 128, 0, 1)"`;

exports[`color to color: mix('#336699', '#f80') 1`] = `"rgba(255, 136, 0, 1)"`;

exports[`color to color: mix('#336699', '#f80', 0.2) 1`] = `"rgba(91, 108, 122, 1)"`;

exports[`color to color: mix('#336699', '#f80', 0.5) 1`] = `"rgba(153, 119, 76, 1)"`;

exports[`color to color: mix('#336699', '#f80', 1) 1`] = `"rgba(255, 136, 0, 1)"`;

exports[`color to color: mix('#336699', '#ff8800') 1`] = `"rgba(255, 136, 0, 1)"`;

exports[`color to color: mix('#336699', '#ff8800', 0.2) 1`] = `"rgba(91, 108, 122, 1)"`;

exports[`color to color: mix('#336699', '#ff8800', 0.5) 1`] = `"rgba(153, 119, 76, 1)"`;

exports[`color to color: mix('#336699', '#ff8800', 1) 1`] = `"rgba(255, 136, 0, 1)"`;

exports[`color to color: mix('#336699', 'rgb(255,128,0)', 1) 1`] = `"rgba(255, 128, 0, 1)"`;

exports[`color to color: mix('#336699', 'rgba(255,128,0,1)') 1`] = `"rgba(255, 128, 0, 1)"`;

exports[`color to color: mix('#336699', 'rgba(255,128,0,1)', 0.2) 1`] = `"rgba(91, 107, 122, 1)"`;

exports[`color to color: mix('#336699', 'rgba(255,128,0,1)', 0.5) 1`] = `"rgba(153, 115, 76, 1)"`;

exports[`color to color: mix('#336699', 'rgba(255,128,0,1)', 1) 1`] = `"rgba(255, 128, 0, 1)"`;

exports[`color to color: mix('rgb(0,128,0)', 'rgb(255,128,0)', 1) 1`] = `"rgba(255, 128, 0, 1)"`;



```
