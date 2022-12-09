# WeatherQuery
Matlab 天气查询软件，2021年Matlab课程设计大作业，使用APP Designer设计，遵循GPLv3.0协议

效果演示见 https://www.bilibili.com/video/BV19v4y1K7mc，喜欢不要吝惜三连哦~

## 使用说明

启动APP Designer，打开代码。

由于天气查询过程中使用了和风天气API（[和风天气开发服务 ~ 强大、丰富的天气数据服务 (qweather.com)](https://dev.qweather.com/)），web请求过程中需要用到和风天气个人账号的key，我在代码中将其设为空值，具体是46行app的properities设置部分：

```matlab
key = '';
```

只需去和风天气API注册一个账号，即可免费获取**<u>一定时长、一定服务范围</u>**的API key，将获取的key写在这里，即可正常运行，和风天气API返回的是一个json。

改完这个后即可运行！不改的话会报错（获取不到天气数据，自然会导致json为空，引用空的属性）

## 注意事项

1. 动画效果采用的是APP Designer内嵌HTML，然后用一些css和js来实现。背景的流星效果参考来源网上，但时间已久记不清楚，在此谢谢某不知名的原作者。谢谢你，幸运原作者，带我度过大作业！
2. 欢迎在我的基础上继续改，把App Designer发扬光大！~~打败guide~~

3. 如有问题，可以提issue或者b站私信~

