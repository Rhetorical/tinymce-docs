## encoding

This option allows you to get XML escaped content out of TinyMCE. By setting this option to "xml", posted content will be converted to an XML string escaping characters such as <, >, ", and & to <, >, ", and &. This option is disabled by default.

An example of this setting is as follows:

```js
tinymce.init({
    encoding: 'xml'
});
```