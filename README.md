# iOS shim for HTML 5 drag'n'drop

This is a very basic demo to show that the shim still works on ios 8.4.1

#Running the Demo
Once you have cloned repo.
Run a simple http server rooted in the demo directory.
You can use what a node, python, ruby what ever is your flavor.
Once you get it up and running, point your ios device at it and you should see that drag and drop essentially works.
It looks like there is something up with the way that ios 8.4.1 is parsing the dom/css.


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
