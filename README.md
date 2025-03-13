## 上马自动签到 [![Run Auto Sign](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml/badge.svg)](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml)

### 基于 Node.js + GitHub Action 实现上海马拉松官网每日签到

### Use 使用

1. Fork本项目（顺手点Star以示鼓励～🥳）
2. 在Repo的Setting页面，添加名为上马官网的用户名：`SM_USERNAME`和密码：`SM_PASSWORD`的Secret 
3. 手动测试运行
<img width="1444" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/695683c9-fbc2-4cab-9ef8-41e2ddf59b78">
在控制台应该能看到 `签到成功/请勿重复签到` 的提示
<img width="990" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/399e89f7-2ad6-486e-9e67-8953564ec528">


### 关于Job执行时间
签到Job执行时间是**UTC时间0点**，也就是**北京时间8点**执行，**不过由于GitHub的负载比较重**，真正签到时间可能延后一段时间，一般是几十分钟，这个延迟时间取决于GitHub Action的负载。

### 申明
- 本项目仅做学习交流, 禁止用于各种非法途径
- Auto Sign-in run successful on Fri Feb 21 01:03:58 UTC 2025
- Auto Sign-in run successful on Sat Feb 22 01:01:55 UTC 2025
- Auto Sign-in run successful on Sun Feb 23 01:08:19 UTC 2025
- Auto Sign-in run successful on Mon Feb 24 01:05:44 UTC 2025
- Auto Sign-in run successful on Tue Feb 25 01:05:01 UTC 2025
- Auto Sign-in run successful on Wed Feb 26 01:04:51 UTC 2025
- Auto Sign-in run successful on Thu Feb 27 01:04:47 UTC 2025
- Auto Sign-in run successful on Fri Feb 28 01:05:17 UTC 2025
- Auto Sign-in run successful on Sat Mar  1 01:09:55 UTC 2025
- Auto Sign-in run successful on Sun Mar  2 01:09:01 UTC 2025
- Auto Sign-in run successful on Mon Mar  3 01:07:10 UTC 2025
- Auto Sign-in run successful on Tue Mar  4 01:05:51 UTC 2025
- Auto Sign-in run successful on Wed Mar  5 01:06:00 UTC 2025
- Auto Sign-in run successful on Thu Mar  6 01:05:55 UTC 2025
- Auto Sign-in run successful on Fri Mar  7 01:06:27 UTC 2025
- Auto Sign-in run successful on Sat Mar  8 00:53:05 UTC 2025
- Auto Sign-in run successful on Sun Mar  9 00:57:46 UTC 2025
- Auto Sign-in run successful on Mon Mar 10 00:56:24 UTC 2025
- Auto Sign-in run successful on Tue Mar 11 01:06:32 UTC 2025
- Auto Sign-in run successful on Wed Mar 12 01:05:42 UTC 2025
- Auto Sign-in run successful on Thu Mar 13 01:06:56 UTC 2025
