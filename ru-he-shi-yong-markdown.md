# 如何使用markdown

## 基本教程

快速入门：http://www.appinn.com/markdown/basic.html
完整语法：http://www.appinn.com/markdown/
在线编辑器：http://mahua.jser.me/

## 展示

# H1标题
## H2标题
### H3标题
#### H4标题
##### H5标题
###### H6标题

正文

---------------------------------------

普通列表

- 列表第一项
- 列表第一项
- 列表第一项

排序列表

1. 列表第一项
1. 列表第二项
1. 列表第三项

添加图片

![banner说明](/assets/banner.png)

添加视频

<embed src="https://imgcache.qq.com/tencentvideo_v1/playerv3/TPout.swf?max_age=86400&v=20161117&vid=p0302yexhjy&auto=0" allowFullScreen="true" quality="high" width="480" height="400" align="middle" allowScriptAccess="always" type="application/x-shockwave-flash"></embed>

添加代码

```xml
<!-- 这里是业务自定义的receiver，若已配置请设置exported为false，否则可忽略之 --> 
<receiver android:name="您的自定义MessageReceiver，继承于XGPushBaseReceiver" android:exported="false"> 
      <intent-filter> 
            <!-- 接收消息透传 --> 
            <action android:name="com.tencent.android.tpush.action.PUSH_MESSAGE" /> 
            <!-- 监听注册、反注册、设置/删除标签、通知被点击等处理结果 --> 
            <action android:name="com.tencent.android.tpush.action.FEEDBACK" />
      </intent-filter>
</receiver>
```

展示部分的markdown源码：

```
# H1标题
## H2标题
### H3标题
#### H4标题
##### H5标题
###### H6标题

正文

---------------------------------------

普通列表

- 列表第一项
- 列表第一项
- 列表第一项

排序列表

1. 列表第一项
1. 列表第二项
1. 列表第三项

添加图片

![banner说明](/assets/banner.png)

添加视频

<embed src="https://imgcache.qq.com/tencentvideo_v1/playerv3/TPout.swf?max_age=86400&v=20161117&vid=p0302yexhjy&auto=0" allowFullScreen="true" quality="high" width="480" height="400" align="middle" allowScriptAccess="always" type="application/x-shockwave-flash"></embed>

添加代码
# H1标题
## H2标题
### H3标题
#### H4标题
##### H5标题
###### H6标题

正文

---------------------------------------

普通列表

- 列表第一项
- 列表第一项
- 列表第一项

排序列表

1. 列表第一项
1. 列表第二项
1. 列表第三项

添加图片

![banner说明](/assets/banner.png)

添加视频

<embed src="https://imgcache.qq.com/tencentvideo_v1/playerv3/TPout.swf?max_age=86400&v=20161117&vid=p0302yexhjy&auto=0" allowFullScreen="true" quality="high" width="480" height="400" align="middle" allowScriptAccess="always" type="application/x-shockwave-flash"></embed>

```