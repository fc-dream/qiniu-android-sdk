qiniu-android-sdk
=================

Qiniu Resource (Cloud) Storage SDK for Android  http://docs.qiniu.com/

## 声明

此项目代码完全基于七牛云存储官方源码

参考文档：[七牛云存储 Android SDK 使用指南](https://github.com/qiniu/android-sdk/tree/develop/docs)

项目来源：[https://github.com/qiniu/android-sdk](https://github.com/qiniu/android-sdk)

## 说明

由于七牛android-sdk提供的demo没有生成token的代码，比如上传图片必须根据AccessKey / SecretKey生成UploadToken, 而官方是建议生成token的过程放在服务端，但是如果你非要在客户端生成token，那么这个项目就提供了客户端生成token的算法。

## 使用

在con.qiniu.config.Conf中把ACCESS_KEY, SECRET_KEY, BUCKET_NAME改为你自己七牛账号对应的即可。
