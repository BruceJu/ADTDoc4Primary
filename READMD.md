<style>
.div-border-image{
    margin-top: 20px;
    margin-bottom: 10px;
    box-shadow: 10px 10px 5px #888888;
    width:100%;
    hegiht:auto;
    padding:10px;
    background: whitesmoke;
    border: yellowgreen inset;
    border-right-width: 0px;
    border-top-width: 0px;
    border-bottom-width: 0px;
    border-left-width: 5px;
    border-radius: 5px;
    }
.div-border-question{
    margin-top: 20px;
    margin-bottom: 10px;
    box-shadow: 10px 10px 5px #888888;
    width:100%;
    hegiht:50px;
    padding:20px;
    background: whitesmoke;
    border: red inset;
    border-right-width: 0px;
    border-top-width: 0px;
    border-bottom-width: 0px;
    border-left-width: 5px;
    border-radius: 5px;
    }
.div-border-answer{
    margin-top: 20px;
    margin-bottom: 10px;
    box-shadow: 10px 10px 5px #888888;
    width:100%;
    hegiht:50px;
    padding:20px;
    background: whitesmoke;
    border: #4876FF inset;
    border-right-width: 0px;
    border-top-width: 0px;
    border-bottom-width: 0px;
    border-left-width: 5px;
    border-radius: 5px;
    }      
</style>
## 概况
------

> * 管理中心页面可以通过点击Ad Tracking主界面上的【管理中心】按钮和扳手图标进入(如下图)

<div class="div-border-image"> 
<div style="margin:10px,padding:10px">
   <img src='http://i2.bvimg.com/630822/d53f4d60cd69d3d0.png' width=100% height=200px>
</div>
</div>

> * 进入管理中心后Ad Tracking有三大功能(如下图)
>    * 【授权账户】
>    * 【渠道管理】
>    * 【数据管理】

<div class="div-border-image"> 
<div style="margin:10px,padding:10px">
   <img src='http://i2.bvimg.com/630822/03a7fdd24900e3da.png' width=100% height=60px>
</div>
</div>

## 使用背景
------
* 【授权账户】
   * 当广告主需要将自己账号中的报表数据开放给其它账号查看时
   * 就可以用“授权账户”功能给其它账号分别授予对应权限
   * 授权成功后再使用已授权账户登录`Ad Tracking`平台去查看数据

* 【渠道管理】
   * 当需要投放的渠道是`Ad Tracking`未对接的渠道时
   * 广告主可以在`渠道管理`中创建自定义渠道
   * 以便可以使用自定义渠道来进行投放，并可以选择是否给自定义渠道设置回调
   
*【数据管理】
   * 当广告主需要实时给自己的服务器发送数据，以便广告主可以在本地整理和分析数据时
   * 就可以设置“数据管理”中的数据回调功能来给广告主实时回调数据
   

## 功能使用
------
#### 【授权账户】
------
##### <h4>:100: 新建授权账户</h4>
------
>在【授权账户】页面中点击【新建授权账户】

<div class="div-border-image"> 
<div style="margin:10px,padding:10px">
   <img src="http://i2.bvimg.com/630822/1b22dd2cb06654be.png" width="100%" />
</div>
</div>

>进入【新建授权账户】页面后，先要填写需要授权的账户名<font color=red>（账户名必须为邮箱地址）</font>

<div class="div-border-image"> 
<div style="margin:10px,padding:10px">
   <img src="http://i2.bvimg.com/630822/fcbcc8f71380a82f.png" width="100%" />
</div>
</div>

> 填写好登录名后就可以选择需要授权的推广活动

<div class="div-border-image"> 
<div style="margin:10px,padding:10px">
   <img src="http://i2.bvimg.com/630822/a9a35c3957c5e324.png" width="100%" />
</div>
</div>

>选择好授权推广活动再选择该授权账户可以使用的权限后保存即可

<div class="div-border-image"> 
<div style="margin:10px,padding:10px">
   <img src="http://i2.bvimg.com/630822/119a44e1bfcdb527.png" width="100%" />
