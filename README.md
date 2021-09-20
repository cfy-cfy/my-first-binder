# my-first-binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cfy-cfy/my-first-binder.git/HEAD)

.. image:: https://mybinder.org/badge_logo.svg
 :target: https://mybinder.org/v2/gh/cfy-cfy/my-first-binder.git/HEAD
 
<!-- ——————————————————————————————————————————————————————————————— -->

【1】Binder提供代码以及执行它的硬件和软件的服务：https://www.pythonheidong.com/blog/article/467216/3a5f2526e1b8ce63bc96/

  【创建仓库】

    在GitHub创建仓库"my-first-binder"
        确定仓库是public
        不要忘记初始化README

    通过Web界面创建一个名为hello.py的文件，添加内容print（“ Hello from Binder！”）并提交给master分支
    
【使用Binder启动仓库】
  
  打开 https://mybinder.org
  在"GitHub repo or URL" 输入框中，键入新建仓库地址：https://github.com/cfy-cfy/my-first-binder.git
  单击“Launch”按钮，等待环境创建成功后，浏览器会自动弹出Jupyter Notebook界面
  
 【运行 hello.py】
  
    在Jupyter Notebook右上角，单击"New" -> “Terminal”
    在新Tab页面的终端中键入python hello.py，并回车

    终端会执行脚本，打印Hello from Binder!
【添加依赖】

    代码仓库新建requirements.txt
    添加 numpy==1.14.5
    提交代码
    重新启动“Launch”，并查看" Build Logs"

【检查环境】

    在Jupyter Notebook右上角，单击"New" -> “Python3” 打开notebook
    新建一个Cell，键入：

    import numpy
    print(numpy.__version__)
    numpy.random.randn()

【共享】
  直接分享链接： https://mybinder.org/v2/gh/cfy-cfy/my-first-binder.git/HEAD
