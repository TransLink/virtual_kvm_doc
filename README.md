<!--
 * @Description: 
 * @Date: 2020-09-01 23:29:53
 * @LastEditors: CK.Zh
 * @LastEditTime: 2020-11-22 20:03:21
 * @FilePath: \virtual_kvm_doc\README.md
-->
# Virtual KVM

* KVM 即 Keyboard Video Mouse

# virtual_kvm_doc

软件下载链接 https://github.com/virtualkvm/virtual_kvm_doc/releases


# 接口及指示灯
![](img/virtual_kvm_interface.png)


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
