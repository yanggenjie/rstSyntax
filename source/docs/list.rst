.. index::
   single: 列表 枚举列表 水平列表 选项列表

============
列表
============

- 符号列表1
- 符号列表2

  + 二级符号列表1

  - 二级符号列表2

  * 二级符号列表3

* 符号列表3

+ 符号列表4


.. note::

  符号列表可以使用 **-** 、 ***** 、 **+** 来表示。

  不同的符号结尾需要加上空行，下级列表需要有空格缩进。

枚举列表
============

可以使用的枚举有：

- 阿拉伯数字: 1, 2, 3, ... (无上限)。
- 大写字母: A-Z。
- 小写字母: a-z。
- 大写罗马数字: I, II, III, IV, ..., MMMMCMXCIX (4999)。
- 小写罗马数字: i, ii, iii, iv, ..., mmmmcmxcix (4999)。


1. 枚举列表1
#. 枚举列表2
#. 枚举列表3

A. 枚举列表1
#. 枚举列表2
#. 枚举列表3

a. 枚举列表1
#. 枚举列表2
#. 枚举列表3

源码 ::

  1. 枚举列表1
  #. 枚举列表2
  #. 枚举列表3

  A. 枚举列表1
  #. 枚举列表2
  #. 枚举列表3

  a. 枚举列表1
  #. 枚举列表2
  #. 枚举列表3


水平列表
============

该指令生成水平列表. 它将列表项横向显示并减少项目的间距使其较为紧凑.

生成器需支持水平分布, 这里的 columns 选项定义显示的列数，默认为2. 例如:

.. hlist::
   :columns: 3

   * 列表
   * 的子
   * 项会
   * 水平
   * 排列

源码 ::

  .. hlist::
     :columns: 3

     * 列表
     * 的子
     * 项会
     * 水平
     * 排列


选项列表
============

选项列表是一个类似两列的表格，左边是参数，右边是描述信息。当参数选项过长时，参数选项和描述信息各占一行。

选项与参数之间有一个空格，参数选项与描述信息之间至少有两个空格。

-a            command-line option "a"
-b file       options can have arguments
              and long descriptions
--long        options can be long also
--input=file  long options can also have
              arguments
/V            DOS/VMS-style options too


源码 ::

  -a            command-line option "a"
  -b file       options can have arguments
                and long descriptions
  --long        options can be long also
  --input=file  long options can also have
                arguments
  /V            DOS/VMS-style options too