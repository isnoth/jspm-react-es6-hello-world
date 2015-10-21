## jspm React ES6 Hello World
A "Hello World" application that uses jspm, React, Flux, Bootstrap, SASS, and
ES6.

### Installation
- Run `npm install`,
- Run `jspm install`,
- Run `npm run dev-server`,
- Observe *Hello, world!* text on browser!

### Development
- `jspm-server` will auto refresh the page whenever a file changes,
so you don't need to do anything in order to see your `JS` changes.
- You can also bundle your `JS` files by running `npm run css-builder`.
- In order to revert back to using source files for `JS`, simply run
`npm run css-unbuilder`.
- In order to apply `SASS` changes on the fly, simply run  `npm run css-watcher`
alongside with `npm run dev-server`. The watcher will compile final `main.css`
file.
- If you prefer compiling the css file yourself, simply run
`npm run css-builder` instead.
