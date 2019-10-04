# DSA - 
### `名詞解釋`

Week1(9/09-9/13)
======

Week2(9/16-9/20)-Linked List
======
##### Linked-list是由一連串的節點（Node）所構成，每個節點指向下一個節點，而最後一個節點則指向Null（在python裡面是None）。
因此，每個節點本身應該要有兩種屬性（attribute），一個是本身帶有的值或者是資料，另一個則是指向下一個節點的指標（pointer）。
我想Linked-list與一般陣列（array）比起來最大的不同點在於：
陣列使用一連串的記憶體位置，因此可以透過array[index]直接存取資料，但是相對的，若要在陣列中加入或是刪除元素，則需要大量的資料搬移。（python中的list雖然用法跟陣列很類似，並卻不是這樣子的實作方式。而像是在C語言中，陣列所記錄的其實是第一個元素的地址，而index就是相對於第一個元素的偏移量了，所以才是從0開始。）

Week3(9/23-9/27)-Stack & Queue
======
##### 堆疊(Stack)
加入(push)與刪除(pop)於同一端
</n>具有後進先出(LIFO, Last-in-First-out)或先進後出
(FILO, First-in-Last-out)性質的有序串列
例子：疊盤子、發牌、走迷宮

##### 佇列(Queue)
加入(enqueue)與刪除(dequeue)於不同端(front & rear)
先進先出(FIFO, First-in-First-out)
例子：排隊買票、坐公車

Week4(9/30-10/04)-Set & Insertion Sort
======

