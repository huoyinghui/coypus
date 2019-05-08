# coypus  海狸鼠

> 基于 goframe 框架,完成 go web后端 基本组件开发

## 目录

```
- app	  业务逻辑层	所有的业务逻辑存放目录。
    - api	业务接口	接收/解析用户输入参数的入口/接口层。
    - model	数据模型	数据管理层，仅用于操作管理数据，如数据库操作。
    - service	逻辑封装	业务逻辑封装层，实现特定的业务需求，可供不同的包调用。
- boot	初始化包	用于项目初始化参数设置。
- config	配置管理	所有的配置文件存放目录。
- docfile	项目文档	DOC项目文档，如: 设计文档、脚本文件等等。
- library	公共库包	公共的功能封装包，往往不包含业务需求实现。
- log           日志
- public	静态目录	仅有该目录下的文件才能对外提供静态服务访问。
- router	路由注册	用于路由统一的注册管理。
- template	模板文件	MVC模板文件存放的目录。
- test          单元测试
- go.mod	依赖管理	使用Go Module包管理的依赖描述文件。
- main.go	入口文件	程序入口文件。
```

## 实现功能
* 登录
* jwt验证
* 权限验证(casbin)


## 作者
* 何全