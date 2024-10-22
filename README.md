# theatrixx-angular-design-package

To test locally:
`cd go/to/frontend-framework/`
`npm link`
`npm run watch`

in an other terminal:
`cd go/to/test/folder/`
`npm link @theatrixx/frontend-framework`

import the package style in your scss file (after @use "@angular/material" as mat):
`@use "@theatrixx/frontend-framework";`

or

import the style in your angular.json
`"styles": [ "node_modules/@theatrixx/frontend-framework/dist/index.css", "src/styles.scss"],`

Start your angular application

## Installation

Make sure you already installed the @theatrixx/theatrixx-design package

`npm install git+https://github.com/theatrixx/theatrixx-angular-design-package.git`

import the style in your angular.json

`"styles": [ "node_modules/@theatrixx/frontend-framework/dist/index.css", ...],`
