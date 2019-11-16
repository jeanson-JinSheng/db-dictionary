# db-dictionary
导出数据字典工具，支持mysql、oracle

### 环境搭建
intelij idea pom文件，导入maven工程

### 配置
配置你的数据库信息
```
#数据库连接
db.url=jdbc:mysql://localhost:3306/sc_auth?useUnicode=true&characterEncoding=utf8&characterSetResults=utf8&useSSL=false&allowMultiQueries=true
#数据库用户
db.username=root
#数据库密码
db.password=root123
#数据库名
db.dbname=sc_auth
#数据库类型，当前支持mysql、oracle
db.dbType=mysql
#导出路径
exportPath=/Users/wish/Downloads/
```
### 启动
执行 DbDictionaryApplication main方法，即可导出数据字典。
