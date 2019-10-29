# react-native-key-mapper

## Getting started

`$ npm install react-native-key-mapper --save`

### Mostly automatic installation

`$ react-native link react-native-key-mapper`

### Manual installation


#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.reactlibrary.KeyMapperPackage;` to the imports at the top of the file
  - Add `new KeyMapperPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-key-mapper'
  	project(':react-native-key-mapper').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-key-mapper/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-key-mapper')
  	```


## Usage
```javascript
import KeyMapper from 'react-native-key-mapper';

// TODO: What to do with the module?
KeyMapper;
```