</div>
</div>

##### <h4>:100: 注意事项</h4>
------
>在授权账户列表中【角色】显示【创建者】的是主账号，【用户】是子账号

<div class="div-border-image"> 
<div style="margin:10px,padding:10px">
   <img src="http://i2.bvimg.com/630822/d2c281fee4cafb14.png" width="100%" />
</div>
</div>

>主账号授权应用时一定要选择一个推广活动，否则子账号登录将看不到授权的应用


>如果给子账号授权时选择【点击和激活数据】，那么子账号在报表中可以看到展示、点击、排重点击，激活-推广量

<div class="div-border-image"> 
<div style="margin:10px,padding:10px">
   <img src="http://i2.bvimg.com/630822/d7d9b4405424a7c6.png" width="100%" />
</div>
</div>

>如果给子账号授权时选择【效果点数据】，那么子账号在报表中可以看到活跃、注册、登录、订单，付费等事件数据


>如果给子账号授权时选择【成本、收入数据】，那么子账号在报表中可以看到成本花费、渠道收入、ROI

<div class="div-border-image"> 
<div style="margin:10px,padding:10px">
   <img src="http://i2.bvimg.com/630822/05ffb503ea609864.png" width="100%" />
</div>
</div>

>如果给子账号授权时选择【自然维度数据】，那么子账号在报表中可以看到各事件的自然量数据

>如果给子账号授权时选择【应用管理】，那么子账号在【产品设置】-【基本信息】中可以修改应用名，下载地址等

<div class="div-border-image"> 
<div style="margin:10px,padding:10px">
   <img src="http://i2.bvimg.com/630822/a9b203dcc9a4feb4.png" width="100%" />
</div>
</div>

>如果给子账号授权时选择【推广活动权限】，那么子账号可以创建推广活动，并可以编辑修改已生成的推广活动
>如果给子账号授权时选择【导出权限】，那么子账号可以使用日志导出功能进行导出操作

<div class="div-border-image"> 
<div style="margin:10px,padding:10px">
   <img src="http://i2.bvimg.com/630822/8284adcd3008048e.png" width="100%" />
</div>
</div>


#####  <h4>:100: 授权账户FAQ<h4>
------
<div class="div-border-question">Q：授权之后授权账号没有收到验证邮件，怎么办？

<div class="div-border-answer">A:可以先去垃圾邮箱中查找下有无验证邮件，如果没有可以在登录界面点击【没有收到邮箱认证邮件】重新发送验证邮件</div>

<div style="margin:10px,padding:10px">
   <img src="http://i2.bvimg.com/630822/e980e0a900e538bc.png" width="100%" />
</div>
</div>

<div class="div-border-question">Q：主账号授权了全部权限，为什么不能设置推广活动组？
<div class="div-border-answer">A:目前没有设置推广活动组的权限，推广活动组只有主账号可以操作</div>
</div>
<div class="div-border-question">Q:自定义渠道是否可以授权给子账号？
<div class="div-border-answer"> 
<h6>A:不可以的，渠道是账号级别的，不支持授权。</h6>
  <li>主账号选择自定义渠道生成的推广活动，授权给子账号，子账号能看到推广活动，看不到渠道</li>
  <li>同理，主账号授权给子账号创建推广活动权限，子账号选择自定义渠道创建的推广活动</li>
  <li>主账号也是看不到自定义渠道信息。</li>
</div>
</div>


<div class="div-border-question">Q:主账号给子账号授权后为什么子账号看不到应用？
<div class="div-border-answer">A:因为授权是基于推广活动进行操作的，主账号应用下没有推广活动，所以给子账号授权后子账号看不到应用。</div>
</div>

#### 【渠道管理】
------

##### <h4>:100: 新建自定义渠道</h4>
------
> 在【渠道管理】中点击【添加自定义渠道】

<div class="div-border-image"> 
<div style="margin:10px,padding:10px">
   <img src="http://i2.bvimg.com/630822/366ef2c746e88c3d.png" width="100%" />
</div>
</div>

