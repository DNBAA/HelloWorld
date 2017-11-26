<h1>a</h1><br>
a
```
use samp_db;
create table users(
	id int unsigned not null auto_increment primary key,
	username char(10) not null,
	password char(10) not null);

insert into users(username,password) values("DNBAA",PASSWORD("838xxxxx"));
```
a<br>
```
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
```
