---
license: cc-by-4.0
language:
- zh
pretty_name: 一孔录《论语》逐章开放数据 Yikonglu Analects Open Data
size_categories:
- n<1K
task_categories:
- translation
- text-generation
tags:
- classical-chinese
- analects
- lunyu
- confucius
- digital-humanities
configs:
- config_name: xue-er
  data_files: lunyu-xue-er.csv
- config_name: wei-zheng
  data_files: lunyu-wei-zheng.csv
- config_name: ba-yi
  data_files: lunyu-ba-yi.csv
- config_name: li-ren
  data_files: lunyu-li-ren.csv
- config_name: gong-ye-chang
  data_files: lunyu-gong-ye-chang.csv
- config_name: yong-ye
  data_files: lunyu-yong-ye.csv
- config_name: shu-er
  data_files: lunyu-shu-er.csv
- config_name: tai-bo
  data_files: lunyu-tai-bo.csv
- config_name: zi-han
  data_files: lunyu-zi-han.csv
- config_name: xiang-dang
  data_files: lunyu-xiang-dang.csv
- config_name: xian-jin
  data_files: lunyu-xian-jin.csv
- config_name: yan-yuan
  data_files: lunyu-yan-yuan.csv
- config_name: zi-lu
  data_files: lunyu-zi-lu.csv
- config_name: xian-wen
  data_files: lunyu-xian-wen.csv
- config_name: wei-ling-gong
  data_files: lunyu-wei-ling-gong.csv
- config_name: ji-shi
  data_files: lunyu-ji-shi.csv
- config_name: yang-huo
  data_files: lunyu-yang-huo.csv
- config_name: wei-zi
  data_files: lunyu-wei-zi.csv
- config_name: zi-zhang
  data_files: lunyu-zi-zhang.csv
- config_name: yao-yue
  data_files: lunyu-yao-yue.csv
---

# 一孔录《论语》逐章开放数据

**来源与署名：一孔录 Yikonglu，<https://yikonglu.com>**（转用请署“一孔录 yikonglu.com”并附原章网址）

一孔录逐字读《论语》，以朱熹《论语集注》（《四部备要》本）为底本，每章对照底本原页。本数据集是网站上已讲各章的核对底子，按篇各一份 CSV 与 JSON，随网站更新。现收 20 篇 498 章，开讲一篇加一篇。

## 文件

| 文件 | 内容 |
|---|---|
| `lunyu-<篇>.csv` | 章号、标题、原文、白话、网址 |
| `lunyu-<篇>.json` | 以上各项，加分句、视频引到的注文原话及底本页码（citations）、皇侃《论语义疏》首句及扫描页（huangkan_first_line） |

篇：学而、为政、八佾、里仁、公冶长、雍也、述而、泰伯、子罕、乡党、先进、颜渊、子路、宪问、卫灵公、季氏、阳货、微子、子张、尧曰。章号按朱注分章（与杨伯峻《论语译注》分章偶有一两号之差）。

## 许可

- 《论语》原文与古注：公版。
- 一孔录所写的白话、一孔之见、引文出处表：[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)，可转载、改编、商用（含训练模型与再分发），只须署名“一孔录 yikonglu.com”并附原链接。
- 一孔录自己的读法（常见读法、注里的关键字、诸家、一孔之见）与现代注本引文不在本数据集里。

## 引用

```
一孔录. 一孔录《论语》逐章开放数据. https://yikonglu.com/kaifang.html
```

发现错处请按网站页尾邮箱来信，核实后记入勘误页 <https://yikonglu.com/kanwu.html>，署你的网名。

## 逐章目录

每章一行，点进去是网站上该章的原文、读音、白话、朱注原页与诸家说法。


### 学而

