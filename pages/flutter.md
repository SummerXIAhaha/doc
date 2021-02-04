### mac安装flutter

#### 1. 添加环境变量
```
在.bash_profile文件中添加
export PUB_HOSTED_URL=https://pub.flutter-io.cn
export FLUTTER_STORAGE_BASE_URL=https://storage.flutter-io.cn
```  

#### 2. 下载flutter安装包 
下载地址 [国内](https://github.com/flutter/flutter/releases)


#### 3. 解压安装包并添加flutter环境变量地址
```
.bash_profile文件添加环境变量
export PATH=`安装包所在位置`/flutter/bin:$PATH
```

#### 4. 运行 flutter doctor
1. android-licenses not accepted
```
命令行运行，一直Y回车即可
flutter doctor --android-licenses
```

2.  CocoaPods installed but not initialized.
```
安装1.7.5版本
sudo gem uninstall cocoapods
sudo gem install cocoapods -v 1.7.5
pod setup
```

3. Flutter plugin not installed; this adds Flutter specific functionality.
Dart plugin not installed; this adds Dart specific functionality
```
Andriod Studio -> Preferences -> Plugins -> search Dart/Flutter -> install Dart

配置dart sdk路径

```