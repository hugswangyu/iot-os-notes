# 物联网终端操作系统笔记

物联网终端操作系统选修课的学习笔记，基于 [Quarto](https://quarto.org) 构建，部署于 GitHub Pages。

**在线阅读：[hugswangyu.github.io/iot-os-notes](https://hugswangyu.github.io/iot-os-notes/)**

## 内容

| 章节 | 主题 |
|------|------|
| Ch1 | 物联网及嵌入式概述 |
| Ch2-3 | 物联网操作系统的关键技术 |
| Ch4 | 连接技术（NB-IoT、LoRa/LoRaWAN） |
| Ch5 | 连接与协议（MQTT、CoAP、LwM2M） |
| Ch6 | LiteOS 操作系统及其移植 |
| Ch7 | 任务 |
| Ch8 | 信号量与互斥锁 |
| Ch9 | 消息队列、事件与软件定时器 |
| Ch10 | 内存管理与中断管理 |
| Ch11 | 物联网操作系统的应用案例 |

## 本地构建

```bash
# 安装 Quarto：https://quarto.org/docs/get-started/
quarto render
quarto preview   # 本地预览，自动热重载
```

## 部署

推送到 `main` 分支后，GitHub Actions 自动渲染并部署到 GitHub Pages。
