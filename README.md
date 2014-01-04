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

