
####一.安装配置

#####1.第一步
```
git clone https://github.com/jiangqqlmj/GaGaMall.git
```
#####2.第二步
```
cd GaGaMall
```
#####3.第三步
```
npm install
```
#####4.第四步
```
1.运行Android版本
Mac OS X:react-native run-android  or Windows OS:react-native start and react-native run-android
2.运行iOS版本
Mac OS X:react-native run-ios or  xcode open project and run project
```
####二.套餐教程
[1.[RN实战-嘎嘎商城]之仿快递时间轴布局实现(订单状态)](http://www.lcode.org/?p=1855)</br>
[2.[RN实战-嘎嘎商城]之轻松实现Tab底部菜单导航栏切换效果-Android/iOS双适配](http://www.lcode.org/?p=1857)</br>
[3.[RN实战-嘎嘎商城]之商家详情界面布局分析与实现](http://www.lcode.org/?p=1865)</br>

####三.运行效果
#####整体效果
![个人中心](./screenshot/demo_center.gif) 
![城市选择](./screenshot/1.jpeg) 
![订单列表](./screenshot/2.jpeg) 
![订单详情1](./screenshot/3.jpeg) 
![订单详情2](./screenshot/4.jpeg) 
![订单状态](./screenshot/5.jpeg) 
![订单结果](./screenshot/6.jpeg) 
![商品列表](./screenshot/7.jpeg) 
![商家详情](./screenshot/8.jpeg) 

####四.打包方法
#####1.Android版本
```
1.签名key以及release签名信息已配置
2.cd GaGaMall
3.cd android && ./gradlew assembleRelease
4.上述命令执行完毕,在android/app/build/outputs/apk目录下面生成app-release.apk
```

####五.安装包下载
#####[1.Android版本](./apks/app-release.apk)