>填写自定义渠道信息，如渠道需要回调则【新增数据回调】，如不需要则保存即可(如下图)

* 其中【渠道名称】：可自定义渠道名称，中文/英文都支持。
* 而【渠道类型】包含以下类型：
   * A.【广告平台】：选择‘广告平台’创建自定义渠道后，选择该渠道生成的推广活动为短链推广。
   * B.【应用市场】：选择‘应用市场’创建自定义渠道后，选择该渠道生成的推广活动为分包推广。
* 【点击样本有效期】：即点击到激活之间的有效匹配时间，默认为1天，最短可设置12小时，最长为30天。
* 比如【点击样本有效期】选择1天，那么在点击后24小时内进行激活，该激活就可以匹配点击，
* 匹配上就是推广量，匹配不上就是自然量，而超过24小时再激活，那么该激活就无法匹配到点击了则会归为自然量。
   
> 渠道需要回调，点击【新增数据回调】，填写回调信息后点击保存即可(如下图)

*  其中【选择应用】：选择需要回调数据的应用。
*  而【数据范围】包括：
   * A.【全量数据】：回调应用的全部数据，包括应用内所有的自然量数据以及所有推广渠道带来的推广量数据。
   * B.【仅‘推广渠道’数据】：仅回调该推广渠道带来的数据，不包含自然量数据和其它渠道的推广量数据。
*  比如在‘今日头条’进行投放，那么回调的就只是‘今日头条’这个渠道所带来的推广数据。
* 【选择事件】：选择需要回调的事件，事件包括：
    * `激活`、`注册`、`登录`、`订单`、`付费`、`创建角色`、`点击`、`添加到购物车`、`查看购物车`、`查看商品`以及`自定义事件`
* 【数据接收URL】：填写接收服务器的有效接收地址，该URL地址支持http和https协议。
* 【事件参数】：文本框中填写接收的参数名，该参数名可以自定义，只要填写的参数名符合接收服务器的接收标准即可。

<div class="div-border-image"> 
<div style="margin:10px,padding:10px">
   <img src="http://i2.bvimg.com/630822/510cd4f88260390b.png" width="100%" />
</div>
</div>

##### <h4>:100: 注意事项</h4>
------
>* 注意自定义渠道名时不要和Ad Tracking已对接的渠道名称以及已创建的自定义渠道名重复。
>* 回调自定义渠道的推广数据时，【ADNETNAME】字段的回调值与创建自定义渠道时填写的渠道名一致。
>* 【广告平台】类型的渠道创建推广活动后会生成监测链接，【应用市场】类型的渠道创建推广活动后会生成渠道ID。
>* 对接渠道的【点击样本有效期】有些是根据客户需求来设定的，以下渠道是无法修改设定

|渠道名称 |渠道id|点击样本有效期</font>|
|--|--|--|
|多盟 | domob |	7 |
|广点通	| gdt	|7 |
| Inmobi | Inmobi | 7 |
| 今日头条 | toutiao | 7|
| adwords | adwords	| 30 |
>* 【有效接收地址】：地址中的域名必须有效或可以ping通，地址中的路径必须可以正常访问。
>* 【@_】此参数是回调点击中带来的所有参数，回调形式为json格式。
>* 样例：
    * 比如点击参数如下 https://lnk0.com/xxxxxx?a=1&b=2&c=3
    * 设置的接收参数是clid 
    * <img src="http://i2.bvimg.com/630822/4a9fe787b8ad5c47.png" width="60%" height="25px" />
    * 那么我们回调给您后您这边接收到的格式如下
```html
http://www.test.com?clid={“a”:”1”,”b”:”2”,”c”:”3”}
```
* `SPREADNAME`、`SPREADURL`和`ADNETNAME`这三个事件参数没有回调就表示回调的数据为自然量数据
* 由于选择【全量数据】会回调应用下的所有数据，因此在给渠道回调的时候慎重选择此回调范围

##### <h4>:100: 渠道管理FAQ</h4>
------

