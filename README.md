[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/owner/my-element)
# \<video-view\>
The video view, search play all urls form youtube, vimeo or url with extensions .mp4 or webm. for example:

### Youtube video
```html 
<video-view url="https://www.youtube.com/watchv=G1TS_5ck0nw"></video-view>
```
### Vimeo video
```html
<video-view 
url="https://vimeo.com/213100067" 
width="100%">
</video-view>
```
### Others video
```html
<video-view url="https://www.html5rocks.com/en/tutorials/video/basics/devstories.webm" 
height="200px">
</video-view>
```
# To Use
Import the component
```html
<link rel="import" href="../video-view.html">
```
Use the tag component
```html
<video-view url="url-video" height="height-box" width="width-box"></video-view>
```

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="video-view.html">
    <video-view url="https://www.youtube.com/watchv=G1TS_5ck0nw"></video-view>
  </template>
</custom-element-demo>
```
-->
```html
<video-view></video-view>
```

## Properties
property | Description | Default
----------------|-------------|----------
`url`      | Video url | 
`width` | width of the video box    | `320px`
`height`      | height of the video box    | `400px`

### Styling

The following custom properties and mixins are available for styling:

Custom property | Description | Default
----------------|-------------|----------
`--video-height`      | height of the video box | `400px`
`--video-width` | width of the video box     | `320px`
## TestComponent
### Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing video-view Element

```
$ polymer serve
```