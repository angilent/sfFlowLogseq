- 定义 #card
  card-last-interval:: 4
  card-repeats:: 1
  card-ease-factor:: 2.36
  card-next-schedule:: 2022-03-06T16:07:15.436Z
  card-last-reviewed:: 2022-03-02T16:07:15.436Z
  card-last-score:: 3
	- 每个元素都代表一个 Flow 可以执行的行动（Action）。
	- Each element represents an action that the flow can execute.
	-
- Flow element 包括：
	- [[Apex Action]]
	- [[Assignment]]
	- [[Core Action]]
	- [[Create Records]]
	- [[Get Records]]
	- [[Decision]]
	- [[Delete Records]]
	- [[Email Alert]]
	- [[Loop]]
	- [[Pause]]
	- [[Screen]]
	- [[Start]]
	- [[Subflow]]
	- [[Update Records]]
- 如果按照不同的类型分类如何分呢？ #学习提示
	- 记录数据操作 Record 相关（[[CRUD]] 操作）
		- [[Create Records]] [[Get Records]] [[Update Records]] [[Delete Records]]
	- 流程逻辑相关
		- [[Start]] [[Pause]] [[Decision]] [[Loop]]
	- 变量相关
		- [[Assignment]]
	- 其他方法调用相关
		- [[Apex Action]] [[Screen]] [[Subflow]] [[Core Action]]
- 在 Trailhead 的 Flow Builder 介绍章节里提到可以按照 screens, logic, and actions 三个类别进行分类 [hyref](https://hyp.is/7VU-_Jq3EeyYs-_LZUSMqQ/trailhead.salesforce.com/en/content/learn/modules/flow-basics/meet-flow-builder)
	- Screens
		- Display data to your users or build a form to collect information from them with Screen elements. [[Screen]]
	- Logic
		- [[Start]] [[Pause]] [[Decision]] [[Loop]] [[Assignment]]
		- Once you collect the data you need, what do you want to do with it? With logic elements, evaluate that data and manipulate it according to your business requirements. Create branches, update data, loop over sets of data, or pause until a specified time.
		- Logic operates only in the flow. If you use logic elements to evaluate or manipulate information in your flow, the resulting data can’t be accessed after the flow finishes. Use an action to store that data somewhere outside of the flow.
		- 在 Flow 的上下文中操作数据
			- 上下文有点像修理工的背包，在上到电线杆上修例过程中可以随事取得。而另外一些可以需要从其他地方取来，或者其他人送过来。 #讲课素材
	- Actions
		- Actions instruct the flow to do something outside of itself, such as in the Salesforce database or in an external system.
		-
	-
-
- ---
- 为什么叫 flow element 而不叫flow action呢？ #我的疑问
- [[flowElement]]
-