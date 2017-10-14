# 魔豆服务器开发基础项目框架
## Maven的集成和使用

### 为什么要使用Maven
1. 抛弃以前的Jar文件引入方式，防止文件冲突
2. 如何查找Maven库项目
### Maven集成到项目
1. 如何引入其他库文件
2. scope的作用
3. optional的作用
4. 项目如何打包？打包相关配置，resource|plugin
### Maven常用命令使用
1. mvn clean （eg：mvn clean package @DskipTests)
### Maven项目中管理
### 定义Maven项目原型
## 极力推荐SpringBoot作为开发框架
### SpringBoot与SpringMVC的区别
### SpringBoot的优势
1. 官网提供繁多的第三方库（提供官方中文文档）
2. 几乎零配置编码（Bean的方便配置，SpringBootApplication, Configuration,自定义属性@Value，防范在linux上会失效，第三种）
3. 第三方项目无法继承到SpringBoot，如何采用xml配置。（ImportResource, PropertySource)
### SpringBoot部署方式
1. jar命令启动，可切换启动不同环境
2. mvn 打包
## 项目中Mybatis的使用
### 数据分页插件
1. 全局获取
2. 直接使用Page实体

### 二级缓存集成和业务缓存集成
### 代码自动生成器
1. 自动反向数据生成业务、实体、Mapper文件
### 实体CRUD简易操作
### 数据操作拦截器
1. 公共数据填充，配套代码生成
2.
## Idea有利的插件

## 基于SpringBoot+Maven+MyBatis集成框架
### 基础项目结构
1. common、parent、service、interface、admin
2. 采用template方式获取，不用重新搭建项目结构
3. 需要提供基础项目需要修改的文件
4.

### 针对各种场景的解决方案
1. 如何解决棘手的跨域问题
2. 如何控制不同访问权限
3. 如何配置静态资源控制
4. 如何是灵活打包
5. 解决jar包引入混乱问题
6. 枚举类型反转
### 权限解决方案
### session同步解决方案
### 日志高级使用方法
### 自动生成API插件集成
### 全局配置处理
### 统一后台开发语言Freemark
