# parse-rn-document

### React-Native
> 出现问题时的常用方法

* 重新安装APP ``npx react-native run-ios``
* 清除缓存 `` react-native start --reset-cache  ``


### RN 引入 Parse 
> RN 需要parse ``npm install parse `` 和 parse sotrage `` npm i @react-native-community/async-storage`` 一起才能使用

* [doc](http://docs.parseplatform.org/js/guide/#getting-started)
* [rn 引入 async-storage](https://react-native-async-storage.github.io/async-storage/docs/install)
* [示例代码](https://github.com/ZAZA-CITY/parse-rn-document/tree/main)

* [back4app](https://www.back4app.com/) 需要注册才能邀请大家到一个共同的数据库里



### async-storage
>
npm i @react-native-community/async-storage
or
yarn add @react-native-community/async-storage
Link the dependency (you may not have to do this if you are using 0.60+ as it has Autolinking)

react-native link @react-native-community/async-storage
Then you import it like this, and use it as before.

import AsyncStorage from '@react-native-community/async-storage';
