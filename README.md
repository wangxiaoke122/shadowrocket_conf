### 全自动切换到可以解锁奈飞ip脚本
```
https://raw.githubusercontent.com/jonyhubber/shadowrocket_conf/master/AutoWarpIp.sh && chmod +x AutoWarpIp.sh && clear && ./AutoWarpIp.sh
```
### 添加crontab脚本任务
```
crontab -e
* */1 * * * /bin/bash /root/AutoWarpIp.sh
```
