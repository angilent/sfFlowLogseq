tags:: [[flowUserCase]]

- 目的：
	- 能系统自动做的，就不要让用户手工做。
- 好处：
	- 节省时间
	- 规范流程
	- 提高数据质量
-
- 使用场景和用途需要分开讲吗？还是一回事？ #我的疑问
-
- You can use an autolaunched flow to create a flow that auto-assigns Volocity licenses to site users. #flowUserCase
	- [[autolaunched flows]]
- a high-touch call center with specific scripts that your agents need to follow based on a customer’s account data. #flowUserCase
	- 这里的 scripts 是指负责收集数据的脚本
- a practice in place where your salespeople should always, always, create a work order after a deal closes. #flowUserCase
-
-
- 使用 [[Decision]] 的场景
	- To give customers a return shipping address or instructions on how to resolve the problem when an item is determined to be faulty.
	- To offer a customer a loan based on the results of a credit scoring formula.
	- To inform sales leaders when an opportunity’s stage is changed to Closed Won.
		- Configure your flow so that it does different things based on what a user selects for a Picklist screen component. To do so, add a decision after the screen to create the branches of the flow based on the choices available in the picklist. Then you can represent each choice in your decision and connect it to a branch of your flow.
-