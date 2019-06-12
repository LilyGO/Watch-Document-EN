*********************************
Windows平台Arduino的安装步骤
*********************************

1. 下载
============

.. image:: ../../_static/w_install2.png 

从 `下载页面 <https://www.arduino.cc/en/Main/Software?setlang=cn>`_ 获取最新版本。您可以选择安装程序（.exe）和Zip包。

.. note::

 我们建议您使用第一个直接安装使用Arduino软件（IDE）所需的一切，包括驱动程序。
 使用Zip包，您需要手动安装驱动程序。如果要创建便携式安装，Zip文件也很有用。下载完成后，继续安装，当您从操作系统收到提示时，请允许驱动程序安装过程。

Arduino-IDE下载
~~~~~~~~~~~~~~~~~~
如果您因为网络原因或其他因素无法进入网页，为了便于下载，可以直接点击下面链接。

当然，出于安全因素，也许会有所迟疑。由右上角 **Source code** 可以看出，只是超链接指向官网最新版本IDE，大可放心下载。

从长远角度来看，我们当然还是建议去Arduino官网简单浏览一下。不管是出于工作或是学习，都会大有裨益。

* :download:`Windows安装包 <https://downloads.arduino.cc/arduino-1.8.9-windows.exe>`。
* :download:`Windows免安装Zip包 <https://downloads.arduino.cc/arduino-1.8.9-windows.zip>`。

2. 安装 
============

.. figure:: ../../_static/DRV_Capture1.png 
   :scale: 100
   :align: center

   选择要安装的组件

.. figure:: ../../_static/DRV_Capture2.png 
   :scale: 100
   :align: center

   选择安装目录（建议不要安装在系统盘--C盘中）

.. figure:: ../../_static/DRV_Capture3.png 
   :scale: 100
   :align: center

   正在安装，安装完成后点击close

3. 配置
============
.. figure:: ../../_static/das2.gif 
   :scale: 100
   :align: left

..

首选项配置:
~~~~~~~~~~~~~

* 写软件之前，我们要配置一些东西（工作文件夹和语言等）
* 打开文件->首选项，更换目录。
* 可以更换语言，中英日德法，全部支持。

.. note::

 默认会在C盘我的文档。因以后我们需要的很多拓展库都会默认生产在这个文件夹，所以我们最好把路径设在非系统盘中。
 语言设置完之后，需要重启软件，才会生效。

4. 测试
=========

打开LED Blink 样例代码：文件>示例>01.Basics > Blink。

.. figure:: ../../_static/blink.gif
   :scale: 100
   :align: left

..
