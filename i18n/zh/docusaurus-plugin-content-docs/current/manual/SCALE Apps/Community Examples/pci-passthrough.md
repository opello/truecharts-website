# PCI(-E) 设备通过

要通过您的 PCI(-E) 卡，您需要：

- 转到已安装的应用程序
- 点击应用卡右侧的菜单按钮
- 选择编辑
- 向下滚动到“资源和设备”部分
- 在配置挂载 USB 设备下单击右侧的添加按钮 (这也适用于PCI 设备)
- 在“主机设备路径” & “容器设备路径”中输入您的卡的 /dev/path (例如：对于dvb 设备，它将是：/dev/dvb)
- 提交您的更改

> *这种方法不能保证正常运行，我们目前官方不支持 PCI(-E) 设备。