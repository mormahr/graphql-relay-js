Contributing
============

After cloning this repo, ensure dependencies are installed by running:

```sh
yarn
```

GraphQL Relay is written in ES6 using [Babel](http://babeljs.io/), widely
consumable JavaScript can be produced by running:

```sh
yarn run build
```

Once `npm run build` has run, you may `import` or `require()` directly from
node.

The full test suite can be evaluated by running:

```sh
yarn test
```

While actively developing, we recommend running

```sh
yarn run watch
```

in a terminal. This will watch the file system run lint, tests, and type
checking automatically whenever you save a js file.

To lint the JS files and type interface checks run `yarn run lint`.
