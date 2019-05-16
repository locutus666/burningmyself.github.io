# 需求又变了，要不要怼回去？

需求变更，让每一个技术人头疼的问题，应该以怎么样的态度来面对需求变更，是今天要讨论的话题。
 
为什么技术人讨厌需求变更？

一个典型的互联网产品项目的流程是：
1. 调研，产品经理设计需求；
2. 产品经理和技术进行需求评审；
3. 技术进行方案设计；
4. 技术进行编码实现；
5. 技术进行功能联调；
6. 技术进行提测，开始进行测试；
7. 若干轮测试与BUG修复，达到准上线状态；
8. 发布沙箱环境，进行最后一轮沙箱测试，达到准发布状态；
9. 将产品系统发布到线上；
 
不管使用敏捷看板，还是传统瀑布式项目管理方法，就单个项目来看，这流程是串行的。
画外音：如果够敏捷，产品、测试、研发等角色是流水线的。
 
可以看到，产品方案是在项目流程的最上游，产品方案确定后，技术同学会按照2-3-4...-7-8-9等步骤将产品发布上线。
 
试想，现在项目流程进行到了第x个步骤，产品经理突然说，产品方案要变化，这意味着什么呢？

这可能意味着一系列工作要推到重来：

* （9）线上发布白干了，产品要回滚；
* （8）沙箱发布白干了，沙箱要回滚；
* （6-7）若干轮测试白干了；
* （5）联调白干了；
* （4）代码白写了；
* （3）技术方案白设计了；
* （2）需求要重新评审；
* （3）技术方案重新设计；
* （4）代码重新开发
* （5）系统重新联调；
* （6-7）重新提测，迭代测试；
* （8）重新发布沙箱；
* （9）重新发布线上；
 
产品经理们，尝试着体会一下技术们的心里感受，就知道为什么技术这么痛恨“需求变更”了。
 
看到这里，一定有产品经理嘀咕“有这么夸张么，只变了10%的需求，需要全部重来么，技术同学也太矫情了”。有必要全部重来么？能不能省去联调、提测、测试的几个环节？

很多人把产品设计比喻成建设高楼大厦，产品经理是大厦设计师，技术是工程师。大厦快建成了，设计师突然说，图纸要修改10%，工程师要不要重来？还是说省去几个环节？
 
那么，需求变更了，技术同学要不要怼回去？
 
在一家互联网公司，产品技术是很难分割的一个整体，他们虽有分工，各有侧重，但归根结底其最终目标是一致的：为达成公司业务目标共同努力。
 
为了这个共同的业务目标，产品经理的工作思路与逻辑应该是：
“在资源有限的情况下，做什么产品、工具、后台、运营活动，对业务目标的达成最有帮助，就最先做什么”。
 
然而，有些产品经理的工作思路与逻辑却是：
“想一出是一出，拍脑袋决策，凭直觉决策”：
登录这里改一下，能够提高转化率
详情页这里改一下，能够提高留存率
过节发个红包，能够拉新，能够提高活跃度
 
无穷多的需求上线后，无非是这几个结果：
产品成功了，哇，天才的构想
产品效果不好，嘘，技术们在忙着做后面的需求，也不会有人注意到
有人想起来要复盘，可以用“互联网产品，还不允许试错啦”搪塞过去
 
在“人人都是产品经理”的时代，有多少没有调研，没有分析，凭借直觉的产品经理，拍脑袋出来的需求，让一大帮技术专家为之操劳花好几月去实现。
画外音：这句话是对产品经理的侮辱，还是？产品经理的门槛很高，专业要求很高的。
 
不仅如此，项目半途，有多少需求是因为产品经理“之前没有想清楚”变更了需求，让“几百人日”的研发投入付之东流。
 
即使有些非常资深，非常厉害的产品经理，但人数一多，每个产品经理都想要业绩，在研发资源有限的情况下，为了争抢资源：
我这提了N个需求，总得排期一个吧
竞品有了这个功能，我们也必须有一个
老板说了，这个功能必须在节前上线
画外音：

（1）既然负责这个产品模块，必须提对应的需求呀；

（2）劣币驱逐良币；

一将无能，累死三军。
 
所以，这不是一个简单的“需求变更，要不要怼回去”的问题，甚至不是一个“需求提过来，要不要承接”的问题：
产品技术作为一个整体，共同为公司的业务目标服务
画外音：有些公司甚至有“技术不允许拒绝需求，不允许拒绝需求变更”的畸形文化。
产品作为技术侧的上游，需要系统性思考问题，而不是拍脑袋提需求
技术侧作为产品侧的下游，不能只是一味的接需求，要帮助他们想清楚，少为业务埋坑
 
技术侧能够如何帮助产品，让他们把需求提得更靠谱呢？
至少，“过节发个红包”这类需求评审时，多问这么一些问题：
哪些产品指标，和业务的最终目标相关
画外音，假设有：新客，转化，留存，下单等。
这些产品指标中，哪些是主要矛盾
画外音：假设是新客。
对于这个产品指标，做哪些事情可以改善
画外音：假设有12345五件事。
对于这五件事，哪件事投入产出比最高
画外音：假设真的是“过节发个红包”这个活动。
对于这个活动，活动方案有几种优缺点是什么，为什么最终选择了这一种，活动逻辑是怎么样的，活动效果有没有预估，有没有埋点，活动结果怎么评估...
画外音：啥？活动只有一种方案？

事先问的问题越多，讨论得越充分，需求就越靠谱，需求变更的几率就越小，埋坑的几率就越小。
 
# 总结：
产品技术作为一个整体，共同为公司的业务目标服务
产品经理要系统性思考问题
技术要帮助产品经理系统性思考问题
 
有技术的同学说，我天天在做需求，没时间想这些问题，没时间和产品经理讨论这些问题，怎么办？
你MB，你活该天天加班。