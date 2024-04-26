# CyberEdge 互联网综合扫描 攻击面测绘

## 0x01 简介

CyberEdge是一款基于已有扫描器进行集成的互联网综合扫描器，可用于网络安全行业进行各种测试。

CyberEdge采用 域名——子域名——IP——端口——目录——漏洞 结构进行综合扫描

## 0x02 优点

GUI界面，清晰展示所有资产。

高自动化集成度，便利于资产之间的互相关联。

易用性，尽可能的设计了常用简单的接口供用户使用。

部署便利，一键部署。

任务调度，多线程执行，速度较快。

提供一键扫描、分步扫描功能，减少人工成本。

代码开源，便于借鉴与参考。

项目长期支持，更新速度较快。

## 0x03 技术栈

后端：Python Django

前端：Vue2 Tdesign

数据库：Postgre

## 0x04 部署方法

```bash
docker-compose up -d
```

前端位于4567端口

后端位于1234端口

## 0x05 使用的组件

子域名扫描: OneForAll

端口扫描: Nmap

路径扫描: ffuf

## 0x06 交流相关

作者邮箱：PayasoNorahC@protonmail.com

QQ群：

![img](https://raw.githubusercontent.com/ZacharyZcR/CyberEdge/main/image/QQ.jpg)