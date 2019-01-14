# react-native-baidu-ocr

## Getting started

`$ npm install react-native-baidu-ocr --save`

### Mostly automatic installation

`$ react-native link react-native-baidu-ocr`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-baidu-ocr` and add `RNBaiduOcr.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNBaiduOcr.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.reactlibrary.RNBaiduOcrPackage;` to the imports at the top of the file
  - Add `new RNBaiduOcrPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-baidu-ocr'
  	project(':react-native-baidu-ocr').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-baidu-ocr/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-baidu-ocr')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNBaiduOcr.sln` in `node_modules/react-native-baidu-ocr/windows/RNBaiduOcr.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Baidu.Ocr.RNBaiduOcr;` to the usings at the top of the file
  - Add `new RNBaiduOcrPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNBaiduOcr from 'react-native-baidu-ocr';

// TODO: What to do with the module?
RNBaiduOcr;
```
  