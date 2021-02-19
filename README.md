# parse-rn-document

#### React-Native
> 出现问题时的常用方法

* 重新安装APP ``npx react-native run-ios``
* 清除缓存 `` react-native start --reset-cache  ``


#### RN 引入 Parse 
* [doc](http://docs.parseplatform.org/js/guide/#getting-started)



* 示例代码

```

const Parse = require('parse/react-native.js');
//appid and  javascriptKey is required only if you have it on server.
Parse.initialize("4CqI88sgCyhVozqeNldH7bfrNx3mUxXxf2SRnHjZ", "ln3sCP4oWq8E1TvWPHVRvBbM5VMlUbF1XkxIxZvK");
Parse.serverURL = 'https://parseapi.back4app.com/'


Parse.setAsyncStorage(AsyncStorage);

const GameScore = Parse.Object.extend("GameScore");
const gameScore = new GameScore();

gameScore.set("score", 123321);
gameScore.set("playerName", "deng Plott");
gameScore.set("cheatMode", false);

gameScore.save()
.then((gameScore) => {
  // Execute any logic that should take place after the object is saved.
  alert('New object created with objectId: ' + gameScore.id);
}, (error) => {
  // Execute any logic that should take place if the save fails.
  // error is a Parse.Error with an error code and message.
  alert('22Failed to create new object, with error code: ' + error.message);
});


```
