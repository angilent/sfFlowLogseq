- 不同形式的自动化 后台的和需要与用户交互的
	- Behind-the-Scenes Automation #card
		- Build  [[autolaunched flows]]  that specifies a record trigger in Flow Builder.
		- Build an Apex trigger with Apex code.
	- Guided Visual Experiences #card
		- [[screen flows]]
		- Lightning component
- 自动化解决方案的比较
	- 都是可以用户输入信息的方式
		- [[quick actions]]
			- 只能做简单数据保存，不能做更多的数据逻辑处理。
				- **can't** do Conditional logic and actions
		- [[Flow]]
		- [[Lightning component]]
			- 需要编码
-
- Salesforce 流程自动化的一些建议 #学习提示
	- To round out this business process, it would be good to provide some sort of confirmation that the business process has finished. If we note what the flow did in Chatter, more users can access that information than if we communicated through a closed channel like email. Let’s add two more requirements.
		- Confirm what happened by posting on Chatter. [[Post to Chatter]]
		- Confirm to the user that the business process is complete. [[Send Email]] [[Email Alert]]
- 计划做 Flow 时需注意  #重要 #学习提示
	- No matter which tool you use, it’s important to plan out your business process before you try to automate it.