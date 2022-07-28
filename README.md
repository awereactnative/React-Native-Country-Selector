# React-Native-Country-Selector

# Introduction
React Native Countries v1.0.2 will provide you directly native countries list. The names of the countries come with their flags.

# Demo 

![video__1_](https://user-images.githubusercontent.com/86215353/181410816-a286c9d6-7fb4-4879-897f-b74c0c5fd0b9.gif)


# Installation
```
npm install --save react-native-country-picker-modal
```

# Example
```js

import * as React from 'react';
import { View, StyleSheet } from 'react-native';
import Constants from 'expo-constants';
import CountryPicker from 'react-native-country-picker-modal';

export default class App extends React.Component {
  render() {
    return (
      <View style={styles.container}>
        <CountryPicker 
          withEmoji
        />
      </View>
    );
  }
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    justifyContent: 'center',
    alignItems: 'center',
    paddingTop: Constants.statusBarHeight,
    backgroundColor: '#ecf0f1',
    padding: 8,
  },
});

```

# Tutorial

Coming Soon...
