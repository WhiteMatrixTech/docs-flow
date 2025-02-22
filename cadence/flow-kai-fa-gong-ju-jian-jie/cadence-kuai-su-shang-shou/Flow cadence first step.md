# 第一步

---



在本教程中，我们将学习如何使用智能合约、切换账户以及查看账户状态。

 

## **了解Cadence**

---



Cadence是一种用于Flow区块链的新型智能合约编程语言，并为智能合约编程引入新的特质，以帮助开发者确保其代码安全、清晰、可运行。其部分特质如下：

- 类型安全且静态类型系统稳定

- 采用新式范例——面向资源编程，即将Linear-type类型与对象功能匹配，通过确保资源（及其关联assets文件）同时刻仅存于一个位置，且不能被复制、意外丢失及删除，从而为数字所有权创建安全的描述性模型。

- 功能及[交易](https://docs.onflow.org/cadence/language/transactions/)内置前置（Pre-condition）及后置（Post-condition）程序

- 基于能力的安全性使用：通过将访问权限仅限制于所有者及具备有效引用权的访问者，进而增强访问控制

请浏览链接：[Cadence introduction](https://docs.onflow.org/cadence/) 查阅更多有关该语言的高阶设计信息

 

## **了解Flow开发者平台**

---



 

Flow开发者平台（[Flow Playground](https://play.onflow.org/local?type=account&id=LOCAL-account-0)）中包含浏览器内编辑器和Flow实验模拟器。您可以使用该平台编写Cadence智能合约，应用于Flow本地仿真区块链网络以及提交交易。

各标准的网页浏览器皆可兼容Flow开发者平台，但目前为止，其仅于谷歌浏览器中完成了测试和优化，因而我们更推荐您使用谷歌浏览器。

 

### **关于平台**



该平台可让您充分了解Cadence智能合约开发以及事物脚本的执行和使用。

平台预设合约及事物模板，且与文档站教程内容契合。在特定教程中下载合约时，请点击平台上方的“实例”（Examples）查阅各教程目录。

点击链接时，教程内容将会于新标签页打开，平台模板中包含合约、事物及脚本，供您使用

 

### **账户及合约**



账户界面位于屏幕左侧，活跃账户也在此显示。您可以在主编辑器中点击“账户”选项（Account）来查看与该账户相关联的合约。

 [![Wfkj7d.png](https://z3.ax1x.com/2021/07/26/Wfkj7d.png)](https://imgtu.com/i/Wfkj7d)

当在包含合约的账户编辑器中打开Cadence代码时，您可以点击屏幕右上方的“部署”选项（Deploy），将该合约部署到当前选择的账户中。

 

几秒钟后，可以看到控制台中的信息——合约已确认部署（The Contract Was Deployed）。同时可以查看到账户选项中展示的合约名称，表明当前合约已部署至账户中。

[![WfAK3V.png](https://z3.ax1x.com/2021/07/26/WfAK3V.png)](https://imgtu.com/i/WfAK3V)



您也可以从左侧目录中选择事物和脚本，然后上传至已部署的智能合约中进行交互编辑。Hello World教程中已涵盖上述操作。

这是平台功能的冰山一角，如您想了解更多细节介绍，请查阅平台操作手册

 

### **资源**



本系列教程涵盖事物、合约及脚本等多个文件，所有您需要的的代码都会出现在教程正文中，供您复制和粘贴。同时，您也可以查阅平台中预设的教程内容。

 

### **运行程序： 你好，世界!**



现在，您可以运行Flow的开发者平台，并为Flow创建智能合约了！