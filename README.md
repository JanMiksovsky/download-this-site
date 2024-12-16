This little project explores the use of the async-tree library's [BrowserFileTree](https://weborigami.org/async-tree/BrowserFileTree.html) class to enable a "Download this site" button that saves a website to local files.

[Demo](https://download-this-site.netlify.app/)

This demo uses the [showDirectoryPicker](https://developer.mozilla.org/en-US/docs/Web/API/Window/showDirectoryPicker) method which, as of December 2024, is only implemented in Chrome, Edge, and Opera.

The demo relies on `.keys.json` files to comply with the [JSON Keys](https://weborigami.org/async-tree/jsonkeys.html) protocol, allowing a site's resources to be programmatically enumerated.
