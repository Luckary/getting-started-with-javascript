### Lesson one 

##### 1 类比代码执行流程

写代码---编译器---解释器---输出

写代码就像我们去银行申请信用卡去填写申请单

调用内置库就像我们申请信用卡时，在银行里面用到的复印，拍照，查询逾期，外国入境查询等的内部服务

调用第三方库就像我们申请信用卡时，要去公安局开XXX证明等等

预处理就像我们把申请单交上去后，工作人员检查有没有格式错误，错别字，信息准确性的过程

执行就像是我们的表单被工作人员拿去核对征信，核对资格的过程

输出，就像最后的通过或者驳回

#### 2 运行环境

相当于银行的开户环境，普通开户环境，VIP开户环境，提供一整套服务，包含需要用到的打印，复制等的内部服务，检查申请单和核对申请单，执行

就像一个婴儿活在世上，他需要的环境就是爸爸，妈妈，衣服，奶粉，家，自然环境超市，医院，玩具，游乐场，婴儿不需要上学。。。

就像一个小学生活在世上，他需要的环境就是爸爸，妈妈，超市，学校，医院，游戏，家，自然环境，衣服，体育馆，而不需要玩具，游乐场

不同的人活着需要不同的环境

运行环境就是我们干事请时需要的环境，没有这个环境就不行，浏览器运行环境和Nodejs运行环境不同，因为干的事情不同，一个是负责前端，一个是负责后端，不过他们的核心V8引擎是相同的，还有都有JS内置对象，因为都用到JavaScript

我们重点要关注库

#### 3 V8引擎

相当于申请信用卡时服务我们的那两个工作人员，负责预处理和执行，掌握业务的核心

#### 4 编译器/解释（执行）器

编译器相当工作人员1是负责预处理的，检查代码的语法，格式，准确性，优化代码，生成编译文件

解释器是相当于工作人员2用来解释代码，执行代码的，然后输出结果

#### 5 内置库

相当于银行内部的打印，拍照等内部服务，是内置在JS里面的服务

#### 6 第三方库

相当于银行外面的警察局，公交站，饭店等，我们会用到的服务，如申请信用卡时，需要出生证明，那么就需要到警察局去拿证明，第三方库就像这样，提供额外的，在银行外面的，围绕申请信用卡的我们需要的服务。

#### 7学习JavaScript的方向

1 初学者忽略V8引擎

2 学会使用JavaScript来编程，要会调用库完成自己的需求---“掌握编程语言，用编程方式调用服务来完成自己的需求“

3 了解库，要会用---“了解和掌握重要的服务能力，使其能服务自己的业务。”

4 深入了解不同的库，思考不同库之间存在的差异，思考他们的价值到底在哪里--- “善于比较服务/技术之间的差异性，用最好的方式实现自己的业务” “任何一个东西产生，都有它自己的价值”

聚焦在库和写代码上。


