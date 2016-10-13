> 翻译于[Effective Code Reviews](http://codeahoy.com/2016/04/03/effective-code-reviews/)，本文对代码审查会遇到的问题（变成审查者炫技，开发者依赖审查找出代码问题对自己的代码不管不顾，总是等代码ready后才审查等），从管理者，开发者和审查者都提出了不少实用有效的建议（如建立合适的团队文化，讲点人情味，对事不对人，谦虚点~）

代码审查就是开发者写的代码被其他开发者来审视看是否有缺陷和可提升点的过程。换句话说，开发者先独立完成他们的编码工作，然后召集一次代码审查。

代码审查是一种被证明可以推升软件质量的编程方法。在Google，所有的代码都需要被同事进行审查才能入库。从《代码大全2》中列举两个例子：

- IBM的Orbit项目有近50w行代码量，通过使用11种级别的审查，从而这个项目比预期更早发布，只有预期1%的代码错误bug数量。
- 对AT&T的一个拥有多达200人的组织调研发现，当引入代码审查后，他们工作效率提升了14%，软件的缺陷数量降低了近90%。

不过，现在还是有很多团队在代码审查上做的并不好甚至还没有全完意识到它的好处。在这样『功能紊乱』的组织或团队中，很快会所有参与其中的人感到痛苦难过。

- 代码审查常常会变为审查人通过指出其他同事的代码『错误』的炫技平台。而实际这仅仅是他个人很牵强的观点而已
- 开发者通常对代码审查不够积极总是说要等待代码最终ready后才进行。这是有些好处，不过也会错过代码审核的最佳时间点
- 开发者对要被审核代码的不管不顾，等着其他人来帮他找到错误

在这篇文章中，我们聊聊组织团队通过实施哪些规则和方法，让每个参与代码审查的人都能感到满意和愉快。

### 给管理者：建立正确的文化

### 给所有人：人情味

### 给审查者：谦虚点

### 给开发者：对事不对人

### 总结

同事间的代码审查是相互交流沟通的过程，这其中的低效也是源自于社交层面的。不过不少管理者花了不少时间去考虑工具是否好用，是否酷炫。工具当然会有提升，不过仅仅通过它不会带来最终的好结果。从建立正确的文化开始，然后剩下的人与人之间配合和沟通~


PS：经过大半年的野蛮发展，我们交付了不错的软件应用给业务部门，随着团队的增大和后续人员的加入，新的功能点也需要在原有项目上迭代，我们广发团队们也开始了陆陆续续的Code Review的进展工作，你有什么好建议？
