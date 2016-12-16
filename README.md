# react-native-color-picker

React Native implementation of color picker for both Android and iOS.

![](preview_android.png | height=500)
![](preview_iphone.png | height=500)

* [x] works both in controlled and uncontrolled way
TODO img

## Getting started
Install the color picker
```
npm install react-native-color-picker --save
```
And use it in your application
```
import { ColorPicker } from 'react-native-color-picker'
...
    <ColorPicker
      onColorSelected={color => alert(`Color selected: ${color}`)}
      style={{flex: 1}}
    />
```
Color picker will use space ...

## API

## Limitations
* Does not work well within `ScrollView` due to touch event interference.

## Thanks
Our implementation was inspired by [Android Holo ColorPicker](https://github.com/LarsWerkman/HoloColorPicker)