<div class="div-border-question">Q:自定义渠道名设置成中文也是回调中文么？
<div class="div-border-answer">A:是的，不过回调的名字是URLEncode转码之后回调的，接收到以后需要进行URLDecode解码才能正常查看。</div>
</div>
<div class="div-border-question">Q:所有的渠道都可以回调推广量和自然量么？
<div class="div-border-answer">A:只有自定义的渠道可以选择回调的数据范围（全量数据和推广渠道数据），对接过的渠道只回调推广量。</div>
</div>

#### 【数据管理】
------
##### <h4>:100: 新建自定义数据回调</h4>
------

> 【数据管理】中点击【添加数据回调】

<div class="div-border-image"> 
<div style="margin:10px,padding:10px">
   <img src="http://i2.bvimg.com/630822/68a7a833177c3362.png" width="100%" />
</div>
</div>

> 填写数据回调配置信息，确认无误后点击保存即可(如下图)

* 其中【名称】：回调名称可以自定义，中/英文都支持。
* 【选择应用】：选择需要回调数据的应用。
* 【回调事件】：选择需要回调的事件，事件包括：
   `激活`、`注册`、`登录`、`订单`、`付费`、`创建角色`、`点击`、`添加到购物车`、`查看购物车`、`查看商品`以及`自定义事件`
* 【数据接收URL】：填写接收服务器的有效接收地址，该URL地址支持http和https协议。
* 【事件参数】：文本框中填写接收的参数名，该参数名可以自定义，只要填写的参数名符合接收服务器的接收标准即可。

<div class="div-border-image">
<div style="margin:10px,padding:10px">
   <img src="http://i2.bvimg.com/630822/d7f16dfe54b2d944.png" width="100%" />
</div>
</div>

> 保存回调配置信息后需要启用回调后才可正常使用回调服务

<div class="div-border-image">
<div style="margin:10px,padding:10px">
   <img src="http://i2.bvimg.com/630822/d0e60e7dae13f565.png" width="100%" />
</div>
</div>
* PS：[点我查看-自定义数据回调参数说明文档，参数描述和定义](http://doc.talkingdata.com/posts/163)


##### <h4>:100: 注意事项</h4>
------
<div class="div-border-image"> 
<div style="margin:10px,padding:10px">
  <img src="http://i2.bvimg.com/630822/b7f6ed37e0bd29e2.png" width="100%" />
</div>
</div>

>* 【有效接收地址】：地址中的域名必须有效或可以ping通，地址中的路径必须可以正常访问。
>* `SPREADNAME`、`SPREADURL`和`ADNETNAME`这三个事件参数没有回调就表示回调的数据为自然量数据。
>* `CHANNELPACKAGEID`此参数回调的是SDK中init接口内channelID的值。
>* `TDID`回调的是TD生成的对设备的唯一标识
>    * 此标识是根据设备ID(`idfa`，`androidid`，`imei`，`mac`等）
>    * 加上设备系统参数并加密后生成的，“TDID”通过SDK接口也是可以获取的。
>        * `Android`：TalkingDataAppCpa.getDeviceId(this);
>        * `IOS`：+ (NSString *)getDeviceId;   
>* 【数据接收URL】无法正常访问，保存回调配置后会出现【发送调试请求】按钮
>    * 只有配置的URL可以正常访问后此按钮才会变为【停用/启用】按钮。
>* 【数据管理】中设置的回调是全量数据回调，回调数据是应用下所有的推广量和自然量数据
     * 并且此回调范围无法调整，因此建议不要用此功能给渠道设置回调。
 
##### <h4>:100: 数据管理FAQ</h4>
------

<div class="div-border-question">Q：两个推广活动回调后怎么区分他们之间的数据？
<div class="div-border-answer">A:根据SPREADNAME参数区分就可以，这个参数回调的是推广活动名，可以根据这个来区分是后台哪个推广活动的数据。</div>
</div>

<div class="div-border-question">Q：自定义数据回调的UA为什么和本地获取的UA不一致？
<div class="div-border-answer">A:自定义数据回调中UA的回调方式，优先从SDK中获取，SDK中获取不到会获取激活对应点击中的UA信息。</div>
</div>






