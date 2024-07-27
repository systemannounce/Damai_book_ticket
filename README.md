# 大麦网自动抢票脚本

现在正式支持抢多张票

> 说起来也是机缘巧合，不知道以前什么时候，在哪里用的脚本，现在刚好翻了出来，不出意外不能用，简简单单修补一下，诶，又可以用了。  
> 如果该项目侵犯到您的权益，[请联系我](mailto:copyright@systemannounce.com)

## 使用方法：
### 1. 更改config.conf文件里面的信息，指定你的抢票需求。

![image-20240725231435962](https://cdn.jsdelivr.net/gh/systemannounce/piceeimg/2024/image-20240725231435962.png)

| 参数        | 值                                     |
| ----------- | -------------------------------------- |
| account     | 不需要填写                             |
| password    | 同上                                   |
| nick_name   | 同上                                   |
| book_url    | 订票网页地址                           |
| session     | 场次（可多选）                         |
| price       | 票价（可多选）                         |
| name_num    | 买几张                                |
| who         | 如有，选择订单信息页哪些人的信息买票     |
| num         | 抢票最大尝试次数                       |
| date_time   | 定时开始抢票                           |
| driver_path | chromedriver驱动的所在位置             |

### 2. 运行main.py脚本执行任务

第一次登录会让你登录，扫码登录即可。

> 注意，登录有时限，记得在用以前cookie的时候提前打开脚本测试有没有同步登录状态。
> 即便还没有开始抢票，也能根据弹出的浏览器查看是否已经登录上了。

如果前面配置的信息没错，而且，你的电脑时间是精准的！！！！！（这点很重要！！！）

想要查看时间的准确性，可以去[time.is](https://time.is)查看与标准时间的误差。

建议你可以用一个冷们场次测试一下信息是否准确并且程序是否被网站和谐。

![image-20240725232425385](https://cdn.jsdelivr.net/gh/systemannounce/piceeimg/2024/image-20240725232425385.png)

### 3. enjoy
