# battleships-ui

The UI for the Battleships smart contract developed within the Blockchain Bootcamp

* `develop` [![CircleCI](https://circleci.com/gh/industrieco/battleships-ui/tree/develop.svg?style=svg)](https://circleci.com/gh/industrieco/battleships-ui/tree/develop) [codecov badge]
* `master` [![CircleCI](https://circleci.com/gh/industrieco/battleships-ui/tree/master.svg?style=svg)](https://circleci.com/gh/industrieco/battleships-ui/tree/master) [codecov badge

## Development

* Simple Redux / React front end built off the `react-create-app` base.

### Development Prerequisites

* [NodeJS](htps://nodejs.org), version 9.8+ (I use [`nvm`](https://github.com/creationix/nvm) to manage Node versions — `brew install nvm`.)
* [create-react-app](https://github.com/facebook/create-react-app)

### Initialisation

    npm install

### Testing

#### Standalone

    npm test

or with code coverage (when there is code to test)

    npm test -- --coverage

### Linting

We provide the following linting options

* `npm run lint` — to lint the Javascript.

## Contributing

Please see the [contributing notes](CONTRIBUTING.md).
