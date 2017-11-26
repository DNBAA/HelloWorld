 ## 1. 编写一个完整的html登录页面并提交;里面要有登录表单，表单有用户名和密码，点击提交时，使用js做本地验证
<br>

	<!DOCTYPE html>
	<html>
	<head>

	</head>
	<body>
	<script type="text/javascript">
	function validateFrom()
	{
		var x=document.forms["myForm"]["Username"].value;
		var y=document.forms["myForm"]["Password"].value;
		if (x!="admin"||y!="pwd")
		{
			alert("账号或密码错误");
			return false;
		}
	}
		
	</script>
	<form name="myForm" onsubmit="return validateFrom()" method="post">
	Username:<br>
	<input type="text" name="Username" >
	<br>
	Password:<br>
	<input type="password" name="Password">
	<br><br>
	<input type="submit" value="登陆">
	</form>
	
	</body>

 ## 4.手动创建一个数据库，提交sql文件<br>

```
CREATE DATABASE xi_dian;

CREATE TABLE xi_dian.member (
       id int(11) unsigned not null auto_increment primary key,
       username varchar(255) not null,
       password varchar(255)
       );
           
INSERT INTO xi_dian.member (
       username,
       password
       )
       VALUES (
       'sz1900599168',
       PASSWORD('123456')
       );
       
INSERT INTO xi_dian.member (
       username,
       password
       )
       VALUES (
       'LeeH0ng',
       PASSWORD('123456')
       );
       
INSERT INTO xi_dian.member (
       username,
       password
       )
       VALUES (
       'WeC9',
       PASSWORD('123456')
       );
       
INSERT INTO xi_dian.member (
       username,
       password
       )
       VALUES (
       'WeiiiiiA',
       PASSWORD('123456')
       );
       
INSERT INTO xi_dian.member (
       username,
       password
       )
       VALUES (
       'ZoEplA',
       PASSWORD('123456')
       );
       
INSERT INTO xi_dian.member (
       username,
       password
       )
       VALUES (
       'loading2772',
       PASSWORD('123456')
       );
       
INSERT INTO xi_dian.member (
       username,
       password
       )
       VALUES (
       'mingmei233',
       PASSWORD('123456')
       );
       
INSERT INTO xi_dian.member (
       username,
       password
       )
       VALUES (
       'sulayman',
       PASSWORD('123456')
       );   
```
