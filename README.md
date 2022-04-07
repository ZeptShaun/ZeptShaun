- 👋 Hi, I’m @ZeptShaun
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 🎶 右鍵 -> 表情符號 -> 選擇表情，即可輸入表情符號
<!--- 註解
ZeptShaun/ZeptShaun is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

` You can click ` the Preview 
 > link to take a look at your changes.


### 還是可以輸入中文的嗎？

正體中文也是沒有問題[^1] ！！

[^1]:first comment. <!--備註會顯示在最下面-->


```
<?php

//資料庫 設定
$db_host = "localhost"; //路徑
$db_username = "root"; //帳號
$db_password = "9876"; //密碼
$db_name = "tci_ss";
//pdo -> mysql連線
try{
	$db_link = new
	PDO("mysql:host={$db_host};dbname={$db_name};charset=utf8",$db_username,$db_password);
}catch(PDOException $e){
	print "資料庫連結失敗...Msg:{$e->getMessage()}<br/>";
	die();
}

?>
```


