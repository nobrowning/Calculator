# iOS矩阵计算器
本程序实现了大学线性代数有关矩阵的几乎所有运算，包括行列式、逆、行最简、矩阵的乘法等。并自己设计了一个表示分数的类，用于更佳人性化的显示。

## 类的功能：
* ViewController
>主屏幕控制器

* DoubleViewController
>用于实现双波轮的行数列数选择器：

![image](https://github.com/nobrowning/Matrix-Calculator/blob/master/ScreenShot/DoublePickView.png)

* MyPickerViewController
>用于实现单波轮的列数选择器(做乘法时用)：

![image](https://github.com/nobrowning/Matrix-Calculator/blob/master/ScreenShot/SinglePickView.PNG)

* ToolBarViewController
>实现键盘上的工具栏：

![image](https://github.com/nobrowning/Matrix-Calculator/blob/master/ScreenShot/Input.PNG)

* JZRankClass
>计算秩和行最简式

* NIJZClass
>计算逆矩阵

* FractionalClass
>分数类，使程序支持分数。包括了对基本运算符的重载、与基本数据类型的相互转换。


本项目还针对不同尺寸的设备，用简单的方式做了现实布局的适配。



## 程序运行截图

![image](https://github.com/nobrowning/Matrix-Calculator/blob/master/ScreenShot/Launch.PNG)

![image](https://github.com/nobrowning/Matrix-Calculator/blob/master/ScreenShot/Single.gif)

![image](https://github.com/nobrowning/Matrix-Calculator/blob/master/ScreenShot/Double.gif)
## 总结
矩阵计算器练习这个小项目是我大二初学iOS开发时做的，本想着上架AppStore。但后来觉得这个小的项目，我做的也挺粗糙的，也就搁置下来了。虽然很简单，但它对我的意义却很大：
* 熟悉了iOS开发的基本技术 
* 在编写算法的同时也增进了我的编程基础的 
* 对面向对象开发有了更深的理解
* 对从无到有的软件开发流程有了初步的尝试了～
