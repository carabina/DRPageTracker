# DRPageTracker
DRPageTracker is a sample iOS class for tracking view controller didappear

## Installation

```
pod 'DRPageTracker'
``` 

That's all


## Usage

run your app(debug model), and check the output log:

```
UINavigationController viewDidAppear

HomeViewController viewDidAppear

UIInputWindowController viewDidAppear

PageViewController viewDidAppear

HomeViewController viewDidAppear

PageViewController viewDidAppear

HomeViewController viewDidAppear
...
```

## Notes

If you already have a hack of UIViewController#viewDidAppear method, this pod maybe not work, please be careful.

#中文版本

DRPageTracker 是一个用来追踪ViewController是否显示的库，用到了OC的runtime特性，比较轻量，对现有代码结构无影响

## 安装

```
pod 'DRPageTracker'
``` 

安装完运行即可看到效果，不需要有任何代码接入

## 使用

运行你的工程(debug模式下)，在App里面随便打开几个ViewController，然后你就可以在日志里面找到类似如下的内容:

```
UINavigationController viewDidAppear

HomeViewController viewDidAppear

UIInputWindowController viewDidAppear

PageViewController viewDidAppear

HomeViewController viewDidAppear

PageViewController viewDidAppear

HomeViewController viewDidAppear
...
```

## 需要注意的地方

如果你的代码中原先已经有UIViewController#viewDidAppear的hack方法了，再使用DRPageTracker也许会造成冲突，请谨慎使用






