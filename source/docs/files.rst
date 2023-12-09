.. index::
   single: 引入外部文件

.. _我的锚点:

============
引入外部文件
============

.. warning::

   该语法不属于 rst ，属于 Sphinx 的配置。

由于某些需要，需要引入外部JS、样式。

此时，你需要在 **conf.py** 文件中，

增加

.. code-block:: bash

    html_js_files = ['script.js',
                     'https://example.com/scripts/custom.js',
                     ('custom.js', {'async': 'async'})]

    html_css_files = ['custom.css'
                      'https://example.com/css/custom.css',
                      ('print.css', {'media': 'print'})]


并将，引入的文件放入 **_static** 目录中。

详见 `Options for HTML output <https://www.sphinx-doc.org/en/latest/usage/configuration.html#options-for-html-output>`_ ，了解更多信息。