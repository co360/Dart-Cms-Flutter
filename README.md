# Dart-Cms-Flutter
这是一个使用flutter技术开发的Dart-Cms的安卓客户端

## 免责申明
> 本项目仅供学习参考，请勿用于任何商业、非法用途。由此带来的法律责任，本人概不承担！

## chewie播放修改，参考这位大佬
[链接地址](https://www.jianshu.com/p/a9105d748533) ,首先他说的文件位置并不对，应该是给ChewieController传递参数MaterialControls，然后MaterialControls里面则是需要修改的东西，也就是大佬的修改内容。关于视频标题，你需要自己想办法传递进去。树是死的，人是活的。自己想办法。

## 预览
<p align="center">
    <img width="380" src="https://cdn.jsdelivr.net/gh/abcd498936590/pic@master/img/dart-cms-flutter-1.png" />
    <img width="380" src="https://cdn.jsdelivr.net/gh/abcd498936590/pic@master/img/dart-cms-flutter-2.png" />
    <img width="380" src="https://cdn.jsdelivr.net/gh/abcd498936590/pic@master/img/dart-cms-flutter-3.png" />
    <img width="380" src="https://cdn.jsdelivr.net/gh/abcd498936590/pic@master/img/dart-cms-flutter-4.png" />
    <img src="https://cdn.jsdelivr.net/gh/abcd498936590/pic@master/img/dart-cms-flutter-5.png" />
</p>

## Dart-Cms-Manage（后台）

[后台管理系统部分(使用vue全家桶)](https://github.com/abcd498936590/Dart-Cms-Manage)

## Dart-Cms（完整项目）

[完整Dart-Cms项目](https://github.com/abcd498936590/Dart-Cms)


## 项目结构

``` bash
├─module                     // 对依赖包的修改都放到这里
│   │
│   └──CustomControls.dart  // chewie播放器自定义ui
│
├─components                 // 公共的一些组件
│
├─schema                     // json解析类，模型
│
├─utils                      // 工具函数
│   │
│   ├──api.dart             // 所有的ajax请求
│   │
│   ├──cache.dart           // 关于app缓存的
│   │
│   ├──loading.dart         // loading封装
│   │
│   ├──config.dart          // 配置，请求地址，app名称，uniqueKey等
│   │
│   ├──request.dart         // dio的封装，网络请求
│   │
│   └──tools.js             // 工具方法
│
├─views                      // 所有的页面
│
├─main.dart                  // 主入口文件
│
├─router.dart                // 所有的路由配置
```

## 捐助一下失业的我
<p align="center">
    <img width="300" src="https://cdn.jsdelivr.net/gh/abcd498936590/pic@master/img/alipay.jpg" />
    <img width="300" src="https://cdn.jsdelivr.net/gh/abcd498936590/pic@master/img/tenpay.jpg" />
</p>