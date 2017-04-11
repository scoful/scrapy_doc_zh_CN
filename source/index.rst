.. _topics-index:

=======================================
Scrapy |version| 中英双语文档 by scoful
=======================================

This documentation contains everything you need to know about Scrapy.
  这个文档包含所有的Scrapy相关的资料。

Getting help | 获取帮助
=======================

Having trouble? We’d like to help!
  有问题？我们很希望能给予帮助！

* Try the :doc:`FAQ <faq>` -- it's got answers to some common questions.
* 尝试看看 :doc:`问题集锦 <faq>` -- 它包含大部分大家都会遇到的问题。
* Looking for specific information? Try the :ref:`genindex` or :ref:`modindex`.
* 想找更具体的信息? 试试看 :ref:`genindex` 或是 :ref:`modindex` (索引或是模块索引)。
* Ask or search questions in `StackOverflow using the scrapy tag`_,
* 或是在 `StackOverflow using the scrapy tag`_ 上提问或直接搜索，
* Search for information in the `archives of the scrapy-users mailing list`_, or `post a question`_.
* 在邮件列表里搜索 `archives of the scrapy-users mailing list`_ , 或是提问 `post a question`_ 。
* Ask a question in the `#scrapy IRC channel`_,
* 在这个频道上提问 `#scrapy IRC channel`_，
* Report bugs with Scrapy in our `issue tracker`_.
* 在 `issue tracker`_ 上报bug。


.. _archives of the scrapy-users mailing list: https://groups.google.com/forum/#!forum/scrapy-users
.. _post a question: https://groups.google.com/forum/#!forum/scrapy-users
.. _StackOverflow using the scrapy tag: https://stackoverflow.com/tags/scrapy
.. _#scrapy IRC channel: irc://irc.freenode.net/scrapy
.. _issue tracker: https://github.com/scrapy/scrapy/issues

First steps | 第一步
====================

.. toctree::
   :caption: First steps
   :hidden:

   intro/overview
   intro/install
   intro/tutorial
   intro/examples

:doc:`intro/overview`
    Understand what Scrapy is and how it can help you.
      了解Scrapy是什么及它有什么用。

:doc:`intro/install`
    Get Scrapy installed on your computer.
      安装Scrapy。

:doc:`intro/tutorial`
    Write your first Scrapy project.
      开发第一个Scrapy项目。

:doc:`intro/examples`
    Learn more by playing with a pre-made Scrapy project.
      学习怎么玩转一个成品Scrapy项目。

.. _section-basics:

Basic concepts | 基础概念
=========================

.. toctree::
   :caption: Basic concepts
   :hidden:

   topics/commands
   topics/spiders
   topics/selectors
   topics/items
   topics/loaders
   topics/shell
   topics/item-pipeline
   topics/feed-exports
   topics/request-response
   topics/link-extractors
   topics/settings
   topics/exceptions


:doc:`topics/commands`
    Learn about the command-line tool used to manage your Scrapy project.
      学习用命令行模式管理Scrapy项目。

:doc:`topics/spiders`
    Write the rules to crawl your websites.
      编写爬取网站的爬虫。

:doc:`topics/selectors`
    Extract the data from web pages using XPath.
      用XPath来从网页上提取数据。

:doc:`topics/shell`
    Test your extraction code in an interactive environment.
      在互动环境测试爬虫代码。

:doc:`topics/items`
    Define the data you want to scrape.
      定义想要爬取的数据结构。

:doc:`topics/loaders`
    Populate your items with the extracted data.
      把爬取到的数据填充到数据结构里。

:doc:`topics/item-pipeline`
    Post-process and store your scraped data.
      爬取完数据后处理数据并保存。

:doc:`topics/feed-exports`
    Output your scraped data using different formats and storages.
      导出爬取的数据，用不同的格式存储。

:doc:`topics/request-response`
    Understand the classes used to represent HTTP requests and responses.
      理解用到的 HTTP requests 和 responses 。

:doc:`topics/link-extractors`
    Convenient classes to extract links to follow from pages.
      便捷得爬取网页上的链接。

:doc:`topics/settings`
    Learn how to configure Scrapy and see all :ref:`available settings <topics-settings-ref>`.
      学习如何配置Scrapy ，查看Scrapy所有的配置 :ref:`available settings <topics-settings-ref>` 。

:doc:`topics/exceptions`
    See all available exceptions and their meaning.
      查看所有可能出现的异常报错。

Built-in services | 内置服务
============================

.. toctree::
   :caption: Built-in services
   :hidden:

   topics/logging
   topics/stats
   topics/email
   topics/telnetconsole
   topics/webservice

