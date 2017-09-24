# 目录

---

* [序](/Preface/README.md)

  * [序言](/Preface/Preface.md)

* [第一章 介绍 AAA 和 RADIUS](/Chapter01/README.md)

  * Authentication, Authorization 和 Accounting
    * Authentication （认证）
    * Authorization （授权）
    * Accounting （计费）
  * RADIUS
    * RADIUS 协议 \(RFC 2865\)
    * RADIUS 计费 \(RFC 2866\)
    * RADIUS 扩展
  * FreeRADIUS
  * Summary

* 第二章 安装

  * 开始之前
  * 预编译程序
  * Time for action - 安装 FreeRADIUS
  * 从源码编译
  * Time for action - 编译 CentOS RPMs
  * Time for action - SUSE 从tarball 到 RPMs
  * Time for action - Ubuntu 从tarball 到 debs
  * 安装的二进制程序
  * 是否作为 root 运行
  * 客户端程序的字典访问
  * 确保合适的启动
  * Summary

* 第三章 开始使用 FreeRADIUS

  * 简单的安装
  * Time for action - 配置 FreeRADIUS
  * 获取帮助
  * 发现 FreeRADIUS 可利用的 man pages
  * 黄金法则
  * radiusd 内部
  * Summary

* 第四章 Authentication （认证）

  * 认证协议
    * PAP
    * CHAP
    * MS-CHAP
  * FreeRADIUS - 在认证之前 Authorize（授权、委托）
  * Time for action - 使用 FreeRADIUS 认证某个用户
  * 存储密码
  * Time for action – 哈希 our password
  * 其他的认证方法
  * Summary

* 第五章 用户名和密码的来源

  * 用户存储
  * 系统用户
  * Time for action – 在 FreeRADIUS 中包含 Linux 系统用户
  * Mysql 作为用户存储
  * Time for action – 在 FreeRADIUS 中包含 Mysql 数据库
  * LDAP 作为用户存储
  * Time for action – 连接 FreeRADIUS 到 LDAP
  * AD 作为用户存储
  * Time for action – 连接 FreeRADIUS 到 AD
  * Summary

* 第六章 Accounting （计费）

  * 本章的要求
  * 基本的计费
  * Time for action – 模拟来自 NAS 的计费
  * 限制用户的同时会话
  * Time for action – 限制用户的同时会话
  * 限制某个用户的使用量
  * Time for action – 限制用户的同时会话
  * 计费数据的管理
  * Summary

* 第七章 Authorization（授权）

  * 实现限制
  * 在 FreeRADIUS 中授权
  * 介绍 unlang
  * Time for action – 在 unlang 中使用 if 声明
  * Time for action – 引用属性
  * Time for action – SQL 声明作为变量
  * Time for action – 设置变量的默认值
  * Time for action – 使用命令替换
  * Time for action – 使用正则表达式
  * unlang 实践
  * Time for action – 使用unlang创建数据计数器
  * Summary

* 第八章 虚拟服务器

  * 为什么使用虚拟服务器
  * 定义和启用虚拟服务器
  * Time for action – 创建两个虚拟服务器
  * 使用启用的虚拟服务器
  * Time for action – 使用虚拟服务器
  * 虚拟服务器的”欢乐时光”
  * Time for action – 包含 Hotspot “欢乐时光” 策略
  * 使用虚拟服务器加强现有的配置
  * 为计算机创建一个虚拟服务器
  * 科学能力
  * 预定义的虚拟服务器
  * Summary

* 第九章 模块

  * 安装的、可用的和缺失的模块
  * Time for action – 发现可用的模块
  * 包括和配置头文件
  * Time for action – 包含 expiration 和 linelog 模块
  * 使用带有不同配置文件的模块
  * 模块的顺序和返回码
  * Time for action – 研究模块的顺序
  * 一些有趣的模块
  * Summary

* 第十章 EAP

  * EAP 基础
  * EAP 实践
  * Time for action – 在 FreeRADIUS 用 JRadius 测试 EAP
  * 模拟器
  * 在 EAP 生产中
  * Time for action – 为你的组织创建一个 RADIUS PKI
  * Time for action – 在 inner-tunnel 测试 authentication
  * 虚拟服务器
  * Time for action – 禁用未使用的EAP方法
  * Summary

* 第十一章 Dictionaries （字典）

  * 为什么需要字典
  * 怎样包含字典
  * Time for action – 包含新的字典
  * FreeRADIUS 怎样包含 dictionary 文件
  * Time for action – 更新 MikroTik 字典
  * 字典文件的格式
  * Summary

* 第十二章 漫游和代理

  * 漫游 - 概览
  * Realms
  * Time for action – 研究 FreeRADIUS 中默认的 realms
  * Time for action – 激活 NULL realm
  * Time for action – 定义 realm
  * Time for action – 拒绝没有 realm 的请求
  * 代理
  * Time for action – 配置两个组织之间的代理
  * Time for action – 过虑 被home 服务器返回的 reply attributes
  * Time for action – 为状态检查使用更好的方式
  * Time for action – 模拟代理的计费
  * Summary

* 第十三章 故障排除

  * 基本原则
  * FreeRADIUS 未启动
  * FreeRADIUS 缓慢
  * Time for action – 进行基准速度测试
  * FreeRADIUS 死亡
  * 客户机相关的问题
  * Time for action – 使用 control-socket 和 raddebug
  * 认证用户
  * 代理问题
  * 在线资源
  * 使用邮件列表
  * Summary

* 附录 每章问题的答案



