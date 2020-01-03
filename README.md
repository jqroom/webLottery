# webLottery
网页抽奖程序，示例运行：[https://jqroom.github.io/webLottery/](https://jqroom.github.io/webLottery/)

### 新增本地存储配置＋全屏
新的线上地址：[https://lloydzhou.github.io/webLottery/](https://lloydzhou.github.io/webLottery/)

### 抽奖软件
> 在浏览器上运行的抽奖程序

### 操作方便
> 抽奖过程全键盘操作, 只需要按回车(Enter)键即可, 类似播放PPT幻灯片, 非常简单.

### 配置灵活
> 可配置的选项有: 活动标题, 奖项, 候选人, 摇奖时的跳转速度, 背景图片. 其中, 每一个奖项, 可以一次开完, 也可以一次只开一部分. 例如, 三等奖一共6个, 每次只开2个, 需要开3次才能开完三等奖, 增加娱乐性. 图片可以更换为带自己公司Logo的图片, 以便适应当前节日, 所以, 本抽奖程序任何节日的任何类似的抽奖节目都可使用.

### 抽奖流程
- 等待开始
- 开场(open): 奖项介绍
- 奖项循环: 如果多于一个奖项, 则循环
- 奖项开场(step_open)
- 摇奖循环: 如果不是一次开完一个奖项, 则循环
- 摇奖开始(rotate_start)
- 摇奖结束(rotate_stop)
- 奖项结束(step_close): 单项中奖名单
- 闭场(close)
