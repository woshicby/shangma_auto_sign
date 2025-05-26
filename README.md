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
- Auto Sign-in run successful on Fri Mar 14 01:05:43 UTC 2025
- Auto Sign-in run successful on Sat Mar 15 01:05:10 UTC 2025
- Auto Sign-in run successful on Sun Mar 16 01:11:20 UTC 2025
- Auto Sign-in run successful on Mon Mar 17 01:09:04 UTC 2025
- Auto Sign-in run successful on Tue Mar 18 01:06:36 UTC 2025
- Auto Sign-in run successful on Wed Mar 19 01:07:34 UTC 2025
- Auto Sign-in run successful on Thu Mar 20 01:06:04 UTC 2025
- Auto Sign-in run successful on Fri Mar 21 01:07:33 UTC 2025
- Auto Sign-in run successful on Sat Mar 22 01:06:00 UTC 2025
- Auto Sign-in run successful on Sun Mar 23 01:12:07 UTC 2025
- Auto Sign-in run successful on Mon Mar 24 01:09:39 UTC 2025
- Auto Sign-in run successful on Tue Mar 25 01:07:58 UTC 2025
- Auto Sign-in run successful on Wed Mar 26 01:07:45 UTC 2025
- Auto Sign-in run successful on Thu Mar 27 01:07:28 UTC 2025
- Auto Sign-in run successful on Fri Mar 28 01:07:20 UTC 2025
- Auto Sign-in run successful on Sat Mar 29 01:06:52 UTC 2025
- Auto Sign-in run successful on Sun Mar 30 01:13:14 UTC 2025
- Auto Sign-in run successful on Mon Mar 31 01:11:47 UTC 2025
- Auto Sign-in run successful on Tue Apr  1 01:16:18 UTC 2025
- Auto Sign-in run successful on Wed Apr  2 01:09:07 UTC 2025
- Auto Sign-in run successful on Thu Apr  3 01:08:20 UTC 2025
- Auto Sign-in run successful on Fri Apr  4 01:07:59 UTC 2025
- Auto Sign-in run successful on Sat Apr  5 01:06:55 UTC 2025
- Auto Sign-in run successful on Sun Apr  6 01:12:40 UTC 2025
- Auto Sign-in run successful on Mon Apr  7 01:10:41 UTC 2025
- Auto Sign-in run successful on Tue Apr  8 01:08:23 UTC 2025
- Auto Sign-in run successful on Wed Apr  9 01:08:37 UTC 2025
- Auto Sign-in run successful on Thu Apr 10 01:08:39 UTC 2025
- Auto Sign-in run successful on Fri Apr 11 01:09:12 UTC 2025
- Auto Sign-in run successful on Sat Apr 12 01:07:39 UTC 2025
- Auto Sign-in run successful on Sun Apr 13 02:36:55 UTC 2025
- Auto Sign-in run successful on Mon Apr 14 01:12:02 UTC 2025
- Auto Sign-in run successful on Tue Apr 15 01:11:04 UTC 2025
- Auto Sign-in run successful on Wed Apr 16 01:10:29 UTC 2025
- Auto Sign-in run successful on Thu Apr 17 01:09:37 UTC 2025
- Auto Sign-in run successful on Fri Apr 18 01:09:01 UTC 2025
- Auto Sign-in run successful on Sat Apr 19 01:06:41 UTC 2025
- Auto Sign-in run successful on Sun Apr 20 01:14:33 UTC 2025
- Auto Sign-in run successful on Mon Apr 21 01:13:08 UTC 2025
- Auto Sign-in run successful on Tue Apr 22 01:09:59 UTC 2025
- Auto Sign-in run successful on Wed Apr 23 01:10:25 UTC 2025
- Auto Sign-in run successful on Thu Apr 24 01:10:36 UTC 2025
- Auto Sign-in run successful on Fri Apr 25 01:10:46 UTC 2025
- Auto Sign-in run successful on Sat Apr 26 01:08:16 UTC 2025
- Auto Sign-in run successful on Sun Apr 27 01:14:34 UTC 2025
- Auto Sign-in run successful on Mon Apr 28 01:12:47 UTC 2025
- Auto Sign-in run successful on Tue Apr 29 01:10:48 UTC 2025
- Auto Sign-in run successful on Wed Apr 30 01:11:04 UTC 2025
- Auto Sign-in run successful on Thu May  1 01:17:36 UTC 2025
- Auto Sign-in run successful on Fri May  2 01:11:54 UTC 2025
- Auto Sign-in run successful on Sat May  3 01:09:39 UTC 2025
- Auto Sign-in run successful on Sun May  4 01:18:05 UTC 2025
- Auto Sign-in run successful on Mon May  5 01:14:20 UTC 2025
- Auto Sign-in run successful on Tue May  6 01:11:52 UTC 2025
- Auto Sign-in run successful on Wed May  7 01:12:18 UTC 2025
- Auto Sign-in run successful on Thu May  8 01:12:53 UTC 2025
- Auto Sign-in run successful on Fri May  9 01:12:06 UTC 2025
- Auto Sign-in run successful on Sat May 10 01:09:40 UTC 2025
- Auto Sign-in run successful on Sun May 11 01:16:43 UTC 2025
- Auto Sign-in run successful on Mon May 12 01:14:54 UTC 2025
- Auto Sign-in run successful on Tue May 13 01:13:29 UTC 2025
- Auto Sign-in run successful on Wed May 14 01:12:24 UTC 2025
- Auto Sign-in run successful on Thu May 15 01:10:11 UTC 2025
- Auto Sign-in run successful on Fri May 16 01:13:17 UTC 2025
- Auto Sign-in run successful on Sat May 17 01:11:32 UTC 2025
- Auto Sign-in run successful on Sun May 18 01:17:45 UTC 2025
- Auto Sign-in run successful on Mon May 19 01:16:14 UTC 2025
- Auto Sign-in run successful on Tue May 20 01:14:05 UTC 2025
- Auto Sign-in run successful on Wed May 21 01:13:35 UTC 2025
- Auto Sign-in run successful on Thu May 22 01:12:57 UTC 2025
- Auto Sign-in run successful on Fri May 23 01:12:56 UTC 2025
- Auto Sign-in run successful on Sat May 24 01:10:14 UTC 2025
- Auto Sign-in run successful on Sun May 25 01:19:34 UTC 2025
- Auto Sign-in run successful on Mon May 26 01:15:03 UTC 2025
