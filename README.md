该版本的发布系统只支持全量发布和回滚，不支持单文件发布
该系统可部署在单独的服务器上，但消息worker端必须与Git仓库部署在一起
使用的python扩展如下：

  tornado

  oslo.config

  sqlalchemy

  python-mysql

  fabric3

  pika

  pygit2

  oss2
