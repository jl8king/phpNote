##��ȡ��������(���ӣ�fly.cn)
###define('__SERVER_NAME__',$_SERVER['SERVER_NAME']);

##��ȡ������������ַ(���ӣ�fly.cn:8081)
###echo $_SERVER['HTTP_HOST']."<br />";

##��ȡ��վ�����·��
###define('__BASE_PATH__',str_replace('\\','/',realpath(dirname(__FILE__).'/'))."/");

##��ȡ��ҳ��ַ
###echo $_SERVER['PHP_SELF']."<br />";
  
##��ȡ��ַ����
###echo $_SERVER["QUERY_STRING"]."<br />";
  
##��ȡ�û�����
###echo $_SERVER['HTTP_REFERER']."<br />";
