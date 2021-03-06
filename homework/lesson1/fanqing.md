# 第一课作业

经过好几天逐渐加码的预热练习，JS同学的学习热情都已被调动起来，17年8月8日，我们的第一次正式课开课。

第一课是Javascript的概况讲解课，并同时老师很有心的与初学者进行了学习方法的探讨，对如何利用这门课、该如何学习、该如何提高以及该怎么进阶给出了建议与方向，力求让我们的学习更加高效、更多获益。
开始我的学习与理解~

对于初期接触编程的人来说，直接讲代码设计流程、执行流程、框架等都太抽象，老师采用了类比的方式进行代码执行流程的讲解，由现实场景引向抽象世界。

### 以银行开户流程作为类比说明：

有开户需求的客户在银行内使用银行提供的复印、拍照等服务完成申请所需资料准备，提交至银行窗口，窗口服务人员受理后，由负责审查的人员对简单的填写格式、准确性问题进行检查预处理（不是每个银行都如此），预处理检查通过的后，有权限的工作人员核对征信及资格，通过的给予客户发卡，未通过的给予驳回。窗口服务人员的内部工作是整个开户业务的核心部分。对于客户来说只需要与窗口服务人员对接沟通，保证了客户的服务感知。

JS的代码执行流程与之类似，程序员通过调用内置服务功能，编写提交符合业务需求的代码至JS代码执行的核心（V8引擎），内部一系列处理后输出执行结果。

针对不同的客户，还可以区分出普通客户与VIP客户，这时会采用不同的流程——普通柜台以及VIP柜台，也就是不同的业务环境，与之类似，JS也有针对不同类业务需求的不同运行环境。

### JS的运行环境框架：

运行环境（含两类）、第三方库、JS代码。

#### 两类运行环境分别是：

1.浏览器运行环境；2.Node运行环境。总体看两个环境均由V8引擎（核心）、内置服务、第三方库以及JS代码构成。

为了更好的理解“环境”的概念，同样的，用婴儿与学生的生活环境不同进行类比，有助对于运行环境差异的理解。

细分看两个运行环境，相同在于：均有V8引擎、JS内置对象、JS代码以及某些第三方库，不同在于：其他内置服务库的不同，浏览器运行环境内置库有HTTP、WebAPI等，Node运行环境内置库仅有Node API，以及一些第三方库的不同。

#### V8引擎：

是一个可执行代码的黑盒，它发挥着编译器/解释（执行）器的功能，每条代码在需要执行时都可以进行编译，翻译成机器语言进行执行。相对C、C++等编译型语言（需要整体编译完成后才能执行），开发效率高但运行效率低。

#### 编译器/解释（执行）器：

功能包含分析词法、分析语法、分析语义、优化代码、解释代码、执行代码。JS是解释性语言，以上功能合为一体。编译型语言是将后面的“解释代码”“执行代码”需要提交至单独的执行器来完成。

#### 内置库：

即内置服务库，包含JS内置对象以及其他的内置服务。这些由运行环境内置，基本运行环境启用之后，可以直接调用，就像银行内的复印服务、拍照服务、查询逾期服务等。

#### 第三方库：

是为了提供更便利、更丰富的开发应用功能，类似银行的警务服务、理财公司专柜服务等，就像分工协作的社会，各自发挥所长。在内置库功能不能满足的情况下，我们学会充分运用第三方库，会事半功倍。JS的浏览器运行环境的第三方库有jQuery、Vue、AngularJS、React等，JS的Node运行环境的第三方库有Express、Koa、Webpack、Promise等。
