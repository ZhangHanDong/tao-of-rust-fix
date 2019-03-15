# Rust编程之道•求真集

本项目是对《Rust编程之道》勘误的一次重新梳理。

### 关于每章副标题名言的说明：

有读者比较好奇，这些名言警句都出自哪里？ 借这个机会我梳理一下：

**第一章：不谋全局者，不足谋一域。出自：陈澹然\[清\]《寤言二迁都建藩议》**

第一章是全书的起始，我希望读者可以从整体上对Rust有一个宏观的认识，然后再开始学习后面的内容。

**第二章： 好读书，不求甚解；每有会意，便欣然忘食。  出自： 晋·陶渊明《五柳先生传》**

第二章是对Rust语法的精要罗列，因为在学习任何一门之前，至少要对它的语法有一个比较基本的认识，然后在这个基础上，去掌握它。语法上其实和其他语言的也没有多少差别。但不同的是，第二章还贯穿着一根主线，那就是表达式，或者说，语法中的共性，一致性。用这个副标题，就是想让大家在看这一章的时候，没必要去抠细节，因为很多内容后面还会讲。应该抓住每一章的重点。这也迎合了陶渊明先生的这句名言。

**第三章：  本性决定行为,本性取决于行为。 出自：罗伯特·穆齐尔 《没有个性的人》**

第三章讲的是类型系统。Rust是类型安全的语言，一切皆类型。而trait则是Rust一切抽象的基础。类型，比如数字、字符串等等类型，各有各的本性。而trait，则是对这些类型的行为的抽象。 什么样的类型（本性），决定了它应该实现什么样的trait（行为）。反过来，什么样的trait（行为），也能决定它的类型（本性），比如trait对象。

**第四章： 清空你的杯子，方能再行注满，空无以求全。出自： 李小龙**

第四章讲的是内存管理。我为什么会想到李小龙的这句话呢？主要有三点原因：

1. 李小龙也算是我的偶像了，他创立的截拳道，是吸取了众派所长，然后形成了一个精简的武学模型。而Rust语言，在这一点上也比较类似，集合了各家语言之所长，然后融合到一个精简的模型中。
2. Rust的内存管理，独树一帜。没有走传统的GC路线，也没有走C和Cpp的自由的手工管理。而是借助了所有权机制，这一点，很像以空杯心态来重新审视内存安全的问题。
3. 对于我们学习者而言，也需要有这种空杯心态，来面对新的技术。

**第五章：  律者，所以定分止争也。出自：《管子·七臣七主》**

第五章，讲所有权系统。所有权系统，就是Rust语言中的法律，而编译器，就是所有权「法律」的执行者。作为Rust语言使用者，应该牢记这一点，你应该做一个「懂法」的人，如果「不懂法」，那只会被编译器「就地正法」。

**第六章：语言影响或决定人类的思维方式。 出自： TED演讲：**[**《语言如何塑造我们的思维方式》**](https://www.ted.com/talks/lera_boroditsky_how_language_shapes_the_way_we_think/transcript?language=zh-cn)

第六章，讲函数、闭包和迭代器。这一章涉及了Rust中对函数式编程范式的支持，因为Rust是一个混合范式语言，而且我观察到社区里，来自于其他不同语言社区的人，对Rust的理解也是不同。来自Haskell的人，想方设法地要用Rust实现各种高阶魔法。而来自C语言社区，则对Rust提供的在其他高级语言中最常见的基本抽象表达能力赞叹不绝。这是为什么呢？ 这就是语言对思维方式的影响。而编程语言范式，也是因为不同思维的语言作者，而创造出的不同范式。

而Rust语言也在改变我的思维，在我刚用Rust的一段时间里，我还纠结OOP和函数式语言范式，但是用习惯Rust以后，我发现自己已经有很长时间没有关注语言编程范式了。

**第七章：形每万变，神唯守一。出自： 《斗拱》维基百科**

第七章讲结构体、枚举相关的内容。结构体和枚举，是Rust编程的基础，也是Rust代码的基本组织单元。这不禁让我想到了中国古代的「斗拱」结构。斗拱属于榫卯结构的一种，其上承屋顶，下接立柱，在中国古建筑中扮演的是顶天立地 的角色。而斗拱仅仅由5 个简单的部件组成，利用独一无二的榫卯结构，可以拼接出种类繁 多且左右对称的各种样式，无不令人称赞。这正应了“形每万变，神唯守一”的规律。

**第八章：阵而后战，兵法之常，运用之妙，存乎一心。  出自：《宋史·岳飞传》**

第八章讲字符串和集合类型。这基本是任何语言里最常用的数据结构了。数据结构在我的心里，就像是一种「阵法」。编程，其实就是解决问题，算法是解决问题的思路，数据结构是解决问题的

第九章：每个人都有错，但只有愚者才会执迷不悟。出自：西塞罗

第十章：良好的秩序是一切美好事物的基础。  出自：埃德蒙·伯克

第十一章： 万物并育而不相害，道并行而不相悖。 出自：《中庸》

第十二章：道生一，一生二，二生三，三生万物。出自： 《道德经》

第十三章：混沌涌现秩序，光明源自黑暗。出自： 《魔兽世界》

