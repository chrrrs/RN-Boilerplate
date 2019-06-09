# RN Boilerplate

This is a simple React Native boilerplate that utilises common package which are used in the development of apps. Folder structure is optimized for readability and linking purposes. Ships with Jest for testing.

`.keep` files located in the `src` folder structure can be deleted after adding real files to the folders. They are only there to keep the basic folder structure in place.

## Installation

Use the package manager [yarn](https://yarnpkg.com/en/) to install.

```bash
$ yarn add
```

This boilerplate uses the following packages:
1. [Jest](https://jestjs.io/)
2. [React Navigation](https://reactnavigation.org/)
3. [React Native SVG](https://github.com/react-native-community/react-native-svg)
4. [React Native SVG Transformer](https://github.com/kristerkari/react-native-svg-transformer)
5. [Async Storage](https://github.com/react-native-community/react-native-async-storage#readme)
6. [Status Bar Height](https://github.com/ovr/react-native-status-bar-height#readme)

## Clone Project

To use this boilerplate you first need to change the application name.
This can be easily done by utilising the [react-native-rename](https://github.com/junedomingo/react-native-rename#readme) package.

First globally install the rename package

``` bash
$ yarn global add react-native-rename
or
$ npm install react-native-rename -g
```
Then clone the project to your local dev environment

```
$ git clone https://github.com/iamchrisjp/RN-Boilerplate.git <newName>
```

If changes have been made, switch to new branch
> better to have back-up

```
git checkout -b rename-app
```

#### Usage
```
react-native-rename <newName>
```

> With custom Bundle Identifier (Android only. For iOS, please use Xcode)

```
react-native-rename <newName> -b <bundleIdentifier>
```

## Running application

### iOS

`$ react-native run-ios`

### Android

`$ react-native run-android`

### Run bundler and development server

`$ react-native start`

## Testing

Test are performed through Jest. All tests are served from the root folder `__tests__`

### Check for changes

`$ yarn test`

### Update snapshots

`$ yarn test -u`

## Default linting

> coming soon ...
