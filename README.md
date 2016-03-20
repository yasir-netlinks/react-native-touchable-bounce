# react-native-touchable-bounce

React Native Touchable Bounce component.

<img src="https://cloud.githubusercontent.com/assets/2464966/13904982/de81a4ae-eeb2-11e5-93d5-797ba1758a23.gif" width="300" />

## Installation

```bash
$ npm install react-native-touchable-bounce --save
```

## Usage

Simply `require('react-native-touchable-bounce')` and use just like any other `Touchable*` component.

```js
var React = require('react-native');
var { Text, View } = React;
var TouchableBounce = require('react-native-touchable-bounce');

var Example = React.createClass({
  render() {
    return (
      <View>
        <TouchableBounce onPress={() => console.log('pressed')}>
          <Text>Click me</Text>
        </TouchableBounce>
      </View>
    );
  }
});
```

## Running example

Start the packager by doing:

```bash
$ cd ./example && npm start
```

This step is required to run packager so that it will look into src folder for our TouchableBounce component
