基于清华大学镜像源`https://github.com/tuna/tunasync`，一个shell启动停止脚本，使用于CentOS

将tunasync编译好的程序放在/usr/bin目录下

下载启动停止脚本

wget -P /etc/init.d/ https://raw.githubusercontent.com/whsir/tunasync-bin/master/tunasync-manager

wget -P /etc/init.d/ https://raw.githubusercontent.com/whsir/tunasync-bin/master/tunasync-worker

赋予执行权限

chmod +x /etc/init.d/tunasync-manager

chmod +x /etc/init.d/tunasync-worker

修改脚本中配置文件路径

OPTIONS="worker --config /etc/tunasync/worker.conf"
