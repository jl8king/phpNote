## 获取服务域名(例子：fly.cn)
```PHP
define('__SERVER_NAME__',$_SERVER['SERVER_NAME']);
```

## 获取域名或主机地址(例子：fly.cn:8081)
```PHP
echo $_SERVER['HTTP_HOST']."<br />";
```

## 获取网站物理跟路径
```PHP 
define('__BASE_PATH__',str_replace('\\','/',realpath(dirname(__FILE__).'/'))."/");
```

## 获取网页地址
```PHP
echo $_SERVER['PHP_SELF']."<br />";
```

## 获取网址参数
```PHP
echo $_SERVER["QUERY_STRING"]."<br />";
```

## 获取用户代理
```PHP
echo $_SERVER['HTTP_REFERER']."<br />";
```

