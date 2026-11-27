# xin-skills · 小说文风锁定技能集

> 为 AI 写作助手打造的一组「文风锁定」技能：从指定小说的正文样本中萃取**十维写作风格规范**，让 AI 严格模仿该小说的叙事视角、句式节奏、对话体系与情绪基调进行创作——**只学文笔，不抄剧情**。

<!-- BEGIN:SKILL-STATS -->
- 共 **137 个技能**：**番茄小说风格 19 个** ＋ **古龙武侠风格 4 个** ＋ **金庸武侠风格 10 个** ＋ **黄易风格 7 个** ＋ **梁羽生武侠风格 22 个** ＋ **女作者言情风格 29 个** ＋ **王朔风格 15 个** ＋ **网络文学名家风格 31 个**
- 每个技能 = `SKILL.md`（十维风格规范）＋ `references/style_examples.md`（风格样本，135 个技能附带）
<!-- END:SKILL-STATS -->
- 一键安装：`npx skills add oscar-wang-xin/xin-skills`
- 格式兼容 Reasonix Skills / Claude Skills / 通用 Agent Skills

---

## 目录

- [技能总览](#技能总览)
- [安装方法](#安装方法)
- [使用方法](#使用方法)
- [风格画像](#风格画像)
- [技能内部结构](#技能内部结构)
- [版权与使用声明](#版权与使用声明)

---

## 技能总览

<!-- BEGIN:SKILL-INDEX -->

<!-- 本节自动生成，请勿手改 -->

### 🍅 番茄小说风格（19 个）

| 技能目录名 | 文风锁定对象 | 风格关键词 |
| --- | --- | --- |
| `xin-fanqie-style-baiyujing` | 《剑起白玉京》 | 轻松沙雕仙侠 · 现代口语解构修仙 · 双线交织 |
| `xin-fanqie-style-busidishi` | 《不死帝师》 | 长生流 · 时间差碾压 · 旁观式温情 |
| `xin-fanqie-style-diaodazhutian` | 《镇守百万年，我的徒弟吊打诸天》 | 搞笑轻松 · 爽文碾压 · 师徒反差 |
| `xin-fanqie-style-difujiaowoxiaoxiansheng` | 《地府叫我小先生》 | 悬疑灵异 · 北方乡土语言 · 民间传说考据 |
| `xin-fanqie-style-feishengshaletiandi` | 《危！刚飞升我就杀了天帝？》 | 沙雕爽文 · 仙侠狼人杀 · 悬疑推理 |
| `xin-fanqie-style-fengliuzongshi` | 《风流宗师，从五禽拳开始镇压帝女》 | 苟道流 · 老头扮猪吃虎 · 杀伐果断 |
| `xin-fanqie-style-fenshi` | 《我靠焚尸超凡入圣》 | 半文半白悬疑灵异 · 系统奖励升级 · 恐怖+冷幽默 |
| `xin-fanqie-style-gou` | 《每年加一点从山野村夫成仙界道祖》 | 苟道流 · 长生苟王 · 延迟复仇 |
| `xin-fanqie-style-guishe` | 《诡舍》 | 悬疑无限流 · 微惊悚求生 · 规则谜题 |
| `xin-fanqie-style-hanfeixiuxian` | 《谁让这个悍匪修仙的！》 | 搞笑腹黑 · 土匪思维解构修仙 · 反差爽文 |
| `xin-fanqie-style-moshibianzhi` | 《我给末世主角们发编制》 | 反套路 · 国家力量降维打击 · 冷幽默群像 |
| `xin-fanqie-style-shirizhongyan` | 《十日终焉》 | 冷峻悬疑 · 死亡博弈 · 推理反转 |
| `xin-fanqie-style-wobushixishen` | 《我不是戏神》 | 中式怪诞 · 诡异恐怖 · 冷幽默 |
| `xin-fanqie-style-yanyulou` | 《烟雨楼》 | 传统玄幻扮猪吃虎 · 多视角 · 冷幽默 |
| `xin-fanqie-style-yishoumicheng` | 《异兽迷城》 | 都市克苏鲁 · 兽化生存 · 悬疑推演 |
| `xin-fanqie-style-zhanshen` | 《我在精神病院学斩神》 | 温馨日常 · 悬疑暗线 · 信息差 |
| `xin-fanqie-style-zhenliyijian` | 《真理，掌握在我一剑之内》 | 冷峻黑暗复仇 · 锋利讽刺 · 热血燃 |
| `xin-fanqie-style-zhenyaoguan` | 《从前有座镇妖关》 | 黑色幽默 · 反差沙雕 · 都市高武 |
| `xin-fanqie-style-zhushenyuxi` | 《诸神愚戏》 | 克系黑色幽默 · 神明末世 · 荒诞吐槽 |

### 🥋 古龙武侠风格（4 个）

| 技能目录名 | 文风锁定对象 | 风格关键词 |
| --- | --- | --- |
| `xin-gulong-style-7wuqi-quantou` | 《七种武器之拳头》 | 热血浪子 · 黑色幽默 · 江湖残酷 |
| `xin-gulong-style-chuliuxiangdashamo` | 《楚留香系列·大沙漠》 | 武侠悬疑 · 朋友情谊 · 冷幽默 |
| `xin-gulong-style-duoqingjianke` | 《多情剑客无情剑》 | 苍凉浪漫 · 江湖豪情 · 个人悲歌 |
| `xin-gulong-style-huanleyingxiong` | 《欢乐英雄》 | 轻松欢乐 · 底层温情 · 以弱制强 |

### ⚔️ 金庸武侠风格（10 个）

| 技能目录名 | 文风锁定对象 | 风格关键词 |
| --- | --- | --- |
| `xin-jinyong-style-bixuejian` | 《碧血剑》 | 金庸早期 · 传统武侠白描 · 家国悲慨 |
| `xin-jinyong-style-lianchengjue` | 《连城诀》 | 阴冷反讽 · 老实人悲剧 · 余韵式收束 |
| `xin-jinyong-style-ludingji` | 《鹿鼎记》 | 市井滑稽 · 反讽解构 · 韦小宝 |
| `xin-jinyong-style-shediaoyingxiongzhuan` | 《射雕英雄传》 | 新武侠 · 家国恩义 · 少年成长 |
| `xin-jinyong-style-shendiaoxialv` | 《神雕侠侣》 | 至情叙事 · 悲壮底色 · 情义恩怨 |
| `xin-jinyong-style-tianlongbabu` | 《天龙八部》 | 多线群像 · 命运悲剧 · 悲喜交替 |
| `xin-jinyong-style-xiakexing` | 《侠客行》 | 质朴敦厚 · 冷峻江湖 · 善意与凶险错位 |
| `xin-jinyong-style-xiaoaojianghu` | 《笑傲江湖》 | 狂放不羁 · 权力倾轧 · 高喜剧浓度 |
| `xin-jinyong-style-xueshanfeihu` | 《雪山飞狐》 | 罗生门结构 · 嵌套叙事 · 克制悲怆 |
| `xin-jinyong-style-yitiantulongji` | 《倚天屠龙记》 | 悲壮侠义 · 旧白话武侠 · 义与不得已 |

### 🌊 黄易风格（7 个）

| 技能目录名 | 文风锁定对象 | 风格关键词 |
| --- | --- | --- |
| `xin-huangyi-style-dajianshi` | 《大剑师传奇》 | 第一人称玄幻 · 港台武侠 · 复仇热血 |
| `xin-huangyi-style-datangshuanglongzhuan` | 《大唐双龙传》 | 隋唐武侠 · 历史权谋 · 双男主逆袭 |
| `xin-huangyi-style-posuixukong` | 《破碎虚空》 | 黄易武侠风 · 道家哲思 · 苍凉恢宏 |
| `xin-huangyi-style-shikonglangzu` | 《时空浪族》 | 都市异能 · 预知梦境 · 港式商战 |
| `xin-huangyi-style-shouxinghuigui` | 《兽性回归》 | 科幻悬疑 · 理性克制 · 兽性撕扯 |
| `xin-huangyi-style-xingjilangzi` | 《星际浪子》 | 太空歌剧 · 黄易科幻 · 人性探索 |
| `xin-huangyi-style-xunqinji` | 《寻秦记》 | 穿越权谋 · 雄性爽文 · 战国香艳 |

### 📖 梁羽生武侠风格（22 个）

| 技能目录名 | 文风锁定对象 | 风格关键词 |
| --- | --- | --- |
| `xin-liangyusheng-style-baifamonvzhuan` | 《白发魔女传》 | 悲剧底色 · 家国政局 · 白头题眼 |
| `xin-liangyusheng-style-binghexijianlu` | 《冰河洗剑录》 | 正剧底 · 市井谐趣 · 章回体 |
| `xin-liangyusheng-style-bingpohanguangjian` | 《冰魄寒光剑》 | 浪漫武侠 · 异域冒险 · 深情克制 |
| `xin-liangyusheng-style-feifengqianlong` | 《飞凤潜龙》 | 侦探武侠 · 悬疑对话体 · 短段快切 |
| `xin-liangyusheng-style-fengleizhenjiuzhou` | 《风雷震九州》 | 忠义对照 · 三层收束 · 章回体 |
| `xin-liangyusheng-style-fengyunleidian` | 《风云雷电》 | 少年侠气 · 家国对抗 · 群像 |
| `xin-liangyusheng-style-guanglingjian` | 《广陵剑》 | 萍踪系列 · 悲慨 |
| `xin-liangyusheng-style-hanhaixiongfeng` | 《瀚海雄风》 | 苍凉悲壮 · 家国流离 · 大漠 |
| `xin-liangyusheng-style-huanjianlingqi` | 《幻剑灵旗》 | 悲情基调 · 悬疑张力 · 成人江湖 |
| `xin-liangyusheng-style-huijianxinmo` | 《慧剑心魔》 | 少年群像 · 唐代三部曲 · 少女心事 |
| `xin-liangyusheng-style-jianghusannvxia` | 《江湖三女侠》 | 侠义悲慨 · 国仇家恨 · 人物幽默 |
| `xin-liangyusheng-style-lianjianfengyunlu` | 《联剑风云录》 | 萍踪系列 · 回目形制 · 对话密度 |
| `xin-liangyusheng-style-longhudoujinghua` | 《龙虎斗京华》 | 新派开山 · 清末乱世 · 家国为骨 |
| `xin-liangyusheng-style-muyeliuxing` | 《牧野流星》 | 天山系列 · 侠义为骨 · 内敛 |
| `xin-liangyusheng-style-pingzongxiayinglu` | 《萍踪侠影录》 | 旷达悲慨 · 名士气 · 家国大义 |
| `xin-liangyusheng-style-qijianxiatianshan` | 《七剑下天山》 | 反清复明 · 多线群侠 · 诗词入文 |
| `xin-liangyusheng-style-saiwaiqixiazhuan` | 《塞外奇侠传》 | 天山前传 · 新派确立期 |
| `xin-liangyusheng-style-sanhuanvxia` | 《散花女侠》 | 萍踪续篇 · 少女成长 |
| `xin-liangyusheng-style-tanzhijinglei` | 《弹指惊雷》 | 身世悲情 · 儿女情长 · 武学传承 |
| `xin-liangyusheng-style-wulintianjiao` | 《武林天骄》 | 晚期代表作 · 宋金背景 · 檀羽冲 |
| `xin-liangyusheng-style-xiagudanxin` | 《侠骨丹心》 | 轻喜剧 · 痞侠金逐流 · 章回体 |
| `xin-liangyusheng-style-yunhaiyugongyuan` | 《云海玉弓缘》 | 恩仇痴情 · 正剧底色 |

### 💃 女作者言情风格（29 个）

| 技能目录名 | 文风锁定对象 | 风格关键词 |
| --- | --- | --- |
| `xin-lady-style-12years-gurenxi` | 《十二年，故人戏》 | 民国言情 · 短段碎行 · 对白嵌入叙述 |
| `xin-lady-style-baiseganlanshu` | 《白色橄榄树》 | 现代军旅 · 战地言情 · 克制留白 |
| `xin-lady-style-beichengyouxue` | 《北城有雪》 | 都市言情 · 婉约细腻 · 破镜重圆 |
| `xin-lady-style-caomeixi` | 《谁懂啊，娘娘写了一百条宫规》 | 宫斗群像 · 谨慎大女主 · 冷幽默吐槽 |
| `xin-lady-style-changanxiaofanguan` | 《长安小饭馆》 | 古风美食 · 现代梗互文 · 市井轻喜剧 |
| `xin-lady-style-changdi` | 《长嫡》 | 唐风宅斗 · 梦境预知 · 心理推演 |
| `xin-lady-style-dongchangguanchabiji` | 《东厂观察笔记》 | 明朝穿越 · 短段节奏 · 现代学术吐槽 |
| `xin-lady-style-gongyu` | 《攻玉》 | 原耽朝堂 · 双男主互怼 · 高台词占比 |
| `xin-lady-style-jiaoniangyijing` | 《娇娘医经》 | 古言种田 · 医术流 · 标签密挂 |
| `xin-lady-style-jiuchongzi` | 《九重紫》 | 宅斗重生 · 账本笔法 · 笑道标签 |
| `xin-lady-style-kunning` | 《坤宁》 | 宫廷重生 · 碎行流 · 情绪直给 |
| `xin-lady-style-meigongqing` | 《媚公卿》 | 魏晋门阀 · 重生发家 · 半角冒号直引 |
| `xin-lady-style-moumou` | 《某某》 | 现代校园 · 群口对白 · 少年群像 |
| `xin-lady-style-niaosongmi` | 《冷战三年，扯证离婚他却悔红了眼》 | 先婚后爱 · 追妻火葬场 · 冷感毒舌 |
| `xin-lady-style-nvjiangxing` | 《重生之女将星》 | 女扮男装 · 重生复仇 · 宣言短钩 |
| `xin-lady-style-qiafengyuliantian` | 《恰逢雨连天》 | 权谋言情 · 朝堂书卷语 · 对白收束 |
| `xin-lady-style-quanhuanxintouzhushazhi` | 《权宦心头朱砂痣》 | 宅门权谋 · 二嫁古言 · 反问式钩子 |
| `xin-lady-style-shanzhong` | 《善终》 | 宅斗重生 · 物件证重生 · 家人暖线 |
| `xin-lady-style-shenghua` | 《盛华》 | 重生权谋 · 家族群像 · 绵密长句 |
| `xin-lady-style-sijin` | 《似锦》 | 宅斗权谋 · 重生宠文 · 心理蒙太奇 |
| `xin-lady-style-xiangshijiexianshangxianyu` | 《向师祖献上咸鱼》 | 穿越仙侠 · 咸鱼吐槽 · 表情包收尾 |
| `xin-lady-style-xionganxianchangzhibo` | 《凶案现场直播》 | 悬疑直播 · 多媒介文本 · 冷幽默毒舌 |
| `xin-lady-style-xuyizhufeng` | 《癫，都癫，癫点好啊》 | 穿书恋综 · 发癫女主 · 多声部弹幕 |
| `xin-lady-style-yidaijunshi` | 《随波逐流之一代军师》 | 第一人称谋士 · 史传引文 · 流水句推演 |
| `xin-lady-style-youfei` | 《有匪》 | 武侠言情 · 文白杂糅 · 长句连缀 |
| `xin-lady-style-yuanlaiyueliangxiandongxin` | 《原来月亮先动心》 | 校园甜宠 · 年龄差 · 轻喜剧对白 |
| `xin-lady-style-yuemingqianli` | 《月明千里》 | 和亲穿书 · 文人雅言 · 西域丝路 |
| `xin-lady-style-zhenxiuji` | 《珍馐记》 | 美食经营 · 预知梦悬疑 · 群像喜剧 |
| `xin-lady-style-zheyao` | 《折腰》 | 乱世权谋 · 先婚后爱 · 半文半白 |

### 🎭 王朔风格（15 个）

| 技能目录名 | 文风锁定对象 | 风格关键词 |
| --- | --- | --- |
| `xin-wangshuo-style-dongwuxiongmeng` | 《动物凶猛》 | 第一人称回忆 · 少年青春 · 不可靠叙事 · 大院北京 · 长句思辨 |
| `xin-wangshuo-style-haomaobabu` | 《好猫八不》 | 猫叙事 · 京味聊天体 · 第三人称丙 · 事语 · 克制哀悼 |
| `xin-wangshuo-style-kongzhongxiaojie` | 《空中小姐》 | 第一人称初恋 · 海空抒情 · 早期王朔 · 年龄差 · 克制伤感 |
| `xin-wangshuo-style-meirenzengwomenghanyao` | 《美人赠我蒙汗药》 | 双人对谈 · 文化批评 · 长轮次 · 京味痞话 · 知识分子批判 |
| `xin-wangshuo-style-nibushiyigesuren` | 《你不是一个俗人》 | 1990年代 · 捧人喜剧 · 对话驱动 · 京味讽刺 · 短段落 |
| `xin-wangshuo-style-qianwanbiewobadangren` | 《千万别把我当人》 | 荒诞闹剧 · 媒体奇观 · 黑色讽刺 · 官僚黑话 · 群众场面 |
| `xin-wangshuo-style-qichu-jinian` | 《起初·纪年》 | 汉武编年 · 京味口语 · 无引号对白 · 公文戏仿 · 冷幽默 |
| `xin-wangshuo-style-qichu-jueditiantong` | 《起初·绝地天通》 | 涿鹿之战 · 伪文献 · 物质考据 · 京味口语 · 黑色幽默 |
| `xin-wangshuo-style-qichu-yutian` | 《起初·鱼甜》 | 汉武童年 · 上古双线 · 京味回忆录 · 无引号对白 · 黑色幽默 |
| `xin-wangshuo-style-qichu-zhushu` | 《起初·竹书》 | 上古编年 · 伪考据 · 京味口语 · 全球神话互文 · 苍凉幽默 |
| `xin-wangshuo-style-wandezhuoshixintiao` | 《玩的就是心跳》 | 第一人称悬疑 · 记忆拼图 · 京味痞话 · 梦境现实 · 身份错认 |
| `xin-wangshuo-style-wanzhu` | 《顽主》 | 三T公司 · 对话喜剧 · 1980年代讽刺 · 京味群像 · 冷面荒诞 |
| `xin-wangshuo-style-woshinibaba` | 《我是你爸爸》 | 父子日常 · 京味写实 · 尴尬喜剧 · 心理暗写 · 短段对白 |
| `xin-wangshuo-style-yibanshihuoyan-yibanshihaishui` | 《一半是火焰 一半是海水》 | 第一人称忏悔 · 黑色爱情 · 京味写实 · 上下篇 · 冷峻抒情 |
| `xin-wangshuo-style-yongshiawo` | 《永失我爱》 | 第一人称绝症爱情 · 短段短句 · 克制煽情 · 工地北京 · 医疗细节 |

### 📚 网络文学名家风格（31 个）

| 技能目录名 | 文风锁定对象 | 风格关键词 |
| --- | --- | --- |
| `xin-aiqianshuidewuzei-style-guimizhizhu` | 《诡秘之主》（爱潜水的乌贼） | 克苏鲁 · 冷峻悬疑 · 黑色幽默 |
| `xin-apu-style-shanhaijingmima` | 《山海经密码》（阿菩） | 史诗苍凉 · 上古神话探秘 · 权谋博弈 |
| `xin-chunjiedexiaolong-style-laoshiren` | 《捞尸人》（纯洁滴小龙） | 东北乡村年代传奇 · 灵异 |
| `xin-ergen-style-qiumo` | 《求魔》（耳根） | 苍凉孤执 · 命运抗争 · 画面感 |
| `xin-ergen-style-xianni` | 《仙逆》（耳根） | 逆天改命 · 坚韧沧桑 · 杀伐决断 |
| `xin-fenghuoxizhuhou-style-jianlai` | 《剑来》（烽火戏诸侯） | 市井烟火 · 冷幽默 · 哲理 |
| `xin-fenghuoxizhuhou-style-xuezhonghandaoxing` | 《雪中悍刀行》（烽火戏诸侯） | 市井江湖气 · 文人雅致 · 从容闲笔 |
| `xin-fennudexiangjiao-style-nitianwudi` | 《逆天武帝》（愤怒的香蕉） | 废柴逆袭 · 亲情温情 · 隐忍复仇 |
| `xin-fennudexiangjiao-style-yinsha` | 《隐杀》（愤怒的香蕉） | 杀手重生 · 轻松YY · 冷面笑匠反差 |
| `xin-fennudexiangjiao-style-yiyuqiushengriji` | 《异域求生日记》（愤怒的香蕉） | 温柔哀伤 · 哲学沉思 · 抒情 |
| `xin-jiangnan-style-xiedu` | 《亵渎》（烟雨江南） | 暗黑欲望 · 权谋 · 反英雄 |
| `xin-jiangnan-style-yongyejunzhu` | 《永夜君王》（烟雨江南） | 暗黑残酷 · 绝境逆袭 · 末世科幻 |
| `xin-jiyueren-style-xuanjianxianzu` | 《玄鉴仙族》 | 家族修仙 · 代际传承 · 冷静克制 |
| `xin-maibaoxiaolangjun-style-dafengdagengren` | 《大奉打更人》（卖报小郎君） | 探案 · 黑色幽默 · 现代社畜穿越 |
| `xin-maoni-style-dadaochaotian` | 《大道朝天》（猫腻） | 剑修 · 智性视角 · 疏离诙谐 |
| `xin-maoni-style-jiangye` | 《将夜》（猫腻） | 长句铺陈 · 文气克制 · 章末留白 |
| `xin-maoni-style-qingyunian` | 《庆余年》（猫腻） | 穿越权谋 · 庙堂江湖 · 范闲 |
| `xin-qingheyikan-style-chixinxuntian` | 《赤心巡天》（情何以堪） | 沉郁悲悯 · 侠气 · 苍凉 |
| `xin-rushuiyi-style-woqiangshen` | 《我枪神》（如水意） | 都市枪战 · 硬核写实 · 战友群像 |
| `xin-wangyu-style-fanrenxiuxianzhuan` | 《凡人修仙传》（忘语） | 冷静克制 · 写实 · 低对话高内心 |
| `xin-wenchaogong-style-gouzailiangjiexiuxian` | 《苟在两界修仙》（文抄公） | 苟道流 · 两界穿越 · 理性克制 |
| `xin-xiaoding-style-zhuxian` | 《诛仙》（萧鼎） | 古典仙侠 · 半文半白 · 张小凡 |
| `xin-xionglanggou-style-meiqianxiushenmexian` | 《没钱修什么仙》（熊狼狗） | 科学修仙 · 都市无厘头 |
| `xin-yanleisheng-style-tianxingjian` | 《天行健》（燕垒生） | 史诗战争 · 冷静克制 · 军旅厚重 |
| `xin-yuantong-style-limingzhijian` | 《黎明之剑》（远瞳） | 基建种田 · 理工男吐槽 · 文明苍凉 |
| `xin-yuantong-style-yichangshengwu` | 《异常生物见闻录》（远瞳） | 轻松搞笑 · 吐槽 · 都市科幻 |
| `xin-yutingjun-style-huangtiancangtianyisi` | 《我名黄天苍天已死什么鬼》（玉庭君） | 历史穿越 · 沙雕玩梗 · 非系统修仙 |
| `xin-zhangxiaohua-style-shishangdiyihunluan` | 《史上第一混乱》（张小花） | 反穿越 · 恶搞 · 历史人物现代 |
| `xin-zhangxiaohua-style-wojiushiyaoguai` | 《我就是妖怪》（张小花） | 妖怪日常 · 贱萌吐槽 · 市井喜剧 |
| `xin-zhouzi-style-qingshan` | 《青山》（会说话的肘子） | 灵气复苏 · 冷峻克制 · 孤独底色 |
| `xin-zhouzi-style-yedemingmingshu` | 《夜的命名术》（会说话的肘子） | 梦境穿越 · 平行世界 · 少年悲悯 |

<!-- END:SKILL-INDEX -->

---

## 安装方法

### 方式一：npx skills add（推荐）

本仓库符合 Agent Skills 规范（每个技能均含带 `name` / `description` 的 `SKILL.md`），可用官方 CLI 一条命令安装——CLI 会自动发现仓库内全部技能，并检测本机已安装的 AI Agent：

```bash
# 安装全部技能
npx skills add oscar-wang-xin/xin-skills

# 先预览仓库中有哪些技能
npx skills add oscar-wang-xin/xin-skills --list

# 只安装指定技能（--skill 可重复多次）
npx skills add oscar-wang-xin/xin-skills --skill xin-fanqie-style-baiyujing

# 指定目标 Agent 并跳过交互提示
npx skills add oscar-wang-xin/xin-skills -a reasonix -a claude-code -y

# 全局安装（对所有项目生效）
npx skills add oscar-wang-xin/xin-skills -g -y
```

- **安装范围**：项目级 `./<agent>/skills/`（默认）或全局 `~/<agent>/skills/`（加 `-g`）
- **支持的 Agent**：Reasonix、Claude Code、Codex、Cursor 等 20+ 种；未检测到时会提示选择
- **配套命令**：`npx skills list` 查看已装、`npx skills update` 更新、`npx skills remove` 卸载

### 方式二：通用 Agent Skills

以目录为单位放置：把 `xin-fanqie-style-xxx/`（含 `SKILL.md`）复制到 Agent 的 skills 目录（如 `~/.claude/skills/`），目录名即技能名。

### 方式三：zip 上传至 AI 工具（豆包 / WorkBuddy 等）

支持自定义技能/插件导入的 AI 工具（如豆包、WorkBuddy 等）普遍采用 **zip 上传**方式：直接上传对应技能的 `.zip` 文件，工具会自动解压并识别 `SKILL.md` 完成技能安装，无需手动放置目录。

技能包在 [Releases](https://github.com/oscar-wang-xin/xin-skills/releases) 页面下载，每个技能一个 `.zip`，文件名与技能目录名一致。

### 方式四：zip 直接分发

从 [Releases](https://github.com/oscar-wang-xin/xin-skills/releases) 下载单个 `.zip`，解压即得完整技能目录，适合手动分享与离线安装。

> 为什么仓库里没有 zip：每个 zip 与对应目录内容完全相同，会让仓库体积与根目录条目成倍膨胀，且每改一次技能正文就多一份二进制历史。所以 zip 只在发布时作为 Release 附件提供。

---

## 使用方法

在写作指令中带上对应技能的**触发词**，AI 即自动套用该文风规范。示例：

```
按《剑起白玉京》文风写一章：主角许闲参加宗门问心考核……
```

常用触发词可以直接问 AI「用《书名》文风写」，技能描述里已内置触发词；
需要逐个查表时看 [触发词一览](docs/triggers.md)（由脚本从各技能 description 生成，不会过期）。

---

## 风格画像

每个技能都有一页「风格画像」：这本书的文风长什么样、核心特征与情绪基调。

<!-- BEGIN:CATALOG-INDEX -->

| 分类 | 数量 | 画像页 |
| --- | --- | --- |
| 🍅 番茄小说风格 | 19 | [查看](docs/catalog/fanqie.md) |
| 🥋 古龙武侠风格 | 4 | [查看](docs/catalog/gulong.md) |
| ⚔️ 金庸武侠风格 | 10 | [查看](docs/catalog/jinyong.md) |
| 🌊 黄易风格 | 7 | [查看](docs/catalog/huangyi.md) |
| 📖 梁羽生武侠风格 | 22 | [查看](docs/catalog/liangyusheng.md) |
| 💃 女作者言情风格 | 29 | [查看](docs/catalog/lady.md) |
| 🎭 王朔风格 | 15 | [查看](docs/catalog/wangshuo.md) |
| 📚 网络文学名家风格 | 31 | [查看](docs/catalog/mingjia.md) |

<!-- END:CATALOG-INDEX -->

> 画像正文按「分类」手工维护；新增技能时在对应页面追加一节即可，不需要重排编号。

---

## 技能内部结构

每个技能都包含一份从正文样本萃取的**十维写作风格规范**（写入 `SKILL.md`）：

1. **叙事视角** — 人称、视点切换规则与标记方式
2. **句式特征** — 句长、分段、标点节奏
3. **对话体系** — 台词长度、交锋节奏、对话标签用法
4. **叙事节奏** — 冲突切入速度、铺垫方式、信息释放
5. **词汇与修辞** — 高频词清单、专属设定名词、惯用修辞
6. **情绪基调** — 调性定位、每章情绪曲线模板、幽默与爽感来源
7. **章节钩子写法** — 章末悬念类型、收尾句式偏好
8. **环境描写** — 描写密度上限、手法与位置规则
9. **行文禁忌** — 明确禁止项（如无标记视角跳跃、堆砌成语、上帝视角）
10. **开篇习惯** — 开篇切入方式与前 200 字信息密度要求

`SKILL.md` 还包含「允许与禁止清单」与「写作执行要求」，保证 AI 只模仿文笔、绝不回退到通用 AI 书面腔。

```
xin-fanqie-style-baiyujing/
├── SKILL.md                        # 技能主文件：十维风格规范
└── references/
    └── style_examples.md           # 风格样本（多数技能附带）
```

仓库本身的结构：

```
xin-skills/
├── xin-<author>-style-<book>/   # 每个技能一个目录，根目录即安装单位
└── docs/
    ├── catalog/                 # 分类画像页（README「风格画像」的来源）
    └── triggers.md              # 触发词一览
```

技能格式遵循 Agent Skills 规范：目录名即技能名，`SKILL.md` 里的 `name` 必须与目录名一致。

---

## 版权与使用声明

- 本仓库中的技能**仅包含文风规范**，不包含任何参考小说的正文内容；`references/style_examples.md` 为风格特征提炼，非原文摘录。
- 所有参考作品的版权归原作者/版权方所有。本技能用于写作风格学习与创作辅助，**请勿**将其用于抄袭、洗稿、侵权再创作等用途。
- 每个 `SKILL.md` 均内置硬性规则：只模仿文笔、叙事节奏与语感，严禁抄袭、复述样本剧情。
- 本仓库的代码与技能文本以 [MIT](LICENSE) 许可发布；上述使用建议是作者的态度，不构成额外的许可限制。
