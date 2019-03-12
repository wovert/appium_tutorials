# Appium

## Appium 环境搭建

### 1. Java环境配置

1. JAVA_HOME 配置
2. PATH 配置 `%JAVA_HOME%\bin`
3. Java环境验证

### 2. Android 环境配置

1. 下载解压 `adt-bundle-windows-x86_64-xxxx`
2. 配置Android_Home 配置
3. Path加入 `%Android_Home%\tools;%Android_Home%\platform-tools`
4. 结果验证 `adb devices`
5. 验证指令是否能识别 `emulator`

### 3. Appium 相关组件安装卸载

#### Appium命令行安装方法1

> 进入官网地址并下载

https://bitbucket.org/appium/appium.app/downloads/

完整安装带UI的appium，可以从官网直接下载dmg（mac）或者zip（Windows），运行里面的app即可

appium安装好后：找到这个文件安装目录`D:\appium\node_modules\.bin`
将上面的地址添加到环境变量path下

#### Appium命令行安装方法2

1. 安装NodeJS
2. 安装 .NET framework4.5
3. 安装 Appium 服务

```sh
$ npm i -g appium --registry=https://registry.npm.taobao.org
$ appium -v
$ npm i -g appium-doctor
$ appium-doctor
```

命令安装的appium是控制台程序，没有UI界面。可到**github**搜索appium的[appium-desktop](https://github.com/appium/appium-desktop/releases/tag/v1.11.0)项目中下载最新版本


MSBUILD : error MSB3428: 未能加载 Visual C++ 组件“VCBuild.exe”

错误原因：缺少windows构建插件

解决方法：`npm install --global --production windows-build-tools`  （全局安装windows构建工具）

#### Appium 服务

```sh
Appium 服务安装验证
$ appium-dockter

Apppium 服务启动方式
$ appium
```

### 4. Appium 实例演示

## Appium模拟器的配置过程

## Xpath 技术在appium中的应用

## Xpath webview应用方法

## Appium的 API

## Appium中的 hibernate应用

## Appium中的driver 技术

## Appium中的testNG应用

## Appium的数据参数化

## Appium框架

## ant对annpium脚本的管理

## Appium脚本的并发测试

## Appium自动化测试持续集成

## Appium中的PO模式封装

## log4技术配置

## Appiumn中的spring应用

