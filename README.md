# decryptor

Migrate from npm to yarn3 (#49)
* Migrate from npm to yarn

This makes the install pass without extra flags, since yarn allows
unresolvable peer dependencies where npm does not. The real answer to
that misalignment would be to stop depending on the unmaintained
react-hyperscript, which is restricted to react < 17.

* update package metadata

* update bundle.js

* *****************

## To run:Add commentMore actions

`npm start`
`yarn start`

## To build:

`npm run build`
`yarn build`

Then just include `bundle.js` in an HTML file.
