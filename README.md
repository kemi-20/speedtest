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


## Server requirements
* A reasonably fast web server with Apache 2 (nginx, IIS also supported)
* PHP 5.4 (other backends also available)
* MySQL database to store test results (optional, PostgreSQL and SQLite also supported)
* A fast! internet connection

## Installation videos
* [Quick start installation guide for Ubuntu Server 19.04](https://fdossena.com/?p=speedtest/quickstart_v5_ubuntu.frag)

## Android app
A template to build an Android client for your LibreSpeed installation is available [here](https://github.com/librespeed/speedtest-android).

## Docker
A docker image is available on the [Docker Hub](https://registry.hub.docker.com/r/adolfintel/speedtest), see `doc_docker.md` for more info about it

## Go backend
A Go implementation is available in the [`speedtest-go`](https://github.com/librespeed/speedtest-go) repo, maintained by [Maddie Zhan](https://github.com/maddie).

## Node.js backend
A partial Node.js implementation is available in the `node` branch, developed by [dunklesToast](https://github.com/dunklesToast). It's not recommended to use at the moment.

## Donate
[![Donate with Liberapay](https://liberapay.com/assets/widgets/donate.svg)](https://liberapay.com/fdossena/donate)  
[Donate with PayPal](https://www.paypal.me/sineisochronic)  

## License
Copyright (C) 2016-2021 Federico Dossena

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Lesser General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU Lesser General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/lgpl>.
