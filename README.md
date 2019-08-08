
# 个人信息

- 手机：18701496016
- Email：luckywulin@gmail.com 
- 吴淋/男/1988 
- 本科/南京大学计算机科学与技术
- 工作年限：9年
- 期待职位：资深工程师，架构师（Php/Go/Python）

# 工作经历

## 北京链商电子商务有限公司 （ 2015年7月 ~ 至今）
 
### 链商优供 (B2B供应链平台) 
- 商城项目
   - B2B一站式网上订货平台，电商APP，包含用户，商品，运营管理，秒杀，订单，搜索，计算等模块服务。
- 客户关系管理项目
   - 实现管理销售地推团队，建立任务，指导拜访，奖励合算，数据决策等。
- 运输管理项目
   - 实现订单出库，系统集成，自动化排线，司机管理，运输可视化等。
- 其他项目
   - 司机管理系统，MIS管理系统，权限系统等。
- 主要职责&涉及技术难点
   - 百万级PV，月GMV5kw，行项目3kw+, 作为技术负责人, 0-1搭建php技术团队（10+人），负责系统架构设计，核心模块实现，难点攻坚，技术规划等。
   - 系统微服务化演变，通用服务中台化，分布式高可用高伸缩架构演进，独立系统10+，模块80+。
   - 通用ES检索服务引入，解决了数据分散，业务跨系统查询效率低，体验差，用户端查询慢等问题。
   - 分布式REDIS缓存对热点数据不友好，容易造成IO问题，通过PIPELINE & 本地化缓存改造将APP单台服务器QPS提升100%。
   - 秒杀系统优化，事务SQL简化，减少单事务锁定时间，库存持久化redis，通过异步队列入库保证最终一致性，秒杀单机QPS提升200%。
   - 数据流程长，系统交互多，分布式事务一致性问题通过TCC模式，幂等操作，定时补偿解决。
   - 使用技术：LNMP,Redis,ELasticSearch,Kafka,Python,Zookeeper等。

### 邻选
- 无人便利店
   - 创新型项目，新型业态，主要实现手机自由购，结算台自助购，人脸识别开门，门店进销存管理，门店监控防损等功能。
- 主要职责&涉及技术难点
   - 技术负责人，摸索门店管理，调研线下解决方案，主要难点在于多端（手机，平板，摄像头，门禁，电视，RF枪）联合部署，系统交互多，一站式云端管理和监控各种硬件，保证系统稳定运行。主要系统涉及UC服务，结算服务，人脸服务，门禁服务，进销存管理平台，硬件监控平台等。当前有十几家门店使用我们的云解决方案，在用户体验和服务支持上反馈良好。
   - 多端协议有HTTP，UDP，RTMP，TCP长连接自有协议，多类型硬件调试&部署上积累了一定的经验。
   - 多端中台化，服务化部署，系统独立，耦合性低，支持云方案的即插即拔。
   - 使用技术：LNMP,Redis,ELasticSearch,Java,Dubbo,Go等。

### 接龙圈
- 社区拼团工具
   - 有一定的社交属性，创新型项目，为团长解决群内接龙问题，提高拼团和履约效率。
- 主要职责&涉及技术难点
   - 技术负责人，项目包含接龙圈小程序，用户平台（团长PC版），商户端(APP)， MIS平台。需求迭代迅速，用户场景复杂（比如实时打印,分销模式等）, 在无外部资源投入情况下，通过技术数据抓取分析等手段，3个月做到月200wGMV增量，2wDAU。
   - 反编译微信APP，前期想通过模拟微信协议进行自动化接龙导入接龙圈，由于时间和成本问题未长期投入，但对微信协议mmtls，数据安全，防反编译有一定的了解。
   - 钱包模块设计实现，业务场景复杂，交易频繁，自动化对账，具有可回溯，防篡改等特性。
   - 技术和业务结合，不断分析和理解业务，通过技术的方式帮助业务，业务从0-1的自我成长。
   - 使用技术：LNMP,Redis,ELasticSearch,Java,Dubbo,Python等。
   
### 其他项目
- 物美招商平台
   - 包含商品证照管理，招标展示，在线竞标，合同管理，标后管理等。互联网颠覆原有招商模式，流程更透明，效率更高，效果更好，实现双赢，现在物美集团已全部互联网数字化招商。成交金额在百亿级别。
  
## 百度时代网络技术有限公司 国际化部门（ 2014年7月 ~ 2015年6月 ）

### DUNEWS 
- 主要负责服务端架构设计实现工作
   - 产品是一个新闻聚合类产品，有印尼、埃及等版本，主要包含数据实时抓取，信息提取，转码、个性化推荐，异地灾备等，这方面沉淀了一定的数据抓取聚合类产品的解决方案，国际化建设也积累了经验。
   - 关键词提取使用TF-IDF算法，分类使用SVM算法，通过协同过滤，历史查看加权，热门推荐等进行个性化推荐。
   - 异地数据同步通过MIMO队列进行，灾备采用一主多从，极端情况下进行国外流量迁移国内进行切换。
   - 使用技术：LNMP,Python,Mimo,Redis等

### 其他项目
- DUTUBE 接管
   - 视频类项目，视频抓取同步，分类、异步审核等流程，技术栈和DUNEWS基本一致。
   - 视频审核同步进行优化，之前是HTTP同步，由于网络抖动和带宽问题很容易超时断开，后续改用数据库同步。
  
## 创业阶段（ 2010年6月 ~ 2014年6月 ）

### 创业项目
- 技术合伙人身份持续创业，先后从事Web开发，FE，客户端开发，不断迭代自身所需技能，胜负欲强，不甘于平庸，勇于坚持和突破。
- 视频问答社交类项目，仿国外FormSpring,负责视频接入&管理，社交系统建设，天使轮100w。
- O2O教育在线交易平台，仿国外SkillShare,O2O流程建设，在线电商类交易系统研发，天使轮400w。
- 页游平台&手游项目，负责三方页游接入和管理（已实现盈利），即时对战类手游客服端研发（类似我叫MT），天使轮200w。
- 期间在宝钢、百度彩票有过短暂任职。

# 自我评价
- 扎实的计算机基础，良好的编码能力、逻辑能力，善于沟通，业务理解透彻，较强的自驱力，较好的领导力。
- 丰富的0-1研发经验，资源协调能力强，抗压能力好，年轻积极心态，能打硬仗，想打胜仗。
- 技术学习能力强，灵活运用，有热情，喜欢做有挑战的事情，工程上有一定的完美主义倾向。
