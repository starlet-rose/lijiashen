# lijiashen
 git clone https://github.com/gaocuiqun/user-management.git  克隆项目
ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'ljs2455009782@'      改myqky密码，注：后面加；号
show databases 查看数据库所建内容
《《《《
create database sampledb; 
use sampledb;  
create table registered_user (
  user_id varchar(50) not null primary key,
  user_name varchar(50) not null,
  password varchar(50)
);       
SELECT * FROM registered_user r;

insert into registered_user(
  user_id,
  user_name,
  password
) values (
  '1000',
  'Gaocuiqun',
  'my-secret-pw'
);  

》》》》数据库
