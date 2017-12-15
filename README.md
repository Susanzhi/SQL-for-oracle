# SQL-for-oracle
基本SQL语句以及空间索引
登陆语句
C: > sqlplus /as sysdba
//不显露密码的登陆方式
C: > sqlplus                      
   Enter user-name：sys
   Enter password：password as sysdba 
C: > sqlplus /nolog             //登陆但不连接数据库
SQL> conn /as sysdba
C: > sqlplus scott/tiger      --非管理员用户登陆
C: > sqlplus scott/tiger@orcl    --非管理员用户使用tns别名登陆
C: > sqlplus sys/password@orcl as sysdba --管理员用户使用tns别名登陆
