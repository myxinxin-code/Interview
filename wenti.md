###八股文准备
####c++
完美转发与移动构造：深入理解c++11特性书
（移动构造，引用折叠：将复杂的未知表达式折叠为已知的的简单表达式）
[move vs forward](https://www.jianshu.com/p/b90d1091a4ff)
malloc的原理， brk系统调用， mmap系统调用
c++内存管理
如何判断内存泄露？
new和malloc区别
reactor模型
epoll,select原理，区别，限制，性能
STL内存优化
c++11的特性
c++11可变参数模板
lambda
引用传递与指针传递的区别
形参与实参的区别
引用与指针的区别
static的用法及作用
static变量初始化
const
const与指针的用法
mutable
extern用法
深拷贝与浅拷贝
c++模板[link](https://www.runoob.com/w3cnote/c-templates-detail.html)
[底层实现](https://blog.csdn.net/baidu_28312631/article/details/47975385)
c结构体与c++结构体区别
c++结构体与类[link](https://www.cnblogs.com/xumaomao/articles/11042772.html)
虚函数可以为inline吗
[answer](https://blog.csdn.net/flydreamforever/article/details/61429140)
[answer1](https://blog.csdn.net/shltsh/article/details/45999947)
类成员的初始化方式、构造函数的执行顺序、为什么成员初始化列表会更快一点？
虚拟基类与虚继承？（看一哈）
构造函数为什么不能为虚函数？析构函数为什么要虚函数？
构造函数和析构函数可以调用虚函数吗，为什么
构造函数的执行顺序？析构函数的执行顺序？构造函数内部干了啥？拷贝构造干了啥？
虚析构函数的作用，父类的析构函数是否要设置为虚函数？
C语言模拟c++继承和多态
继承机制中对象之间如何转换？指针和引用之间如何转换？
组合与继承优缺点？
左值右值
移动构造函数
C 语言的编译链接过程？
vector 与 list 的区别与应用？怎么找某 vector 或者 list 的倒数第二个元素
STL vector 的实现，删除其中的元素，迭代器如何变化？为什么是两倍扩容？释放空间？
容器内部删除一个元素
map、set 是怎么实现的，红黑树是怎么能够同时实现这两种容器？ 为什么使用红黑树？
STL 中 unordered_map(hash_map) 和 map 的 区 别[here](https://blog.csdn.net/qq_21997625/article/details/84672775) ，hash_map 如何解决冲突以及扩容（hash_map被unordered_map替代了啊）
unordered_map如何插入自定义对象呢（[here](https://www.cnblogs.com/jasmineTang/p/14369296.html) [and](https://www.cnblogs.com/crazy-machine/articles/6639347.html)）
STL 中的 allocator,deallocator
.函数指针？
说说你对 c 和 c++的看法，c 和 c++的区别？
.c/c++的内存分配，详细说一下栈、堆、静态存储区？
堆与栈的区别？
野指针是什么？如何检测内存泄漏？
悬空指针和野指针有什么区别？
new 和 malloc 的区别？
delete p;与 delete[]p，allocator
malloc 与 free 的实现原理？
动态内存管理[weikan](http://data.biancheng.net/view/52.html)
使用智能指针管理内存资源，RAII
[=delete](https://blog.csdn.net/qq_29996285/article/details/84851745)
为什么内存对齐
[noexcept](https://www.cnblogs.com/sword03/p/10020344.html)
define、const、typedef、inline 使用方法？
define 和别名 typedef 的区别
define 与 inline 的区别
C++中类成员的访问权限和继承权限问题。
C++类型转换有四种
[volatile详细看看哈](https://blog.csdn.net/weixin_44363885/article/details/92838607)
何时需要成员初始化列表？过程是什么？
哪些函数不能是虚函数
请你来说一下 C++里是怎么定义常量的？常量存放在内存的哪个位置？
请你来说一下 map 和 set 有什么区别，分别又是怎么实现的？
请你来说一说 STL 迭代器删除元素
请你来说一下 STL 中迭代器的作用，有指针为何还要迭代器
请你回答一下什么是右值引用，跟左值又有什么区别？
请你来说一下 reactor 模型组成
请你说说 select，epoll 的区别，原理，性能，限制都说一说
子类的虚函数内部可以调用父类对应的虚函数吗
DDS，SOA？
c++ stl容器是线程安全的吗
c如何实现继承与成员函数
c如何实现类
内存调优技术？
网络编程TCP流程
设计模式？
[协程](https://www.jianshu.com/p/6dde7f92951e)
[动态多态](https://mp.weixin.qq.com/s?__biz=MzkyMjIxMzIxNA==&mid=2247485303&idx=1&sn=985f6128d6910a3f7376f10b61ce03f7&chksm=c1f68946f6810050e21b70ff44e7f302f355e63213a5139aaaf9b482ce44a13b9c98efcb68e4&token=760577494&lang=zh_CN#rd)

override:
	- 当子类没有重写父类虚函数，而是重新定义了同名的函数，互不影响，但没有动态多态性。
	- 当子类重写后，依然可以在重写的虚函数内调用父类的虚函数，base::func
空类大小[1](https://blog.csdn.net/lihao21/article/details/47973609)
- 空类（不含虚函数）大小为1，包含虚函数x64平台8B



####操作系统
[read...](https://www.ofweek.com/ai/2021-04/ART-201715-11000-30495589_2.html)
进程与线程概念及区别
进程与线程的同步
进程通信
线程通信
linux虚拟地址空间原理，优点，缺点
操作系统的内存结构（BSS 段属于静态分配，程序结束后静态变量资源由系统自动释放）
缺页中断
fork与vfork区别
页表寻址
线程需要保存哪些上下文信息
线程的同步方式包括系统调用
进程切换需要分两步：切换页目录、刷新 TLB 以使用 新的地址空间；切换内核栈和硬件上下文（寄存器）；而同一进程的线程间逻辑地址空间是一样 的，不需要切换页目录、刷新 TLB。
缺页置换算法
死锁发生的条件以及如何解决死锁
地址转换（段式与页式）
段页式的区别
操作系统中结构体对齐，字节对齐
[缓存颠簸](https://blog.csdn.net/dd2016124/article/details/113868151?utm_medium=distribute.pc_relevant_download.none-task-blog-2~default~BlogCommendFromBaidu~default-3.test_version_3&depth_1-utm_source=distribute.pc_relevant_download.none-task-blog-2~default~BlogCommendFromBaidu~default-3.test_version_3)
[缓存抖动](https://baike.baidu.com/item/%E7%BC%93%E5%AD%98%E6%8A%96%E5%8A%A8/4621847)
[GDT-LDT](https://blog.csdn.net/billpig/article/details/5833980)
缓存抖动是由于正在进行的计算无法读取缓存系统数据导致失败的现象
[参考]((5条消息) 缓存穿透、缓存并发、缓存雪崩、缓存抖动、热点缓存、缓存双写一致性等问题_Saintyyu的博客-CSDN博客_缓存抖动)
c++锁
进程状态
c++虚函数与多态
孤儿进程与僵尸进程？
进程、线程和协程的区别和联系---[协程](https://www.jianshu.com/p/6dde7f92951e)
一个进程可以创建多少线程，和什么有关？
外中断和异常有什么区别？
进程线程模型你知道多少？
wait与waitpid函数了解一下[here](https://blog.csdn.net/yiyi__baby/article/details/45539993),exit(),_exit(),abort(),
[进程关系](https://www.cnblogs.com/tianzeng/p/11059284.html)
[进程表](https://zhuanlan.zhihu.com/p/56251739)
进程调度算法你了解多少？
Linux下进程间通信方式？
Linux下同步机制？
如果系统中具有快表后，那么地址的转换过程变成什么样了？
快表换入换出？
内存交换和覆盖有什么区别？[ans](https://blog.csdn.net/weixin_42229896/article/details/80701209)
[exit()与_exit()](https://blog.csdn.net/weixin_42904113/article/details/99216237?utm_medium=distribute.pc_relevant.none-task-blog-2~default~baidujs_baidulandingword~default-5.base&spm=1001.2101.3001.4242) [ans](https://blog.csdn.net/manonghouyiming/article/details/79880624?utm_medium=distribute.pc_relevant.none-task-blog-2~default~baidujs_title~default-0.base&spm=1001.2101.3001.4242)
动态分区分配算法有哪几种？可以分别说说吗？
- 首次适应算法


[分区](https://blog.csdn.net/weixin_34295316/article/details/89861547)
[2](https://www.eefocus.com/embedded/434688)
虚拟技术你了解吗？
进程状态的切换你知道多少？
一个程序从开始运行到结束的完整过程，你能说出来多少？
静态链接和动态链接
通过例子讲解逻辑地址转换为物理地址的基本过程
分段与分页区别？（查一下）
进程同步的四种方法？[here](https://www.cnblogs.com/Allen-rg/p/7172958.html)
线程同步方式[here](https://blog.csdn.net/wuhuagu_wuhuaguo/article/details/78591330)
操作系统在对内存进行管理的时候需要做些什么?
进程通信方法（Linux和windows下），线程通信方法（Linux和
windows下）
[互斥、同步、通信](https://blog.csdn.net/weixin_41413441/article/details/80548683)
虚拟内存的目的是什么？
说一下你理解中的内存？他有什么作用呢？
操作系统经典问题之哲学家进餐问题
操作系统经典问题之读者-写者问题
介绍一下几种典型的锁？
怎么回收线程？有哪几种方法？
内存的覆盖是什么？有什么特点？
内存交换是什么？有什么特点？
什么时候会进行内存的交换？
终端退出，终端运行的进程会怎样
[三个重要信号](https://blog.csdn.net/z_ryan/article/details/80952498)
什么是快表，你知道多少关于快表的知识？
地址变换中，有快表和没快表，有什么区别？
守护进程、僵尸进程和孤儿进程
程序从堆中动态分配内存时，虚拟内存上怎么操作的
常见的几种磁盘调度算法
- 先来先服务
- 最短寻道时间优先
- 电梯扫描算法

抖动你知道是什么吗？它也叫颠簸现象
从堆和栈上建立对象哪个快？（考察堆和栈的分配效率比较）
常见内存分配方式有哪些？
内存交换中，被换出的进程保存在哪里？
在发生内存交换时，有些进程是被优先考虑的？你可以说一说吗？
原子操作的是如何实现的
系统并发和并行，分得清吗？
可能是最全的页面置换算法总结了
- 最佳置换法
- LFU（最不经常访问淘汰算法）
- FIFO（先进先出淘汰算法）
- LRU-K（LRU-2、LRU-3）最久未使用 K 次淘汰算法。
- LRU（最近最少使用替换算法）
- 2Q

共享是什么？
死锁
- 概念：死锁是指两个（多个）线程相互等待对方数据的过程，死锁的产生会导致程序卡死，不解锁程序将永远
无法进行下去。
- 四个必要条件
- 处理方法：
	- 鸵鸟策略：因为解决死锁问题的代价很高，因此鸵鸟策略这种不采取任务措施的方案会获得更高的性能。当发生死锁时不会对用户造成多大影响，或发生死锁的概率很低，可以采用鸵鸟策略。
	- 死锁检测与死锁恢复
		- 死锁恢复：利用抢占恢复，利用回滚恢复，通过杀死进程恢复
	- 死锁预防
		- 资源一次性分配，从而剥夺请求和保持条件
		- 可剥夺资源：即当进程新的资源未得到满足时，释放已占有的资源，从而破坏不可剥夺的条件
		- 资源有序分配法：系统给每类资源赋予一个序号，每个进程按编号递增的请求资源，释放则相反，从而破坏环路等待的条件
	- 死锁避免
		- 安全状态：如果没有死锁发生，并且即使所有进程突然请求对资源的最大需求，也仍然存在某种调度次序能够使得每一个进程运行完毕，则称该状态是安全的。

为什么分段式存储管理有外部碎片而无内部碎片？为什么固定分区分
配有内部碎片而不会有外部碎片？
> 分段式分配是按需分配，而固定式分配是固定分配的方式

内部碎片与外部碎片
> 内碎片：分配给某些进程的内存区域中有些部分没用上，常见于固定分配方式
> 外碎片：内存中某些空闲区因为比较小，而难以利用上，一般出现在内存动态分配方式中

如何消除碎片文件?查一下
- 对于外部碎片，通过紧凑技术消除，就是操作系统不时地对进程进行移动和整理。但是这需要动态重定位寄存器地支持，且相对费时。
- 


冯诺依曼结构有哪几个模块？分别对应现代计算机的哪几个部分？
多进程和多线程的区别是什么？换句话说，什么时候该用多线程，什
么时候该用多进程？
- 需要频繁创建和销毁的优先使用多线程
- 需要大量计算的优先使用多线程 因为需要消耗大量CPU资源且切换频繁，所以多线程好一点
- 任务间相关性比较强的用多线程，相关性比较弱的用多进程。因为线程之间的数据共享和同步比较简单。
- 可能要扩展到多机分布的用多进程，多核分布的用多线程。

在执行malloc申请内存的时候，操作系统是怎么做的？
[一文搞定基址寄存器、界限寄存器、静态重定位与动态重定位](https://blog.csdn.net/Jiangtagong/article/details/108974042)
分段与分页[1](https://www.cnblogs.com/holmes7521/p/15118070.html)
 现在普遍采取的内存分配方式是段页式内存分配。将内存分为不同的段，再将每一段分成固定大小的页。通过页表机制，使段内的页可以不必连续处于同一内存区域。

[1wei&2](https://blog.csdn.net/yangkuiwu/article/details/53493458)
[分段、分页、段页式转换详解](https://blog.csdn.net/smilesundream/article/details/70148878)
[gdtr](http://www.techbulo.com/708.html)
[段页式](https://blog.csdn.net/Willy__QI/article/details/105059712)
可以针对不同类型的段采取不同的保护，可以按段为单位来进行共享，包括通过动态链接进行代码共享。
如何解决内存碎片[here](https://www.nowcoder.com/questionTerminal/b7ec12323842436d80fbb3e56162a67a)
外部碎片与内部碎片


###mysql
[read](https://www.cnblogs.com/crazylqy/p/7821481.html)
[read](https://blog.csdn.net/it_lihongmin/article/details/115192102)

关系型和非关系型数据库的区别你了解多少？
为什么使用索引？
Innodb为什么要用自增id作为主键？
MyISAM和InnoDB实现B树索引方式的区别是什么？
主键字段不宜过长--[解释](https://blog.csdn.net/shenjian58/article/details/101442706)
说一下MySQL是如何执行一条SQL的？具体步骤有哪些？
你了解MySQL的内部构造吗？一般可以分为哪两个部分？
存储过程、执行计划、触发器
说一说Drop、Delete与Truncate的共同点和区别
数据库隔离级别
Next-Key Lock 锁算法
都知道数据库索引采用B+树而不是B树，原因也有很多，主要原因是什么？
数据库系统中的局部性原理？
文件索引和数据库索引为什么使用B+树?
听说过视图吗？那游标呢？
MySQL中为什么要有事务回滚机制？
数据库引擎InnoDB与MyISAM的区别[晕](https://www.cnblogs.com/timor0101/p/12883649.html)
- innodb可预测读
- 自动创建的自适应哈希索引
- 加速插入操作的插入缓冲区

[1级与2级索引](http://www.mybatis.cn/archives/941.html)
[index](https://www.jianshu.com/p/fa8192853184)
[局部性原理和磁盘预读](https://www.jianshu.com/p/d689f806c745)
[关于MySQL buffer pool的预读机制](https://www.cnblogs.com/geaozhang/p/7397699.html)
[自适应hash索引](https://blog.csdn.net/it_lihongmin/article/details/115206442)
[插入缓冲](https://zhuanlan.zhihu.com/p/39812854)
数据库并发事务会带来哪些问题？
数据库悲观锁和乐观锁的原理和应用场景分别有什么？
[for update](https://segmentfault.com/a/1190000023045909)
MySQL索引主要使用的两种数据结构是什么？
数据库为什么要进行分库和分表呢？都放在一个库或者一张表中不可以吗？
不可重复读和幻读区别是什么？可以举个例子吗？
MySQL中有四种索引类型，可以简单说说吗？
RTREE？？？
视图的作用是什么？可以更改吗？（什么条件可以修改）
什么时候需要建立数据库索引呢？
覆盖索引是什么？
数据库中的主键、超键、候选键、外键是什么？（很棒）
SQL中的NOW()和CURRENT_DATE()两个函数有什么区别？
聚集索引与非聚集索引的区别是什么?
创建索引时需要注意什么？
MySQL中CHAR和VARCHAR的区别有哪些？
MySQL 索引使用的注意事项
- 不要在列上使用函数，这将导致索引失效而进行全表扫描。
- 尽量避免使用 != 或 not in或 <> 等否定操作符
- 应该尽量避免在 where 子句中使用 or 来连接条件，因为这会导致索引失效而进行全表扫描。
- 多个单列索引并不是最佳选择
- 复合索引的最左前缀原则
- 覆盖索引的好处
- 复合索引中只要有一列含有 NULL值，那么这一列对于此复合索引就是无效的。
- 删除长期未使用的索引，不用的索引的存在会造成不必要的性能损耗

既然索引有那么多优点，为什么不对表总的每一列创建一个索引呢？
增加B+树的路数可以降低树的高度，那么无限增加树的路数是不是可以有最优的查找效率？
说一下数据库表锁和行锁吧
SQL语法中内连接、自连接、外连接（左、右、全）、交叉连接的区别分别是什么？
你知道哪些数据库结构优化的手段？
- 范式优化
- 反范式优化
- 限定数据的范围
- 读/写分离

为什么MySQL索引要使用B+树，而不是B树或者红黑树？
为什么MySQL索引适用用B+树而不用hash表和B树？
既然Hash比B+树更快，为什么MySQL用B+树来存储索引呢？
数据库如何保证一致性？
数据库如何保证原子性？
数据库如何保证持久性？
[RTREE](https://blog.csdn.net/wzf1993/article/details/79547037)
[DML](https://www.cnblogs.com/henryhappier/archive/2010/07/05/1771295.html)
[binlog](https://blog.csdn.net/ouyang111222/article/details/50300851)



###网络
OSI 的七层模型分别是？各自的功能是什么？
- 物理层: 通过媒介传输比特,确定机械及电气规范,传输单位为 bit；
- 数据链路层: 将比特组装成帧和点到点的传递,传输单位为帧,
- 网络层：负责数据包从源到宿的传递和网际互连，传输单位为包
- 传输层：提供端到端的可靠报文传递和错误恢复，传输单位为报文
- 会话层：建立、管理和终止会话，传输单位为 SPDU
- 表示层: 对数据进行翻译、加密和压缩,传输单位为 PPDU

说一下一次完整的HTTP请求过程包括哪些内容？
你知道DNS是什么？
DNS的工作原理？
> 将主机域名转换为ip地址，属于应用层协议，使用UDP传输。
主机向本地域名服务器的查询一般都是采用递归查询。
本地域名服务器向根域名服务器的查询的迭代查询。

为什么域名解析用UDP协议？
HTTP长连接和短连接的区别
什么是TCP粘包/拆包？发生的原因？
> 一个完整的业务可能会被TCP拆分成多个包进行发送，也有可能把多个小的包封装成一个大的数据包发送，这个就是TCP的拆包和粘包问题。
<b>原因</b>：
- 应用程序写入数据的字节大小大于套接字发送缓冲区的大小.
- 进行MSS(MSS的取值受限于MTU)大小的TCP分段。( MSS=TCP报文段长度-TCP首部长度)
- 以太网的payload大于MTU(1500)进行IP分片。
>[补充](https://www.cnblogs.com/panchanggui/p/9518735.html)

>解决办法：
>- 发送端给每个数据包添加包首部，首部中应该至少包含数据包的长度，这样接收端在接收到数据后，通过读取包首部的长度字段，便知道每一个数据包的实际长度了。
>- 发送端将每个数据包封装为固定长度（不够的可以通过补0填充），这样接收端每次从接收缓冲区中读取固定长度的数据就自然而然的把每个数据包拆分开来。
>- 可以在数据包之间设置边界，如添加特殊符号，这样，接收端通过这个边界就可以将不同的数据包拆分开。

HTTP请求方法你知道多少？
>  GET请求指定的页面信息，并返回实体主体。
>  POST向指定资源提交数据进行处理请求（例如提交表单或者上传文件）。数据被包含在请求体中。POST请求可能会导致新的资源的建立和/或已有资源的修改。

GET和POST的区别，你知道哪些？
一个TCP连接可以对应几个HTTP请求？
一个 TCP 连接中 HTTP 请求发送可以一起发送么?[1](https://blog.csdn.net/zipack/article/details/103397056)
浏览器对同一 Host 建立 TCP 连接到的数量有没有限制？
在浏览器地址栏输入一个URL后回车，背后会进行哪些技术步骤？
全球好像一共有13台根服务器
DNS负载均衡是什么策略？
HTTPS和HTTP的区别
HTTP请求和响应报文有哪些主要字段？
Cookie是什么？
> - HTTP 协议是无状态的，主要是为了让 HTTP 协议尽可能简单，使得它能够处理大量事务，HTTP/1.1 引 入 Cookie 来保存状态信息。
- Cookie 是服务器发送到用户浏览器并保存在本地的一小块数据，它会在浏览器之后向同一服务器再次发起请求时被携带上，用于告知服务端两个请求是否来自同一浏览器。由于之后每次请求都会需要携带Cookie 数据，因此会带来额外的性能开销.

Cookie有什么用途？用途
- 会话状态管理（如用户登录状态、购物车、游戏分数或其它需要记录的信息）
- 个性化设置（如用户自定义设置、主题等）
- 浏览器行为跟踪（如跟踪分析用户行为等）

Session知识大总结
- 除了可以将用户信息通过 Cookie 存储在用户浏览器中，也可以利用 Session 存储在服务器端，存储在服务器端的信息更加安全。
- Session 可以存储在服务器上的文件、数据库或者内存中。
- 使用 Session 维护用户登录状态的过程如下：
	1. 用户进行登录时，用户提交包含用户名和密码的表单，放入 HTTP 请求报文中；
	2. 服务器验证该用户名和密码，如果正确则把用户信息存储到 Redis 中，它在 Redis 中的 Key 称为Session ID；
	3. 服务器返回的响应报文的 Set-Cookie 首部字段包含了这个 Session ID，客户端收到响应报文之后将该cookie 值存入浏览器中；
	4. 客户端之后对同一个服务器进行请求时会包含该 Cookie 值，服务器收到之后提取出 Session ID，从Redis 中取出用户信息，继续之前的业务操作。
	5. >Session ID 的安全性问题，不能让它被恶意攻击者轻易获取，那么就不能产生一个容易被猜到的 Session ID 值。此外，还需要经常重新生成 Session ID。

Session 的工作原理是什么？
Cookie与Session的对比
搜索 baidu，会用到计算机网络中的什么层？每层是干什么的
- DNS域名解析
- 

DNS的工作原理？[ans](https://blog.51cto.com/369369/812889)
GET 和 POST 的区别，你知道哪些？
一个TCP连接可以对应几个HTTP请求？
一个 TCP 连接中 HTTP 请求发送可以一起发送么（比如一起发三个
请求，再三个响应一起接收）？
浏览器对同一 Host 建立 TCP 连接到的数量有没有限制？
在浏览器地址栏输入一个URL后回车，背后会进行哪些技术步骤？
Session 的工作原理是什么？
MTU和MSS分别是什么？
对于FIN_WAIT_2，CLOSE_WAIT状态和TIME_WAIT状态？你知道
多少?
请你说一说 TCP 拥塞控制？以及达到什么情况的时候开始减慢增长的速度？
- 慢开始
- 拥塞避免
- 快重传
- 快恢复

请问 TCP 用了哪些措施保证其可靠性？
- 序列号、确认应答、超时重传
- 窗口控制与高速重发控制/快速重传（重复确认应答）
- 拥塞控制
- 数据包校验
- 对失序数据包重新排序（TCP报文具有序列号）
- 丢弃重复数据

请你来说一下 TCP 拥塞控制？
请你来说一下 socket 编程中服务器端和客户端主要用到哪些函数
1. TCP：
	- 服务器：
		- 创建一个 socket，用函数 socket()
		- 绑定 IP 地址、端口等信息到 socket 上，用函数 bind()
		- 设置允许的最大连接数，用函数 listen()
		- 接收客户端上来的连接，用函数 accept()
		- 收发数据，用函数 send()和 recv()，或者 read()和 write()
		- 关闭网络连接
	- 客户端：
		- 创建一个 socket，用函数 socket()
		- 设置要连接的对方的 IP 地址和端口等属性
		- 连接服务器，用函数 connect()
		- 收发数据，用函数 send()和 recv()，或 read()和 write()
		- 关闭网络连接
2. 基于 UDP 的 socket
	- 服务器端流程
		- 建立套接字文件描述符，使用函数 socket()，生成套接字文件描述符。
		- 设置服务器地址和侦听端口，初始化要绑定的网络地址结构。
		- 绑定侦听端口，使用 bind()函数，将套接字文件描述符和一个地址类型变量进行绑定。
		- 接收客户端的数据，使用 recvfrom()函数接收客户端的网络数据。
		- 向客户端发送数据，使用 sendto()函数向服务器主机发送数据。
		- 关闭套接字，使用 close()函数释放资源。UDP 协议的客户端流程
	- 客户端：
		- 建立套接字文件描述符，socket()。
		- 设置服务器地址和端口，struct sockaddr。
		- 向服务器发送数据，sendto()。
		- 接收服务器的数据，recvfrom()。
		- 关闭套接字，close()。
 
TCP 利用滑动窗口实现流量控制的机制？
> 流量控制是为了控制发送方发送速率，保证接收方来得及接收。TCP 利用滑动窗口实现流量控制。
> TCP 中采用滑动窗口来进行传输控制，滑动窗口的大小意味着接收方还有多大的缓冲区可以用于接收数据。发送方可以通过滑动窗口的大小来确定应该发送多少字节的数据。当滑动窗口为 0 时，发送方一般不能再发送数据报，但有两种情况除外，一种情况是可以发送紧急数据。发送方可以发送一个 1 字节的数据报来通知接收方重新声明它希望接收的下一字节及发送方的滑动窗口大小。


ping的原理[1](https://blog.csdn.net/zhizhengguan/article/details/109206015)
- 控制报文协议（Internet Control Message Protocol，ICMP）是 TCP/IP 协议族的一个子协议。ICMP 协议用于在 IP 主机和路由器之间传递控制消息，描述网络是否通畅、主机是否可达、路由器是否可用等网络状态。
- ping是基于ICMP协议工作的
- ICMP 主要的功能包括：确认 IP 包是否成功送达目标地址、报告发送过程中 IP 包被废弃的原因和改善网络设置等。
- ICMP报文是封装在IP包里面，它工作在网络层，是IP协议的助手
- 回送消息用于进行通信的主机或者路由器之间，判断所发送的数据包是否已经成功到达对端的一种消息,ping命令就是利用这个消息实现的
- ping命令执行的时候，源主机首先会构建一个 ICMP回送请求消息数据包；
- 然后，由ICMP 协议将这个数据包连同地址 192.168.1.2 一起交给IP 层。IP 层将以 192.168.1.2 作为目的地址，本机 IP 地址作为源地址，协议字段设置为1 表示是 ICMP 协议，再加上一些其他控制信息，构建一个IP 数据包。
- 接下来，需要加入MAC 头。如果在本地ARP映射表中查找出 IP 地址 192.168.1.2 所对应的 MAC地址，则可以直接使用；如果没有，则需要发送 ARP 协议查询 MAC 地址，获得 MAC 地址后，由数据链路层构建一个数据帧，目的地址是 IP 层传过来的 MAC 地址，源地址则是本机的 MAC 地址；还要附加上一些控制信息，依据以太网的介质访问规则，将它们传送出去；
- 主机 B收到这个数据帧后，先检查它的目的 MAC地址，并和本机的 MAC 地址对比，如符合，则接收，否则就丢弃。接收后检查该数据帧，将IP数据包从帧中提取出来，交给本机的IP 层。同样，IP层检查后，将有用的信息提取后交给ICMP 协议。
- 主机B 会构建一个 ICMP 回送响应消息数据包，回送响应数据包的类型字段为 0 ，序号为接收到的请求数据包中的序号，然后再发送出去给主机 A。
- 在规定的时候间内，源主机如果没有接到 ICMP 的应答包，则说明目标主机不可达；如果接收到了ICMP 回送响应消息，则说明目标主机可达。
- IP 包中有一个字段叫做 TTL（ Time To Live，生存周期），它的 值随着每经过一次路由器就会减1，直到减到 0 时该 IP 包会被丢弃。
- 此时，路由器将会发送一个ICMP 超时消息给发送端主机，并通知该包已被丢弃。

TraceRoute原理路径 MTU[here](https://blog.csdn.net/weixin_34185512/article/details/85915945)
- Traceroute是用来侦测主机到目的主机之间所经路由情况的重要工具。
- 首先给目的主机发送一个TTL=1的UDP数据包（每次送出的为3个40字节的包，包括源地址，目的地址和包发出的时间标签
- 而经过的第一个路由器收到这个数据包以后，就自动把TTL减1，而TTL变为0以后，路由器就把这个包给抛弃了，并同时产生 一个主机不可达的ICMP数据报给主机。
- 主机收到这个数据报以后再发一个TTL=2的UDP数据报给目的主机，然后刺激第二个路由器给主机发ICMP数据报。如此往复直到到达目的主机。这样，traceroute就拿到了所有的路由器ip。

TCP数据包校验[here](https://blog.csdn.net/zhangskd/article/details/11770647)[2](https://www.cnblogs.com/zxiner/p/7203192.html)、CRC[1](http://blog.chinaunix.net/uid-30249924-id-5054776.html)

电路交换与分组交换：
总时延 = 传输时延 + 传播时延 + 处理时延 + 排队时延
五层协议
数据在各层之间的传递过程
通信方式：根据信息在传输线上的传送方向
带通调制：带通调制把数字信号转换为模拟信号。
数据链路层：
- 封装成帧
- 透明传输
- 差错检测

信道分类：
- 广播信道
	- 信道复用技术
	- CSMA/CD 协议
- 点对点信道
	- PPP 协议进行控制

信道复用技术
-  频分复用：频分复用的所有主机在相同的时间占用不同的频率带宽资源。
-  时分复用：时分复用的所有主机在不同的时间占用相同的频率带宽资源。
-  统计时分复用：是对时分复用的一种改进，不固定每个用户在时分复用帧中的位置，只要有数据就集中起来组成统计时分复用帧然后发送。
-  波分复用：光的频分复用。由于光的频率很高，因此习惯上用波长而不是频率来表示所使用的光载波。
-  码分复用

CSMA/CD 协议:载波监听多点接入 / 碰撞检测。
- 多点接入
- 载波监听
- 碰撞检测:[截断二进制指数退避算法](https://blog.nowcoder.net/n/c2ba83f3519848c0a9a1e6caef7264dc)

PPP 协议:
互联网用户通常需要连接到某个 ISP 之后才能接入到互联网，PPP 协议是用户计算机和 ISP 进行通信时所使用的数据链路层协议。

MAC 地址:
MAC 地址是链路层地址，长度为 6 字节（48 位），用于唯一标识网络适配器（网卡）。

以太网:
以太网是一种星型拓扑结构局域网。早期使用集线器进行连接，集线器是一种物理层设备，作用于比特而不是帧，当一个比特到达接口时，集线器重新生成这个比特，并将其能量强度放大，从而扩大网络的传输距离，之后再将这个比特发送到其它所有接口。

交换机:
交换机具有自学习能力，学习的是交换表的内容，交换表中存储着 MAC 地址到接口的映射。正是由于这种自学习能力，因此交换机是一种即插即用设备，不需要网络管理员手动配置交换表内容。
交换机有 4 个接口，主机 A 向主机 B 发送数据帧时，交换机把主机 A 到接口 1 的映射写入交换表中。为了发送数据帧到 B，先查交换表，此时没有主机 B 的表项，那么主机 A 就发送广播帧，主机 C 和主机 D 会丢弃该帧。主机 B 收下之后，查找交换表得到主机 A 映射的接口为 1，就发送数据帧到接口 1，同时交换机添加主机B到接口 3 的映射。

虚拟局域网：
为什么客户端最后还要等待2MSL？
- 第一，保证客户端发送的最后一个ACK报文能够到达服务器，因为这个ACK报文可能丢失，站在服务器的角度看来，我已经发送了FIN+ACK报文请求断开了，客户端还没有给我回应，应该是我发送的请求断开报文它没有收到，于是服务器又会重新发送一次，而客户端就能在这个2MSL时间段内收到这个重传的报文，接着给出回应报文，并且会重启2MSL计时器。
- 第二，防止类似与“三次握手”中提到了的“已经失效的连接请求报文段”出现在本连接中。客户端发送完最后一个确认报文后，在这个2MSL时间中，就可以使本连接持续的时间内所产生的所有报文段都从网络中消失。这样新的连接中不会出现旧连接的请求报文。

这里主要展示POST和GET的区别?
- GET请求会被浏览器主动cache
- GET请求在URL中传送的参数是有长度限制的，而POST么有。
- 对参数的数据类型，GET只接受ASCII字符，而POST没有限制。
- GET请求参数会被完整保留在浏览器历史记录里，而POST中的参数不会被保留。








###网络编程
select/poll/epoll [link](https://mp.weixin.qq.com/s/BfnNl-3jc_x5WPrWEJGdzQ)

###项目
线程池：
- 半同步半反应堆模式，半反应堆具体为Proactor事件处理模式；
- 通过信号量提醒有任务要处理；

有限状态机：
是一种抽象的理论模型，通过把有限个变量描述的状态变化过程，以可构造可验证的方式呈现出来

解析报文的整体流程：
[解析](https://mp.weixin.qq.com/s/wAQHU-QZiRt1VACMZZjNlw)

定时器：
- 非活跃；
- 定时事件；
- 定时器
- > 服务器的主循环为每一个连接创建一个定时器，并对每个连接进行定时。利用最小堆将所有定时器串联起来，若主循环接受收到定时通知，则执行定时任务，用alarm函数周期触发SIGALRM信号，信号处理函数利用管道通知主循环，主循环接收到该信号后对定时器进行处理，若该段时间内没有交换数据，则将该连接关闭，释放所占用的资源。分为两大部分：1）定时方法与信号通知流程；2）定时器及其容器设计与定时任务的处理。
> sigaction结构体
> sigaction函数
> sigfillset函数
> socketpair函数
> linux下信号采用的是异步处理机制，信号处理函数与当前进程是两条不同的执行路线。具体的，具体的，当进程收到信号时，操作系统会中断进程当前的正常流程，转而进入信号处理函数执行操作，完成后再返回中断的地方继续执行。为避免信号竞态现象发生，信号处理期间系统不会再次触发它。所以，为确保该信号不被屏蔽太久，信号处理函数需要尽可能快地执行完毕。这里的解决方案是，信号处理函数仅仅发送信号通知程序主循环，将信号对应的处理逻辑放在程序主循环中，由主循环执行信号对应的逻辑代码。具体的，信号处理函数使用管道将信号传递给主循环，信号处理函数往管道的写端写入信号值，主循环则从管道的读端读出信号值，使用I/O复用系统调用来监听管道读端的可读事件，这样信号事件与其他文件描述符都可以通过epoll来监测，从而实现统一处理。

> 补充知识

原子操作atomic(未看)

重定位[here](https://blog.csdn.net/Jiangtagong/article/details/108974042)

ssl tls原理
中断过程
网络编程对应三次握手与四次挥手
自旋锁实现[here](https://blog.csdn.net/jeffasd/article/details/80661804?utm_medium=distribute.pc_relevant.none-task-blog-2~default~baidujs_title~default-0.essearch_pc_relevant&spm=1001.2101.3001.4242)
TCP包长度
红黑树平衡操作
运行时库是什么
多线程同时开始同时结束
bin log, redo, undo区别
持久性如何保证
如何实现隔离性
最左前缀匹配
mysql乐观锁还是悲观锁，有哪些锁
mvcc
时间轮定时器
阻塞与非阻塞
mysql隔离级别
[writev & readv](https://blog.csdn.net/weixin_36750623/article/details/84579243)
存储过程、触发器、视图
悲观锁和乐观锁
最左前缀原则
 CSMA/CD 协议


自旋锁存在哪些问题？
拥塞控制算法在实际场景存在什么问题？
- 为什么慢开始阶段出现拥塞需要将cnwd设置为1
- 为什么快恢复是一半？
- 实际场景中如何选择？
- 什么情况需要将设置1
用户态与内核态如何转换？
虚拟内存
页面置换如何决定置换哪一个进程？
null为什么0地址无法访问？
递归算法如何优化？

<hr>
[红黑树](https://www.jianshu.com/p/e136ec79235c)
##红黑树专题
###正文
红黑树也是二叉查找树，我们知道，二叉查找树这一数据结构并不难，而红黑树之所以难是难在它是自平衡的二叉查找树，在进行插入和删除等可能会破坏树的平衡的操作时，需要重新自处理达到平衡状态。
红黑树并不是一个完美平衡二叉查找树
###红黑树定义和性质
红黑树是一种含有红黑结点并能自平衡的二叉查找树。它必须满足下面性质：
- 性质1：每个节点要么是黑色，要么是红色。
- 性质2：根节点是黑色。
- 性质3：每个叶子节点（NIL）是黑色。
- 性质4：每个红色结点的两个子结点一定都是黑色。
- 性质5：任意一结点到每个叶子结点的路径都包含数量相同的黑结点。

前面讲到红黑树能自平衡，它靠的是什么？三种操作：左旋、右旋和变色。
- 左旋：以某个结点作为支点(旋转结点)，其右子结点变为旋转结点的父结点，右子结点的左子结点变为旋转结点的右子结点，左子结点保持不变。
	- [lizi](https://upload-images.jianshu.io/upload_images/2392382-a95db442f1b47f8a.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)
- 右旋：以某个结点作为支点(旋转结点)，其左子结点变为旋转结点的父结点，左子结点的右子结点变为旋转结点的左子结点，右子结点保持不变。
- 变色：结点的颜色由红变黑或由黑变红。

我们先忽略颜色，可以看到旋转操作不会影响旋转结点的父结点，父结点以上的结构还是保持不变的。
- 左旋只影响旋转结点和其右子树的结构，把右子树的结点往左子树挪了。
- 右旋只影响旋转结点和其左子树的结构，把左子树的结点往右子树挪了。

所以旋转操作是局部的。另外可以看出旋转能保持红黑树平衡的一些端详了：当一边子树的结点少了，那么向另外一边子树“借”一些结点；当一边子树的结点多了，那么向另外一边子树“租”一些结点。
但要保持红黑树的性质，结点不能乱挪，还得靠变色了。怎么变？具体情景又不同变法

###红黑树查找
因为红黑树是一颗二叉平衡树，并且查找不会破坏树的平衡，所以查找跟二叉平衡树的查找无异：
1. 从根结点开始查找，把根结点设置为当前结点；
2. 若当前结点为空，返回null；
3. 若当前结点不为空，用当前结点的key跟查找key作比较；
4. 若当前结点key等于查找key，那么该key就是查找目标，返回当前结点；
5. 若当前结点key大于查找key，把当前结点的左子结点设置为当前结点，重复步骤2；
6. 若当前结点key小于查找key，把当前结点的右子结点设置为当前结点，重复步骤2；
[here](https://upload-images.jianshu.io/upload_images/2392382-07b47eb3722981e6.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)

非常简单，但简单不代表它效率不好。正由于红黑树总保持黑色完美平衡，所以它的查找最坏时间复杂度为O(2lgN)，也即整颗树刚好红黑相隔的时候。能有这么好的查找效率得益于红黑树自平衡的特性，而这背后的付出，红黑树的插入操作功不可没

###红黑树插入
插入操作包括两部分工作：一查找插入的位置；二插入后自平衡。查找插入的父结点很简单，跟查找操作区别不大：
1. 从根结点开始查找；
2. 若根结点为空，那么插入结点作为根结点，结束。
3. 若根结点不为空，那么把根结点作为当前结点；
4. 若当前结点为null，返回当前结点的父结点，结束。
5. 若当前结点key等于查找key，那么该key所在结点就是插入结点，更新结点的值，结束。
6. 若当前结点key大于查找key，把当前结点的左子结点设置为当前结点，重复步骤4；
7. 若当前结点key小于查找key，把当前结点的右子结点设置为当前结点，重复步骤4；
[here](https://upload-images.jianshu.io/upload_images/2392382-7521866b50683a24.png?imageMogr2/auto-orient/strip|imageView2/2/w/1200/format/webp)


ok，插入位置已经找到，把插入结点放到正确的位置就可以啦，但插入结点是应该是什么颜色呢？答案是红色。理由很简单，红色在父结点（如果存在）为黑色结点时，红黑树的黑色平衡没被破坏，不需要做自平衡操作。但如果插入结点是黑色，那么插入位置所在的子树黑色结点总是多1，必须做自平衡。

[插入情景](https://upload-images.jianshu.io/upload_images/2392382-fa2b78271263d2c8.png?imageMogr2/auto-orient/strip|imageView2/2/w/1033/format/webp)

- 插入情景1：红黑树为空树
	> 最简单的一种情景，直接把插入结点作为根结点就行，但注意，根据红黑树性质2：根节点是黑色。还需要把插入结点设为黑色。
	> 处理：把插入结点作为根结点，并把结点设置为黑色
- 插入情景2：插入结点的Key已存在
	> 插入结点的Key已存在，既然红黑树总保持平衡，在插入前红黑树已经是平衡的，那么把插入结点设置为将要替代结点的颜色，再把结点的值更新就完成插入。
	> 处理：
		把I设为当前结点的颜色
		更新当前结点的值为插入结点的值
- 插入情景3：插入结点的父结点为黑结点
	> 由于插入的结点是红色的，并不会影响红黑树的平衡，直接插入即可，无需做自平衡。

- 插入情景4：插入结点的父结点为红结点
	> 再次回想下红黑树的性质2：根结点是黑色。如果插入的父结点为红结点，那么该父结点不可能为根结点，所以插入结点总是存在祖父结点。
	- 插入情景4.1：叔叔结点存在并且为红结点
	  从红黑树性质4可以，祖父结点肯定为黑结点，因为不可以同时存在两个相连的红结点。那么此时该插入子树的红黑层数的情况是：黑红红。显然最简单的处理方式是把其改为：红黑红
	  处理：
		 将P和S设置为黑色
		 将PP设置为红色
	     把PP设置为当前插入结点
	  可以看到，我们把PP结点设为红色了，如果PP的父结点是黑色，那么无需再做任何处理；但如果PP的父结点是红色，根据性质4，此时红黑树已不平衡了，所以还需要把PP当作新的插入结点，继续做插入操作自平衡处理，直到平衡为止。
	  试想下PP刚好为根结点时，那么根据性质2，我们必须把PP重新设为黑色，那么树的红黑结构变为：黑黑红。换句话说，从根结点到叶子结点的路径中，黑色结点增加了。这也是唯一一种会增加红黑树黑色结点层数的插入情景。
      我们还可以总结出另外一个经验：红黑树的生长是自底向上的。这点不同于普通的二叉查找树，普通的二叉查找树的生长是自顶向下的。
	- 插入情景4.2：叔叔结点不存在或为黑结点，并且插入结点的父亲结点是祖父结点的左子结点
	  单纯从插入前来看，也即不算情景4.1自底向上处理时的情况，叔叔结点非红即为叶子结点(Nil)。因为如果叔叔结点为黑结点，而父结点为红结点，那么叔叔结点所在的子树的黑色结点就比父结点所在子树的多了，这不满足红黑树的性质5。后续情景同样如此，不再多做说明了。
	  前文说了，需要旋转操作时，肯定一边子树的结点多了或少了，需要租或借给另一边。插入显然是多的情况，那么把多的结点租给另一边子树就可以了。
	  	- 插入情景4.2.1：插入结点是其父结点的左子结点
	  	  处理： 将P设为黑色 将PP设为红色 对PP进行右旋
		- 插入情景4.2.2：插入结点是其父结点的右子结点
		  处理： 对P进行左旋 把P设置为插入结点，得到情景4.2.1
	- 插入情景4.3：叔叔结点不存在或为黑结点，并且插入结点的父亲结点是祖父结点的右子结点
		- 插入情景4.3.1：插入结点是其父结点的右子结点
		- 插入情景4.3.2：插入结点是其父结点的左子结点

###红黑树删除
红黑树的删除操作也包括两部分工作：一查找目标结点；而删除后自平衡。查找目标结点显然可以复用查找操作，当不存在目标结点时，忽略本次操作；当存在目标结点时，删除后就得做自平衡处理了。删除了结点后我们还需要找结点来替代删除结点的位置，不然子树跟父辈结点断开了，除非删除结点刚好没子结点，那么就不需要替代。

二叉树删除结点找替代结点有3种情情景：
- 情景1：若删除结点无子结点，直接删除
- 情景2：若删除结点只有一个子结点，用子结点替换删除结点
- 情景3：若删除结点有两个子结点，用后继结点（大于删除结点的最小结点）替换删除结点

把二叉树所有结点投射在X轴上，所有结点都是从左到右排好序的，所有目标结点的前后结点就是对应前继和后继结点
删除结点被替代后，在不考虑结点的键值的情况下，对于树来说，可以认为删除的是替代结点！
上面所说的3种二叉树的删除情景可以相互转换并且最终都是转换为情景1！

情景2：删除结点用其唯一的子结点替换，子结点替换为删除结点后，可以认为删除的是子结点，若子结点又有两个子结点，那么相当于转换为情景3，一直自顶向下转换，总是能转换为情景1。（对于红黑树来说，根据性质5.1，只存在一个子结点的结点肯定在树末了）

情景3：删除结点用后继结点（肯定不存在左结点），如果后继结点有右子结点，那么相当于转换为情景2，否则转为为情景1。

删除情景1：替换结点是红色结点
我们把替换结点换到了删除结点的位置时，由于替换结点时红色，删除也了不会影响红黑树的平衡，只要把替换结点的颜色设为删除的结点的颜色即可重新平衡。
处理：颜色变为删除结点的颜色

删除情景2：替换结点是黑结点
当替换结点是黑色时，我们就不得不进行自平衡处理了。我们必须还得考虑替换结点是其父结点的左子结点还是右子结点，来做不同的旋转操作，使树重新平衡。
- 删除情景2.1：替换结点是其父结点的左子结点
	- 删除情景2.1.1：替换结点的兄弟结点是红结点
		处理：
		- 将S设为黑色
		- 将P设为红色
		- 对P进行左旋
		- 进行情景2.1.2.3的处理
	- 删除情景2.1.2：替换结点的兄弟结点是黑结点
		- 删除情景2.1.2.1：替换结点的兄弟结点的右子结点是红结点，左子结点任意颜色
		- 删除情景2.1.2.2：替换结点的兄弟结点的右子结点为黑结点，左子结点为红结点
		- 删除情景2.1.2.3：替换结点的兄弟结点的子结点都为黑结点
- 删除情景2.2：替换结点是其父结点的右子结点
	- 删除情景2.2.1：替换结点的兄弟结点是红结点
	- 替换结点的兄弟结点是黑结点
		- 删除情景2.2.2.1：替换结点的兄弟结点的左子结点是红结点，右子结点任意颜色
		- 删除情景2.2.2.2：替换结点的兄弟结点的左子结点为黑结点，右子结点为红结点
		- 删除情景2.2.2.3：替换结点的兄弟结点的子结点都为黑结点

<hr/>
##一次完整的HTTP请求过程：
1. 首先进行域名解析，域名解析具体过程讲一下:
	- 浏览器搜索自己的DNS缓存，缓存中维护一张域名与IP地址的对应表；
	- 若没有，则搜索操作系统的DNS缓存；
	- 若没有，则操作系统将域名发送至本地域名服务器（递归查询方式），本地域名服务器查询自己的DNS缓存，查找成功则返回结果，否则，通过以下方式迭代查找：
		- 本地域名服务器向根域名服务器发起请求，根域名服务器返回com域的顶级域名服务器的地址；
		- 本地域名服务器向com域的顶级域名服务器发起请求，返回权限域名服务器地址；
		- 本地域名服务器向权限域名服务器发起请求，得到IP地址;
	- 本地域名服务器将得到的IP地址返回给操作系统，同时自己将IP地址缓存起来；
	- 操作系统将IP地址返回给浏览器，同时自己也将IP地址缓存起来；
	- 至此，浏览器已经得到了域名对应的IP地址。
2. 浏览器发起HTTP请求；
3. 接下来到了传输层，选择传输协议，TCP或者UDP，TCP是可靠的传输控制协议，对HTTP请求进行封装，加入了端口号等信息；
4. 然后到了网络层，通过IP协议将IP地址封装为IP数据报；然后此时会用到ARP协议，主机发送信息时将包含目标IP地址的ARP请求广播到网络上的所有主机，并接收返回消息，以此确定目标的物理地址，找到目的MAC地址；
5. 接下来到了数据链路层，把网络层交下来的IP数据报添加首部和尾部，封装为MAC帧，现在根据目的mac开始建立TCP连接，三次握手，接收端在收到物理层上交的比特流后，根据首尾的标记，识别帧的开始和结束，将中间的数据部分上交给网络层，然后层层向上传递到应用层；
6. 服务器响应请求并请求客户端要的资源，传回给客户端:
	- 负载均衡：网站可能会有负载均衡设备来平均分配所有用户的请求。即对工作任务进行平衡分摊到多个操作单元上执行,如图片服务器,应用服务器等。
	- 请求处理阅读请求及它的参数和 cookies

7. 断开TCP连接(四次挥手)，浏览器对页面进行渲染呈现给客户端。

<hr>
###DNS
DNS负载均衡
[dns](https://zhuanlan.zhihu.com/p/52806422)
域名的解析过程:
- 主机向本地域名服务器的查询一般都是采用递归查询。所谓递归查询就是：如果主机所询问的本地域名服务器不知道被查询的域名的IP地址，那么本地域名服务器就以DNS客户的身份，向其它根域名服务器继续发出查询请求报文(即替主机继续查询)，而不是让主机自己进行下一步查询。因此，递归查询返回的查询结果或者是所要查询的IP地址，或者是报错，表示无法查询到所需的IP地址。
- 本地域名服务器向根域名服务器的查询的迭代查询。迭代查询的特点：当根域名服务器收到本地域名服务器发出的迭代查询请求报文时，要么给出所要查询的IP地址，要么告诉本地服务器：“你下一步应当向哪一个域名服务器进行查询”。然后让本地服务器进行后续的查询。根域名服务器通常是把自己知道的顶级域名服务器的IP地址告诉本地域名服务器，让本地域名服务器再向顶级域名服务器查询。顶级域名服务器在收到本地域名服务器的查询请求后，要么给出所要查询的IP地址，要么告诉本地服务器下一步应当向哪一个权限域名服务器进行查询。最后，知道了所要解析的IP地址或报错，然后把这个结果返回给发起查询的主机。

本地域名服务器两种查询的区别：
[a](https://pic3.zhimg.com/80/v2-d4e2bb9ad1b573ab0b0b83b25d56e7ca_720w.jpg)
[b](https://pic3.zhimg.com/80/v2-d4e2bb9ad1b573ab0b0b83b25d56e7ca_720w.jpg)
主机两种查询的区别：
[paper](https://www.jianshu.com/p/6b502d0f2ede)





<hr>
###ARP
[ARP](https://segmentfault.com/a/1190000038968822)


<hr>
MySQL如何实现悲观锁? ok
Atomic原子类
内存和外存的区别，读写速度相差多少数量级
怎么保证DB里面的数据不会被修改
数据库索引引擎为什么用B+树，和B树区别在哪，为什么不用红黑树/AVL树
用户id怎么生成？ ok[here](https://segmentfault.com/a/1190000023588832)
socket编程的流程（服务端、客户端）  ok

网络IO模型有几种，分别是什么（阻塞IO、非阻塞IO、IO多路复用、信号IO、异步IO，详细介绍）[h](https://matt33.com/2017/08/06/unix-io/) ok

进程和线程在应用上的区别，机制上的区别，什么场景选择哪种，为什么？
共享内存访问是在用户态还是内核态
用户态线程是什么

socket是什么? ok
- 所谓套接字(Socket)，就是对网络中不同主机上的应用进程之间进行双向通信的端点的抽象。一个套接字就是网络上进程通信的一端，提供了应用层进程利用网络协议交换数据的机制

动态库和静态库[here](https://www.cnblogs.com/skynet/p/3372855.html)

智能指针内部如何释放对象以及指针如何变动ok
shared_ptr的引用计数如何实现的ok

段页式分配 ok

b,b++[here](https://segmentfault.com/a/1190000020416577)
简述 IO 多路复用？
DNS里的协议
http1.1与http2.0区别[1](https://www.jianshu.com/p/63fe1bf5d445) [2](https://segmentfault.com/a/1190000016496448) [2](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/232) [3](https://vue3js.cn/interview/http/1.0_1.1_2.0.html#%E4%B8%80%E3%80%81http1-0)
- Http1.1 流水线和队头阻塞
	- 客户端首次接受的响应常常不能完全渲染。相反，它包含一些其他需要的资源。 因此，客户端必须发出一些其他请求。 Http1.0客户端的每一个请求必须重新连接，这是非常耗时和资源的。
	- Http1.1 通过引入长连接和流水线技术处理了这个问题。 通过长连接，http1.1假定这个tcp连接应该一直打开直到被通知关闭。 这就允许客户端通过同一连接发送多个请求。不巧的是，这优化策略有个瓶颈。当一个队头的请求不能收到响应的资源，它将会阻塞后面的请求。这就是知名的队头阻塞问题。虽然添加并行的tcp连接能够减轻这个问题，但是tcp连接的数量是有限的，且每个新的连接需要额外的资源。
	- 


pagecache[1](https://cloud.tencent.com/developer/article/1848933) [2](https://blog.csdn.net/damontive/article/details/80552566) [3](https://blog.csdn.net/xiaofei0859/article/details/75106857?utm_medium=distribute.pc_relevant.none-task-blog-2~default~baidujs_baidulandingword~default-0.no_search_link&spm=1001.2101.3001.4242)

0地址[1](https://www.zhihu.com/question/381334088)
DNS[1](https://blog.csdn.net/sisteran/article/details/119314837)
[SPDY协议](https://baike.baidu.com/item/SPDY/3399551)
> 是Google开发的基于TCP的会话层 [1]  协议，用以最小化网络延迟，提升网络速度，优化用户的网络使用体验。SPDY并不是一种用于替代HTTP的协议，而是对HTTP协议的增强。新协议的功能包括数据流的多路复用、请求优先级以及HTTP报头压缩。


TCP连接数[1](https://blog.csdn.net/weixin_44673534/article/details/119851044?utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7Edefault-2.no_search_link&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7Edefault-2.no_search_link) [2](https://cloud.tencent.com/developer/article/1768585) [3](https://www.zhihu.com/question/361111920)
tls和ssl握手

给定 a、b 两个文件，各存放 50 亿个 URL，每个 URL 各占 64B，内存限制是 4G。请找出 a、b 两个文件共同的 URL [1](https://www.cnblogs.com/aspirant/p/7154551.html)

分段锁

[锁](https://www.zhihu.com/question/66733477/answer/1267625567)

Innodb 事务隔离级别和锁的关系是？如何预防死琐？
[ans1](https://tech.meituan.com/2014/08/20/innodb-lock.html) [1](https://cloud.tencent.com/developer/news/305510) [2](http://learn.lianglianglee.com/%E4%B8%93%E6%A0%8F/%E6%9E%B6%E6%9E%84%E8%AE%BE%E8%AE%A1%E9%9D%A2%E8%AF%95%E7%B2%BE%E8%AE%B2/10%20%20%E5%A6%82%E4%BD%95%E5%9B%9E%E7%AD%94%20MySQL%20%E7%9A%84%E4%BA%8B%E5%8A%A1%E9%9A%94%E7%A6%BB%E7%BA%A7%E5%88%AB%E5%92%8C%E9%94%81%E7%9A%84%E6%9C%BA%E5%88%B6%EF%BC%9F.md)

[metadata lock](https://segmentfault.com/a/1190000022883552)
mysql数据库事务 ACID 是如何实现的？ [1](https://www.cnblogs.com/kismetv/p/10331633.html)


MySQL中锁的种类
[1](https://blog.csdn.net/qq_44766883/article/details/105879308) [2](https://blog.csdn.net/zhaoliang831214/article/details/89429334?utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7Eessearch%7Evector-11.no_search_link&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7Eessearch%7Evector-11.no_search_link) [3](https://database.51cto.com/art/201910/604421.htm) [4](http://mysql.taobao.org/monthly/2016/01/01/) [5](https://xie.infoq.cn/article/a9d6332f79cd7c68b260804e4)

网络编程 [1](https://834810071.github.io/2021/03/15/%E7%BD%91%E7%BB%9CIO/#more)
[如何深刻理解Reactor和Proactor？ - 知乎](https://www.zhihu.com/question/26943938)

[https进行SSL认证的全过程](https://blog.csdn.net/qq_40733949/article/details/93405054)

