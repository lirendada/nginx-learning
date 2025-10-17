连接mysql数据库
mysql -uroot -p

创建数据库导入数据
create database ry default character set utf8;
use ry;
source sql/ry_20210924.sql
source sql/quartz.sql