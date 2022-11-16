# 联通余量(v3)
[源仓库](https://github.com/xream/scripts/tree/main/surge/modules/10010v3)
> 本库仅供学习交流，如有问题请看源仓库

## 使用教程-青龙
> 脚本经由本人简单修改方便小白使用，详细教程和原脚本请看源仓库

### 第一步
青龙拉取脚本
```
ql raw https://raw.githubusercontent.com/liyw0205/Unicom-traffic-monitoring/main/10010.js
```

修改定时
> 以下定时为15分钟运行一次
```
*/15 * * * *
```

### 第二步
添加账号信息
脚本管理里找到脚本，在57行添加手机号,59添加服务密码,67行添加APPID
> APPID可以通过抓包或者验证码登录营业厅自动生成
<img src = "https://github.com/liyw0205/Connection-margin-v3-/blob/main/%E8%84%9A%E6%9C%AC/%E6%9D%A5%E6%BA%90/IMG_20221116_152154.jpg" >

修改完成就可以开始跑了
<img src = "https://github.com/liyw0205/Connection-margin-v3-/blob/main/%E8%84%9A%E6%9C%AC/%E6%9D%A5%E6%BA%90/IMG_20221116_163812.jpg" >
<img src = "https://github.com/liyw0205/Connection-margin-v3-/blob/main/%E8%84%9A%E6%9C%AC/%E6%9D%A5%E6%BA%90/IMG_20221116_163757.jpg" >