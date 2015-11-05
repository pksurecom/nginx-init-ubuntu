引用自开源中国博客：http://my.oschina.net/u/1156611/blog/180659

更改拷贝nginx文件到/etc/init.d/nginx，之后修改权限
chmod +x /etc/init.d/nginx

以后启动nginx可用
service nginx start

添加开机启动，执行
sudo update-rc.d -f nginx defaults

重启服务器查看是否成功！
