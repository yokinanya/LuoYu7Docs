# BAWIKI
> 碧蓝档案Wiki插件<br/>
> 插件作者：lgc2333

## 使用方法

### [Arona数据源攻略](#arona)

从Arona Bot数据源中搜索攻略图，支持模糊搜索

可以搜索的内容：

- <font color=#ee7800>学生攻略图</font>（星野，白子 等）
- <font color=#ee7800>主线地图</font>（1-1，H1-1 等）
- <font color=#ee7800>杂图</font>（使用 arona 杂图 可以获取图片列表）

可以用这些指令触发：<br/>

- <font color=#ee7800>#arona</font>
- <font color=#ee7800>#Arona</font>
- <font color=#ee7800>#ARONA</font>
- <font color=#ee7800>#阿罗娜</font>

指令示例：

- <font color=#ee7800>arona</font>（会向你提问需要搜索什么）
- <font color=#ee7800>arona</font> 国际服未来视（精确搜索）
- <font color=#ee7800>arona</font> 国际服（模糊搜索）

### [日程表](#calender)

查看当前未结束的卡池、活动以及起止时间，默认为GameKee源，可以在指令后带参数使用SchaleDB数据源

指令示例：

- <font color=#ee7800>#ba日程表</font> &ensp; （GameKee源）
- <font color=#ee7800>#ba日程表 schaledb</font> &ensp;（SchaleDB源，日服）
- <font color=#ee7800>#ba日程表 国际服</font> &ensp;（SchaleDB源，国际服）


### [制造一图流](#crafont)

发送游戏内制造功能的一图流介绍<br/>
图片作者 B站@夜猫咪喵喵猫

可以用这些指令触发：

- <font color=#ee7800>ba制造</font>
- <font color=#ee7800>ba制作</font>
- <font color=#ee7800>ba合成</font>

### [活动一图流](#event)

发送当前或指定活动一图流攻略图，可能会附带活动特殊机制等<br/>
图片作者 B站@夜猫咪喵喵猫<br/>
指令默认发送日服和国际服当前的活动攻略<br/>
指令后面跟`日`或`j`开头的文本代表查询日服当前活动攻略，带以`国`或`g`开头的文本同理<br/>
跟其他文本则代表指定活动名称<br/>

指令示例：

- <font color=#ee7800>ba活动</font>
- <font color=#ee7800>ba活动 日</font>
- <font color=#ee7800>ba活动 温泉浴场</font>

### [互动家具总览](#furniture)

发送咖啡厅内所有互动家具以及对应学生的总览图<br/>
图片作者 B站@夜猫咪喵喵猫

指令示例：

- <font color=#ee7800>ba互动家具</font>



### [国际服千里眼](#global_future)

发送当前或指定日期的国际服未来卡池与活动列表<br/>
图片作者 B站@夜猫咪喵喵猫

参数可以指定起始日期以及列表个数，但同时指定时请将日期放在列表个数前面，以空格分隔<br/>
参数中含有`全`或`a`时会发送整张前瞻图

日期格式可以为（Y代表4位数年，m代表月，d代表日）：

- <font color=#ee7800>Y/m/d</font>；<font color=#ee7800>m/d</font>
- <font color=#ee7800>Y-m-d</font>；<font color=#ee7800>m-d</font>
- <font color=#ee7800>Y年m月d日</font>；<font color=#ee7800>m月d日</font>

可以用这些指令触发：

- <font color=#ee7800>ba国际服千里眼</font>
- <font color=#ee7800>ba千里眼</font>
- <font color=#ee7800>ba国际服前瞻</font>
- <font color=#ee7800>ba前瞻</font>

指令示例：

- <font color=#ee7800>ba千里眼</font>
- <font color=#ee7800>ba千里眼 all</font>
- <font color=#ee7800>ba千里眼 3</font>
- <font color=#ee7800>ba千里眼 11/15</font>
- <font color=#ee7800>ba千里眼 11/15 3</font>

### [关卡攻略](#level_guide)

获取指定关卡攻略<br/>
来源：GameKee

指令示例：

- <font color=#ee7800>ba关卡 1-1</font>
- <font color=#ee7800>ba关卡 H1-1</font>


### [随机漫画](#manga)

随机发送一话BA官推漫画<br/>
来源：GameKee

指令示例：

- <font color=#ee7800>ba漫画</font>


### [总力战一图流](#raid)

发送当前或指定总力战Boss的配队/机制一图流攻略图<br/>
支持部分Boss别名<br/>
图片作者 B站@夜猫咪喵喵猫

使用 <font color=#ee7800>ba总力战 -h</font> 查询指令用法

指令示例：

- <font color=#ee7800>ba总力战</font>（日服&国际服当前总力战Boss配队攻略）
- <font color=#ee7800>ba总力战 -s j</font>（日服当前总力战Boss配队攻略）
- <font color=#ee7800>ba总力战 -s j -w</font>（日服当前总力战Boss机制图）
- <font color=#ee7800>ba总力战 寿司</font>（Kaiten FX Mk.0 配队攻略）
- <font color=#ee7800>ba总力战 寿司 -t 屋外</font>（Kaiten FX Mk.0 屋外战配队攻略）

