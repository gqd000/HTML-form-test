<html lang="en">

<head>
	<!--<meta http-equiv="refresh" content="3;url=http://www.baidu.com">-->
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta http-equiv="X-UA-Compatible" content="ie=edge">
	<title>表单测试</title>
	<style>
		body {
			text-align: center;
		}
	</style>
	<style type="text/css">
	body{
	background-image: url(https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1577721265798&di=d1cf3ad1b32b6f5a79cc85d47b601dca&imgtype=0&src=http%3A%2F%2Fbpic.ooopic.com%2F16%2F57%2F16%2F16571694-aa80bc5706a31b86e1d1f42b2922b826-1.jpg);
	background-size: cover;
	background-position: center 0;
	background-repeat: no-repeat;
	}
	</style>
</head>

<body>
	<form action="https://gqd000.github.io/Fun-Test/" method="GET">
		<h1>用户反馈界面</h1>
		<p>姓&nbsp;&nbsp;&nbsp;&nbsp;名：
			<input type="text" name="user" size="12" required maxlength="20"></p>
		<p>性&nbsp;&nbsp;&nbsp;&nbsp;别：
			<input type="radio" name="sex" value="male" />男
			<input type="radio" name="sex"  value="female" />女
		</p>
		<p>联系电话：
			<input type="number" value="number"  required minlength="11">
		</p>
		<p>电子邮箱：
			<input type="text" name="email" required="required">
		</p>
		<p>联系地址：
			<input type="text" name="address">
		</p>请输入你对网址的建议：<br>
		<textarea name="advice" cols="30" rows="5"></textarea>
		<p>银行卡号：
			<input type="number" name="userurl" required="required"></p>
		<p>密&nbsp;&nbsp;&nbsp;&nbsp;码：
			<input type="password" name="password"  required minlength="8"></p>
		<p>输入日期：
		<input type="date" required="required">
		</p>
		<p>输入数字：
		<input type="number" name="num" required="required">
		</p>
		<p>滑动滑条：
		<input type="range" name="滑条" required="required">
		</p>
		<input type="submit" value="登录">
		<input type="reset" name="清除">
		<br>
		<p><audio src="http://antiserver.kuwo.cn/anti.s?format=mp3|aac&rid=7069438&type=convert_url&response=res" controls autoplay></audio></p>
	</form>
</body>

</html>
