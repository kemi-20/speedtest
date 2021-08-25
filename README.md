![LibreSpeed Logo](https://github.com/kemi-20/speedtest/blob/master/.logo/logo3.png?raw=true)

[English version](https://github.com/kemi-20/speedtest/blob/master/README_en.md)
# LibreSpeed

没有 Flash，没有 Java，没有 Websocket，没有废话。

这是一个用 Javascript 实现的非常轻量级的 Speedtest，使用 XMLHttpRequest 和 Web Workers。

## 试试吧
[进行速度测试](https://librespeed.org)

## 兼容性
支持所有现代浏览器：IE11、最新版 Edge、最新版 Chrome、最新版 Firefox、最新版 Safari。
也适用于移动版本。

## 特点
* 下载
* 上传
* Ping
* 抖动
* IP 地址、ISP、与服务器的距离（可选）
* 遥测（可选）
* 结果共享（可选）
* 多个测试点（可选）

![Screenshot](https://speedtest.fdossena.com/mpot_v6.gif)


## 服务器要求
* 带有 Apache 2 的相当快的 Web 服务器（也支持 nginx、IIS）
* PHP 5.4（其他后端也可用）
* 用于存储测试结果的 MySQL 数据库（可选，也支持 PostgreSQL 和 SQLite）
* 一个快的互联网连接！

## 安装视频
* [Ubuntu Server 19.04 快速入门安装指南](https://fdossena.com/?p=speedtest/quickstart_v5_ubuntu.frag)

## Android应用
 [此处](https://github.com/librespeed/speedtest-android)提供了为 LibreSpeed 安装构建 Android 客户端的模板。

## Docker
[Docker Hub](https://registry.hub.docker.com/r/adolfintel/speedtest)上提供了一个 docker 映像，请参阅 `doc_docker.md` 以获取有关它的更多信息。

## Go 后端
由 [Maddie Zhan](https://github.com/maddie) 维护的 [`speedtest-go`](https://github.com/librespeed/speedtest-go) 存储库中提供了 Go 实现。

## Node.js 前端
由 [dunklesToast](https://github.com/dunklesToast) 开发的 `node` 分支中提供了部分Node.js实现。暂时不推荐使用。

## 捐赠
[![Donate with Liberapay](https://liberapay.com/assets/widgets/donate.svg)](https://liberapay.com/fdossena/donate)  
[Donate with PayPal](https://www.paypal.me/sineisochronic)  

## 执照
版权所有 (C) 2016-2021 Federico Dossena

该程序是免费软件：您可以重新分发和/或修改
它根据由发布的 GNU 宽松通用公共许可证的条款
自由软件基金会，许可证的第 3 版，或
（由您选择）任何更高版本。

这个程序是分发的，希望它有用，
但没有任何保证； 甚至没有暗示的保证
特定用途的适销性或适用性。 见
有关更多详细信息，请参阅 GNU 通用公共许可证。

您应该已经收到一份 GNU 宽松通用公共许可证的副本
随着这个程序。 如果没有，请参阅 <https://www.gnu.org/licenses/lgpl>.
