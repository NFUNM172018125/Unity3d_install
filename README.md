## Unity3d_install
#### 安装Unity3D的基本操作
#### 首先安装Unity3d开发平台
* 安装UnitySetup64-5.6.2f1，依照提示安装即可
* 关闭防火干墙和安装好的Unity，安装UnityStandardAssetsSetup-5.6.2f1
* 然后安装UnitySetup-Android-Support-for-Editor-5.6.2f1.exe

#### 然后安装JAVA开发平台
* 安装jdk-8u144-windows-i586_8.0.1440.1(切记不要使用中文作为文件名)

#### 配置环境
* 在电脑属性或设置中找到环境变量
* 新建用户变量，变量名"JAVA_HOME"，变量值D:jdk（即JDK的安装路径）

![配置环境截图](https://github.com/NFUNM172018125/Unity3d_install/blob/master/images/peizhihuanjing.png)
* 编辑变量名"Path"，在原变量值的最后面加上 %JAVA_HOME%\bin之后点击确定
* 设置完成后验证是否成功安装JAVA，出现java版本号即安装成功

![验证Java](https://github.com/NFUNM172018125/Unity3d_install/blob/master/images/cmd_yanzhengJava.png)

#### 安装安卓开发包
* 下载解压缩SDK开发包（软件：android-sdk_r24.4.1-windows）
* 在开发包中找到SDK manger.exe，点击安装
* 资源更新完成，点击install 17 packages进行下载，然后选择Android SDK License -> accept license -> install，大约需半小时。

![安装安卓开发包](https://github.com/NFUNM172018125/Unity3d_install/blob/master/images/Android.png)

#### 配置Android开发环境
* 打开unity，在edit下找到Preferences
* 在Preferences中找到External Tools中，点击SDK、JDK中的点击Browse,选择SDK（安卓开发平台的路径）与JDK（Java的路径）

![选择SDK&JDK路径](https://github.com/NFUNM172018125/Unity3d_install/blob/master/images/sdk%26jdk%20lujing.png)
* 在files中找到build setting，切换到安卓平台，然后点击 switch platform ，点击add open scen新建场景
* 点击 player sitting，修改 other name中的 package name 将里面的内容 xxx.xxx.xx任意修改，然后点击build

![设置player sitting](https://github.com/NFUNM172018125/Unity3d_install/blob/master/images/peizhiAndroidhuanjing.png)

![设置player sitting](https://github.com/NFUNM172018125/Unity3d_install/blob/master/images/peizhiAndroidhuanjing2.png)
* 修改完成后，点击build，添加文件名，选择路径，打包成apk文件
* 打包完成后，可在夜神模拟器中使用

#### 录屏演示成品
[录屏演示](https://pan.baidu.com/s/17o0GXlVnhLulhREXEvtmEA)
**提取码：id15**

