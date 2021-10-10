# 面向对象

我们这一次将要直击每一个学习到「面向对象(Object-Oriented)」这个概念的同学都会进行思考的一个问题

`面向对象(Object-Oriented)究竟是什么？`

> 首先Class这个概念，虽然在大多数面向对象的语言中与Object-Oriented有着紧密的联系，但是它并不是Object-Oriented的本质的一部分。理由也是十分的简单，在某些语言中你可以不Class就可以构造出一个Object、例如JavaScript，我们可以直接对着一个函数new一下创建出一个Object。

但是在大部分的教材之后都有一句广为流传的名言：“面向对象的本质是封装，继承，多态”。由于我不是很能确定大家能否一下子理解这句话，所以建议大家可以参考一下「Object-Oriented」这个术语的创造者也是图灵奖的获得者[Alan key](https://en.wikipedia.org/wiki/Alan_Kay),他本人对于OOP的理解；从他的描述里面我们可以非常直观的发现他对于“messaging”也就是“发送和处理消息”的多次强调，按照他的理解“messaging”才是Object-Oriented的首要特征。

![Alan key](./images/Alan key.jpg)

> 举例：一个世界在他的眼里就是一堆独立运作的节点在互相的发送信息和处理消息，比如A节点给B节点发送消息，翻译成代码大概就是`A这个Object调用了B的某一个Method`

如果大家只知道“封装，继承，多态”这一种说法，恐怕各位同学很难从这中间推理出“messaging”这个本质，同一条消息可以被多个不同类型的节点处理，但是这些节点对于同一条消息的处理方式和结果可能大为不同，这就有点「多态」的味道了；节点A看不到节点B的内部状态，更没有办法直接更改节点B的内部状态，唯一能做的就是给B节点发送消息，这就有点「封装」的味道了；我们从[Alan key](https://en.wikipedia.org/wiki/Alan_Kay)的描述中看不到Class这个字眼，这就表明了Class并不是Object-Oriented的本质，我们也能难看到“继承”这个词，所以“继承”是Object-Oriented的本质之一，还是一种实现的细节呢？

> 这个就是单纯留给大家思考的一部分，可以把自己的想法提出issue和讨论！


