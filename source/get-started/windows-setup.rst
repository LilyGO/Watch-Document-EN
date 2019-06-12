***************************************
安装Arduino IDE
***************************************

1.引言
============


欢迎来到Arduino！在您开始编程之旅之前，您需要设置软件

以编写您的电路板Arduino软件（IDE）允许您编写程序并将其上传到您的电路板。在Arduino Software页面中，您将找到两个选项：

1. 如果您有可靠的Internet连接，则应使用在线IDE（Arduino Web Editor）。它允许您将草图保存在云中，从任何设备上获取它们并备份。您将始终拥有最新版本的IDE，而无需安装更新或社区生成的库。

2. 如果您希望脱机工作，则应使用最新版本的 `桌面IDE <https://www.arduino.cc/en/Main/Software?setlang=cn>`_ 

.. important:: 强烈建议安装桌面版IDE。当然，有机会你也可以尝试使用在线版IDE

.. image:: ../_static/w_install1.png

..
 .. image:: ../_static/das.gif



2.下载
============

.. image:: ../_static/w_install2.png 

从下载页面获取最新版本。您可以选择安装程序（.exe）和Zip包。我们建议您使用第一个直接安装使用Arduino软件（IDE）所需的一切，包括驱动程序。使用Zip包，您需要手动安装驱动程序。如果要创建便携式安装，Zip文件也很有用 。
下载完成后，继续安装，当您从操作系统收到警告时，请允许驱动程序安装过程。

2.1 Arduino下载：
^^^^^^^^^^^^^^^^^^^^^

    * :download:`Windows安装包 <https://downloads.arduino.cc/arduino-1.8.9-windows.exe>`。
    * :download:`Windows免安装Zip包 <https://downloads.arduino.cc/arduino-1.8.9-windows.zip>`。

3.安装 
============

.. figure:: ../_static/DRV_Capture1.png 
   :scale: 100
   :align: center

   选择要安装的组件

.. figure:: ../_static/DRV_Capture2.png 
   :scale: 100
   :align: center

   选择安装目录（建议不要安装在系统盘--C盘中）

.. figure:: ../_static/DRV_Capture3.png 
   :scale: 100
   :align: center

   正在安装，安装完成后点击close

4.配置
============
.. figure:: ../_static/das2.gif 
   :scale: 100
   :align: left

..

4.1首选项配置
^^^^^^^^^^^^^

* 写软件之前，我们要配置一些东西（工作文件夹和语言等）
* 打开文件->首选项，更换目录。
* 可以更换语言，中英日德法，全部支持。

.. note::
    #. 默认会在C盘我的文档。因以后我们需要的很多拓展库都会默认生产在这个文件夹，所以我们最好把路径设在非系统盘中。
    #. 语言设置完之后，需要重启软件，才会生效。
..
    :width:  733px
    :height: 550px
    工具链的设置
    ===============

    快速设置的方法是从 dl.espressif.com 下载集成在一起的工具链和 MSYS2 压缩文件：

    https://dl.espressif.com/dl/esp32_win32_msys2_environment_and_toolchain-20181001.zip

    将 zip 压缩文件解压到 ``C:\`` (或其它路径，这里假设是 ``C:\``)，它会使用预先准备的环境创建一个 ``msys32`` 目录。

    检出
    ============

    运行 ``C:\msys32\mingw32.exe`` 打开一个 MSYS2 的终端窗口。该窗口的环境是一个 bash shell。创建一个 ``esp`` 目录作为开发 ESP32 应用的默认地址。运行指令 ::

        mkdir -p ~/esp  
        
    输入 ``cd ~/esp`` 就进入到新创建的目录。如果没有错误信息出现则表明此步骤已完成。


    .. figure:: ../../_static/msys2-terminal-window.png
        :align: center
        :alt: MSYS2 MINGW32 shell window
        :figclass: align-center

        MSYS2 终端窗口

    后续步骤将会使用这个窗口来为 ESP32 设置开发环境。

    后续步骤
    ==========

    要继续设置开发环境，请参考 :ref:`get-started-get-esp-idf` 一节。

    更新环境
    ========================

    当 IDF 更新时，有时需要新的工具链，或者将新的需求添加到 Windows MSYS2 环境中。要将旧版本的预编译环境中的数据移动到新版本：

    - 把旧的 MSYS2 环境（即 ``C:\msys32``）移动/重命名为不同的目录（即 ``C:\msys32_old``）。
    - 按照前文所述步骤下载新的预编译环境。
    - 将新的 MSYS2 环境解压缩到 ``C:\msys32`` （或其他位置）。
    - 找到旧的 ``C:\msys32_old\home`` 目录并把它移到 ``C:\msys32``。
    - 如果你不再需要 ``C:\msys32_old`` 可以将它删除。

    你可以在系统上拥有独立的不同的 MSYS2 环境，前提是在不同的目录中。

    相关文档
    =================

    .. toctree::
        :maxdepth: 1

        windows-setup-scratch


    .. _MSYS2: https://msys2.github.io/

.. 
Indices and tables
>>>>>>>>>>>>>>>>>>
.. 
* :ref:`genindex`
* :ref:`modindex`
* :ref:`search` :numbered:
.. 
   1.简介 <introduction/index> 
   2.快速上手 <get-started/index>
   3.入门使用篇 <basics/index>
   4.进阶开发篇 <advanced/index>
   5.下载资源 <download/index>
   6.相关链接 <related-links/index>
   introduction/index
   get-started/index
   basics/index
   advanced/index
   download/index
   related-links/index