:doc:`topics/logging`
    Learn how to use Python's builtin logging on Scrapy.
      学习如何在Scrapy上使用python内置的日志模块。

:doc:`topics/stats`
    Collect statistics about your scraping crawler.
      收集你的爬虫的统计信息。

:doc:`topics/email`
    Send email notifications when certain events occur.
      当某些事件发生时自动发邮件提醒。

:doc:`topics/telnetconsole`
    Inspect a running crawler using a built-in Python console.
      通过python内置的控制台检查爬虫。

:doc:`topics/webservice`
    Monitor and control a crawler using a web service.
      通过一个网页服务来监控和控制爬虫。


Solving specific problems | 解决具体的问题
==========================================

.. toctree::
   :caption: Solving specific problems
   :hidden:

   faq
   topics/debug
   topics/contracts
   topics/practices
   topics/broad-crawls
   topics/firefox
   topics/firebug
   topics/leaks
   topics/media-pipeline
   topics/deploy
   topics/autothrottle
   topics/benchmarking
   topics/jobs

:doc:`faq`
    Get answers to most frequently asked questions.
      看看大部分人经常问到的问题的答案。

:doc:`topics/debug`
    Learn how to debug common problems of your scrapy spider.
      学习怎么调试你的爬虫项目。

:doc:`topics/contracts`
    Learn how to use contracts for testing your spiders.
      学习怎么用contracts(#todo契约？合同？)来测试你的爬虫。
:doc:`topics/practices`
    Get familiar with some Scrapy common practices.
      熟悉一些Scrapy实践例子。

:doc:`topics/broad-crawls`
    Tune Scrapy for crawling a lot domains in parallel.
      当爬很多域名的时候，如何并行优化。

:doc:`topics/firefox`
    Learn how to scrape with Firefox and some useful add-ons.
      学习如何借助Firefox和一些有用的插件。

:doc:`topics/firebug`
    Learn how to scrape efficiently using Firebug.
      学习如何有效的利用Firebug。

:doc:`topics/leaks`
    Learn how to find and get rid of memory leaks in your crawler.
      学习在你的爬虫项目里找到和解决内存溢出。

:doc:`topics/media-pipeline`
    Download files and/or images associated with your scraped items.
      下载相关的文件和图片。

:doc:`topics/deploy`
    Deploying your Scrapy spiders and run them in a remote server.
      在远程服务器上部署爬虫。

:doc:`topics/autothrottle`
    Adjust crawl rate dynamically based on load.
      根据负载动态调整爬虫速度。

:doc:`topics/benchmarking`
    Check how Scrapy performs on your hardware.
      检查爬虫是如何在硬件(#todo?)上运行的。

:doc:`topics/jobs`
    Learn how to pause and resume crawls for large spiders.
      学习如何暂停和恢复爬虫。

.. _extending-scrapy:

Extending Scrapy | 相关拓展
===========================

.. toctree::
   :caption: Extending Scrapy
   :hidden:

   topics/architecture
   topics/downloader-middleware
   topics/spider-middleware
   topics/extensions
   topics/api
   topics/signals
   topics/exporters


:doc:`topics/architecture`
    Understand the Scrapy architecture.
      理解Scrapy的体系结构。

:doc:`topics/downloader-middleware`
    Customize how pages get requested and downloaded.
      设计一个页面如何被请求和下载。

:doc:`topics/spider-middleware`
    Customize the input and output of your spiders.
      设计爬虫的入参和出参。

:doc:`topics/extensions`
    Extend Scrapy with your custom functionality
      自定义拓展Scrapy的功能。

:doc:`topics/api`
    Use it on extensions and middlewares to extend Scrapy functionality
      用中间件拓展Scrapy的功能。

:doc:`topics/signals`
    See all available signals and how to work with them.
      查看所有可能的信号(#todo？)及其如何运行的。

:doc:`topics/exporters`
    Quickly export your scraped items to a file (XML, CSV, etc).
      快速导出爬取的数据到本地文件里，支持XML，CSV等等。


All the rest | 其他事项
=======================

.. toctree::
   :caption: All the rest
   :hidden:

   news
   contributing
   versioning

:doc:`news`
    See what has changed in recent Scrapy versions.
      查看最新版本的Scrapy的改变。

:doc:`contributing`
    Learn how to contribute to the Scrapy project.
      学习如何给Scrapy本体项目做贡献。

:doc:`versioning`
    Understand Scrapy versioning and API stability.
      了解Scrapy的版本管理和API稳定性。
