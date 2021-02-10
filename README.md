### 使用ifconfig查看网卡ip



### netstat 查看网络端口号

netstat -tulpn 或者 netstat -ano

### netstat常用选项

t	显示tcp传输协议的连接状态

u	显示udp传输协议的连接状态

l	显示处于监听状态的网络连接

p	显示应用PID和程序名称

n	显示ip地址

a	显示所有连接

o	显示计时器



### 查看进程&&杀掉进程

ps -ef

kill -9 PID



### systemctl

start	启动服务

stop	停止服务

restart	重启服务

enable	设置开机启动

disable	禁止开启启动

status	查看服务状态

daemon-reload	重载服务配置文件

list-unit-files	列出所有服务