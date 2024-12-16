This little project explores the use of the async-tree library's [BrowserFileTree](https://weborigami.org/async-tree/BrowserFileTree.html) class to enable a "Download this site" button that saves a website to local files.

This tiny sample site defines `.keys.json` files to comply with the [JSON Keys](https://weborigami.org/async-tree/jsonkeys.html) protocol, allowing a site's resources to be programmatically enumerated. For this trivial example the `.keys.json` files have been created by hand. For a typical site they would be generates with the [site:jsonKeys](https://weborigami.org/builtins/site/jsonkeys) function.

This demo uses the [showDirectoryPicker](https://developer.mozilla.org/en-US/docs/Web/API/Window/showDirectoryPicker) method which, as of December 2024, is only implemented in Chrome, Edge, and Opera.
