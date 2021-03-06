微信公众平台 Python 开发包文档
====================================

非官方微信公众平台 Python 开发包，包括官方接口和非官方接口。

* 官方接口依据公众平台开发者文档编写，可以实现公众平台开发者文档中的所有内容，具体不列举，请查看 ``WechatBasic`` 文档；

* 非官方接口采用模拟登陆的方式，可以实现更多高级功能，但也存在相应风险。

  目前提供的非官方接口功能有：

  * 主动对指定用户发送文本消息
  * 主动对指定用户发送图片消息
  * 主动对指定用户发送语音消息
  * 主动对指定用户发送视频消息
  * 获取指定用户的个人信息
  * 获取用户列表
  * 获取分组列表
  * 获取图文信息列表
  * 获取与指定用户的对话内容
  * 向指定用户发送图文消息(必须从图文库里选取消息ID传入)
  * 在素材库中创建图文消息
  * 上传素材至素材库 (图片/语音/视频)
  * 向特定用户发送媒体文件 (图片/语音/视频)
  * 获取素材库文件列表
  * 获取用户头像
  * 获取新消息的数目
  * 获取最新一条消息
  * 获取消息列表
  * 根据消息ID获取图片消息内容
  * 根据消息ID获取语音消息内容
  * 根据消息ID获取视频消息内容
  * 获取图文分析信息

**请注意：本开发包并不打算提供一个独立的完整微信解决方案，我们更希望这个开发包可以非常融洽的在各个框架中进行集成并使用，对于HTTP请求及响应方面并不涉及，该开发包仅仅接受必要参数，提供各种微信操作的方法，并返回相应的可以响应微信服务器的数据(Response)或操作执行结果。**

项目地址：`https://github.com/doraemonext/wechat-python-sdk <https://github.com/doraemonext/wechat-python-sdk>`_

目录：

.. toctree::
   :maxdepth: 2

   install
   tutorial
   basic
   ext
   messages
   context
   exceptions
   faq

感谢 `WeRoBot <https://github.com/whtsky/WeRoBot>`_ 项目，本项目中官方接口的许多代码均借鉴于此。

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
