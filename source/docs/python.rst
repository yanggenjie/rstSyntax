.. index::
   single: Python 会话 分隔符 注释 函数

======================
Python会话、分隔符、注释
=======================

>>> print "Hello World!"
Hello World!

源码 ::

  >>> print "Hello World!"
  Hello World!


分隔符
============

分隔符就是一条水平的横线，是由 4 个 - 或者更多组成，需要添加换行。

上面部分

------------

下面部分

源码 ::

  上面部分

  ------------

  下面部分


这篇文章来自我的Github,请参考 reference_。

.. _reference: https://github.com/SeayXu/


注释
============

注释以 **..** 开头，后面接注释内容即可，可以是多行内容，多行时每行开头要加一个空格。

..
 我是注释内容
 你们看不到我

源码 ::

  ..
   我是注释内容
   你们看不到我


函数
============

这里的函数定义，并不是 python 中的方式，而是其他语言 如 PHP。在这里只是为了“高亮”显示。

.. py:function:: clearEof($str);

  清除换行符。

  :param string: $str 待清理的字符串
  :rtype: string

源码 ::

  .. py:function:: clearEof($str);

    清除换行符。

    :param string: $str 待清理的字符串
    :rtype: string


.. function:: clearEof($str)
              getIp()
   :module: Common

   返回用户输入的一行文本.

源码 ::

  .. function:: clearEof($str)
                getIp()
     :module: Common

     返回用户输入的一行文本.