# atom-shell-692

Test case for <https://github.com/atom/atom-shell/issues/692>.

1. `npm install`
2. `./node_modules/.bin/apm install .`
3. `~/Downloads/atom-shell-v0.16.3-darwin-x64/Atom.app/Contents/MacOS/Atom .`

When the window is refreshed, the following error is logged and the canary text is left:

> "Uncaught Error: Module did not self-register.", source: module.js (355)
