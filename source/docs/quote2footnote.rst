.. index::
   single: 引用 脚注 替换 块引用

============
引用、脚柱
============

本文档参考自 [赵子清的技术文章]_。

.. [赵子清的技术文章] 《使用Sphinx + reST编写文档》 https://www.cnblogs.com/zzqcn/p/5096876.html

源码 ::

  本文档参考自 [赵子清的技术文章]_。

  .. [赵子清的技术文章] 《使用Sphinx + reST编写文档》 https://www.cnblogs.com/zzqcn/p/5096876.html


脚注
============

当然，也参考了 seayxu [#简书]_ 的 reStructuredText(rst)快速入门语法说明 [#地址]_ 。

脚注

.. [#简书] seayxu 简书 http://www.jianshu.com/u/3462d3ed1acd
.. [#地址] reStructuredText(rst)快速入门语法说明 http://www.jianshu.com/p/1885d5570b37

源码 ::

  当然，也参考了 seayxu [#简书]_ 的 reStructuredText(rst)快速入门语法说明 [#地址]_ 。

  脚注

  .. [#简书] seayxu |苹果| 简书 http://www.jianshu.com/u/3462d3ed1acd
  .. [#地址] reStructuredText(rst)快速入门语法说明 http://www.jianshu.com/p/1885d5570b37


替换
============

**|release|**

被项目文档的发布版本替换. 这时版本字符串包含完整的标签 alpha/beta/release ,例如 2.5.2b3

**|version|**

被项目文档的版本替换. 版本字符串仅有主要和次要两部分组成，例如版本2.5.1会表示为 2.5

**|today|**

替换今天的日期 (文档被读取的日期), 或者配置文件设置的日期

我非常喜欢吃 |苹果| 。

.. |苹果| replace:: 橘子

源码 ::

  我非常喜欢吃 |苹果| 。

  .. |苹果| replace:: 橘子

.. note::
  替换是全文替换的（我非常喜欢吃 |苹果| ）。


块引用
============

下面是引用的内容：

    “真的猛士，敢于直面惨淡的人生，敢于正视淋漓的鲜血。”

    --- 鲁迅

..

      “人生的意志和劳动将创造奇迹般的奇迹。”

      — 涅克拉索

源码 ::

  下面是引用的内容：

      “真的猛士，敢于直面惨淡的人生，敢于正视淋漓的鲜血。”

      --- 鲁迅

  ..

        “人生的意志和劳动将创造奇迹般的奇迹。”

        — 涅克拉索