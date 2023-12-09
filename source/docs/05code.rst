.. index::
   single: 代码

============
代码
============

在文档中列出代码是开发人员经常用到的一个功能。在reST文档中列出代码有三种方式：

- 行内代码 用``code``
- 简单代码块 在代码块的上一个段落后面加2个冒号，空一行后开始代码块，代码块要缩进
- 复杂代码块 使用code-block指导语句，还可以选择列出行号和高亮重点行等

  + :linenos:显示行号
  + :emphasize-lines:3,6 3,6行高亮

code 方式

``echo "Hello World!";``

源码 ::

  ``echo "Hello World!";``

双冒号方式 ::

  echo "Hello World!";

源码 ::

  双冒号方式 ::

    echo "Hello World!";

code-block 方式

    C

    .. code-block:: c
        :linenos:
        :emphasize-lines: 3,6

        void foo()
        {
            int i;

            for(i=0; i<10; i++)
                printf("i: %d\n", a);
        }

    PHP

    .. code-block:: php
        :linenos:

        <?php
            echo 'hi';
        ?>

    HTML

    .. code-block:: html
        :linenos:

        <b>粗体</b>

    终端

    .. code-block:: console
        :linenos:

        $ ls
        $ uname -a

源码 ::

    .. code-block:: c
        :linenos:
        :emphasize-lines: 3,6

        void foo()
        {
            int i;

            for(i=0; i<10; i++)
                printf("i: %d\n", a);
        }

    .. code-block:: php
        :linenos:

        <?php
            echo 'hi';
        ?>

    .. code-block:: html
        :linenos:

        <b>粗体</b>

    .. code-block:: console
        :linenos:

        $ ls
        $ uname -a