### [综合战术考试一图流](#time_atk)

"发送当前或指定综合战术考试一图流攻略图<br/>
图片作者 B站@夜猫咪喵喵猫

指令默认发送日服和国际服当前的综合战术考试攻略<br/>
指令后面跟`日`或`j`开头的文本代表查询日服当前综合战术考试攻略，带以`国`或`g`开头的文本同理<br/>
跟整数则代表指定第几个综合战术考试

p.s. 综合战术考试 和 合同火力演习 其实是一个东西，国际服叫前者，日服叫后者～

可以用这些指令触发：

- <font color=#EE7800>ba综合战术考试</font>
- <font color=#EE7800>ba合同火力演习</font>
- <font color=#EE7800>ba战术考试</font>
- <font color=#EE7800>ba火力演习</font>

指令示例：\n"

- <font color=#EE7800>ba综合战术考试</font>
- <font color=#EE7800>ba综合战术考试 日</font>
- <font color=#EE7800>ba综合战术考试 8</font>

### [羁绊查询](#stu_fav)

使用学生名称查询该学生解锁L2D看板需求的羁绊等级以及L2D预览，<br/>
或者使用羁绊等级级数查询哪些学生达到该等级时解锁L2D看板<br/>
使用学生名称查询时支持部分学生别名

可以用这些指令触发：

- <font color=#ee7800>ba羁绊</font>
- <font color=#ee7800>ba好感度</font>
- <font color=#ee7800>bal2d</font>
- <font color=#ee7800>balive2d</font>

指令示例：

- <font color=#ee7800>ba羁绊 xcw</font>
- <font color=#ee7800>ba羁绊 9</font>


### [学生评价](#stu_rank)

发送一张指定角色的评价图<br/>
支持部分学生别名<br/>
角评图作者 B站@夜猫咪喵喵猫

可以使用 `all` / `总览` / `全部` 参数 查看全学生角评一图流

可以用这些指令触发：

- <font color=#EE7800>ba学生评价</font>
- <font color=#EE7800>ba角评</font>

指令示例：
- <font color=#EE7800>ba学生评价 白子</font>
- <font color=#EE7800>ba角评 xcw</font>
- <font color=#EE7800>ba角评 总览</font>

### [学生Wiki](#stu_wiki_gamekee)

访问对应学生GameKee Wiki页面并截图，支持部分学生别名

指令示例：

- <font color=#EE7800>ba学生wiki 白子</font>
- <font color=#EE7800>ba学生wiki xcw</font>

### [学生图鉴](#stu_wiki_schale)

访问对应学生SchaleDB页面并截图，支持部分学生别名

指令示例：

- <font color=#EE7800>ba学生图鉴 白子</font>
- <font color=#EE7800>ba学生图鉴 xcw</font>


### [学生语音](#voice)

从GameKee爬取学生语音并发送<br/>
可以用 语音名称 或 中文或日文台词 搜索角色语音<br/>
如果有多个结果，则会从中随机选择一个语音发送

默认获取日配语音，如果角色有中配，则可以在指令后方带上 `中配` 来获取<br/>
如果找不到中配语音对应的台词，则会展示日配台词

可以用这些指令触发：

- <font color=#EE7800>ba语音</font>

指令示例：

- <font color=#EE7800>ba语音 忧</font>
- <font color=#EE7800>ba语音 美游 被cc</font>
- <font color=#EE7800>ba语音 水大叔 好热</font>
- <font color=#EE7800>ba语音中配 白子</font>
- <font color=#EE7800>ba语音中配 大叔 睡午觉</font>

### [抽表情](#emoji)

随机发送一个国际服社团聊天表情<br/>
来源：解包

指令示例：

- <font color=#ee7800>ba表情</font>


### [模拟抽卡](#gacha)

可以使用 <font color=#ee7800>ba切换卡池</font> 指令来切换卡池<br/>
可以指定抽卡次数，需要在1~90之间，默认10

指令示例：

- <font color=#ee7800>ba抽卡</font>
- <font color=#ee7800>ba抽卡 20</font>

设置模拟抽卡功能的UP池角色<br/>
默认从当前数据源UP池中轮流切换<br/>
当参数为 <font color=#EE7800>常驻</font> 时，切换到常驻池（没有UP）<br/>
可以自定义池子UP角色，支持2星与3星角色，参数中学生名称用空格分隔，支持部分学生别名

指令示例：

- <font color=#EE7800>ba切换卡池</font>
- <font color=#EE7800>ba切换卡池 常驻</font>
- <font color=#EE7800>ba切换卡池 小桃 小绿</font>

### [清空缓存](clear_cache)

手动清空插件请求网络缓存下来的数据，如API返回的数据<br/>
注：该指令只能由<font color=#ee7800>超级用户</font>触发

可以用这些指令触发：

- <font color=#ee7800>ba清空缓存</font>
- <font color=#ee7800>ba清除缓存</font>