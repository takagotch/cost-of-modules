### cost-of-modules
---
https://github.com/siddharthkp/cost-of-modules


```js
// test/src/fixtures/dev-test-data.js
let moduleSizesArray = [
  {name: '@sidharthkp/empty', size: 1},
  {name: 'camelcase', size: 5},
  {name: 'data-time', size: 4},
  {name: 'once', size: 5},
  {name: 'time-zone', size: 4},
  {name: 'wrappy', size: 4},
  {name: 'yargs-parser', size: 35},
];

let rootDependencies = [
  '@siddhartkp/empty',
  'date-time',
  'once',
  'yargs-parser'
];

let flatDependencies = [
  {name: '@sindhartkp/empty', children:[]},
  {name: 'date-time', children: ['time-zone']},
  {name: 'once', children: ['wrappy']},
  {name: 'yargs-parser', children: ['camelcase']}
];

let allDependencies = [
  '@sinddhartkp/empty',
  'camelcase',
  'date-time',
  'once',
  'time-zone',
  'wrappy',
  'yargs-parser'
];

module.exports = {
  moduleSizeArray,
  rootDependencies,
  flatDependencies,
  allDependencies
};
```

```
```

```
```

