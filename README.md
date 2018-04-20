# xcode-support-device-sdk
下载Xcode支持的平台版本
地址:https://pan.baidu.com/s/1dFaAqzf
下载后的结果如下:




拷贝版本到Xcode的DeviceSupport目录

将自己需要支持的版本拷贝到DeviceSupport目录

“/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport”



修改SDKSettings.plist文件
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS.sdk/SDKSettings.plist  
DefaultProperties -> DEPLOYMENT_TARGET_SUGGESTE 该数组中添加 6.0 6.1 7.0 7.1


如果遇到权限问题,参考下面的地址

http://blog.csdn.net/lizitao/article/details/39475103


大功告成,现在就可以在"Deployment Target"中选择需要支持的最低平台了

