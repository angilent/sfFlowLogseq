title:: LIVE: Salesforce Flow Tips

- https://www.youtube.com/watch?v=2sOnL4M-lTk
- 为什么用flow
	- process builder 和 workflow rule 退休了
	- screen flow 很方便支持需要用表单收集数据的流程
- 学习flow 需要先有admin 基础，了解基本的数据模型。
	- whatID
		- non-person ID
	- whoID
		- personID people ID
		- polymorphic
	- whatID 和 whoID 在activity 里。
	- 可以在schema builder 去查看相关对象的关系
	- big five
		- lead contact account opportunity case
- 什么是变量？ placeholder
	- 能代表数字，字符，对象
- 什么是集合 collection
	- 超市结账，一系列产品在一个结账流程。
- program concept
	-
- 还有哪些问题？
	-
- 可以用/slack 去问问题，公开场合
	- share the question
- 传递 recordId can be record ，就可以直接拿对象的属性值了。
- one flow per object
-
- schedule tigger flow
- record  trigger schedule path: delay
-
- 可以设置执行优先级
-
- flow trigger explorer
- flow orchestrate
	- 可以编排salesforce 系统外的流程？
	- 可以替代审批流程？
- new collection sort element
	- filter collection element
		- avoid loop in loop
	- choice element
	- formula 可以帮助你做计算
	- nebula logger
		- https://github.com/jongpie/NebulaLogger
- 为什么复杂的场景不适合flow
	- 同步事务处理中100个gets 限制
	- 循环中 2000个element的限制
		- Spring ’21, there are currently 2,000 element executions allowed per flow interview. Consider a scenario where you are looping more than 1,500 contacts.
	-