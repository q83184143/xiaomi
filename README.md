> 小米运动 微信步数 支付宝步数 `bash mimotion.sh $PARAMETER`  

####  使用AC每天自动运行
* Fork后进入仓库,点击`Settings`,右侧栏点击`Secrets`,点击`New secret`,添加`PARAMETER`的值为脚本支持的参数,间隔符使用空格  

| PARAMETER参数 | 说明 |
| -------- | ----- |
| `18812345678@password@10000-20000` | 账号@密码@随机步数起止点,可多次传入支持多账号 |
| `deviceId@*************` | 设备ID,无则使用随机ID |
| `token@*** chat_id@***` | telegram bot通知所需参数,无则不进行信息通知 |
| `others` | 其它说明查看脚本内容 |

* 默认每天18:35运行一次,也可在参数设置完毕后点击star仓库立即运行  

* 微信排行榜开关:微信-设置-通用-辅助功能-微信运动-隐私及提醒设置  

* 支付宝排行榜开关:支付宝运动-...-设置  

#### thanks:  
* jd_docker
* [mimotion](https://github.com/Squaregentleman/mimotion)
