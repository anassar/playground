# Deep playground

Deep playground is an interactive visualization of neural networks, written in TypeScript using d3.js.
We use GitHub issues for tracking new requests and bugs. Your feedback is highly appreciated!

**If you'd like to contribute, be sure to review the [contribution
guidelines](CONTRIBUTING.md).**

## Development

To run the visualization locally you just need a server to serve all the files from the `dist` directory. You can run `npm install` then `npm run serve` if you don't have one handy. To see the visualization, visit `http://localhost:8080/` on your browser.

Install Node.js.

`git clone https://github.com/anassar/playground.git`

`cd playground`

`npm run build`

`cd dist`

`npm install`

`npm run serve-watch`

It will automatically open `http://localhost:8080/` in your browser.

When developing, use `npm run serve-watch`. This will start a static server and also watchers to automatically compile the TypeScript, HTML and CSS files
whenever they change.

To produce a minified JavaScript file for production, run `npm run build`.

To push to production: `git subtree push --prefix dist origin gh-pages`.

This is not an official Google product.
