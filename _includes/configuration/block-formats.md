## block_formats

List of formats to be displayed under `formatselect` dropdown. Each item in the list should be specified in a form of: `title=block` and separated by semi-colon.

**Type:** `String`

**Default Value:** `'Paragraph=p;Heading 1=h1;Heading 2=h2;Heading 3=h3;Heading 4=h4;Heading 5=h5;Heading 6=h6;Preformatted=pre'`

##### Example

```js
tinymce.init({
  selector: 'textarea',  // change this value according to your html
  block_formats: 'Paragraph=p;Header 1=h1;Header 2=h2;Header 3=h3'
});
```
