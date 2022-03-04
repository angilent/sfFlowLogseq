- 定义 #card
  card-last-interval:: 4
  card-repeats:: 1
  card-ease-factor:: 2.36
  card-next-schedule:: 2022-03-06T16:07:09.932Z
  card-last-reviewed:: 2022-03-02T16:07:09.932Z
  card-last-score:: 3
	- Connectors determine the available paths that a flow can take at run time.On the canvas in Flow Builder, a connector looks like an arrow that points from one element to another.
	- 连接器决定了一个流在运行时可以采取的可用路径。在Flow Builder的画布上，连接器看起来像一个箭头，从一个元素指向另一个。
- 种类：
	- Unlabeled
		- Identifies which element to execute next.
		- ![image.png](../assets/image_1646116650106_0.png)
	- Decision outcome
		- Identifies which element to execute when the criteria of a Decision outcome are met.
		- ![image.png](../assets/image_1646116676603_0.png)
	- Pause configuration label
		- Identifies which element to execute when an event that’s defined in a Pause element occurs.
		- ![image.png](../assets/image_1646116736040_0.png)
	- Fault
		- Identifies which element to execute when the previous element results in an error.
		- ![image.png](../assets/image_1646117048321_0.png)
	- For each item
		- Identifies the first element to execute for each iteration of a Loop element.
		- ![image.png](../assets/image_1646117055153_0.png)
	- After last item
		- Identifies which element to execute after a Loop element finishes iterating through a collection.
		- ![image.png](../assets/image_1646117062012_0.png)
	- Go To (Beta)
		- Identifies which element to go to and execute next.
		- ![image.png](../assets/image_1646117069113_0.png)
	-
-
- ----
- [[canvas]] [[Flow Builder]]