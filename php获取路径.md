## ��ȡ��������(���ӣ�fly.cn)
```PHP
define('__SERVER_NAME__',$_SERVER['SERVER_NAME']);
```

## ��ȡ������������ַ(���ӣ�fly.cn:8081)
```PHP
echo $_SERVER['HTTP_HOST']."<br />";
```

## ��ȡ��վ�����·��
```PHP 
define('__BASE_PATH__',str_replace('\\','/',realpath(dirname(__FILE__).'/'))."/");
```

## ��ȡ��ҳ��ַ
```PHP
echo $_SERVER['PHP_SELF']."<br />";
```

## ��ȡ��ַ����
```PHP
echo $_SERVER["QUERY_STRING"]."<br />";
```

## ��ȡ�û�����
```PHP
echo $_SERVER['HTTP_REFERER']."<br />";
```

