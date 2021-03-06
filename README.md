# mVi-MultiLoopFW
mVi-MultiLoopViFW(mVi Academy Multi-Loop Virtual Instrument Framework)是mVi基于LabVIEW开发的一套开源多任务应用程序框架。该框架旨在简化复杂多任务虚拟仪器系统的开发，并提高系统的可靠性和灵活性。mVi-MultiLoopViFW已广泛应用于各种工业虚拟仪器系统中。

生产/消费者多循环框架可作为多数虚拟仪器项目主框架，但是有些时候，需要对项目的不同处理模块进一步分类，将同种类型的工作归为一类以期获得较高的运行效率。例如我们常希望由一个独立的循环来处理GUI事件、一个独立的循环进行数据采集、一个独立的循环进行数据处理以及另一个单独的循环进行错误集中处理等等，这种情况下就需引入大型的多任务处理模式。
大型的多任务模式通常由两个以上独立队列在多个任务循环之间传递不同类别的数据，以协调各循环完成不同的功能。vmVi-MultiLoopViFW提供了一套可靠性高，灵活性强的大型多任务引用程序框架模板，可使开发人员更快速的处理各种负责问题。
![image](https://user-images.githubusercontent.com/90971380/133905766-9d526db8-937b-4312-b965-d34f60317bca.png)
![image](https://user-images.githubusercontent.com/90971380/133905774-42d74926-d30c-4895-8716-5680aba02226.png)

1. 更新历史：

    1. 2013-03-30：mVi viFW 1.1, 设置部分子Vi为可重入
    2. 010-06-24: mVi viFW 1.0, 第一版发布.
    
2. 技术支持：

    1. Email：gaoke.yang@hotmail.com
    2. QQ交流群：186796050
    4. 源码下载：https://github.com/mVi-Academy
