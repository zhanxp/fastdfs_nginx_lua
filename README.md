# fastdfs_nginx_lua
==================
fastdfs nginx lua 自动生成缩略图，无group版

注意点：
----------------
＃修改 fastdfs.lua 中 fdfs:set_tracker("192.168.1.196", 22122)  为自己的IP
＃nginx.conf 中添加 user root;
＃安装 GraphicsMagick

使用效果：
----------------
http://www.xxxx.com/M00/00/19/wKgB0lcQlqeESQT6AAAAAFcjGOY583.jpg_40x40.jpg
http://www.xxxx.com/M00/00/19/wKgB0lcQlqeESQT6AAAAAFcjGOY583.jpg_80x80.jpg
http://www.xxxx.com/M00/00/19/wKgB0lcQlqeESQT6AAAAAFcjGOY583.jpg_160x100.jpg
http://www.xxxx.com/M00/00/19/wKgB0lcQlqeESQT6AAAAAFcjGOY583.jpg_160x100.jpg
http://www.xxxx.com/M00/00/19/wKgB0lcQlqeESQT6AAAAAFcjGOY583.jpg_320x200.jpg


＊fastdfs.lua 中 可以配置
＊local image_sizes = {"40x40", "80x80", "160x160", "320x320","640x400","320x200","160x100"};  

