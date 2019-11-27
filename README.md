清华大学镜像源，启动停止脚本（https://github.com/tuna/tunasync）

只需要修改对应配置文件路径即可

wget -P /etc/init.d/ https://raw.githubusercontent.com/whsir/tunasync-bin/master/tunasync-manager

wget -P /etc/init.d/ https://raw.githubusercontent.com/whsir/tunasync-bin/master/tunasync-worker

chmod +x /etc/init.d/tunasync-manager

chmod +x /etc/init.d/tunasync-worker
