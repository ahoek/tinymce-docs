## browser_spellcheck

One of the several spell checking options developers have available is to use the browser's native spell checker. `browser_spellcheck` handles this behavior.

**Type:** `Boolean`

**Default Value:** `false`

**Possible Values:** `true`, `false`

```js
tinymce.init({
  selector: 'textarea',  // change this value according to your HTML
  browser_spellcheck: true
});
```

For more information about spell checking in TinyMCE see [this page]({{ site.baseurl }}/get-started/spell-checking/) in the Get Started guide.
