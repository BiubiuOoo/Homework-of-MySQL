## 从零开始学习MySQL语言命令

### 一、介绍对数据库操作相关的命令
#### 1.创建一个新的数据库

**执行命令如下:**

```SQL
	CREATE DATABASE biu1;   # biu1为数据库名称
```
##### 执行上面SQL语句结果显示如图所示：
![](https://github.com/BiubiuOoo/Homework-of-MySQL/blob/master/images/1.png?raw=true)

#### 2.查看和选择数据库：

**执行命令如下：**

```SQL
	SHOW DATABASES; 	# 显示全部数据库
	USE biu1;		# 选择biu1数据库
```
##### 执行上面SQL语句结果显示如图所示：
![](https://github.com/BiubiuOoo/Homework-of-MySQL/blob/master/images/2.png?raw=true)

#### 3.删除数据库：

**执行命令如下：**

```SQL
	DROP DATABASE biu1; 	# 删除biu1数据库
```
##### 执行上面SQL语句结果显示如图所示：
![](https://github.com/BiubiuOoo/Homework-of-MySQL/blob/master/images/3.png?raw=true)

### 二、如何查看MySQL数据库中的存储引擎
#### 1.查看所支持的存储引擎

**执行命令如下:**

```SQL
	SHOW ENGINES;  
```
##### 执行上面SQL语句结果显示如图所示：
![](https://github.com/BiubiuOoo/Homework-of-MySQL/blob/master/images/4.png?raw=true) 

#### 2.查看默认的存储引擎

**执行命令如下:**

```MySQL
	SHOW VARIABLES LIKE '%storage_engine%';  
```
##### 执行上面SQL语句结果显示如图所示：
![](https://github.com/BiubiuOoo/Homework-of-MySQL/blob/master/images/5.png?raw=true) 

### 三、介绍对表操作的相关命令
#### 1.在数据库中创建一个新的表

**执行命令如下:**

```SQL
	CREATE TABLE t_dept(
 	deptno INT,
	dname VARCHAR(20),
	loc VARCHAR(40)
	); 
```
##### 执行上面SQL语句结果显示如图所示：
![](https://github.com/BiubiuOoo/Homework-of-MySQL/blob/master/images/6.png?raw=true) 

#### 2.查看表的定义信息

**执行命令如下:**

```SQL
	DESCRIBE t_dept;	# 查看表的定义
	SHOW CREATE TABLE t_dept; 	 # 查看表的详细定义
```
##### 执行上面SQL语句结果显示如图所示：
![](https://github.com/BiubiuOoo/Homework-of-MySQL/blob/master/images/7.png?raw=true) 

#### 3.删除表

**执行命令如下:**

```SQL
	DROP TABLE t_dept;	#删除表t_dept
	DESCRIBE t_dept;      #查看表t_dept是否存在
```
##### 执行上面SQL语句结果显示如图所示：
![](https://github.com/BiubiuOoo/Homework-of-MySQL/blob/master/images/8.png?raw=true) 

