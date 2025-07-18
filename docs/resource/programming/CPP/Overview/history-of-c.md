---
comments: true
---
# C++的历史

[C++语言](https://www.geeksforgeeks.org/c-plus-plus/)是一种[面向对象编程语言](https://www.geeksforgeeks.org/object-oriented-programming-in-cpp/)，它结合了低级语言和高级语言的特点——即中级语言。该编程语言由丹麦计算机科学家比亚内·斯特劳斯特鲁普（Bjarne Stroustrup）在贝尔电话实验室（现称诺基亚贝尔实验室）创建、设计和开发，地点在新泽西州的穆雷山。他希望有一种灵活且动态的语言，与C语言相似，但增加了主动类型检查、基本继承、默认函数参数、类、内联等特性，因此推出了C++（即“C与类”）。

**C++最初被称为“C with classes”，并于1983年更名为C++。++是编程中表示加一的简写，因此C++大致意味着“比C高一个级别”。**



- C++编程语言的踪迹可以追溯到**1979年**，当时**比亚内·斯特劳斯特鲁普**正在为其博士论文进行一些开发。在所有的编程语言中，斯特劳斯特鲁普接触过的一个语言是**Simula**，正如其名字所示，这是一种主要用于模拟的语言。Simula 67语言——这是斯特劳斯特鲁普所使用的变体——被认为是支持面向对象编程范式的首个语言。斯特劳斯特鲁普发现这种范式对软件包开发很有帮助，但Simula语言在实际应用中速度过慢。

- 不久之后，他开始开发“**C with Classes**”，顾名思义，它旨在成为C语言的一个超集。他的主要目标是将他创建的高级面向对象编程特性引入C语言。那时，C语言因其灵活性、可移植性和紧凑性而广受尊重，同时又不牺牲速度或低级实用性。他的编程语言包括内联、基本继承、默认函数参数、类以及可靠的类型检查，同时保留了C语言的所有功能。

- 第一个C with Classes编译器被称为**Cfront**，它源自一个名为**CPre**的C编译器。Cfront是一个旨在将C with Classes代码转换为通用C的程序。一个值得注意的有趣点是，Cfront主要是用C with Classes编写的，使其成为一个自我托管的编译器（即能够编译自身的编译器）。Cfront在1993年被弃用，因为将新功能（主要是C++异常处理）集成进去变得困难。然而，Cfront对未来编译器的实现以及UNIX操作系统产生了重大影响。

- 在1983年，这门语言的名称从C with Classes改为C++。在C语言中，++运算符用于递增变量，这也反映了斯特劳斯特鲁普对这门编程语言的看法。此时，语言新增了多个重要特性，其中最显著的包括虚函数、函数重载、带有const关键字的引用，以及通过两个正斜杠（这是从语言**BCPL**中借鉴的特性）实现的单行注释。

- 1985年，Stroustrup的关于C++的著作**《The C++ Programming Language》**出版并发布。同年，C++作为商业产品正式推出，标志着其商业化的开始。尽管该编程语言尚未正式标准化，但这本书成为了一个重要的参考资料。1989年，编程语言进行了更新，加入了保护和静态成员，以及从多个类和类别中继承的功能。

- 1990年，《The Annotated C++ Manual》作为参考资料发布。就在同一年，Borland的**Turbo C++编译器**也作为商业产品推出。Turbo C++添加了大量其他库，对C++的发展产生了重大影响。尽管Turbo C++的最后稳定版本在2006年发布，该编译器仍然被广泛使用。

- 1998年，C++标准咨询与标准委员会发布了第一个国际标准**C++ ISO/IEC 14882:1998**，非正式称为C++98。《The Annotated C++ Manual》被认为对标准的发展有重大影响。1979年开始构建的标准模板库（也称为[Standard Template Library](https://www.geeksforgeeks.org/cpp-stl-tutorial/)）也被纳入其中。2003年，委员会对1998年的标准进行了修订，修改后的语言被称为**C++03**。

- 2005年，同一C++委员会发布了技术报告（称为**TR1**），详细说明了他们计划在最新C++标准中引入的各种选项。由于预计新标准将在十年结束前发布，该标准被非正式地称为**C++0x**。讽刺的是，这一新标准直到2011年中期才完成。在此之前，许多技术报告被发布，一些编译器开始添加对新功能的实验性支持。

- 2011年中，新C++标准（称为C++11）最终完成。

  **Boost库**

  Boost库项目对新标准产生了重大影响，一些新的模块直接来源于Boost库。包括的若干新特性有：

  1. 新的for循环语法，提供了类似于某些语言中的[foreach循环](https://www.geeksforgeeks.org/g-fact-40-foreach-in-c-and-java/)的实用性。
  2. 标准线程库（直到2011年，C和C++都缺乏此功能）。
  3. 可变参数模板（Variadic templates）。
  4. 自动类型推导（AUTO）关键字。
  5. 新的工具类别和类。
  6. 新的C++时间库，支持原子操作。
  7. 完整的组织库。
  8. 正则表达式支持。
  9. 对联合体（unions）和数组初始化列表（array-initialization lists）的更高支持。

  - [C++20](https://www.geeksforgeeks.org/features-of-c-20/) 是C++的最新版本。更现代和先进的C++版本正在发布，即C++23。
  - **根据TIOBE指数2019年的最新研究，C++仍然是第三大最流行的编程语言**，仅次于Java和C，超越了Python。所有的功劳归于新发布的C++11版本，该版本据用户反馈使C++变得更加稳健、安全、更简单且更具表现力。

  Bjarne Stroustrup在C++方面做出了卓越的贡献。C是一种低级编程语言，因此不具备类的概念。它没有许多能使编程更为便利的特性，尽管它是最快的语言（汇编语言更快，但编程结构并不是你考虑的事情），Bjarne Stroustrup所做的是引入了面向对象的部分，将代码视为实际对象。C++的美妙之处在于它既拥有C的速度，又是一种高级编程语言，因而结合了两者的优点。然而另一方面，C++对初学者来说较为困难，而且用Python编写相同的代码可能只需要C++所需时间的四分之一。

  **C++的特点：** C++的五大最佳特点是：

  1. 在竞赛编程中，C++是使用最广泛的语言。大多数高评分的程序员通常使用C++进行加密，你可以在任何在线网站上看到它。
  2. [STL](https://www.geeksforgeeks.org/the-c-standard-template-library-stl/)（标准模板库）：对于了解C并且仍在编写冒泡排序代码的人来说，它是一个极大的时间节省工具。
  3. [运算符重载](https://www.geeksforgeeks.org/operator-overloading-c/)。
  4. [多重继承](https://www.geeksforgeeks.org/multiple-inheritance-in-c/)。许多语言不具备此功能。
  5. 能够模块化代码，[封装](https://www.geeksforgeeks.org/encapsulation-in-c/)，以及[多态](https://www.geeksforgeeks.org/polymorphism-in-c/)。

  **C++版本历史的总结表：** 

|            版本            | 发布日期 |                           主要变化                           |
| :------------------------: | :------: | :----------------------------------------------------------: |
| C++98 (ISO/IEC 14882:1998) | 1998.10  |                          第一个版本                          |
| C++03 (ISO/IEC 14882:2003) |  2003.2  |           引入了值初始化（value initialization）。           |
|           C++11            |  2011.8  | 引入了Lambda表达式、委托构造函数、统一初始化语法、nullptr、自动类型推导和decltype、右值引用等。 |
|           C++14            |  2014.8  | 引入了多态Lambda表达式、数字分隔符、泛化Lambda捕获、变量模板、二进制整数字面量、引号字符串等。 |
|           C++17            | 2017.12  | 引入了折叠表达式、十六进制浮点字面量、u8字符字面量、带初始化器的选择语句、内联变量等。 |
|           C++20            |  2020.3  | 此更新扩展了C++，增加了检查程序实体（如变量、枚举、类及其成员、Lambda及其捕获等）的功能。 |
|           C++23            | 未来发布 |                  C++标准的下一个主要修订版                   |

 