# iOS shim for HTML 5 drag'n'drop

This is a very basic demo to show that it still works on ios 8.4
```html
<script>
var iosDragDropShim = { enableEnterLeave: true }
</script>
<script src="vendor/ios-drag-drop.js"></script>
```

## Shim behaviour

- all drag events, with `dragenter`, `dragover` and `dragleave` enabled via config flag
- creates a partially transparent drag image based on the dragged element

## Thanks

To the [amazing contributors](https://github.com/timruffles/ios-html5-drag-drop-shim/graphs/contributors) who've provided massive extensions and fixes to the original.

<a href="http://twitter.com/rem">@rem</a> - who created the original demo used to demo this shim's
drop-in nature.

## License

[MIT License](LICENSE)
