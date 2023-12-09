.. index::
   single: 提示文本 版本提示 参见

============
提示文本
============

以下类型不一定全被支持，通常 `note` 及 `warning` 是可用的。

.. note::

   注解型提示。

源码 ::

    .. note::

       注解型提示。

.. warning::

   警告型提示。

源码 ::

    .. warning::

       警告型提示。

.. error::

   错误型提示。

源码 ::

    .. error::

       错误型提示。

.. caution::

   小心提示。

源码 ::

    .. caution::

       小心提示。

.. tip::

   普通提示。

源码 ::

    .. tip::

       普通提示。


版本提示
============

新版本功能
============

.. versionadded:: 2.5
    The *spam* parameter.

源码 ::

  .. versionadded:: 2.5
      The *spam* parameter.


版本中修改
============

.. versionchanged:: 2.6
   The *spam* parameter.

与 versionadded 相似，但它描述的是该功能在版本中的更改(新参数，效果改变等)。

源码 ::

  .. versionchanged:: 2.6
     The *spam* parameter.

版本中移除
============

.. deprecated:: 3.1
   使用 :func:`newFunc` 代替。

源码 ::

  .. deprecated:: 3.1
     使用 :func:`newFunc` 代替。

============
参见
============

.. seealso::

   Common :py:mod:`getIp`
      标准模块 :py:mod:`Common` 的文档.

   `段落级别的标记 <http://zh-sphinx-doc.readthedocs.io/en/latest/markup/para.html>`_
      创建简单的段落。

源码 ::

  .. seealso::

     Common :py:mod:`getIp`
        标准模块 :py:mod:`Common` 的文档.

     `段落级别的标记 <http://zh-sphinx-doc.readthedocs.io/en/latest/markup/para.html>`_
        创建简单的段落。
