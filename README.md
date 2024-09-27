# theatrixx-angular-design-package

To test locally:
`cd go/to/angular-package/`
`npm link`
`npm run watch`

in an other terminal:
`cd go/to/test/folder/`
`npm link @theatrixx123/angular-package`

import the package style in your scss file (after @use "@angular/material" as mat):
`@use "@theatrixx123/angular-package";`

or

import the style in your angular.json
`"styles": [ "node_modules/@theatrixx123/angular-package/dist/index.css", "src/styles.scss"],`

Start your angular application
