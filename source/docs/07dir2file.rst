.. index::
   single: 子目录 引入 rst 文件

============
子目录
============

当文档很多时，那么，你需要用到 **子目录** 了。

根目录下
index.rst 加入 ``modelList/index`` ；在目录中，index.rst 文件，可以写为

源码 ::

  模块列表
  ----------

  .. toctree::
	  :glob:
	  :titlesonly:

	  *


引入 rst 文件
==================

.. include:: inc.rst

源码 ::

    .. header:: 源文件路径，读取到文件头部
    .. include:: 源文件路径，按顺序读取
    .. footer:: 源文件路径，读取到文件尾部

    .. header:: header.rst
    .. include:: inc.rst
    .. footer:: footer.rst