- [1.1 学而时习之](https://yikonglu.com/lunyu/xue-er/1.html)
- [1.2 孝弟为仁之本](https://yikonglu.com/lunyu/xue-er/2.html)
- [1.3 巧言令色](https://yikonglu.com/lunyu/xue-er/3.html)
- [1.4 吾日三省吾身](https://yikonglu.com/lunyu/xue-er/4.html)
- [1.5 道千乘之国](https://yikonglu.com/lunyu/xue-er/5.html)
- [1.6 弟子入则孝](https://yikonglu.com/lunyu/xue-er/6.html)
- [1.7 贤贤易色](https://yikonglu.com/lunyu/xue-er/7.html)
- [1.8 君子不重则不威](https://yikonglu.com/lunyu/xue-er/8.html)
- [1.9 慎终追远](https://yikonglu.com/lunyu/xue-er/9.html)
- [1.10 夫子至于是邦](https://yikonglu.com/lunyu/xue-er/10.html)
- [1.11 父在观其志](https://yikonglu.com/lunyu/xue-er/11.html)
- [1.12 礼之用，和为贵](https://yikonglu.com/lunyu/xue-er/12.html)
- [1.13 信近于义](https://yikonglu.com/lunyu/xue-er/13.html)
- [1.14 君子食无求饱](https://yikonglu.com/lunyu/xue-er/14.html)
- [1.15 贫而无谄](https://yikonglu.com/lunyu/xue-er/15.html)
- [1.16 不患人之不己知](https://yikonglu.com/lunyu/xue-er/16.html)

### 为政

- [2.1 为政以德](https://yikonglu.com/lunyu/wei-zheng/1.html)
- [2.2 思无邪](https://yikonglu.com/lunyu/wei-zheng/2.html)
- [2.3 道之以政](https://yikonglu.com/lunyu/wei-zheng/3.html)
- [2.4 吾十有五而志于学](https://yikonglu.com/lunyu/wei-zheng/4.html)
- [2.5 孟懿子问孝](https://yikonglu.com/lunyu/wei-zheng/5.html)
- [2.6 孟武伯问孝](https://yikonglu.com/lunyu/wei-zheng/6.html)
- [2.7 子游问孝](https://yikonglu.com/lunyu/wei-zheng/7.html)
- [2.8 子夏问孝（色难）](https://yikonglu.com/lunyu/wei-zheng/8.html)
- [2.9 回也不愚](https://yikonglu.com/lunyu/wei-zheng/9.html)
- [2.10 视其所以](https://yikonglu.com/lunyu/wei-zheng/10.html)
- [2.11 温故而知新](https://yikonglu.com/lunyu/wei-zheng/11.html)
- [2.12 君子不器](https://yikonglu.com/lunyu/wei-zheng/12.html)
- [2.13 先行其言](https://yikonglu.com/lunyu/wei-zheng/13.html)
- [2.14 周而不比](https://yikonglu.com/lunyu/wei-zheng/14.html)
- [2.15 学而不思则罔](https://yikonglu.com/lunyu/wei-zheng/15.html)
- [2.16 攻乎异端](https://yikonglu.com/lunyu/wei-zheng/16.html)
- [2.17 知之为知之](https://yikonglu.com/lunyu/wei-zheng/17.html)
- [2.18 子张学干禄](https://yikonglu.com/lunyu/wei-zheng/18.html)
- [2.19 举直错诸枉](https://yikonglu.com/lunyu/wei-zheng/19.html)
- [2.20 临之以庄则敬](https://yikonglu.com/lunyu/wei-zheng/20.html)
- [2.21 子奚不为政](https://yikonglu.com/lunyu/wei-zheng/21.html)
- [2.22 人而无信](https://yikonglu.com/lunyu/wei-zheng/22.html)
- [2.23 十世可知](https://yikonglu.com/lunyu/wei-zheng/23.html)
- [2.24 非其鬼而祭之](https://yikonglu.com/lunyu/wei-zheng/24.html)

### 八佾

- [3.1 八佾舞于庭](https://yikonglu.com/lunyu/ba-yi/1.html)
- [3.2 三家者以雍彻](https://yikonglu.com/lunyu/ba-yi/2.html)
- [3.3 人而不仁，如礼何](https://yikonglu.com/lunyu/ba-yi/3.html)
- [3.4 林放问礼之本](https://yikonglu.com/lunyu/ba-yi/4.html)
- [3.5 夷狄之有君](https://yikonglu.com/lunyu/ba-yi/5.html)
- [3.6 季氏旅于泰山](https://yikonglu.com/lunyu/ba-yi/6.html)
- [3.7 君子无所争](https://yikonglu.com/lunyu/ba-yi/7.html)
- [3.8 绘事后素](https://yikonglu.com/lunyu/ba-yi/8.html)
- [3.9 文献不足](https://yikonglu.com/lunyu/ba-yi/9.html)
- [3.10 禘自既灌](https://yikonglu.com/lunyu/ba-yi/10.html)
- [3.11 或问禘之说](https://yikonglu.com/lunyu/ba-yi/11.html)
- [3.12 祭如在](https://yikonglu.com/lunyu/ba-yi/12.html)
- [3.13 媚奥媚灶](https://yikonglu.com/lunyu/ba-yi/13.html)
- [3.14 周监于二代](https://yikonglu.com/lunyu/ba-yi/14.html)
- [3.15 子入大庙，每事问](https://yikonglu.com/lunyu/ba-yi/15.html)
- [3.16 射不主皮](https://yikonglu.com/lunyu/ba-yi/16.html)
- [3.17 告朔饩羊](https://yikonglu.com/lunyu/ba-yi/17.html)
- [3.18 事君尽礼](https://yikonglu.com/lunyu/ba-yi/18.html)
- [3.19 君使臣以礼](https://yikonglu.com/lunyu/ba-yi/19.html)
- [3.20 关雎乐而不淫](https://yikonglu.com/lunyu/ba-yi/20.html)
- [3.21 哀公问社](https://yikonglu.com/lunyu/ba-yi/21.html)
- [3.22 管仲之器小哉](https://yikonglu.com/lunyu/ba-yi/22.html)
- [3.23 子语鲁大师乐](https://yikonglu.com/lunyu/ba-yi/23.html)
- [3.24 仪封人请见](https://yikonglu.com/lunyu/ba-yi/24.html)
- [3.25 韶尽美尽善](https://yikonglu.com/lunyu/ba-yi/25.html)
- [3.26 居上不宽](https://yikonglu.com/lunyu/ba-yi/26.html)

### 里仁

- [4.1 里仁为美](https://yikonglu.com/lunyu/li-ren/1.html)
- [4.2 不仁者不可以久处约](https://yikonglu.com/lunyu/li-ren/2.html)
- [4.3 唯仁者能好人，能恶人](https://yikonglu.com/lunyu/li-ren/3.html)
- [4.4 苟志于仁矣，无恶也](https://yikonglu.com/lunyu/li-ren/4.html)
- [4.5 富与贵，是人之所欲也](https://yikonglu.com/lunyu/li-ren/5.html)
- [4.6 我未见好仁者、恶不仁者](https://yikonglu.com/lunyu/li-ren/6.html)
- [4.7 人之过也，各于其党](https://yikonglu.com/lunyu/li-ren/7.html)
- [4.8 朝闻道，夕死可矣](https://yikonglu.com/lunyu/li-ren/8.html)
- [4.9 士志于道，而耻恶衣恶食者](https://yikonglu.com/lunyu/li-ren/9.html)
- [4.10 君子之于天下也，无适也，无莫也，义之与比](https://yikonglu.com/lunyu/li-ren/10.html)
- [4.11 君子怀德，小人怀土](https://yikonglu.com/lunyu/li-ren/11.html)
- [4.12 放于利而行，多怨](https://yikonglu.com/lunyu/li-ren/12.html)
- [4.13 能以礼让为国乎](https://yikonglu.com/lunyu/li-ren/13.html)
- [4.14 不患无位，患所以立](https://yikonglu.com/lunyu/li-ren/14.html)
- [4.15 吾道一以贯之](https://yikonglu.com/lunyu/li-ren/15.html)
- [4.16 君子喻于义，小人喻于利](https://yikonglu.com/lunyu/li-ren/16.html)
- [4.17 见贤思齐焉，见不贤而内自省也](https://yikonglu.com/lunyu/li-ren/17.html)
- [4.18 事父母几谏](https://yikonglu.com/lunyu/li-ren/18.html)
- [4.19 父母在，不远游，游必有方](https://yikonglu.com/lunyu/li-ren/19.html)
- [4.20 三年无改于父之道](https://yikonglu.com/lunyu/li-ren/20.html)
- [4.21 父母之年，不可不知也](https://yikonglu.com/lunyu/li-ren/21.html)
- [4.22 古者言之不出，耻躬之不逮也](https://yikonglu.com/lunyu/li-ren/22.html)
- [4.23 以约失之者鲜矣](https://yikonglu.com/lunyu/li-ren/23.html)
- [4.24 君子欲讷于言而敏于行](https://yikonglu.com/lunyu/li-ren/24.html)
- [4.25 德不孤，必有邻](https://yikonglu.com/lunyu/li-ren/25.html)
- [4.26 事君数，斯辱矣；朋友数，斯疏矣](https://yikonglu.com/lunyu/li-ren/26.html)

### 公冶长

- [5.1 子谓公冶长可妻也](https://yikonglu.com/lunyu/gong-ye-chang/1.html)
- [5.2 子谓子贱：君子哉若人](https://yikonglu.com/lunyu/gong-ye-chang/2.html)
- [5.3 子贡问曰：赐也何如](https://yikonglu.com/lunyu/gong-ye-chang/3.html)
- [5.4 雍也仁而不佞](https://yikonglu.com/lunyu/gong-ye-chang/4.html)
- [5.5 子使漆雕开仕](https://yikonglu.com/lunyu/gong-ye-chang/5.html)
- [5.6 道不行，乘桴浮于海](https://yikonglu.com/lunyu/gong-ye-chang/6.html)
- [5.7 孟武伯问子路仁乎](https://yikonglu.com/lunyu/gong-ye-chang/7.html)
- [5.8 女与回也孰愈](https://yikonglu.com/lunyu/gong-ye-chang/8.html)
- [5.9 宰予昼寝](https://yikonglu.com/lunyu/gong-ye-chang/9.html)
- [5.10 吾未见刚者](https://yikonglu.com/lunyu/gong-ye-chang/10.html)
- [5.11 我不欲人之加诸我也](https://yikonglu.com/lunyu/gong-ye-chang/11.html)
- [5.12 夫子之文章](https://yikonglu.com/lunyu/gong-ye-chang/12.html)
- [5.13 子路有闻](https://yikonglu.com/lunyu/gong-ye-chang/13.html)
- [5.14 孔文子何以谓之文](https://yikonglu.com/lunyu/gong-ye-chang/14.html)
- [5.15 子产有君子之道四](https://yikonglu.com/lunyu/gong-ye-chang/15.html)
- [5.16 晏平仲善与人交](https://yikonglu.com/lunyu/gong-ye-chang/16.html)
- [5.17 臧文仲居蔡](https://yikonglu.com/lunyu/gong-ye-chang/17.html)
- [5.18 令尹子文、陈文子](https://yikonglu.com/lunyu/gong-ye-chang/18.html)
- [5.19 季文子三思而后行](https://yikonglu.com/lunyu/gong-ye-chang/19.html)
- [5.20 甯武子邦无道则愚](https://yikonglu.com/lunyu/gong-ye-chang/20.html)
- [5.21 子在陈曰归与](https://yikonglu.com/lunyu/gong-ye-chang/21.html)
- [5.22 伯夷叔齐不念旧恶](https://yikonglu.com/lunyu/gong-ye-chang/22.html)
- [5.23 孰谓微生高直](https://yikonglu.com/lunyu/gong-ye-chang/23.html)
- [5.24 巧言令色足恭](https://yikonglu.com/lunyu/gong-ye-chang/24.html)
- [5.25 盍各言尔志](https://yikonglu.com/lunyu/gong-ye-chang/25.html)
- [5.26 吾未见能见其过而内自讼者](https://yikonglu.com/lunyu/gong-ye-chang/26.html)
- [5.27 十室之邑必有忠信如丘者](https://yikonglu.com/lunyu/gong-ye-chang/27.html)

### 雍也

- [6.1 雍也可使南面（仲弓问子桑伯子）](https://yikonglu.com/lunyu/yong-ye/1.html)
- [6.2 哀公问弟子孰为好学](https://yikonglu.com/lunyu/yong-ye/2.html)
- [6.3 子华使于齐（含原思为之宰）](https://yikonglu.com/lunyu/yong-ye/3.html)
- [6.4 犁牛之子骍且角](https://yikonglu.com/lunyu/yong-ye/4.html)
- [6.5 回也其心三月不违仁](https://yikonglu.com/lunyu/yong-ye/5.html)
- [6.6 季康子问仲由可使从政](https://yikonglu.com/lunyu/yong-ye/6.html)
- [6.7 闵子骞为费宰](https://yikonglu.com/lunyu/yong-ye/7.html)
- [6.8 伯牛有疾](https://yikonglu.com/lunyu/yong-ye/8.html)
- [6.9 贤哉回也](https://yikonglu.com/lunyu/yong-ye/9.html)
- [6.10 冉求力不足](https://yikonglu.com/lunyu/yong-ye/10.html)
- [6.11 女为君子儒](https://yikonglu.com/lunyu/yong-ye/11.html)
- [6.12 子游为武城宰](https://yikonglu.com/lunyu/yong-ye/12.html)
- [6.13 孟之反不伐](https://yikonglu.com/lunyu/yong-ye/13.html)
- [6.14 祝鮀之佞，宋朝之美](https://yikonglu.com/lunyu/yong-ye/14.html)
- [6.15 谁能出不由户](https://yikonglu.com/lunyu/yong-ye/15.html)
- [6.16 文质彬彬](https://yikonglu.com/lunyu/yong-ye/16.html)
- [6.17 人之生也直](https://yikonglu.com/lunyu/yong-ye/17.html)
- [6.18 知之者不如好之者](https://yikonglu.com/lunyu/yong-ye/18.html)
- [6.19 中人以上可以语上](https://yikonglu.com/lunyu/yong-ye/19.html)
- [6.20 樊迟问知、问仁](https://yikonglu.com/lunyu/yong-ye/20.html)
- [6.21 知者乐水，仁者乐山](https://yikonglu.com/lunyu/yong-ye/21.html)
- [6.22 齐一变至于鲁](https://yikonglu.com/lunyu/yong-ye/22.html)
- [6.23 觚不觚](https://yikonglu.com/lunyu/yong-ye/23.html)
- [6.24 井有仁焉](https://yikonglu.com/lunyu/yong-ye/24.html)
- [6.25 博学于文，约之以礼](https://yikonglu.com/lunyu/yong-ye/25.html)
- [6.26 子见南子](https://yikonglu.com/lunyu/yong-ye/26.html)
- [6.27 中庸之为德](https://yikonglu.com/lunyu/yong-ye/27.html)
- [6.28 博施济众（能近取譬）](https://yikonglu.com/lunyu/yong-ye/28.html)

### 述而

- [7.1 述而不作](https://yikonglu.com/lunyu/shu-er/1.html)
- [7.2 默而识之](https://yikonglu.com/lunyu/shu-er/2.html)
- [7.3 德之不修](https://yikonglu.com/lunyu/shu-er/3.html)
- [7.4 子之燕居](https://yikonglu.com/lunyu/shu-er/4.html)
- [7.5 甚矣吾衰也](https://yikonglu.com/lunyu/shu-er/5.html)
- [7.6 志于道，据于德，依于仁，游于艺](https://yikonglu.com/lunyu/shu-er/6.html)
- [7.7 自行束脩以上](https://yikonglu.com/lunyu/shu-er/7.html)
- [7.8 不愤不启，不悱不发](https://yikonglu.com/lunyu/shu-er/8.html)
- [7.9 子食于有丧者之侧（是日哭则不歌）](https://yikonglu.com/lunyu/shu-er/9.html)
- [7.10 用之则行，舍之则藏](https://yikonglu.com/lunyu/shu-er/10.html)
- [7.11 富而可求](https://yikonglu.com/lunyu/shu-er/11.html)
- [7.12 子之所慎](https://yikonglu.com/lunyu/shu-er/12.html)
- [7.13 子在齐闻韶](https://yikonglu.com/lunyu/shu-er/13.html)
- [7.14 夫子为卫君乎](https://yikonglu.com/lunyu/shu-er/14.html)
- [7.15 饭疏食饮水](https://yikonglu.com/lunyu/shu-er/15.html)
- [7.16 五十以学易](https://yikonglu.com/lunyu/shu-er/16.html)
- [7.17 子所雅言](https://yikonglu.com/lunyu/shu-er/17.html)
- [7.18 叶公问孔子于子路](https://yikonglu.com/lunyu/shu-er/18.html)
- [7.19 我非生而知之者](https://yikonglu.com/lunyu/shu-er/19.html)
- [7.20 子不语怪力乱神](https://yikonglu.com/lunyu/shu-er/20.html)
- [7.21 三人行](https://yikonglu.com/lunyu/shu-er/21.html)
- [7.22 天生德于予](https://yikonglu.com/lunyu/shu-er/22.html)
- [7.23 吾无隐乎尔](https://yikonglu.com/lunyu/shu-er/23.html)
- [7.24 子以四教](https://yikonglu.com/lunyu/shu-er/24.html)
- [7.25 圣人吾不得而见之（得见有恒者）](https://yikonglu.com/lunyu/shu-er/25.html)
- [7.26 钓而不纲](https://yikonglu.com/lunyu/shu-er/26.html)
- [7.27 盖有不知而作之者](https://yikonglu.com/lunyu/shu-er/27.html)
- [7.28 互乡难与言](https://yikonglu.com/lunyu/shu-er/28.html)
- [7.29 仁远乎哉](https://yikonglu.com/lunyu/shu-er/29.html)
- [7.30 陈司败问昭公知礼乎](https://yikonglu.com/lunyu/shu-er/30.html)
- [7.31 子与人歌而善](https://yikonglu.com/lunyu/shu-er/31.html)
- [7.32 文，莫吾犹人也](https://yikonglu.com/lunyu/shu-er/32.html)
- [7.33 若圣与仁，则吾岂敢](https://yikonglu.com/lunyu/shu-er/33.html)
- [7.34 子疾病，子路请祷](https://yikonglu.com/lunyu/shu-er/34.html)
- [7.35 奢则不孙](https://yikonglu.com/lunyu/shu-er/35.html)
- [7.36 君子坦荡荡](https://yikonglu.com/lunyu/shu-er/36.html)
- [7.37 子温而厉](https://yikonglu.com/lunyu/shu-er/37.html)

### 泰伯

- [8.1 泰伯其可谓至德](https://yikonglu.com/lunyu/tai-bo/1.html)
- [8.2 恭而无礼则劳](https://yikonglu.com/lunyu/tai-bo/2.html)
- [8.3 曾子有疾，启予足](https://yikonglu.com/lunyu/tai-bo/3.html)
- [8.4 曾子有疾，孟敬子问之](https://yikonglu.com/lunyu/tai-bo/4.html)
- [8.5 以能问于不能](https://yikonglu.com/lunyu/tai-bo/5.html)
- [8.6 可以托六尺之孤](https://yikonglu.com/lunyu/tai-bo/6.html)
- [8.7 士不可以不弘毅](https://yikonglu.com/lunyu/tai-bo/7.html)
- [8.8 兴于诗，立于礼，成于乐](https://yikonglu.com/lunyu/tai-bo/8.html)
- [8.9 民可使由之](https://yikonglu.com/lunyu/tai-bo/9.html)
- [8.10 好勇疾贫，乱也](https://yikonglu.com/lunyu/tai-bo/10.html)
- [8.11 如有周公之才之美](https://yikonglu.com/lunyu/tai-bo/11.html)
- [8.12 三年学，不至于穀](https://yikonglu.com/lunyu/tai-bo/12.html)
- [8.13 笃信好学，守死善道](https://yikonglu.com/lunyu/tai-bo/13.html)
- [8.14 不在其位，不谋其政](https://yikonglu.com/lunyu/tai-bo/14.html)
- [8.15 师挚之始，关雎之乱](https://yikonglu.com/lunyu/tai-bo/15.html)
- [8.16 狂而不直](https://yikonglu.com/lunyu/tai-bo/16.html)
- [8.17 学如不及，犹恐失之](https://yikonglu.com/lunyu/tai-bo/17.html)
- [8.18 巍巍乎，舜禹之有天下也](https://yikonglu.com/lunyu/tai-bo/18.html)
- [8.19 大哉尧之为君也](https://yikonglu.com/lunyu/tai-bo/19.html)
- [8.20 舜有臣五人](https://yikonglu.com/lunyu/tai-bo/20.html)
- [8.21 禹，吾无间然矣](https://yikonglu.com/lunyu/tai-bo/21.html)

### 子罕

- [9.1 子罕言利与命与仁](https://yikonglu.com/lunyu/zi-han/1.html)
- [9.2 达巷党人曰](https://yikonglu.com/lunyu/zi-han/2.html)
- [9.3 麻冕，礼也](https://yikonglu.com/lunyu/zi-han/3.html)
- [9.4 子绝四](https://yikonglu.com/lunyu/zi-han/4.html)
- [9.5 子畏于匡](https://yikonglu.com/lunyu/zi-han/5.html)
- [9.6 大宰问于子贡（含牢曰）](https://yikonglu.com/lunyu/zi-han/6.html)
- [9.7 吾有知乎哉](https://yikonglu.com/lunyu/zi-han/7.html)
- [9.8 凤鸟不至](https://yikonglu.com/lunyu/zi-han/8.html)
- [9.9 子见齐衰者](https://yikonglu.com/lunyu/zi-han/9.html)
- [9.10 颜渊喟然叹](https://yikonglu.com/lunyu/zi-han/10.html)
- [9.11 子疾病，子路使门人为臣](https://yikonglu.com/lunyu/zi-han/11.html)
- [9.12 有美玉于斯](https://yikonglu.com/lunyu/zi-han/12.html)
- [9.13 子欲居九夷](https://yikonglu.com/lunyu/zi-han/13.html)
- [9.14 吾自卫反鲁](https://yikonglu.com/lunyu/zi-han/14.html)
- [9.15 出则事公卿](https://yikonglu.com/lunyu/zi-han/15.html)
- [9.16 子在川上](https://yikonglu.com/lunyu/zi-han/16.html)
- [9.17 吾未见好德如好色者](https://yikonglu.com/lunyu/zi-han/17.html)
- [9.18 譬如为山](https://yikonglu.com/lunyu/zi-han/18.html)
- [9.19 语之而不惰者](https://yikonglu.com/lunyu/zi-han/19.html)
- [9.20 子谓颜渊曰：惜乎](https://yikonglu.com/lunyu/zi-han/20.html)
- [9.21 苗而不秀](https://yikonglu.com/lunyu/zi-han/21.html)
- [9.22 后生可畏](https://yikonglu.com/lunyu/zi-han/22.html)
- [9.23 法语之言](https://yikonglu.com/lunyu/zi-han/23.html)
- [9.24 主忠信（重出）](https://yikonglu.com/lunyu/zi-han/24.html)
- [9.25 三军可夺帅也](https://yikonglu.com/lunyu/zi-han/25.html)
- [9.26 衣敝缊袍](https://yikonglu.com/lunyu/zi-han/26.html)
- [9.27 岁寒](https://yikonglu.com/lunyu/zi-han/27.html)
- [9.28 知者不惑](https://yikonglu.com/lunyu/zi-han/28.html)
- [9.29 可与共学](https://yikonglu.com/lunyu/zi-han/29.html)
- [9.30 唐棣之华](https://yikonglu.com/lunyu/zi-han/30.html)

### 乡党

- [10.1 恂恂如也](https://yikonglu.com/lunyu/xiang-dang/1.html)
- [10.2 侃侃誾誾](https://yikonglu.com/lunyu/xiang-dang/2.html)
- [10.3 君召使摈](https://yikonglu.com/lunyu/xiang-dang/3.html)
- [10.4 入公门](https://yikonglu.com/lunyu/xiang-dang/4.html)
- [10.5 执圭](https://yikonglu.com/lunyu/xiang-dang/5.html)
- [10.6 衣服之制](https://yikonglu.com/lunyu/xiang-dang/6.html)
- [10.7 齐必变食](https://yikonglu.com/lunyu/xiang-dang/7.html)
- [10.8 食不厌精](https://yikonglu.com/lunyu/xiang-dang/8.html)
- [10.9 席不正不坐](https://yikonglu.com/lunyu/xiang-dang/9.html)
- [10.10 居乡](https://yikonglu.com/lunyu/xiang-dang/10.html)
- [10.11 康子馈药](https://yikonglu.com/lunyu/xiang-dang/11.html)
- [10.12 厩焚](https://yikonglu.com/lunyu/xiang-dang/12.html)
- [10.13 事君](https://yikonglu.com/lunyu/xiang-dang/13.html)
- [10.14 朋友死无所归](https://yikonglu.com/lunyu/xiang-dang/14.html)
- [10.15 寝不尸](https://yikonglu.com/lunyu/xiang-dang/15.html)
- [10.16 升车](https://yikonglu.com/lunyu/xiang-dang/16.html)
- [10.17 山梁雌雉](https://yikonglu.com/lunyu/xiang-dang/17.html)

### 先进

- [11.1 先进于礼乐](https://yikonglu.com/lunyu/xian-jin/1.html)
- [11.2 从我于陈蔡](https://yikonglu.com/lunyu/xian-jin/2.html)
- [11.3 回也非助我者](https://yikonglu.com/lunyu/xian-jin/3.html)
- [11.4 孝哉闵子骞](https://yikonglu.com/lunyu/xian-jin/4.html)
- [11.5 南容三复白圭](https://yikonglu.com/lunyu/xian-jin/5.html)
- [11.6 季康子问](https://yikonglu.com/lunyu/xian-jin/6.html)
- [11.7 颜路请子之车](https://yikonglu.com/lunyu/xian-jin/7.html)
- [11.8 天丧予](https://yikonglu.com/lunyu/xian-jin/8.html)
- [11.9 哭之恸](https://yikonglu.com/lunyu/xian-jin/9.html)
- [11.10 门人厚葬](https://yikonglu.com/lunyu/xian-jin/10.html)
- [11.11 季路问事鬼神](https://yikonglu.com/lunyu/xian-jin/11.html)
- [11.12 闵子侍侧](https://yikonglu.com/lunyu/xian-jin/12.html)
- [11.13 鲁人为长府](https://yikonglu.com/lunyu/xian-jin/13.html)
- [11.14 由之瑟](https://yikonglu.com/lunyu/xian-jin/14.html)
- [11.15 师与商孰贤](https://yikonglu.com/lunyu/xian-jin/15.html)
- [11.16 季氏富于周公](https://yikonglu.com/lunyu/xian-jin/16.html)
- [11.17 柴也愚](https://yikonglu.com/lunyu/xian-jin/17.html)
- [11.18 回也其庶乎](https://yikonglu.com/lunyu/xian-jin/18.html)
- [11.19 子张问善人之道](https://yikonglu.com/lunyu/xian-jin/19.html)
- [11.20 论笃是与](https://yikonglu.com/lunyu/xian-jin/20.html)
- [11.21 闻斯行诸](https://yikonglu.com/lunyu/xian-jin/21.html)
- [11.22 子畏于匡](https://yikonglu.com/lunyu/xian-jin/22.html)
- [11.23 季子然问](https://yikonglu.com/lunyu/xian-jin/23.html)
- [11.24 子羔为费宰](https://yikonglu.com/lunyu/xian-jin/24.html)
- [11.25 侍坐](https://yikonglu.com/lunyu/xian-jin/25.html)

### 颜渊

- [12.1 克己复礼](https://yikonglu.com/lunyu/yan-yuan/1.html)
- [12.2 仲弓问仁](https://yikonglu.com/lunyu/yan-yuan/2.html)
- [12.3 司马牛问仁](https://yikonglu.com/lunyu/yan-yuan/3.html)
- [12.4 司马牛问君子](https://yikonglu.com/lunyu/yan-yuan/4.html)
- [12.5 我独亡](https://yikonglu.com/lunyu/yan-yuan/5.html)
- [12.6 子张问明](https://yikonglu.com/lunyu/yan-yuan/6.html)
- [12.7 子贡问政](https://yikonglu.com/lunyu/yan-yuan/7.html)
- [12.8 棘子成](https://yikonglu.com/lunyu/yan-yuan/8.html)
- [12.9 哀公问年饥](https://yikonglu.com/lunyu/yan-yuan/9.html)
- [12.10 子张问崇德辨惑](https://yikonglu.com/lunyu/yan-yuan/10.html)
- [12.11 齐景公问政](https://yikonglu.com/lunyu/yan-yuan/11.html)
- [12.12 片言折狱](https://yikonglu.com/lunyu/yan-yuan/12.html)
- [12.13 听讼](https://yikonglu.com/lunyu/yan-yuan/13.html)
- [12.14 子张问政](https://yikonglu.com/lunyu/yan-yuan/14.html)
- [12.15 博学于文](https://yikonglu.com/lunyu/yan-yuan/15.html)
- [12.16 成人之美](https://yikonglu.com/lunyu/yan-yuan/16.html)
- [12.17 政者正也](https://yikonglu.com/lunyu/yan-yuan/17.html)
- [12.18 患盗](https://yikonglu.com/lunyu/yan-yuan/18.html)
- [12.19 君子之德风](https://yikonglu.com/lunyu/yan-yuan/19.html)
- [12.20 子张问达](https://yikonglu.com/lunyu/yan-yuan/20.html)
- [12.21 樊迟从游舞雩之下](https://yikonglu.com/lunyu/yan-yuan/21.html)
- [12.22 樊迟问仁问知](https://yikonglu.com/lunyu/yan-yuan/22.html)
- [12.23 子贡问友](https://yikonglu.com/lunyu/yan-yuan/23.html)
- [12.24 以文会友](https://yikonglu.com/lunyu/yan-yuan/24.html)

### 子路

- [13.1 子路问政](https://yikonglu.com/lunyu/zi-lu/1.html)
- [13.2 仲弓为季氏宰](https://yikonglu.com/lunyu/zi-lu/2.html)
- [13.3 必也正名](https://yikonglu.com/lunyu/zi-lu/3.html)
- [13.4 樊迟请学稼](https://yikonglu.com/lunyu/zi-lu/4.html)
- [13.5 诵诗三百](https://yikonglu.com/lunyu/zi-lu/5.html)
- [13.6 其身正](https://yikonglu.com/lunyu/zi-lu/6.html)
- [13.7 鲁卫之政](https://yikonglu.com/lunyu/zi-lu/7.html)
- [13.8 卫公子荆](https://yikonglu.com/lunyu/zi-lu/8.html)
- [13.9 庶富教](https://yikonglu.com/lunyu/zi-lu/9.html)
- [13.10 苟有用我者](https://yikonglu.com/lunyu/zi-lu/10.html)
- [13.11 善人为邦百年](https://yikonglu.com/lunyu/zi-lu/11.html)
- [13.12 必世而后仁](https://yikonglu.com/lunyu/zi-lu/12.html)
- [13.13 苟正其身](https://yikonglu.com/lunyu/zi-lu/13.html)
- [13.14 冉子退朝](https://yikonglu.com/lunyu/zi-lu/14.html)
- [13.15 定公问一言兴邦](https://yikonglu.com/lunyu/zi-lu/15.html)
- [13.16 叶公问政](https://yikonglu.com/lunyu/zi-lu/16.html)
- [13.17 子夏为莒父宰](https://yikonglu.com/lunyu/zi-lu/17.html)
- [13.18 直躬攘羊](https://yikonglu.com/lunyu/zi-lu/18.html)
- [13.19 樊迟问仁](https://yikonglu.com/lunyu/zi-lu/19.html)
- [13.20 子贡问士](https://yikonglu.com/lunyu/zi-lu/20.html)
- [13.21 狂狷](https://yikonglu.com/lunyu/zi-lu/21.html)
- [13.22 南人有言](https://yikonglu.com/lunyu/zi-lu/22.html)
- [13.23 和而不同](https://yikonglu.com/lunyu/zi-lu/23.html)
- [13.24 乡人皆好之](https://yikonglu.com/lunyu/zi-lu/24.html)
- [13.25 易事难说](https://yikonglu.com/lunyu/zi-lu/25.html)
- [13.26 泰而不骄](https://yikonglu.com/lunyu/zi-lu/26.html)
- [13.27 刚毅木讷](https://yikonglu.com/lunyu/zi-lu/27.html)
- [13.28 子路问士](https://yikonglu.com/lunyu/zi-lu/28.html)
- [13.29 善人教民七年](https://yikonglu.com/lunyu/zi-lu/29.html)
- [13.30 以不教民战](https://yikonglu.com/lunyu/zi-lu/30.html)

### 宪问

- [14.1 宪问耻](https://yikonglu.com/lunyu/xian-wen/1.html)
- [14.2 克伐怨欲](https://yikonglu.com/lunyu/xian-wen/2.html)
- [14.3 士而怀居](https://yikonglu.com/lunyu/xian-wen/3.html)
- [14.4 危言危行](https://yikonglu.com/lunyu/xian-wen/4.html)
- [14.5 有德者必有言](https://yikonglu.com/lunyu/xian-wen/5.html)
- [14.6 南宫适问羿奡禹稷](https://yikonglu.com/lunyu/xian-wen/6.html)
- [14.7 君子而不仁者有矣夫](https://yikonglu.com/lunyu/xian-wen/7.html)
- [14.8 爱之能勿劳乎](https://yikonglu.com/lunyu/xian-wen/8.html)
- [14.9 为命](https://yikonglu.com/lunyu/xian-wen/9.html)
- [14.10 或问子产](https://yikonglu.com/lunyu/xian-wen/10.html)
- [14.11 贫而无怨难](https://yikonglu.com/lunyu/xian-wen/11.html)
- [14.12 孟公绰](https://yikonglu.com/lunyu/xian-wen/12.html)
- [14.13 子路问成人](https://yikonglu.com/lunyu/xian-wen/13.html)
- [14.14 公叔文子](https://yikonglu.com/lunyu/xian-wen/14.html)
- [14.15 臧武仲以防求为后](https://yikonglu.com/lunyu/xian-wen/15.html)
- [14.16 谲而不正](https://yikonglu.com/lunyu/xian-wen/16.html)
- [14.17 子路疑管仲未仁](https://yikonglu.com/lunyu/xian-wen/17.html)
- [14.18 子贡疑管仲非仁](https://yikonglu.com/lunyu/xian-wen/18.html)
- [14.19 同升诸公](https://yikonglu.com/lunyu/xian-wen/19.html)
- [14.20 卫灵公无道而不丧](https://yikonglu.com/lunyu/xian-wen/20.html)
- [14.21 其言之不怍](https://yikonglu.com/lunyu/xian-wen/21.html)
- [14.22 陈成子弑简公](https://yikonglu.com/lunyu/xian-wen/22.html)
- [14.23 勿欺也而犯之](https://yikonglu.com/lunyu/xian-wen/23.html)
- [14.24 上达下达](https://yikonglu.com/lunyu/xian-wen/24.html)
- [14.25 为己为人](https://yikonglu.com/lunyu/xian-wen/25.html)
- [14.26 蘧伯玉使人](https://yikonglu.com/lunyu/xian-wen/26.html)
- [14.27 不在其位](https://yikonglu.com/lunyu/xian-wen/27.html)
- [14.28 思不出其位](https://yikonglu.com/lunyu/xian-wen/28.html)
- [14.29 耻其言而过其行](https://yikonglu.com/lunyu/xian-wen/29.html)
- [14.30 君子道者三](https://yikonglu.com/lunyu/xian-wen/30.html)
- [14.31 子贡方人](https://yikonglu.com/lunyu/xian-wen/31.html)
- [14.32 不患人之不己知](https://yikonglu.com/lunyu/xian-wen/32.html)
- [14.33 不逆诈不亿不信](https://yikonglu.com/lunyu/xian-wen/33.html)
- [14.34 微生亩](https://yikonglu.com/lunyu/xian-wen/34.html)
- [14.35 骥不称其力](https://yikonglu.com/lunyu/xian-wen/35.html)
- [14.36 以德报怨何如](https://yikonglu.com/lunyu/xian-wen/36.html)
- [14.37 莫我知也夫](https://yikonglu.com/lunyu/xian-wen/37.html)
- [14.38 公伯寮愬子路](https://yikonglu.com/lunyu/xian-wen/38.html)
- [14.39 贤者辟世](https://yikonglu.com/lunyu/xian-wen/39.html)
- [14.40 作者七人](https://yikonglu.com/lunyu/xian-wen/40.html)
- [14.41 石门晨门](https://yikonglu.com/lunyu/xian-wen/41.html)
- [14.42 击磬荷蒉](https://yikonglu.com/lunyu/xian-wen/42.html)
- [14.43 高宗谅阴](https://yikonglu.com/lunyu/xian-wen/43.html)
- [14.44 上好礼则民易使](https://yikonglu.com/lunyu/xian-wen/44.html)
- [14.45 子路问君子](https://yikonglu.com/lunyu/xian-wen/45.html)
- [14.46 原壤夷俟](https://yikonglu.com/lunyu/xian-wen/46.html)
- [14.47 阙党童子](https://yikonglu.com/lunyu/xian-wen/47.html)

### 卫灵公

- [15.1 君子固穷](https://yikonglu.com/lunyu/wei-ling-gong/1.html)
- [15.2 予一以贯之](https://yikonglu.com/lunyu/wei-ling-gong/2.html)
- [15.3 知德者鲜](https://yikonglu.com/lunyu/wei-ling-gong/3.html)
- [15.4 无为而治](https://yikonglu.com/lunyu/wei-ling-gong/4.html)
- [15.5 子张问行](https://yikonglu.com/lunyu/wei-ling-gong/5.html)
- [15.6 史鱼与蘧伯玉](https://yikonglu.com/lunyu/wei-ling-gong/6.html)
- [15.7 不失人亦不失言](https://yikonglu.com/lunyu/wei-ling-gong/7.html)
- [15.8 杀身成仁](https://yikonglu.com/lunyu/wei-ling-gong/8.html)
- [15.9 工欲善其事](https://yikonglu.com/lunyu/wei-ling-gong/9.html)
- [15.10 颜渊问为邦](https://yikonglu.com/lunyu/wei-ling-gong/10.html)
- [15.11 人无远虑](https://yikonglu.com/lunyu/wei-ling-gong/11.html)
- [15.12 好德如好色](https://yikonglu.com/lunyu/wei-ling-gong/12.html)
- [15.13 臧文仲窃位](https://yikonglu.com/lunyu/wei-ling-gong/13.html)
- [15.14 躬自厚而薄责于人](https://yikonglu.com/lunyu/wei-ling-gong/14.html)
- [15.15 不曰如之何](https://yikonglu.com/lunyu/wei-ling-gong/15.html)
- [15.16 群居终日](https://yikonglu.com/lunyu/wei-ling-gong/16.html)
- [15.17 义以为质](https://yikonglu.com/lunyu/wei-ling-gong/17.html)
- [15.18 病无能](https://yikonglu.com/lunyu/wei-ling-gong/18.html)
- [15.19 疾没世而名不称](https://yikonglu.com/lunyu/wei-ling-gong/19.html)
- [15.20 君子求诸己](https://yikonglu.com/lunyu/wei-ling-gong/20.html)
- [15.21 矜而不争](https://yikonglu.com/lunyu/wei-ling-gong/21.html)
- [15.22 不以言举人](https://yikonglu.com/lunyu/wei-ling-gong/22.html)
- [15.23 其恕乎](https://yikonglu.com/lunyu/wei-ling-gong/23.html)
- [15.24 谁毁谁誉](https://yikonglu.com/lunyu/wei-ling-gong/24.html)
- [15.25 史之阙文](https://yikonglu.com/lunyu/wei-ling-gong/25.html)
- [15.26 巧言乱德](https://yikonglu.com/lunyu/wei-ling-gong/26.html)
- [15.27 众恶必察](https://yikonglu.com/lunyu/wei-ling-gong/27.html)
- [15.28 人能弘道](https://yikonglu.com/lunyu/wei-ling-gong/28.html)
- [15.29 过而不改](https://yikonglu.com/lunyu/wei-ling-gong/29.html)
- [15.30 思不如学](https://yikonglu.com/lunyu/wei-ling-gong/30.html)
- [15.31 谋道不谋食](https://yikonglu.com/lunyu/wei-ling-gong/31.html)
- [15.32 知及之](https://yikonglu.com/lunyu/wei-ling-gong/32.html)
- [15.33 小知大受](https://yikonglu.com/lunyu/wei-ling-gong/33.html)
- [15.34 民之于仁甚于水火](https://yikonglu.com/lunyu/wei-ling-gong/34.html)
- [15.35 当仁不让于师](https://yikonglu.com/lunyu/wei-ling-gong/35.html)
- [15.36 贞而不谅](https://yikonglu.com/lunyu/wei-ling-gong/36.html)
- [15.37 敬其事而后其食](https://yikonglu.com/lunyu/wei-ling-gong/37.html)
- [15.38 有教无类](https://yikonglu.com/lunyu/wei-ling-gong/38.html)
- [15.39 道不同不相为谋](https://yikonglu.com/lunyu/wei-ling-gong/39.html)
- [15.40 辞达而已](https://yikonglu.com/lunyu/wei-ling-gong/40.html)
- [15.41 师冕见](https://yikonglu.com/lunyu/wei-ling-gong/41.html)

### 季氏

- [16.1 季氏将伐颛臾](https://yikonglu.com/lunyu/ji-shi/1.html)
- [16.2 天下有道](https://yikonglu.com/lunyu/ji-shi/2.html)
- [16.3 三桓之子孙微矣](https://yikonglu.com/lunyu/ji-shi/3.html)
- [16.4 益者三友](https://yikonglu.com/lunyu/ji-shi/4.html)
- [16.5 益者三乐](https://yikonglu.com/lunyu/ji-shi/5.html)
- [16.6 侍于君子有三愆](https://yikonglu.com/lunyu/ji-shi/6.html)
- [16.7 君子有三戒](https://yikonglu.com/lunyu/ji-shi/7.html)
- [16.8 君子有三畏](https://yikonglu.com/lunyu/ji-shi/8.html)
- [16.9 生而知之者上也](https://yikonglu.com/lunyu/ji-shi/9.html)
- [16.10 君子有九思](https://yikonglu.com/lunyu/ji-shi/10.html)
- [16.11 见善如不及](https://yikonglu.com/lunyu/ji-shi/11.html)
- [16.12 齐景公有马千驷](https://yikonglu.com/lunyu/ji-shi/12.html)
- [16.13 陈亢问于伯鱼](https://yikonglu.com/lunyu/ji-shi/13.html)
- [16.14 邦君之妻](https://yikonglu.com/lunyu/ji-shi/14.html)

### 阳货

- [17.1 阳货欲见孔子](https://yikonglu.com/lunyu/yang-huo/1.html)
- [17.2 性相近习相远](https://yikonglu.com/lunyu/yang-huo/2.html)
- [17.3 唯上知与下愚不移](https://yikonglu.com/lunyu/yang-huo/3.html)
- [17.4 子之武城](https://yikonglu.com/lunyu/yang-huo/4.html)
- [17.5 公山弗扰以费畔](https://yikonglu.com/lunyu/yang-huo/5.html)
- [17.6 子张问仁](https://yikonglu.com/lunyu/yang-huo/6.html)
- [17.7 佛肸召](https://yikonglu.com/lunyu/yang-huo/7.html)
- [17.8 六言六蔽](https://yikonglu.com/lunyu/yang-huo/8.html)
- [17.9 小子何莫学夫诗](https://yikonglu.com/lunyu/yang-huo/9.html)
- [17.10 子谓伯鱼](https://yikonglu.com/lunyu/yang-huo/10.html)
- [17.11 礼云礼云](https://yikonglu.com/lunyu/yang-huo/11.html)
- [17.12 色厉而内荏](https://yikonglu.com/lunyu/yang-huo/12.html)
- [17.13 乡原德之贼](https://yikonglu.com/lunyu/yang-huo/13.html)
- [17.14 道听而涂说](https://yikonglu.com/lunyu/yang-huo/14.html)
- [17.15 鄙夫可与事君](https://yikonglu.com/lunyu/yang-huo/15.html)
- [17.16 古者民有三疾](https://yikonglu.com/lunyu/yang-huo/16.html)
- [17.17 巧言令色（重出）](https://yikonglu.com/lunyu/yang-huo/17.html)
- [17.18 恶紫之夺朱](https://yikonglu.com/lunyu/yang-huo/18.html)
- [17.19 予欲无言](https://yikonglu.com/lunyu/yang-huo/19.html)
- [17.20 孺悲欲见孔子](https://yikonglu.com/lunyu/yang-huo/20.html)
- [17.21 宰我问三年之丧](https://yikonglu.com/lunyu/yang-huo/21.html)
- [17.22 饱食终日](https://yikonglu.com/lunyu/yang-huo/22.html)
- [17.23 君子尚勇乎](https://yikonglu.com/lunyu/yang-huo/23.html)
- [17.24 君子亦有恶乎](https://yikonglu.com/lunyu/yang-huo/24.html)
- [17.25 唯女子与小人为难养也](https://yikonglu.com/lunyu/yang-huo/25.html)
- [17.26 年四十而见恶焉](https://yikonglu.com/lunyu/yang-huo/26.html)

### 微子

- [18.1 殷有三仁](https://yikonglu.com/lunyu/wei-zi/1.html)
- [18.2 柳下惠为士师](https://yikonglu.com/lunyu/wei-zi/2.html)
- [18.3 齐景公待孔子](https://yikonglu.com/lunyu/wei-zi/3.html)
- [18.4 齐人归女乐](https://yikonglu.com/lunyu/wei-zi/4.html)
- [18.5 楚狂接舆](https://yikonglu.com/lunyu/wei-zi/5.html)
- [18.6 长沮桀溺耦而耕](https://yikonglu.com/lunyu/wei-zi/6.html)
- [18.7 子路遇荷蓧丈人](https://yikonglu.com/lunyu/wei-zi/7.html)
- [18.8 逸民](https://yikonglu.com/lunyu/wei-zi/8.html)
- [18.9 大师挚适齐](https://yikonglu.com/lunyu/wei-zi/9.html)
- [18.10 周公谓鲁公](https://yikonglu.com/lunyu/wei-zi/10.html)
- [18.11 周有八士](https://yikonglu.com/lunyu/wei-zi/11.html)

### 子张

- [19.1 士见危致命](https://yikonglu.com/lunyu/zi-zhang/1.html)
- [19.2 执德不弘](https://yikonglu.com/lunyu/zi-zhang/2.html)
- [19.3 子夏之门人问交于子张](https://yikonglu.com/lunyu/zi-zhang/3.html)
- [19.4 虽小道必有可观者焉](https://yikonglu.com/lunyu/zi-zhang/4.html)
- [19.5 日知其所亡](https://yikonglu.com/lunyu/zi-zhang/5.html)
- [19.6 博学而笃志](https://yikonglu.com/lunyu/zi-zhang/6.html)
- [19.7 百工居肆](https://yikonglu.com/lunyu/zi-zhang/7.html)
- [19.8 小人之过也必文](https://yikonglu.com/lunyu/zi-zhang/8.html)
- [19.9 君子有三变](https://yikonglu.com/lunyu/zi-zhang/9.html)
- [19.10 信而后劳其民](https://yikonglu.com/lunyu/zi-zhang/10.html)
- [19.11 大德不逾闲](https://yikonglu.com/lunyu/zi-zhang/11.html)
- [19.12 子夏之门人小子](https://yikonglu.com/lunyu/zi-zhang/12.html)
- [19.13 学而优则仕](https://yikonglu.com/lunyu/zi-zhang/13.html)
- [19.14 丧致乎哀而止](https://yikonglu.com/lunyu/zi-zhang/14.html)
- [19.15 吾友张也为难能也](https://yikonglu.com/lunyu/zi-zhang/15.html)
- [19.16 堂堂乎张也](https://yikonglu.com/lunyu/zi-zhang/16.html)
- [19.17 人未有自致者也](https://yikonglu.com/lunyu/zi-zhang/17.html)
- [19.18 孟庄子之孝](https://yikonglu.com/lunyu/zi-zhang/18.html)
- [19.19 孟氏使阳肤为士师](https://yikonglu.com/lunyu/zi-zhang/19.html)
- [19.20 纣之不善不如是之甚也](https://yikonglu.com/lunyu/zi-zhang/20.html)
- [19.21 君子之过也如日月之食](https://yikonglu.com/lunyu/zi-zhang/21.html)
- [19.22 仲尼焉学](https://yikonglu.com/lunyu/zi-zhang/22.html)
- [19.23 子贡贤于仲尼](https://yikonglu.com/lunyu/zi-zhang/23.html)
- [19.24 仲尼不可毁也](https://yikonglu.com/lunyu/zi-zhang/24.html)
- [19.25 子为恭也](https://yikonglu.com/lunyu/zi-zhang/25.html)

### 尧曰

- [20.1 尧曰咨尔舜](https://yikonglu.com/lunyu/yao-yue/1.html)
- [20.2 子张问从政](https://yikonglu.com/lunyu/yao-yue/2.html)
- [20.3 不知命无以为君子](https://yikonglu.com/lunyu/yao-yue/3.html)
