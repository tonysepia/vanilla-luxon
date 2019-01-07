# vanilla-Luxon

[![MIT License][license-image]][license]  [![PRs welcome][contributing-image]][contributing-url]

vanilla-Luxon is a library of prototype extentions that allow luxon objects to be used with components that expect 'vanilla' JS Date

```js
jsDate = new Date('2019-01-04T21:15:53.436Z')
jsDate.getTime() // --> 1546636553436

luxonDate = luxon.DateTime.fromISO('2019-01-04T21:15:53.436Z')
luxonDate.getTime() // --> 1546636553436
```

## How to contribute
 * Bind a luxon object to a component that expects a JavaScript date (i.e. uib-datepicker)
 * Open the developer console and look for an error like 'a.getTime() is not a function'
 * Raise a PR or open an Issue
 * I will add a prototype extention for luxon that would make a luxon object behave a bit more like JavaScript Date

## Install

Simply include vanilla-luxon.js after importing luxon

[license-image]: http://img.shields.io/badge/license-MIT-blue.svg
[license]: license.txt

[contributing-url]: https://github.com/tonysepia/vanilla-luxon
[contributing-image]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg
