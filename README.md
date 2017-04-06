# HackerNews Share Button

The HackerNews Share Button web component provides a simple and customizable
interface for sharing URLs directly to HackerNews.

* Automatically uses the URL, title and description of the page when present
* Allows you to override the URL and text to share to HackerNews.
* Allows you to configure the display with your own text and icons.
* When combined with `<share-button>` element, it will automatically bind to the
  data from it's host component and be embedded in the share control.

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/owner/my-element)

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="hackernews-share-button.html">
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <script src="hackernews-share-button.js"></script>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<hackernews-share-button></hackernews-share-button>
```

## Customize the UI

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="hackernews-share-button.html">
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <script src="hackernews-share-button.js"></script>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<hackernews-share-button>HackerNews Button</hackernews-share-button>
```

## Add an image

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="hackernews-share-button.html">
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <script src="hackernews-share-button.js"></script>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<hackernews-share-button href="https://test.com"><img src="https://storage.googleapis.com/material-icons/external-assets/v4/icons/svg/ic_share_black_24px.svg"></hackernews-share-button>
```

## Customize the URL to share
<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="hackernews-share-button.html">
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <script src="hackernews-share-button.js"></script>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<hackernews-share-button href="https://test.com"></hackernews-share-button>
```

## Customize the text to share

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="hackernews-share-button.html">
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <script src="hackernews-share-button.js"></script>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<hackernews-share-button text="Testing attribute">Attribute Text Test</hackernews-share-button>
```


## The full 9 yards
<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="hackernews-share-button.html">
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <script src="hackernews-share-button.js"></script>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<hackernews-share-button href="https://test.com" text="Testing URL attribute">Attribute and URL Test</hackernews-share-button>
```