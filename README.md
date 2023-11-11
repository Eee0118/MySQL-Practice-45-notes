# 《MySQL实战45讲学习笔记

本书主要从FastAPI核心功能出发，结合后端项目介绍各组件使用，包括： 
1. 熟悉FastAPI初始化及配置，并了解HTTP的8个方法的构建，详细介绍了`@app`的装饰器使用，以及FastAPI的路径参数、查询参数、默认参数、可选参数、请求正文、请求头、响应数据等。
2. 结合智能旅游系统项目，探索核心功能，包含API服务的实现、注册router、状态响应码、异常处理、转换JSON兼容的对象、后台任务埋点、日志管理等。
3. 结合在线食谱系统，了解依赖注入原理，包含依赖函数和可调用类的注入、缓存依赖项以及注入依赖项的方法，还可以采用第三方容器`Dependency Inject`和`Lagom`。
4. 结合大学企业资源计划系统，采用子域分解方式，构建教师、图书馆和学生管理模块，结合领域模型，实现微服务应用程序，其中包括子模块的挂载、异常处理、集中日志记录、配置管理等。
5. 结合健身俱乐部管理系统，介绍使用`SQLAlchemy`创建CRUD事务，使用多种ORM框架（Pony ORM、Peewee）构建存储库层，还介绍了CQRS设计模式，分离查询事务与命令事务（插入、更新、删除）
6. 结合在线图书转售系统，介绍使用`PyMongo`、`Motor`创建CRUD事务，比较`MongoEngine`、`Beanie`、`ODMantic`和`MongoFrames`的功能，其中`Beanie`是`Motor`的升级版，`ODMantic`是`Motor`和`Pydantic`的组合版，创建异步CRUD时，可以使用`ODMantic`框架，创建同步CRUD时，可以使用`MongoFrames`框架。
7. 结合安全的在线拍卖系统，介绍身份验证和授权管理，身份验证包含`Basic`和`Digest`两个基础的身份验证、基于`OAuth2`的密码身份验证、`JWT`的`token`密钥验证，授权管理包括基于作用域的授权、`OAuth2AuthorizationCodeBearer`的授权码流，并和`Keycloak`、`Auth0`、`Okta`等系统集成，完成身份和用户管理。
8. 结合在线报纸管理系统，介绍协程和异步后台任务的创建与使用，并了解`Celery`任务，使用`RabbitMQ`或`Kafka`发布和订阅消息。还通过`rx`包介绍反应式编程范式。
9. 结合在线餐厅评论系统，介绍一些FastAPI高级功能，包括基于`request.session`的会话管理、使用`CORSMiddleware`的CORS解决方案、自定义`APIRoute`和`Request`解决数据正文的加解密，还介绍了响应的选择、OpenAPI 3.x规范，以及使用pytest进行API端点测试。
10. 结合定期普查和计算系统的基本框架，介绍Piccolo ORM框架，使用`sympy`、`numpy`、`pandas`和`scipy`进行数据处理与统计分析，并通过Celery模拟BPMN工作流，还介绍了Neo4j数据库的集成。
11. 结合在线体育管理系统，介绍基于`starlette-exporter`的API服务监控、基于`opentelemetry-exporter-jaeger`的服务跟踪、基于`py_eureka_client`的服务注册和发现，还对Docker部署、Flask和Django子应用的集成进行了讲解。

建议学习时长：6天

原书项目地址：https://github.com/PacktPublishing/Building-Python-Microservices-with-FastAPI

## 在线阅读地址
在线阅读地址：https://relph1119.github.io/fastapi-learning-notes

## 项目结构
<pre>
docs---------------------------------------学习笔记
codes--------------------------------------代码练习
+---ch01---------------------------------------第1章 设置FastAPI
requirements.txt---------------------------运行环境依赖包
</pre>

## 环境安装
### Python版本
Python 3.10 Windows环境

### 运行环境配置
安装相关的依赖包
```shell
pip install -r requirements.txt
```