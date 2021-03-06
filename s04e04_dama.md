# s04e04

- 小组合作,
- 结合你自己熟悉的专属领域,克服知识的诅咒,面向其他组的成员,
- 用500字,介绍一个知识或技能. 

## 和合技之 BLAME 界面

在小组基于 github 进行 和合 协作时, 
有个基础问题:

> 如何去对应版本评论最新修订?

这个问题的来源是这样的:

假定大家都进入了 github;
然后, 通过决议,选定了一位同学的稿件作为小组作品原稿;

那么, 共同和合推进文字快速演化的流程之一是:

    观棋但语
    不动手

也就是说:

- 大家在相关界面中针对文稿的具体一行文字进行讨论,给出改进意见
    + 然后, 主笔定期, 或是快速根据意见修改对应行
    + 提交新版本文稿到 github 中
- 接着,大家根据新的版本变化继续讨论

问题来了...

- github 中, 可以进行逐行和合讨论的界面是 commit-log 界面
- 也就是每次对应文件变更记录, 即 commit 指令提交的内容
- 而这个界面, 只显示对应版本中, 变化的部分
- 可文章, 总是要整体来看, 才有文章的感觉, 才能给出中肯的建议哪

所以, 推荐大家使用 Blame ~ 追责 界面, 进入很简单:

- 进入小组协同仓库的 Code 
- 点击我们要点评的文件
- 然后, 就能在右上角看到 `[Raw|Blame|History]` 三个按钮
- 进入 Blame 将看到类似界面


![blame](http://ydlj.zoomquiet.top/ipic/2020-02-28-ScreenShot%202020-02-28%2022.54.13.jpg)


这里:

- 右面是就文件最新版本的所有内容
- 左面, 则是每一行相关修改的对应版本情况
- 那么, 刚刚的问题就好解决了:
    + 我们就在这儿整体查阅文章
    + 哪一行不满意,对应点击左侧相关修订版本链接
    + 就进入熟悉的 commit-log 界面, 可以逐行评注了


以上.


