# parse-rn-document

### React-Native
> 出现问题时的常用方法

* 重新安装APP ``npx react-native run-ios``
* 清除缓存 `` react-native start --reset-cache  ``


### RN 引入 Parse 
> RN 需要parse ``npm install parse `` 和 parse sotrage `` npm i @react-native-community/async-storage`` 一起才能使用

* [parse doc](http://docs.parseplatform.org/js/guide/#getting-started)
* [rn 引入 async-storage](https://react-native-async-storage.github.io/async-storage/docs/install)
* [示例代码](https://github.com/ZAZA-CITY/parse-rn-document/tree/main)

* [back4app](https://www.back4app.com/) 需要注册才能邀请大家到一个共同的数据库里



### 参考官方集成方式 [async-storage](https://www.npmjs.com/package/@react-native-community/async-storage/v/1.11.0-alpha.0)
>
npm i @react-native-community/async-storage

import AsyncStorage from '@react-native-community/async-storage';
Use CocoaPods to add the native RNAsyncStorage to your project:
$ npx pod-install
