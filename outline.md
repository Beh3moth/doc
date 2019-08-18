## 需要的文档  

> 这个文档列出我们需要编写的文档内容。其中，每一个大标题可以单独作为一个文件存在。建议的分工同时列出了。写文档的同时将代码再整理一遍，确保代码可运行、尽量精简/优化代码可读性，并整合各个仓库的代码（删减无用分支）。

### CPU部分  

* （CZK）整体实现思路（附设计图）及各个模块相互关系：
  * 取指
  * 译码
  * 计算
  * 访存
  * 写回  
  * IO相关模块
  * ...
* （PQL）特权指令模块文档
* （LYY）Verilog层面控制器文档
* （CZK）异步访存的整体实现思路

### （CZK、PQL）监控程序文档

> CZK先写初稿，PQL协助整理。

* 各功能说明及对应的运行截图
* 添加相关代码注释，删除无用代码
* 改写过程中遇到的问题
* 使用方法（编译方法，编译选项等）

### （PQL）OS部分文档  

### （LYY）decaf编译器文档及运行结果  

### （CZK）report.md  

* 该文件主要作用：
  * 列出所有的成果和详细分工