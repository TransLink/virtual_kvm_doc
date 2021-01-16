<!--
 * @Description: 
 * @Date: 2020-09-01 23:29:53
 * @LastEditors: CK.Zh
 * @LastEditTime: 2021-01-09 00:41:21
 * @FilePath: \virtual_kvm_doc\README.md
-->
# Virtual KVM

### 🛒购买直达：[淘宝店铺](http://store.trans.link/)


![](img/virtual_kvm_interface.png)
![](img/virtual_kvm_interface_l.png)
![](img/virtual_kvm_interface_r.png)

## 特性

* USB typeC？ 简直标配，不值一提
* 全平台免驱、即插即用
* 可能是全球首款虚拟KVM
* 能看会控
* 玩转树莓派，何必再需~~键盘、鼠标、显示器~~
* <font size=2>身材mini</font>，<font size=4>功能MAX</font>

## 场景

> `一台电脑 + Virtual KVM` 可以让你如此大展身手：

* 录制软件教程
* 批量安装计算机操作系统
* 树莓派、Jetson Nano等开源硬件调试

（以下待验证）
* Smartisan OS TNT
* 三星手机PC模式
* 华为手机PC模式
* iOS设备投屏
* 电视盒子
* Switch

## 快速开始

1. 使用USB线连接`HOST`口到主机电脑
2. 使用USB线连接`SLVAE`口到被控设备，使用HDMI线连接`HDMI`口到被控设备视频输出口
3. 在主控电脑上打开`VirtualKVM APP`

## 接口及指示灯


| 接口  | 功能                          | 连接至 |
|-------|-------------------------------|--------|
| HOST  | UVC视频数据输出 </br> 键鼠数据输入 | 主控机 |
| SLAVE | 键鼠数据输出                  | 被控机 |
| HDMI  | HDMI视频数据输入              | 被控机 |



| 指示灯| 功能             | 常亮●               | 熄灭○               | 闪烁◐                   |
|------|------------------|--------------------|--------------------|------------------------|
| STA1 | 视频采集（硬件） | 工作中             | 未工作             | N/A                    |
| STA2 | 键鼠模拟（硬件） | 工作中             | 未工作             | N/A                    |
| STA3 | 预览画面（软件） | 主控机正在预览画面 | 主控机未在预览画面 | N/A                    |
| ENUM | 键鼠枚举（软件） | 被控机已识别键鼠   | 被控机未识别键鼠   | N/A                    |
| UP   | 键鼠通信（软件） | N/A                | N/A                | 键鼠数据已发送至被控机 |

## 兼容平台

| 操作系统  | 状态                          |
|-------|-------------------------------|
| Windows 10  | 已发布 |
| Windows 7 | 已开发、未测试                  |
| Ubuntu 20.04  | 规划中              |
| macOS | N/A                  |
| Android | N/A                  |
| iOS | N/A                  |

## 客户端下载

 https://github.com/translink/virtual_kvm_doc/releases

