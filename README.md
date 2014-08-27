haxe_s
======

NEKOVM:
安装Apache
在安装目录conf中httpd.conf文件添加：
#BEGIN NEKO
  LoadModule neko_module "C:/HaxeToolkit/neko/mod_neko2.ndll"
  AddHandler neko-handler .n
  DirectoryIndex index.n
#END NEKO

//解决haxe - mysql 入库中文的问题
var sql = "SET NAMES 'utf8';";  
cnx.request(sql);

SomeCode：
var _box2:Box = cast(e.currentTarget);
var _target = Type.getClassFields(_box)[20];
		
