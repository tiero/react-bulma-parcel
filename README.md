# React template with Bulma CSS and Parcel


## 🏗 Scaffold your project 


* Install dev dependencies

```sh
$ yarn init
$ yarn add --dev tsdx tslib typescript sass parcel-bundler husky bulma react react-dom @types/react @types/react-dom @types/jest push-dir cpx
```

* Pull down the template in a different folder

```
$ git clone https://github.com/tiero/react-bulma-parcel.git
```

* Copy the follwing keys from the `package.json` file in the `react-bulma-parcel` folder to your project

```json
"engines": {},
"scripts": {},
"prettier": {},
"husky": {},
"browserslist": []
```

* Copy the `public`, `src` and `test` folder to your project

```
$ cp -R react-bulma-parcel/src myproject
$ cp -R react-bulma-parcel/test myproject
$ cp -R react-bulma-parcel/public myproject
```

* Copy the `tsconfig.json` file to your project

```
$ cp react-bulma-parcel/tsconfig.json myproject
```


## 🖥 Local Development

Below is a list of commands you will probably find useful.

### `yarn serve`

Runs the project in development/watch mode. Your project will be rebuilt upon changes. Error messages are pretty printed and formatted for compatibility VS Code's Problems tab. Your library will be rebuilt if you make edits.

### `yarn bundle`

Bundles the package to the `dist` folder.

### `yarn test`

Runs the test watcher (Jest) in an interactive mode.
By default, runs tests related to files changed since the last commit.

### `yarn deploy`

Deploy to Github Pages pushing the `dist` directory to remote `gh-pages` branch 


