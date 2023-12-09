.. index::
   single: 图片 表格

============
图片及表格
============

图片
=====

.. image:: http://ramble.3vshej.cn/wp-content/uploads/2017/12/2017-12-06_raspberry-pi-e1512540834201.png
  :width: 200px

源码 ::

  .. image:: ./2017-12-06_raspberry-pi-e1512540834201.png
    :width: 200px


表格
============

简单的表格

=====  =====  ======
输入          输出
------------  ------
A      B      A or B
=====  =====  ======
False  False  False
True   False  True
False  True   True
True   True   True
=====  =====  ======

源码 ::

  =====  =====  ======
  输入          输出
  ------------  ------
  A      B      A or B
  =====  =====  ======
  False  False  False
  True   False  True
  False  True   True
  True   True   True
  =====  =====  ======

复杂的表格

+------------------------+------------+----------+----------+
| Header row, column 1   | Header 2   | Header 3 | Header 4 |
| (header rows optional) |            |          |          |
+========================+============+==========+==========+
| body row 1, column 1   | column 2   | column 3 | column 4 |
+------------------------+------------+----------+----------+
| body row 2             | Cells may span columns.          |
+------------------------+------------+---------------------+
| body row 3             | Cells may  | - Table cells       |
+------------------------+ span rows. | - contain           |
| body row 4             |            | - body elements.    |
+------------------------+------------+---------------------+


源码 ::

  +------------------------+------------+----------+----------+
  | Header row, column 1   | Header 2   | Header 3 | Header 4 |
  | (header rows optional) |            |          |          |
  +========================+============+==========+==========+
  | body row 1, column 1   | column 2   | column 3 | column 4 |
  +------------------------+------------+----------+----------+
  | body row 2             | Cells may span columns.          |
  +------------------------+------------+---------------------+
  | body row 3             | Cells may  | - Table cells       |
  +------------------------+ span rows. | - contain           |
  | body row 4             |            | - body elements.    |
  +------------------------+------------+---------------------+


.. note::
  参见：Sphinx rst 创建表格技巧 http://ramble.3vshej.cn/sphinx-rst-create-table-tips/