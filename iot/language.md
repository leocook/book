# 物联网编程语言选择

## 物联网

前几天和朋友聊到当下的技术日新月异，本质上还是硬件和网络得到了长足的发展，所以很多以前的想法变成了现实，回看技术的本质其实还是没有变。

AlphaGo的强大依赖于芯片和网络技术的进度，才有了令人惊艳的表现。

物联网其实是互联网的一个延伸，物联网的本质还是互联网，只不过终端不再是计算机（PC、服务器），而是嵌入式计算机系统及其配套的传感器。只要有硬件或产品连上网，发生数据交互，就叫物联网。

服务器技术叫“云”，单片机叫“智能硬件”，网络单片机应用叫“物联网”，车载单片机应用叫“车联网”，数据库技术应用叫“大数据”。

物联网涉及软硬件、互联网、App等多个领域，作为个人而言，只可能精其一样。

![分层结构](http://images.ofweek.com/Upload/News/2017-05/08/lime/1494224235227084156.jpg)

要选择物联网项目使用的语言，您首先必须了解物联网生态系统。这一点非常重要，因为不同级别的软件和固件所使用的处理器架构和资源相差很大。

底部的边缘设备：这些设备和周围的世界互动，代表了可穿戴和其他互联设备。这些设备采集并创造数据，通过致动器与世界互动。

中间的网关设备：这些设备属于中间设备，用于将数据传输到其它系统，以进行处理。网关也可以从许多边缘设备中收集数据，提供一条连接终端设备的控制路径。

顶部的是云：云是一系列可扩展计算、网络和存储资源，能够对终端设备和网关收集的数据进行存储、分析和可视化处理。

### 边缘设备(C语言)
比汇编语言更为高级，C语言支持创建资源受限型代码，提供出色的可读性和可维护性。C 语言的优势使其广泛存在于各个使用模式中。

### 网关设备(Python语言)
一种能够简化原型构建的解释性语言，您还可以将它用户生产环节。Python支持大量的库和模块，可以利用较少的代码完成更多的任务。适用于更强大的边缘设备、网关，甚至云。

### 云(JavaScript语言)
我偏向于使用 JavaScript， 更适合全栈物联网。

JavaScript 可以用于开发各种原型软件、及大部分的客户端软件：
- 基于mosca架设Node服务，通过mqtt协议可以将边缘设备采集的数据传输到MongoDB数据库
- 使用 Electron 开发桌面客户端，来帮助传统
- 使用 React 同构应用，可以开发全端应用，获取一致性的体验
- 使用 Ruff、Tessel 开发硬件端的应用
- 编写微信小程序直接访问蓝牙设备，进行交互与数据传输
- 在嵌入式系统 Linux 上，又可以制作 UI 界面来加速开发


### 资料文献

- [冷静审视人工智能技术的本质](https://zhuanlan.zhihu.com/p/28419753)
- [什么是物联网？](https://www.zhihu.com/question/19751763)