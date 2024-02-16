# 第1章 面向对象
java是面向对象语言，表现为java完全支持面向对象的三种基本特征：继承、封装、多态
最小程序单位是类
对象：从现实世界中客观存在的事物
面向对象方式组成部分：OOA(面向对象分析)、OOD(面向对象设计)、               OOP（面向对象编程）
UML（统一建模语言）描述
软件开发主流的开发方式：结构化开发方式（C、Basic）、面向对象开发方式C++,Java
## 结构化程序设计
结构化程序按功能来分析系统需求，自顶而上、逐步求精、模块化
面向功能的程序设计方法
面向数据流的处理方式：每个功能处理、接收、分析数据
结构化程序设计最小程序单元为函数
## 程序的三种基本结构
顺序、选择、循环
## 面向对象程序设计
对现实世界客观存在的事物（对象）出发构造软件系统，并以对象为中心思考，抽取事物的本质特点为类，作为基本构成单元
**成员变量（状态数据）+方法（行为）=类**
面向对象的程序单位是类
面向过程的程序单位是函数
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683210112819-8d29e0d1-1da9-4d8f-ab4c-b20b3cd349b7.png#averageHue=%23f3f2f2&clientId=u0c96f3b3-58e7-4&from=paste&height=306&id=u2076a9f9&originHeight=382&originWidth=751&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=9858&status=done&style=none&taskId=ue5e82331-b45c-401c-a7eb-095e7e857ce&title=&width=600.8)
基于对象没有继承和多态，而面向对象有
## UML语言
最常用的UML图包括用例图、类图、组件图、部署图、顺序图、活动图、状态机图
1、用例图：
描述系统提供的系列功能（可视化）
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683276144721-455946f2-ee3a-4aad-a71d-26d7458511dc.png#averageHue=%23f8f8f8&clientId=u56d5d3d8-aa21-4&from=paste&height=291&id=u1b3a5d53&originHeight=499&originWidth=1003&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=88464&status=done&style=none&taskId=u865e46a6-6da5-44bb-83b5-01f8f8984a2&title=&width=584)
2、类图：
包含实体和实体间的关联
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683276176217-a0304568-4299-4733-b122-2df3bce59ed9.png#averageHue=%23ded5cd&clientId=u56d5d3d8-aa21-4&from=paste&height=237&id=u6aa8e5c2&originHeight=296&originWidth=906&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=78353&status=done&style=none&taskId=ue5475c2e-a473-4e6a-aae0-f2b37bd12b6&title=&width=724.8)
类与类之间的关系：
（1）关联：类中的某个属性引用到另外一个实体。具有方向性：仅能从一个类单向访问另一个类，为单向关联；如果两个类之间可以互相访问，为双向关联。
包括聚合和组合
（2）泛化：即继承，是指子类是一种特殊的父类
（3）依赖：一个类的改动导致另一个类的改动，则两个类之间存在依赖
3、组件图：
提供系统的物理试图，显示系统中的软件对其他软件组件的依赖关系
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683276211357-9af9c8e7-5e95-436d-b71a-6c45232cd1b0.png#averageHue=%23f4f4f4&clientId=u56d5d3d8-aa21-4&from=paste&height=427&id=u82908b6b&originHeight=635&originWidth=904&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=76636&status=done&style=none&taskId=ue1c1c467-d88e-4793-b2ea-d1add49e522&title=&width=607.2000122070312)
4、部署图
描述软件系统如何部署到硬件环境中，显示软件系统不同组件在何处物理运行，如何通信
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683276243590-f088c0f3-444b-454a-a7e0-665fdb4d572a.png#averageHue=%23eeeeee&clientId=u56d5d3d8-aa21-4&from=paste&height=343&id=ua88166cb&originHeight=531&originWidth=993&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=139901&status=done&style=none&taskId=u58e4dcb2-a3ff-4955-998b-5652561062e&title=&width=642)
5、顺序图
描述对象之间的交互、描述消息及时间顺序
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683276263897-9b9169f0-d02d-4348-8dcd-3b238d089763.png#averageHue=%23edece7&clientId=u56d5d3d8-aa21-4&from=paste&height=397&id=u8be8d523&originHeight=496&originWidth=906&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=182334&status=done&style=none&taskId=ud7cba3e2-b8e5-417a-b458-e21ab4d40d7&title=&width=724.8)
6、活动图
描述用例内部活动或方法的流程，除去并行活动描述，类似流程图
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683276278682-7a917a84-1adb-4762-82de-52ea62db7bb3.png#averageHue=%23fdfdfc&clientId=u56d5d3d8-aa21-4&from=paste&height=484&id=uae6acb4b&originHeight=605&originWidth=924&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=217102&status=done&style=none&taskId=ud13df29d-a5dc-40f5-9858-b765ca94ded&title=&width=739.2)
7、状态机图
描述某一对象生命周期中需要关注的不同状态
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683276296464-25c2dc22-bef6-47a0-aecf-e66bb8878a73.png#averageHue=%23fefefd&clientId=u56d5d3d8-aa21-4&from=paste&height=425&id=u1d55670b&originHeight=531&originWidth=804&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=110869&status=done&style=none&taskId=u55b735e2-b23a-40a4-a17f-d2d56cd41b8&title=&width=643.2)
## 面向对象特征
除基本数据类型外，一切都是对象。
对象具有状态和操作，对象实现了数据和操作之间的结合
java里的对象具有唯一性
java语言不直接访问对象，通过对对象的引用来操作对象
对象是实际存在的该类事物的个体，也被称作实例
对象的抽象化是类，类的具体化是对象，类的实例是对象
类规定了某类对象所共同具有的数据和行为特征
java是强类型语言。 强类型语言：① 所有 的变量必须先声明、后使用；② 指定类型的变量只能接受类型与之匹 配的值  
变量---成员变量---静态变量（类变量）
    ---实例变量
---局部变量
# 第2章 数据类型和运算符
## 注释
###  文档注释  ：
 1、过程：如果 编写Java源代码时添加了合适的文档注释，然后通过JDK提供的 javadoc工具可以直接将源代码里的文档注释提取成一份系统的API文 档。  
2、API: API文档就是用以说明这些应用程序接口的文档。对于Java语言 而言，API文档通常详细说明了每个类、每个方法的功能及用法等  
 3、格式：文档注释以斜线后紧跟两个星号（/**）开始，以星号后紧跟一个 斜线（*/）结束，中间部分全部都是文档注释，会被提取到API文档 中。
  ![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683277202017-fee66e48-11f0-446d-8219-01c54d5e312c.png#averageHue=%23e3e3e3&clientId=uc40827c6-3208-4&from=paste&height=534&id=uc713d79c&originHeight=667&originWidth=835&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=138174&status=done&style=none&taskId=u5a47efe5-0ec6-4e04-b1e0-172addcbfe4&title=&width=668)
## 标志符和关键字
标志符规则： 
Java语言 的标识符必须以字母、下画线（_）、美元符（$）开头，后面可以跟 任意数目的字母、数字、下画线（_）和美元符（$）。此处的字母并 不局限于26个英文字母，而且可以包含中文字符、日文字符等。  
## 数据类型分类
### 1、数据类型
 Java语言支持的类型分为两类：基本类型（Primitive Type）和 引用类型（Reference Type）。
**基本类型**包括boolean类型和数值类型。数值类型有整数类型和浮 点类型。整数类型包括byte、short、int、long、char，浮点类型包 括float和double。  
 **引用类型**包括类、接口和数组类型，还有一种特殊的null类型。 所谓引用数据类型就是对一个对象的引用，对象包括实例和数组两 种。  
### 2、整型
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683277866140-f44570d3-05e7-4f42-890c-ad771069f9ea.png#averageHue=%23dfdfdf&clientId=uc40827c6-3208-4&from=paste&height=218&id=ue99957b2&originHeight=272&originWidth=764&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=89698&status=done&style=none&taskId=u824c79bb-19ad-45af-a17d-c3e2e66e473&title=&width=611.2)
 计算机以补码的形式保存所有的整 数。  
### 3、浮点型
 字符型值有如下三种表示形式。
 ➢ 直接通过单个字符来指定字符型值，例如'A'、'9'和'0'等。 
➢ 通过转义字符表示特殊字符型值，例如'\n'、'\t'等。
 ➢ 直接使用Unicode值来表示字符型值，格式是'\uXXXX'，其中 XXXX代表一个十六进制的整数。  
 只有浮点类型的数值才可以使用科学计数法形式 表示。  
 Java还提供了三个特殊的浮点数值：
正无穷大、负无穷大和非 数，用于表示溢出和出错。
 **正 无 穷 大**~~** **~~通 过 Double 或 Float 类 的 POSITIVE_INFINITY 表 示 ；
 **负 无 穷 大 **通 过 Double 或 Float 类 的 NEGATIVE_INFINITY表示，
**非数**通过Double或Float类的NaN表示。
 必须指出的是，所有的正无穷大数值都是相等的，所有的负无穷 大数值都是相等的；而NaN不与任何数值相等，甚至和NaN都不相等。
 注意： 
只有浮点数除以0才可以得到正无穷大或负无穷大，因为Java语 言会自动把和浮点数运算的0（整数）当成0.0（浮点数）处理。如 果 一 个 整 数 值 除 以 0 ， 则 会 抛 出 一 个 异 常 ： ArithmeticException：/by zero（除以0异常）。      
 数值中使用下画线分隔 ，打印时不打印下划线，不影响数值大小
### 4、布尔型
 字符串"true"和"false"不会直接转换成boolean类型，但如果使 用一个boolean类型的值和字符串进行连接运算，则boolean类型的值 将会自动转换成字符串。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683279022101-945b88c8-06de-47eb-92dc-394fa0daa43d.png#averageHue=%239c7e53&clientId=uc40827c6-3208-4&from=paste&height=270&id=u8e86509e&originHeight=338&originWidth=878&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=33764&status=done&style=none&taskId=u57a2dc21-ecde-47b5-bb95-152041f914a&title=&width=702.4)
### 5、var
java10后
 Java是强类型语言，因此Java使用var定义的变 量依然有明确的类型—为局部变量指定初始值时，该变量的类型就确 定下来了。  
## 类型转换
 有两种类型转换方 式：自动类型转换和强制类型转换。  
### 1、自动类型转换
**范围小->范围大**
 当把一个表数范围小的数值或变量直接赋给另一个表数范围 大的变量时，系统将可以进行自动类型转换；否则就需要强制转换  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683279842825-1f23e286-782c-48b0-a592-bd5752fc2f34.png#averageHue=%23ededed&clientId=uc40827c6-3208-4&from=paste&height=124&id=u38cb8333&originHeight=155&originWidth=683&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=34667&status=done&style=none&taskId=uad404d8a-d541-45f2-8e24-dafc446465c&title=&width=546.4)
 如果希望把基本类型的值转换为对应 的字符串时，可以把基本类型的值和一个空字符串进行连接。  
### 2、强制类型转换
**格式：小类型 变量=（小类型）变量**
**将字符串 转换成基本类型**：
 在通常情况下，字符串不能直接转换为基本类型，但通过基本类 型对应的包装类则可以实现把字符串转换成基本类型。例如，把字符 串转换成int类型，则可通过如下代码实现：  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683280127554-8e615062-f98c-4f00-af12-0ac5ab0db15d.png#averageHue=%23dddddd&clientId=uc40827c6-3208-4&from=paste&height=66&id=ub9f7347e&originHeight=83&originWidth=469&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=20838&status=done&style=none&taskId=u82368ce2-5ea8-4234-b7a3-104ab3b150c&title=&width=375.2)
 Java 为 8 种 基 本 类 型 都 提 供 了 对 应 的 包 装 类 ： boolean 对 应 Boolean、byte对应Byte、short对应Short、int对应Integer、long对 应Long、char对应Character、float对应Float、double对应Double， 8个包装类都提供了一个parseXxx(String str)静态方法用于将字符串 转换成基本类型。  
### 3、表达式类型自动提升
 ➢ 所有的byte类型、short类型和char类型将被提升到int类型。
 ➢ 整个算术表达式的数据类型自动提升到与表达式中最高等级操 作数同样的类型。操作数的等级排列如图3.10所示，位于箭头 右边类型的等级高于位于箭头左边类型的等级。  
## 直接量（字面值）
 并不是所有的数据类型都可以指定直接量，能指定直接量的通常 只有三种类型：基本类型、字符串类型和null类型。  
 null类型是一种特殊类型，它只有 一个值：null，而且这个直接量可以赋给任何引用类型的变量，用以 表示这个引用类型变量中保存的地址为空，即还未指向任何有效对 象。  
 String类型的直接量不能赋给其他类型的变量，null类型的直接 量可以直接赋给任何引用类型的变量，包括String类型。boolean类型 的直接量只能赋给boolean类型的变量，不能赋给其他任何类型的变 量。
## 运算符  
 Java语言中的运算符可分为如下几种。
 ➢ 算术运算符
 ➢ 赋值运算符 
➢ 比较运算符 
➢ 逻辑运算符 
➢ 位运算符 
➢ 类型相关运算符  
### 算术运算符
 0或0.0对零以外的任何数求余都将得到0或0.0。  
 Math类下包含了丰富的静态方法，用于完成各种复杂的数学运 算。  
 注意： 
+除可以作为数学的加法运算符之外，还可以作为字符串的连接 运算符。-除可以作为减法运算符之外，还可以作为求负的运算符。  
### 位运算符
 左移运算符是将操作数的二进制码整体左移指定位数，左移后右 边空出来的位以0填充。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683286016707-8cb44bc9-aaab-4dca-aee6-3c1d5871021d.png#averageHue=%23f1f0f0&clientId=uc40827c6-3208-4&from=paste&height=194&id=u9c49c255&originHeight=243&originWidth=990&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=106611&status=done&style=none&taskId=u24c0e478-a249-4cb8-9836-ba17cd8f7e4&title=&width=792)
 Java的右移运算符有两个：>>和>>>，对于>>运算符而言，把第一 个操作数的二进制码右移指定位数后，左边空出来的位以原来的符号 位填充，即如果第一个操作数原来是正数，则左边补0；如果第一个操 作数是负数，则左边补1。>>>是无符号右移运算符，它把第一个操作 数的二进制码右移指定位数后，左边空出来的位总是以0填充。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683286182226-e7818a81-90f8-43ff-9200-57ed7a75c0b1.png#averageHue=%23f2f1f1&clientId=uc40827c6-3208-4&from=paste&height=194&id=u62ac45aa&originHeight=243&originWidth=984&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=85827&status=done&style=none&taskId=u5a5c3c3e-e7be-420d-b183-b0be10657f9&title=&width=787.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683286237903-2ff11975-af01-4655-8099-44830ee8ddc5.png#averageHue=%23ededed&clientId=uc40827c6-3208-4&from=paste&height=183&id=u7b789817&originHeight=229&originWidth=1003&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=64997&status=done&style=none&taskId=uc1a8d2b9-4c34-4aa1-b99b-544b62fe812&title=&width=802.4)
 进行移位运算时还要遵循如下规则。
 ➢ 对于低于int类型（如byte、short和char）的操作数总是先自 动类型转换为int类型后再移位。
 ➢ 对于int类型的整数移位a>>b，当b>32时，系统先用b对32求余 （因为int类型只有32位），得到的结果才是真正移位的位数。 例如，a>>33和a>>1的结果完全一样，而a>>32的结果和a相同。 
➢ 对于long类型的整数移位a>>b，当b>64时，总是先用b对64求 余（因为long类型是64位），得到的结果才是真正移位的位 数。  
注意：
 当进行移位运算时，只要被移位的二进制码没有发生有效位的 数字丢失（对于正数而言，通常指被移出的位全部都是0），不难发 现左移n位就相当于乘以2的n次方，右移n位则是除以2的n次方。
### 比较运算符
 注意： 基本类型的变量、值不能和引用类型的变量、值使用==进行比 较；boolean类型的变量、值不能与其他任意类型的变量、值使用== 进行比较；如果两个引用类型之间没有父子继承关系，那么它们的 变量也不能使用==进行比较。    
 ➢ &&：与，前后两个操作数必须都是true才返回true，否则返回 false。 
➢ &：不短路与，作用与&&相同，但不会短路。  
 ➢ ||：或，只要两个操作数中有一个是true，就可以返回true， 否则返回false。 ➢ |：不短路或，作用与||相同，但不会短路。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683286602918-be686f8f-fda6-4db6-a3ed-a5151b49979f.png#averageHue=%23e9e9e8&clientId=uc40827c6-3208-4&from=paste&height=427&id=u44805f8b&originHeight=534&originWidth=989&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=136663&status=done&style=none&taskId=u9171c506-763e-4a65-8019-71f32b4872e&title=&width=791.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683286616926-cccbfff8-59cf-4b63-9118-a8c57309748d.png#averageHue=%23ebeae8&clientId=uc40827c6-3208-4&from=paste&height=486&id=u1fd96068&originHeight=608&originWidth=978&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=230136&status=done&style=none&taskId=u64adada7-1790-4452-b32b-3cdb7edd179&title=&width=782.4)
### 运算符的结合性和优先级
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683286817025-fd104f90-c946-4e41-bde8-105503396d1c.png#averageHue=%23f2f2f2&clientId=uc40827c6-3208-4&from=paste&height=654&id=udfdd60d3&originHeight=818&originWidth=986&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=124604&status=done&style=none&taskId=u3bcb7096-8504-463d-92bf-e9f55c9459f&title=&width=788.8)

# 第3章 流程控制与数组
## 顺序结构
## 分支结构
1、if
 在使用if...else语句时有一条基本 规则：总是优先把包含范围小的条件放在前面处理。如age>60和 age>20两个条件，明显age>60的范围更小，所以应该先处理age>60的 情况。 
2、switch
 和if语句不同的是，switch语句中各case标签后代码块的开始点 和结束点非常清晰，因此完全可以省略case后代码块的花括号。  
 注意：
 使用switch语句时，有两个值得注意的地方：
第一个地方是 switch语句后的expression表达式的数据类型只能是byte、short、 char、int四种整数类型，String（从Java 7开始支持）和枚举类 型；
第二个地方是如果省略了case后代码块的break;，将引入一个 陷阱  
## 循环结构
 do while循环的循环条件后必须有一个分 号，这个分号表明循环结束。  
## 控制循环结构
### 直接控制外层循环 outer：
 break语句不仅可以结束其所在的循环，还可以**直接结束其外层循环。**此时需要在break后紧跟一个标签，这个标签用于标识一个外层循 环。  
 Java中的标签就是一个紧跟着英文冒号（:）的标识符。与其他语 言不同的是，Java中的标签只有放在循环语句之前才有作用。例如下 面代码。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683287881771-8423cbc4-3e7a-46ef-b8a4-6c5811429cb9.png#averageHue=%23796646&clientId=ud43e6acf-721b-4&from=paste&height=594&id=u13ea356e&originHeight=743&originWidth=886&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=84136&status=done&style=none&taskId=u56d6b207-fae1-4fdf-841f-c3951106bc4&title=&width=708.8)
 注意： 通常紧跟break之后的标签，必须在break所在循环的外层循环 之前定义才有意义。  
continue outer
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683287961814-af8cc0cf-c3eb-4fb0-abd9-d968ab66b30e.png#averageHue=%237f6946&clientId=ud43e6acf-721b-4&from=paste&height=677&id=u9eadfd7b&originHeight=846&originWidth=875&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=85110&status=done&style=none&taskId=ua994d4fc-4ade-427f-b3d4-eb1c53c5770&title=&width=700)
## 数组
 Java的数组既可以存储基本类型的数据，也可以存储引用类型的 数据，只要所有的数组元素具有相同的类型即可。 
数组也是一种数据类型，它本身是一种引用类 型。例如int是一个基本类型，但int[]（这是定义数组的一种方式） 就是一种引用类型了。  
### 1、定义数组
格式：
type[] arrayName;
type arrayName[];
数组是一种引用类型变量，使用它定义一个变量时，仅仅表示定义了一个引用变量，但还未指向任何有效的内存，因此数组只有初始化后才能使用
### 2、数组初始化
 ➢ **静态初始化：**初始化时由程序员显式指定每个数组元素的初始 值，由系统决定数组长度。 
格式：arrayName=new type[]{element1,element2,element3...}
type[] arrayName=new type[]{element1,element2,element3...}
Tip:前者与后者type类型一致，或后者是前者的子类
➢ **动态初始化：**初始化时程序员只指定数组长度，由系统为数组 元素分配初始值。  
格式：arrayName=new type[length];
 指定初始值时，系统按如下规则分配初始值。
 ➢ 数组元素的类型是基本类型中的整数类型（byte、short、int 和long），则数组元素的值是0。 
➢ 数 组 元 素 的 类 型 是 基 本 类 型 中 的 浮 点 类 型 （ float 、 double），则数组元素的值是0.0。
 ➢ 数组元素的类型是基本类型中的字符类型（char），则数组元 素的值是'\u0000'。
 ➢ 数组元素的类型是基本类型中的布尔类型（boolean），则数 组元素的值是false。
 ➢ 数组元素的类型是引用类型（类、接口和数组），则数组元素 的值是null。  
 注意：
 不要同时使用静态初始化和动态初始化，也就是说，不要在进 行数组初始化时，既指定数组的长度，也为每个数组元素分配初始 值。  
 注意： 
使用静态初始化简化语法执行初始化的数组不能使用var定义数 组变量。  
### foreach循环
适合遍历数组和集合， 使用foreach循环遍历数组和集合元素时，无须获得数组和集合长 度，无须根据索引来访问数组元素和集合元素  
格式：
for(type variableName:array|collection)
{
//variableName 自动迭代访问每个元素
}
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683289321648-878c131b-f979-4b9d-94fc-ed227ea5d13d.png#averageHue=%23766648&clientId=ud43e6acf-721b-4&from=paste&height=462&id=u62bddae8&originHeight=578&originWidth=848&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=63600&status=done&style=none&taskId=ubb88b9e2-76fb-4e8d-84be-2340a9b7000&title=&width=678.4)
  注意： 
使用foreach循环迭代数组元素时，并不能改变数组元素的值， 因此不要对foreach的循环变量进行赋值。  
## 深入数组
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683289547198-4dafa62c-3b0b-4241-b840-57436580ec26.png#averageHue=%23f9f9f9&clientId=ud43e6acf-721b-4&from=paste&height=445&id=ub4b710c2&originHeight=556&originWidth=954&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=97567&status=done&style=none&taskId=uc27032c6-1e02-402c-b597-7d3db2d7b7e&title=&width=763.2)
多维数组
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683290757778-8977f76f-64ab-4886-8190-e71576a20f2c.png#averageHue=%23f4f4f4&clientId=ud43e6acf-721b-4&from=paste&height=380&id=u9b37d34a&originHeight=475&originWidth=831&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=80103&status=done&style=none&taskId=uc1c3893b-13d5-4d15-ba25-ece874b1d71&title=&width=664.8)
 二维数组是一维数组，其数组 元素是一维数组；三维数组也是一维数组，其数组元素是二维数 组……从这个角度来看，Java语言里没有多维数组。  
java8增强的工具类：
 此处中间有疑惑，下图及之后
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683291491459-243ef5eb-a107-48b6-b888-ef7bf4f29446.png#averageHue=%23f7f4f2&clientId=ud43e6acf-721b-4&from=paste&height=530&id=u05fe410d&originHeight=663&originWidth=906&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=275941&status=done&style=none&taskId=u49377268-0e58-4d15-a17e-fbeba7d99f5&title=&width=724.8)
# 第4章 面向对象（上）
## 类和对象
所有类都是引用类型
static修饰的成员不能访问没有static修饰的成员
 一旦程序员为一个类提供了构造器，系统将不再为该类提供构造 器。  
 Tip: 
实际上在Java世界里属性（由property翻译而来）指 的是一组setter方法和getter方法。比如说某个类有age属性，意味 着该类包含setAge()和getAge()两个方法  
     static修饰的成员表明它属于这个类本身，而不属于该类的单个实例，因为通常把static修饰的成员变量和方法也称为类变量、类方法。 静态成员不能直接 访问非静态成员。  
 static修饰的方法和成员变量，既可通过类来调用，也可通过实 例来调用 ，当它使用实例调用时， 底层依然是使用这些实例所属的类作为调用者。  
通过类调用：
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683462494064-e65cd173-a253-4482-b250-1034352303c1.png#averageHue=%232e2c2c&clientId=u79762b7d-c927-4&from=paste&height=328&id=uca9d599d&originHeight=410&originWidth=554&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=26199&status=done&style=none&taskId=u869588fd-ace9-4f1a-b1d3-610284cf914&title=&width=443.2)
### this
 this作为对象的默认引用有两种情 形。 
➢ 构造器中引用该构造器正在初始化的对象。 
➢ 在方法中引用调用该方法的对象。  
再同一类中某方法调用该类的其他方法，使用this.被调用方法
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683462418485-5655aa7b-5d35-4e0f-8ade-4f2d9ef9ade7.png#averageHue=%23e3e3e3&clientId=u79762b7d-c927-4&from=paste&height=376&id=u89d5ffbe&originHeight=470&originWidth=887&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=86473&status=done&style=none&taskId=u50828fd5-e6ae-4655-8b29-383de7d84db&title=&width=709.6)
  ![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683462210825-128571c6-d5ac-4ee2-959e-36c7e1625047.png#averageHue=%23e4e4e4&clientId=u79762b7d-c927-4&from=paste&height=250&id=u1148c409&originHeight=313&originWidth=669&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=39923&status=done&style=none&taskId=ucfbc0f01-1941-49cc-9cdf-e7df9ba9392&title=&width=535.2)
①run()调用jump()一定需要一个Dog对象，②但不一定需要重新创建一个Dog对象
①没有使用static修饰的成员变量和方法的调用必须使用对象调用②当程序运行run()会提供一个Dog对象，可以直接使用已存在的Dog对象调用this.run()；
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683462570015-8b66c5c2-3b2b-4cc6-9d35-1a190e368163.png#averageHue=%232d2c2b&clientId=u79762b7d-c927-4&from=paste&height=306&id=u6f4dfe8f&originHeight=383&originWidth=452&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=15696&status=done&style=none&taskId=u94120cd0-5680-4d78-b1c0-5e7c2eeeef9&title=&width=361.6)
static 修饰的方法中无法使用this关键字，即无法指向合适的对象
因此static修饰的方法不能访问不适用static修饰的普通成员，静态成员不能直接访问非静态成员
 this在构造器中代表该构造器正在初始化的对象。  
## 方法详解
同一个类的 一个方法调用另外一个方法时，如果被调方法是普通方法，则默认使 用this作为调用者；如果被调方法是静态方法，则默认使用类作为调 用者。也就是说，表面上看起来某些方法可以被独立执行，但实际上 还是使用this或者类来作为调用者 。

### 形参个数可变的方法：
 	如果在定义方法时，在最后一个形参的 类型后增加三点（...），则表明该形参可以接受多个参数值，多个参 数值被当成数组传入。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683465041619-f46c88a1-adb6-4768-a872-8a3176dc1fdb.png#averageHue=%23e4e4e4&clientId=u79762b7d-c927-4&from=paste&height=574&id=ufdaf2373&originHeight=717&originWidth=906&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=151124&status=done&style=none&taskId=ub6dd1003-a0bc-49e2-9130-f9f2ff05c1b&title=&width=724.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683465132237-2fdffa6f-ab3d-4360-9ce9-c3ce027536a9.png#averageHue=%23f0efee&clientId=u79762b7d-c927-4&from=paste&height=203&id=ubaa58264&originHeight=254&originWidth=962&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=83017&status=done&style=none&taskId=u017d091d-3cf9-4dfb-91b6-66af8d9a3d2&title=&width=769.6)
 传给books参数的实参数值无须是一个数组，但如果采用数组形参 来声明方法，调用时则必须传给该形参一个数组  
Tips:
 	个数可变的形参只能处于形参列表的最后。一个方法中最多只 能包含一个个数可变的形参。个数可变的形参本质就是一个数组类 型的形参，因此调用包含个数可变形参的方法时，该个数可变的形 参既可以传入多个参数，也可以传入一个数组。  
方法重载： 如果同一个类中包含了两个或两个以上方法的方法名相同，但形 参列表不同，则被称为方法重载  
## 成员变量和局部变量
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683465902238-83026982-4999-45cc-9e42-30d55caa0fb5.png#averageHue=%23f9f9f9&clientId=u79762b7d-c927-4&from=paste&height=351&id=uf3e16f88&originHeight=439&originWidth=957&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=80005&status=done&style=none&taskId=u4c22d9ab-d332-4625-a9e9-7c93ac341d2&title=&width=765.6)
### 1、成员变量和局部变量
 类变 量从该类的准备阶段起开始存在，直到系统完全销毁这个类，类变量 的作用域与这个类的生存范围相同；而实例变量则从该类的实例被创 建起开始存在，直到系统完全销毁这个实例，实例变量的作用域与对 应实例的生存范围相同。  
 与成员变量不同的是，局部变量除形参之外，都必须显式初始 化。也就是说，必须先给方法局部变量和代码块局部变量指定初始 值，否则不可以访问它们。  
 Java允许局部变量和成员变量同名，如果方法里的局部变量和成 员变量同名，局部变量会覆盖成员变量，如果需要在这个方法里引用 被覆盖的成员变量，则可使用this（对于实例变量）或类名（对于类 变量）作为调用者来限定访问成员变量。
### 2、成员变量的初始化和内存中的运行机制：
 ![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683466367659-2a1bf4bb-6756-4e2a-8126-fef6d3be3353.png#averageHue=%23fafafa&clientId=u79762b7d-c927-4&from=paste&height=362&id=ub3b131ce&originHeight=452&originWidth=882&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=70763&status=done&style=none&taskId=u82241158-21cc-49a9-bddb-b5d1c4f17e3&title=&width=705.6) ![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683466378110-0cbdba09-4d25-4996-b0ca-12f267c72927.png#averageHue=%23f8f8f8&clientId=u79762b7d-c927-4&from=paste&height=353&id=ua2d620ca&originHeight=441&originWidth=899&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=84931&status=done&style=none&taskId=ufde9847c-afc2-41ba-8bb7-24881cc1c86&title=&width=719.2)
 eyeNum类变量并不属于Person对象，它是 属于Person类的，所以创建第一个Person对象时并不需要为eyeNum类 变量分配内存，系统只是为name实例变量分配了内存空间，并指定默 认初始值：null。  
 不管通过哪个Person实例来访问eyeNum类 变量，本质其实还是通过Person类来访问eyeNum类变量时，它们所访 问的是同一块内存。  
### 3、局部变量的初始化和内存中的运行机制：
 	局部变量不属于任何类或实例，因此它总是保 存在其所在方法的栈内存中。  
 	栈内存中的变量无须系统垃圾回收，往往随方法或代码块的运行 结束而结束。  因此，局部变量的作用域是从初始化该变量开始，直到 该方法或该代码块运行完成而结束。因为局部变量只保存基本类型的 值或者对象的引用，因此局部变量所占的内存区通常比较小。 
### 4、变量的使用规则：
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683466819587-1a80fd85-807c-4205-a8d2-edf6c84cac47.png#averageHue=%23e3e3e3&clientId=u79762b7d-c927-4&from=paste&height=263&id=u479c8cc0&originHeight=329&originWidth=886&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=45080&status=done&style=none&taskId=ue3f4f857-63bd-4450-9940-a8e00ee67e1&title=&width=708.8)  对于一个循环变量而言，只需要它在 循环体内有效，因此只需要把这个变量放在循环体内（也就是在代码 块内定义），从而保证这个变量的作用域仅在该代码块内。  
## 隐藏和封装
 	封装（Encapsulation）是面向对象的三大特征之一（另外两个是 继承和多态），它指的是将对象的状态信息隐藏在对象内部，不允许 外部程序直接访问对象内部信息，而是通过该类所提供的方法来实现 对内部信息的操作和访问。  
### 1、访问控制符
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683467347248-b32ac5e1-020b-4906-b9b5-80f1e190d7e1.png#averageHue=%23f1f1f1&clientId=u79762b7d-c927-4&from=paste&height=158&id=u946a44bc&originHeight=198&originWidth=894&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=50324&status=done&style=none&taskId=u851fb685-812a-451c-974b-c9a48865e5c&title=&width=715.2)
private（当前类访问权限）：只能在当前类被访问，适合修饰成员变量，使成员变量隐藏在该类内部
default（包访问权限）：可被相同包下其他类访问
protected（子类访问权限）： 如果一个成员（包括成员变 量、方法和构造器等）使用protected访问控制符修饰，那么这 个成员既可以被同一个包中的其他类访问，也可以被不同包中 的子类访问。  通常使用protected修饰一个方法，是希望其子类重写该方法。
当一个包的子类继承其他包的父类时需要导包
public(公共访问权限)：不同包下无关类也可访问
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683467731243-db3ae405-0221-4aca-8600-c94f8ee4703a.png#averageHue=%23efefef&clientId=u37f4acab-bf3a-4&from=paste&height=198&id=u59925d09&originHeight=248&originWidth=907&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=24389&status=done&style=none&taskId=ubfe853d1-3b78-4383-b2a4-bebb7f18807&title=&width=725.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683116661237-7d893612-88fd-4cd0-978b-9bf1406a62b1.png#averageHue=%23f5f9f7&clientId=uf560a116-711a-4&from=paste&height=554&id=ue1803dba&originHeight=692&originWidth=1488&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=168332&status=done&style=none&taskId=u01acdea5-34aa-4424-bf4a-812fcadc9c5&title=&width=1190.4)
Tip:
 	如果一个Java源文件里定义的所有类都没有使用public修饰， 则这个Java源文件的文件名可以是一切合法的文件名；但如果一个 Java源文件里定义了一个public修饰的类，则这个源文件的文件名 必须与public修饰的类的类名相同。  
 	JavaBean 总是一个封装良好的类。setter和getter方法合起来变成属性，如 果只有getter方法，则是只读属性。  
Tip:
 进行程序设计时，应尽量 避免一个模块直接操作和访问另一个模块的数据，模块设计追求高 内聚（尽可能把模块的内部数据、功能实现细节隐藏在模块内部独 立完成，不允许外部直接干预）、低耦合（仅暴露少量的方法给外 部使用）。  
关于访问控制符的使用，存在如下几条基本原则。
 ➢ 类里的绝大部分成员变量都应该使用private修饰，只有一些 static修饰的、类似全局变量的成员变量，才可能考虑使用 public修饰。除此之外，有些方法只用于辅助实现该类的其他 方法，这些方法被称为工具方法，工具方法也应该使用private 修饰。
 ➢ 如果某个类主要用做其他类的父类，该类里包含的大部分方法 可能仅希望被其子类重写，而不想被外界直接调用，则应该使 用protected修饰这些方法。 
➢ 希望暴露出来给其他类自由调用的方法应该使用public修饰。 因此，类的构造器通过使用public修饰，从而允许在其他地方 创建该类的实例。因为外部类通常都希望被其他类自由使用， 所以大部分外部类都使用public修饰。   
### 2、package、import、import static
 	Java引入了包（package）机制，提供了类的 多层命名空间，用于解决类的命名冲突、类文件管理等问题。  
 如果希望把一个类放在指定的包结构下，应该在 Java源程序的第一个非注释行放置如下格式的代码： 
 package packageName;
Tip:
 	父包和子包在用法上则不存在任何关系，如果父包中 的类需要使用子包中的类，则必须使用子包的全名，而不能省略父 包部分。  
 如果创建处于其他包下类的实例，则在调用构造器时也需要使用 包前缀。例如在lee.HelloTest类中创建lee.sub.Apple类的对象，则 需要采用如下代码  :
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683468854635-a0c0312e-d496-49a7-be70-cc94d1292475.png#averageHue=%23e0e0e0&clientId=ub3db4095-01a3-4&from=paste&height=65&id=u04f21696&originHeight=81&originWidth=505&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=20145&status=done&style=none&taskId=u6abb8ea0-fae6-434e-847a-7aba20678d1&title=&width=404)
 一个Java源文件只 能包含一个package语句，但可以包含多个import语句，多个import语 句用于导入多个包层次下的类。 
使用import语句导入单个类的用法如下：  
import package.subpackage...ClassName;
 使用import语句导入指定包下全部类的用法如下：  
import pavkage.subpackage...*;
上面import语句中的星号（*）只能代表类，不能代表包。因此使 用import lee.*；   而lee包下sub子包内的类则不会被导入。  
导入包后，在该源文件 中使用这些类时就可以省略包前缀，不再需要使用类全名。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683469127133-4478187a-13a1-41bc-ba9b-89b23fe7f282.png#averageHue=%23dfdfdf&clientId=ub3db4095-01a3-4&from=paste&height=182&id=u24fb65f2&originHeight=180&originWidth=507&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=34479&status=done&style=none&taskId=u0bfa1c52-4bc8-462f-831c-de95dcde857&title=&width=513.6000061035156)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683469133976-967add21-a04f-4ce2-99cb-e2d22d6f718e.png#averageHue=%23e1e1e1&clientId=ub3db4095-01a3-4&from=paste&height=192&id=u7b799dd5&originHeight=255&originWidth=701&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=44269&status=done&style=none&taskId=u3ff678fa-1825-435d-873e-acbf2554ed8&title=&width=527.7999877929688)
 注意： 
Java默认为所有源文件导入java.lang包下的所有类，因此前面 在Java程序中使用String、System类时都无须使用import语句来导 入这些类。但对于前面介绍数组时提到的Arrays类，其位于 java.util包下，则必须使用import语句来导入该类。  
如果两个包中的类重名，则在代码使用该类时，需要写类的全名
 静态导入使用import static语句，静态导入也有两种语法，分别 用于导入指定类的单个静态成员变量、方法和全部静态成员变量、方 法，其中导入指定类的单个静态成员变量、方法的语法格式如下：  
import static package.subpackage...ClassName.fieldName|methodName;
 导入指定类的全部静态成员变量、方法的语法格式如下：  
import static package.subpackage...ClassName.*;
 用一句话来归纳import和import static的作用：使用 import可以省略写包名；而使用import static则可以连类名都省略。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683469535848-e58d7826-9d2d-4c2e-bb5c-ff431589d82d.png#averageHue=%23dfdfdf&clientId=ub3db4095-01a3-4&from=paste&height=325&id=u6c254df1&originHeight=406&originWidth=800&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=117370&status=done&style=none&taskId=uf4c7fe42-4e1b-404e-80ad-8a2fe3ab568&title=&width=640)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683469561681-99acfb25-4e84-4c5f-bfa3-2bf3b8771f85.png#averageHue=%23e3e3e2&clientId=ub3db4095-01a3-4&from=paste&height=177&id=u7edc6f30&originHeight=221&originWidth=936&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=115983&status=done&style=none&taskId=u9dffc55d-2b2e-4d26-aba6-fde46a6bdf3&title=&width=748.8)
## 深入构造器
拓：
 	通过new关键字调用 构造器时，构造器也确实返回了该类的对象，但这个对象并不是完全 由构造器负责创建的。实际上，当程序员调用构造器时，系统会先为 该对象分配内存空间，并为这个对象执行默认初始化，这个对象已经 产生了——这些操作在构造器执行之前就都完成了。也就是说，当系 统开始执行构造器的执行体之前，系统已经创建了一个对象，只是这 个对象还不能被外部程序访问，只能在该构造器中通过this来引用。 当构造器的执行体执行结束后，这个对象作为构造器的返回值被返 回，通常还会赋给另一个引用类型的变量，从而让外部程序可以访问 该对象。  
 一旦程序员提供了自定义的构造器，系统就不再提供默认的构造 器  
 如果一个类里提供了多个构造 器，就形成了构造器的重载。 
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683469864497-5c58a7c6-a309-4dde-812b-0dbe2a30a01c.png#averageHue=%23ecebeb&clientId=ub3db4095-01a3-4&from=paste&height=261&id=ue4892d0e&originHeight=326&originWidth=582&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=72012&status=done&style=none&taskId=uf1bdbd29-be90-484d-bf33-e93f66a9e08&title=&width=465.6) 
 为了在构造器B中调用构造器A中的初始化代码，又不会重新创 建一个Java对象，可以使用this关键字来调用相应的构造器。下面代 码实现了在一个构造器中直接使用另一个构造器的初始化代码。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683469887911-551de7b2-0a0a-45d2-a0a2-402298f4311d.png#averageHue=%23e2e2e2&clientId=ub3db4095-01a3-4&from=paste&height=515&id=ue5ccdd40&originHeight=644&originWidth=872&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=143393&status=done&style=none&taskId=ua7e08ba2-553b-43f5-aac4-ba99ebb736c&title=&width=697.6)
## 类的继承
 注意： 
子类只能从被扩展的父类获得成员变量、方法和内部类（包括 内部接口、枚举），不能获得构造器和初始化块。  
 java.lang.Object类是所有 类的父类，要么是其直接父类，要么是其间接父类。因此所有的Java 对 象 都 可 调 用 java.lang.Object 类 所 定 义 的 实 例 方 法 。  
### 1、方法的重写
 	方法的重写要遵循“两同两小一大”规则，“两同”即方法名相 同、形参列表相同；“两小”指的是子类方法返回值类型应比父类方 法返回值类型更小或相等，子类方法声明抛出的异常类应比父类方法 声明抛出的异常类更小或相等；“一大”指的是子类方法的访问权限 应比父类方法的访问权限更大或相等。  
 如果需要在 子类方法中调用父类中被覆盖的方法，则可以使用super（被覆盖的是 实例方法）或者父类类名（被覆盖的是类方法）作为调用者来调用父 类中被覆盖的方法。  
 如果子类 中定义了一个与父类private方法具有相同的方法名、相同的形参列 表、相同的返回值类型的方法，依然不是重写，只是在子类中重新定 义了一个新方法。  
![00B3EC6C.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683470380051-5651e8d9-b791-4689-83f1-7b7c86d638b5.png#averageHue=%2354472a&clientId=ub3db4095-01a3-4&from=paste&height=38&id=ub55ab830&originHeight=48&originWidth=48&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=2823&status=done&style=none&taskId=u48cf40c8-4551-471c-ab6f-32001b24924&title=&width=38.4)重载和重写的关系：
 因为重载主要发 生在同一个类的多个同名方法之间，而重写发生在子类和父类的同名 方法之间。
   父类方法和子类方 法之间也可能发生重载，因为子类会获得父类方法，如果子类定义了 一个与父类方法有相同的方法名，但参数列表不同的方法，就会形成 父类方法和子类方法的重载。 
### 2、super
 	如果被覆盖的是类变量，在子类的方法中则可以通过父类名作为 调用者来访问被覆盖的类变量。  
 super是Java提供的一个关键字，super用于限定该对象调用它从 父类继承得到的实例变量或方法。正如this不能出现在static修饰的 方法中一样，super也不能出现在static修饰的方法中。static修饰的 方法是属于类的，该方法的调用者可能是一个类，而不是对象，因而 super限定也就失去了意义。  
 	如果在子类里定义了与父类中已有变量同名的变量，那么子类中 定义的变量会隐藏父类中定义的变量。注意不是完全覆盖，因此系统 在创建子类对象时，依然会为父类中定义的、被隐藏的变量分配内存 空间。  
 注意：
 	为了在子类方法中访问父类中定义的、被隐藏(出现同名)的实例变量，或 为了在子类方法中调用父类中定义的、被覆盖（Override）的方 法，可以通过super.作为限定来调用这些实例变量和实例方法。  
:::info
super.f()//调用父类函数
super.a//调用父类成员变量
super（a）//调用父类构造器
:::
 super调用和this调用的区别：
 	区别在于super调用的是其父类的构造器，而this调用的是同一个类中 重载的构造器。因此，使用super调用父类构造器也必须出现在子类构 造器执行体的第一行，所以this调用和super调用不会同时出现。  
## 多态
 	Java引用变量有两个类型：一个是编译时类型，一个是运行时类 型。编译时类型由声明该变量时使用的类型决定，运行时类型由实际 赋给该变量的对象决定。如果编译时类型和运行时类型不一致，就可 能出现所谓的多态（Polymorphism）。  
 Java允许把一个子类对象 直接赋给一个父类引用变量，无须任何类型转换，或者被称为向上转 型（upcasting），向上转型由系统自动完成。  
```
多态中调用成员的特点：
调用成员变量：编译看左边，运行看左边
调用成员方法：编译看左边，运行看右边
```
### 引用变量的强制转换 
这种强制类型转换不是万能的，当进行强制类型转换 时需要注意：
 ➢ 基本类型之间的转换只能在数值类型之间进行，这里所说的数 值类型包括整数型、字符型和浮点型。但数值类型和布尔类型 之间不能进行类型转换。 
➢ 引用类型之间的转换只能在具有继承关系的两个类型之间进 行，如果是两个没有任何继承关系的类型，则无法进行类型转 换，否则编译时就会出现错误。如果试图把一个父类实例转换 成子类类型，则这个对象必须实际上是子类实例才行（即编译 时类型为父类类型，而运行时类型是子类类型），否则将在运 行时引发ClassCastException异常。  
### instanceof运算符
 	instanceof运算符的前一个操作数通常是一个引用类型变量，后 一个操作数通常是一个类（也可以是接口，可以把接口理解成一种特 殊的类），它用于判断前面的对象是否是后面的类，或者其子类、实 现类的实例。如果是，则返回true，否则返回false。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683548185825-318fc38d-b7c4-4252-852d-c129c8533898.png#averageHue=%23dddddd&clientId=u9357d9b0-e196-4&from=paste&height=608&id=u518b3612&originHeight=760&originWidth=766&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=310731&status=done&style=none&taskId=u8bc9082b-a05e-41fb-b61a-581f3b27310&title=&width=612.8)
 instanceof和(type)是Java提供的两个相关的运算符，通常先用 instanceof判断一个对象是否可以强制类型转换，然后再使用(type) 运算符进行强制类型转换，从而保证程序不会出现错误  
 instanceof和(type)是Java提供的两个相关的运算符，通常先用 instanceof判断一个对象是否可以强制类型转换，然后再使用(type) 运算符进行强制类型转换，从而保证程序不会出现错误  
## 继承与组合
 	如果父类中的方法需要被外部类调用，则 必须以public修饰，但又不希望子类重写该方法，可以使用 final修饰符（该修饰符后面会有更详细的介绍）来修饰该方 法  
 如果希望父类的某个方法被子类重写，但不希望被其他类 自由访问，则可以使用protected来修饰该方法。  
 如果想把某些类设置成最终类，即不能被当成父类，则可以使用 final 修 饰 这 个 类 ， 例 如 JDK 提 供 的 java.lang.String 类 和 java.lang.System类。除此之外，使用private修饰这个类的所有构造 器，从而保证子类无法调用该类的构造器，也就无法继承该类。对于 把所有的构造器都使用private修饰的父类而言，可另外提供一个静态 方法，用于创建该类的实例。   
### 利用组合实现复用
 如果需要复用一个类，除把这个类当成基类来继承之外，还可以 把该类当成另一个类的组合成分，从而允许新类直接复用该类的 public方法。  
 对于继承而言，子类可以直接获得父类的public方法，程序使用 子类时，将可以直接访问该子类从父类那里继承到的方法；而组合则 是把旧类对象作为新类的成员变量组合进来，用以实现新类的功能， 用户看到的是新类的方法，而不能看到被组合对象的方法。因此，通 常需要在新类里使用private修饰被组合的旧类对象。 
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683551723058-5e02d533-d4e7-4fe7-aa26-e5544cbf36ec.png#averageHue=%23e5e5e5&clientId=u9357d9b0-e196-4&from=paste&height=652&id=uf545bee9&originHeight=815&originWidth=961&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=162937&status=done&style=none&taskId=u4d594fb5-8848-4163-817f-80bb136033a&title=&width=768.8) 
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683551683456-424e0148-e0e6-4f63-8f21-de1856a0be96.png#averageHue=%23dfdfdf&clientId=u9357d9b0-e196-4&from=paste&height=202&id=u9870e6a9&originHeight=252&originWidth=511&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=53228&status=done&style=none&taskId=u6db58442-43ad-45fc-a0dc-d1168a7fc42&title=&width=408.8)
组合与继承的选择：
 用一个动物来合成一匹狼毫 无意义：狼并不是由动物组成的。反之，如果两个类之间有明确的整 体、部分的关系，例如Person类需要复用Arm类的方法（Person对象由 Arm对象组合而成），此时就应该采用组合关系来实现复用，把Arm作 为Person类的组合成员变量，借助于Arm的方法来实现Person的方法。
## 初始化块
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683552277106-9d76de5b-010b-4529-a52b-8c8e18803dd0.png#averageHue=%23e5e5e5&clientId=u9357d9b0-e196-4&from=paste&height=98&id=uc41da3bb&originHeight=122&originWidth=841&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=12710&status=done&style=none&taskId=u11266709-0db5-40fd-a8b0-00dc175eb87&title=&width=672.8)
 	初始化块的修饰符只能是static，使用static修饰的初始化块被 称为类初始化块（静态初始化块），没有static修饰的初始化块被称 为实例初始化块（非静态初始化块）。  
### 实例初始化块
 实例初始化块只在创 建Java对象时隐式执行，而且在构造器执行之前自动执行。类初始化 则在类初始化阶段自动执行。 
注意： 
当Java创建一个对象时，系统先为该对象的所有实例变量分配 内存（前提是该类已经被加载过了），接着程序开始对这些实例变 量执行初始化，其初始化顺序是：先执行实例初始化块或声明实例 变量时指定的初始值（这两个地方指定初始值的执行顺序与它们在 源代码中的排列顺序相同），再执行构造器里指定的初始值。  
### 类初始化块
	 此类初始化块总是比实例初始化块先执行。  
 类初始化块不能对实例变量进行初始化 处理  
 静态成员不能访问非静态成员的规则，因此类初始化块 不能访问非静态成员，包括不能访问实例变量和实例方法。  
```java
class Root
{


    static{
    	System.out.println("Root的类初始化块");
    }
    {
   	 	System.out.println("Root的实例初始化块");
	}
    public Root(){
        System.out.println("Root的无参数构造器");
    }

}
class Mid extends Root{
    static{
        System.out.println("Mid的类初始化块");
    }
    {
        System.out.println("Mid的实例初始化块");
    }
    public Mid()
    {
        System.out.println("Mid的无参构造器");
    }
    public Mid(String msg)
    {
        this();
        System.out.println("Mid的带参数构造器，其参数值："+msg);
    }
}
class Leaf extends Mid{
    static{
        System.out.println("Leaf的类初始化块");
    }
    {
        System.out.println("Leaf的实例初始化块");
    }
    public Leaf(){
        super("疯狂");
        System.out.println("执行Leaf的构造器");
    }
}
class Test
{
    public static void main(String[] args)
    {
        new Leaf();
        System.out.println();
        new Leaf();
    }
}

```
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683555646298-2bbf7a4d-435b-42cd-821e-72170dd8e2e1.png#averageHue=%232f2d2d&clientId=u9357d9b0-e196-4&from=paste&height=482&id=u0aa81bf7&originHeight=603&originWidth=598&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=63242&status=done&style=none&taskId=u0294b6d1-d30b-4931-bce9-6824d1194f5&title=&width=478.4)
顺序：
先执行类初始化代码块，再执行实例代码块，最后执行构造器；其中如果夹杂着其他赋值语句，则按顺序来。

# 第5章 面向对象（下）
## 包装类
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683556312651-e876e128-555d-411d-b7d7-1d358f5287df.png#averageHue=%23f1f0f0&clientId=ud9ad78f4-b3f9-4&from=paste&height=240&id=uecb700f8&originHeight=300&originWidth=734&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=83298&status=done&style=none&taskId=u698f57c6-71c6-4faa-8bd4-a3c218b56df&title=&width=587.2)
 自动装箱，就是可以把一个基本类型变量直接赋给对应的包装类变 量，或者赋给Object变量（Object是所有类的父类，子类对象可以直 接赋给父类变量）；
自动拆箱则与之相反，允许直接把包装类对象直 接赋给一个对应的基本类型变量。  
valueOf和parseInt的区别：
valueOf的方法是调用parseInt之后再做一次类型转换，也就是说，它多了一个装箱的操作。因此，这里我们理解IDEA的告警了，如果你想把字符串转换成int类型，那么parseInt即可，如果调用valueOf，会先调用parseInt返回int类型，然后使用Integer.valueOf()做一次装箱操作，然后返回值需要int，Java再做一次拆箱操作，显然这种方式更加低效。而如果返回值是Integer类型，则不管哪种方式都一样。这就是valueOf和parseInt的区别，也就是记住尽量使用parseInt即可。
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683621229659-f5b180c2-920e-4aba-acaa-0827cf2b1b08.png#averageHue=%23f6f6f5&clientId=u2c937f24-30dd-4&from=paste&height=281&id=u610bd601&originHeight=351&originWidth=767&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=94720&status=done&style=none&taskId=ub802a61a-1652-411c-946b-beba37d519d&title=&width=613.6)
包装类型与数值类型比较：
 虽然包装类型的变量是引用数据类型，但包装 类的实例可以与数值类型的值进行比较，这种比较是直接取出包装类 实例所包装的数值来进行比较的。  
包装类型与包装类型比较：
 虽然包装类型的变量是引用数据类型，但包装 类的实例可以与数值类型的值进行比较，这种比较是直接取出包装类 实例所包装的数值来进行比较的。  
 但JDK 1.5以后支持所谓的自动装箱，自动装箱就是可以直接把一 个基本类型值赋给一个包装类实例，在这种情况下可能会出现一些特 别的情形。看如下代码（程序清单同上）。  
比较方法：
Boolean.compare(val1,val2)
## 处理对象
打印对象和toString方法
### ==和equals
 	==：两个变量是基本类型变量且都是数值类型
当两个引用类型使用==比较时，只有指向同一个对象，才返回true
 ==不可用于比较类型上没有父子关系的两个对象  
> "hello"和new String("Hello")区别
> ①字符串直接量“hello”，JVM使用常量池管理
> ②使用new String("hello")时，JVM先使用常量池管理“hello”直接量，再调用String类的构造器来创建一个新的String对象保存在堆内存中。 换句话说，new String("hello")一共产生了两 个字符串对象  
>  提示： 常量池（constant pool）专门用于管理在编译时被确定并被保 存在已编译的.class文件中的一些数据。它包括了关于类、方法、 接口中的常量，还包括字符串常量。  

 equals()方法是Object类提供的一个实例方法，因此所有引用变 量都可调用该方法来判断是否与其他引用变量相等。   但使用这个方法 判断两个对象相等的标准与使用==运算符没有区别  ，同样要求两个引 用变量指向同一个对象才会返回true  
提示： 
String已经重写了Object的equals()方法，String的equals() 方法判断两个字符串相等的标准是：只要两个字符串所包含的字符 序列相同，通过equals()比较将返回true，否则将返回false。  

1.  ==是判断两个变量或实例是不是指向同一个内存空间，equals是判断两个变量或实例所指向的内存空间的值是不是相同 
2. ==是指对内存地址进行比较 ， equals()是对字符串的内容进行比较
3. ==指引用是否相同， equals()指的是值是否相同

重写equals（）方法
```java
package com.liu.equals;

public class OverrideEqualsRight {
    public static void main(String[] args) {
        Person p1=new Person("孙悟空","1234");
        Person p2=new Person("孙行者","1234");
        Person p3=new Person("孙悟饭","999");
        System.out.println("p1和p2是否相等？"+p1.equals(p2));
        System.out.println("p2和p3是否相等？"+p2.equals(p3));
    }
}
class Person{
    private String name;
    private String idStr;

    public Person() {
    }

    public Person(String name, String idStr) {
        this.name = name;
        this.idStr = idStr;
    }

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public String getIdStr() {
        return idStr;
    }

    public void setIdStr(String idStr) {
        this.idStr = idStr;
    }
    public boolean equals(Object obj){
        //如果两个对象为同一个对象
        if(this==obj)
            return true;
        //只有当obj是Person对象时
        if(obj!=null&&obj.getClass()==Person.class)
        {
            Person personObj=(Person)obj;
            if(this.getIdStr().equals(personObj.getIdStr()))
            {
                return true;
            }
        }
        return false;
    }
}

```
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683633628481-bb317bd1-3d0f-44b5-b127-46124c6c7ff2.png#averageHue=%23f7f5f2&clientId=u2c937f24-30dd-4&from=paste&height=340&id=u61dc5192&originHeight=425&originWidth=861&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=162523&status=done&style=none&taskId=u6f2a2f3b-42af-43f0-909f-0c51460ecd5&title=&width=688.8)
## 类成员
### 1、理解类成员
 当使用实例来访问类成员时，实际上依然是委托给该类来访问类 成员，因此即使某个实例为null，它也可以访问它所属类的类成员。
但访问实例成员会报错NullPointerException.  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683634460785-bea4f953-aec9-47b9-b0cd-29373749186a.png#averageHue=%238e7850&clientId=u2c937f24-30dd-4&from=paste&height=479&id=u32ca6aaf&originHeight=599&originWidth=844&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=73549&status=done&style=none&taskId=ud3a160eb-d148-42b5-8242-deb4272b99a&title=&width=675.2)
 	类成员（包括成 员变量、方法、初始化块、内部类和内部枚举）不能访问实例成员 。  因为类成员作用域更大，可能类成员已经初始化完成，但实例成员还没初始化。
### 单例类
单例类：一个类只能创建一个实例
 根据良好封装的原则：一旦把该类的构造器隐藏起来，就需要提 供一个public方法作为该类的访问点，用于创建该类的对象，且该方 法必须使用static修饰（因为调用该方法之前还不存在对象，因此调 用该方法的不可能是对象，只能是类）。  
```java
package com.liu.单例类;

public class SingleTest {
    public static void main(String[] args) {
        //创建Singleton对象不能通过构造器
        //只能通过getInstance方法来得到实例
        Singleton s1=Singleton.getInstance();
        Singleton s2=Singleton.getInstance();
        //两次产生的Singleton对象实际上是同一个对象
        System.out.println(s1==s2);//ture
    }
}
class Singleton
{
    //使用一个类变量来缓存曾经创建的实例
    //要在下面的static方法使用，因此该成员变量也必须是静态
    private static Singleton  instance;
    //对构造器使用private修饰，隐藏该构造器
    private Singleton(){}
    //因为调用该方法前还未存在对象，
    // 因此调用该方法的不可能是对象，只能是类
    public static Singleton getInstance()
    {
        //如果instance为null，则表明还不曾创建Singleton对象
        if(instance==null){
            instance=new Singleton();
        }
        return instance;
    }
}
```
## final修饰符
### final成员变量
 	final修饰的变量不可被改变，一旦获得 了初始值，该final变量的值就不能被重新赋值。 
final修饰： 
类变量：在声明类变量时指定值，或在静态初始化块中指定初始值
实例变量：非静态初始化块 、或声明实例变量 、或构造器中指定初始值
 实例变量不能在静态初始化块中指定初始值，因为静态初始化块 是静态成员，不可访问实例变量—非静态成员 。 
类变量不能在普通初 始化块中指定初始值，因为类变量在类初始化阶段已经被初始化了， 普通初始化块不能对其重新赋值。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683637525834-8e0a9026-e00e-4218-9329-4495b0fb9af0.png#averageHue=%23e3e3e3&clientId=ua48e8a64-ce96-4&from=paste&height=470&id=ud7f6090c&originHeight=587&originWidth=873&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=125750&status=done&style=none&taskId=ua95ef04f-6b88-41c8-a707-6d7a64dea57&title=&width=698.4)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683637543398-a79d065a-1c0e-42d0-ba60-dcfebd455bab.png#averageHue=%23f7f5f2&clientId=ua48e8a64-ce96-4&from=paste&height=166&id=uab8ea5dd&originHeight=208&originWidth=847&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=98399&status=done&style=none&taskId=u69f2d7e6-bf80-4d3a-8c97-e2cb4b7591a&title=&width=677.6)
### final 局部变量
 系统不会对局部变量进行初始化，局部变量必须由程序员显式初 始化。  
### final修饰基本类型变量和引用类型变量的区别
修饰基本类型变量：不能重新赋值
修饰引用类型变量：只保证引用的地址不变，一直引用同一个对象，但对象可以发生改变
下例final修饰数组和Person 对象
```java
package com.liu.final修饰的区别;

import java.util.Arrays;

public class FinalReferenceTest {
    public static void main(String[] args) {
        //final修饰数组变量，iArr是一个引用变量
        final int[] iArr={5,6,12,9};
        System.out.println(Arrays.toString(iArr));
        //对数组元素排序，合法
        Arrays.sort(iArr);
        System.out.println(Arrays.toString(iArr));
        //对数组元素赋值合法
        iArr[2]=-8;
        System.out.println(Arrays.toString(iArr));
        //下面语句对iArr重新赋值，非法
        //iArr=null;
        //final修饰Person变量，p是一个引用变量
        final var p=new Person(45);
        //改变Person对象的aage的实例变量，合法
        p.setAge(23);
        System.out.println(p.getAge());
        //下面语句对p重新赋值，非法
        //p=null
        

    }
}
class Person{
    private int age;
    public Person(){}
    public Person(int age){
        this.age=age;
    }

    public int getAge() {
        return age;
    }

    public void setAge(int age) {
        this.age = age;
    }
}
```
### 可执行“宏替换”的final变量
宏变量： 当定义 final变量时就为该变量指定了初始值，而且该初始值可以在编译时 就确定下来的变量
将该final变量当成“宏变量”处理的情况：被赋直接量，被赋算术表达式或字符串连接运算。
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683639072134-80a1146d-729c-4c4f-b19e-ec89af2ce975.png#averageHue=%23e1e0e0&clientId=ua48e8a64-ce96-4&from=paste&height=359&id=u40eb9bf0&originHeight=449&originWidth=879&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=138532&status=done&style=none&taskId=uefbacc06-f5d2-4d41-ba5b-a836a23902d&title=&width=703.2)
book2变量定义时显式将数值99.0转换为字符串，但由于该变量的值需要调用String类的方法，因此编译器无法编译时确定book2 的值，book2不会被当成“宏变量”处理
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683639576552-0bd26316-b09f-46e9-adc7-9ec78794231a.png#averageHue=%23e0e0e0&clientId=ua48e8a64-ce96-4&from=paste&height=393&id=u381f4eb8&originHeight=491&originWidth=844&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=131598&status=done&style=none&taskId=uc6e3a082-4806-41c1-a64c-a6367dcfe63&title=&width=675.2)
编译时无法确定s3字符串的值，s3无法指向字符串池中缓存的“疯狂java”。
要使s1==s3，将str1,str2宏替换，即s1,s2用final修饰
### final方法
final修饰的方法：子类不可重写父类的方法
Object类中getClass()为final方法
 即使使用final 修饰一个private访问权限的方法，依然可以在其子类中定义与该方法 具有相同方法名、相同形参列表、相同返回值类型的方法。  不是方法的重写，只是重新定义了一个新方法。
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683640082713-7f01e25a-c08e-48dc-94c4-19ffc5bd3187.png#averageHue=%23ebebea&clientId=u55cde1a3-e97d-4&from=paste&height=250&id=ucc52b0db&originHeight=312&originWidth=891&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=81766&status=done&style=none&taskId=uad38da09-1a5e-4004-9a05-d71f1f6a631&title=&width=712.8)
### final类
final修饰的类不可以有子类
### 不可变类
创建该类实例后，该实例的实例变量是不可变得，如包装类![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683640253844-2826f758-038b-4f76-8169-f8bbb6fd722d.png#averageHue=%23f8f6f3&clientId=u55cde1a3-e97d-4&from=paste&height=245&id=u71b83bed&originHeight=306&originWidth=865&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=132535&status=done&style=none&taskId=u628c3d71-e3c6-4bc1-bb55-32d08ff0782&title=&width=692)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683640261962-5e7a61a5-8b79-4694-8586-f9b3e5f7794a.png#averageHue=%23f8f5f2&clientId=u55cde1a3-e97d-4&from=paste&height=161&id=ue6ce2d18&originHeight=201&originWidth=869&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=94092&status=done&style=none&taskId=ueaebaac2-16fa-4854-ab3c-e44fd8719d1&title=&width=695.2)
下例为不可变的Address类：
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683640542909-cddab4f9-a2b3-4ae7-b242-38a33841681e.png#averageHue=%23e4e3e3&clientId=u55cde1a3-e97d-4&from=paste&height=432&id=u2ad43816&originHeight=540&originWidth=790&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=130755&status=done&style=none&taskId=ueae3ecad-ab92-4e21-ab16-e09ab255da3&title=&width=632)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683640559357-c3be5a56-5ef4-4aa4-9641-729094fd6982.png#averageHue=%23e4e4e4&clientId=u55cde1a3-e97d-4&from=paste&height=522&id=ud13e600c&originHeight=652&originWidth=791&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=153376&status=done&style=none&taskId=u5cac9e05-c853-444a-be11-af53eac8db3&title=&width=632.8)
可变类： 
是该类的实例变量的 值是可变的。大部分时候所创建的类都是可变类，特别是JavaBean， 因为总是为其实例变量提供了setter和getter方法。  
 与可变类相比，不可变类的实例在整个生命周期中永远处于初始 化状态，它的实例变量的值不可改变。  
设计不可变类，其引用类型的成员变量是可变的要采取措施，如下
最初：
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683641025781-6a759ecd-86b8-4d02-be71-6bc52c38943d.png#averageHue=%23e5e5e5&clientId=u55cde1a3-e97d-4&from=paste&height=96&id=ue8627d6d&originHeight=120&originWidth=859&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=15844&status=done&style=none&taskId=u4cb97459-eda3-4f37-bb23-bb7c730b8e0&title=&width=687.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683641047457-e8a27164-d99e-4139-87e1-437fabea7206.png#averageHue=%23e2e2e2&clientId=u55cde1a3-e97d-4&from=paste&height=197&id=u49c87483&originHeight=246&originWidth=800&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=49483&status=done&style=none&taskId=uc0ca54a0-4170-413e-9f8e-97f867f489e&title=&width=640)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683641058305-c51ce8be-8679-454a-b4c5-218386e211c2.png#averageHue=%23e1e1e1&clientId=u55cde1a3-e97d-4&from=paste&height=490&id=udb9887f2&originHeight=613&originWidth=793&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=139022&status=done&style=none&taskId=u9b9541dc-beb0-4dbf-9782-a98ab2ffc7d&title=&width=634.4)
通过n.setFirstName()会更改掉p的名字
修改后：
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683641139032-9dbfff84-7494-4d66-9d70-89c3a83bc692.png#averageHue=%23dfdfdf&clientId=u55cde1a3-e97d-4&from=paste&height=342&id=u68b0dd18&originHeight=427&originWidth=806&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=122849&status=done&style=none&taskId=u5f765e4f-dde4-49f1-9a89-23a6518b701&title=&width=644.8)
在构造器传参时，重新创建了个Name对象。Person返回name时，没有直接把实例变量name返回。
### 缓存实例的不可变类
缓存方法之一：通过数组作为缓存池，实现缓存实例的不可变量
```java
package com.liu.缓存实例的不可变类;

import java.util.concurrent.Callable;

public class CacheImmutaleTest {
    public static void main(String[] args) {
        CacheImmutele c1=CacheImmutele.valueOf("hello");
        CacheImmutele c2=CacheImmutele.valueOf("hello");
        System.out.println(c1==c2);
    }
}
class CacheImmutele{
    private static int MAX_SIZE=10;
    private static CacheImmutele[] cache=new CacheImmutele[MAX_SIZE];
    private static int pos=0;
    private final String name;

    private CacheImmutele(String name) {
        this.name = name;
    }
    public String getName(){
        return name;
    }
    public static CacheImmutele valueOf(String name)
    {
        for(int i=0;i<MAX_SIZE;i++)
        {
            //如果已有相同实例，则直接返回该缓存的实例
            if(cache[i]!=null&&cache[i].getName().equals(name))
            {
                return cache[i];
            }
        }
        //如果缓存已满
        if(pos==MAX_SIZE){
            //把缓存的第一个对象覆盖，把刚刚生成的对象放在缓存池的最开始位置
            cache[0]=new CacheImmutele(name);
            pos=1;
        } else{
          cache[pos++]=new CacheImmutele(name);
        }
        return cache[pos-1];
    }
    public boolean equals(Object obj) {
        if(this==obj)
            return true;
        if(obj!=null&&obj.getClass()==CacheImmutele.class)
        {
            CacheImmutele ci=(CacheImmutele)obj;
            if(name.equals(ci.getName()))
                return true;
        }
        return false;
    }

    @Override
    public int hashCode() {
        return name.hashCode();
    }
}

```
是否隐藏构造器，取决于系统需求
是否缓存对象：取决于某个对象重复使用的概率
下例为Integer类构造器和valueOf()方法存在的差异
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683643384127-1a5df190-041a-4423-8aff-1b74b419a880.png#averageHue=%23e0e0e0&clientId=u55cde1a3-e97d-4&from=paste&height=424&id=u5a651540&originHeight=530&originWidth=813&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=143591&status=done&style=none&taskId=u73d0267d-63d5-4610-b347-c3a7fbebfe3&title=&width=650.4)
## 抽象类
 有抽象方法 的类只能被定义成抽象类，抽象类里可以没有抽象方法。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683643552927-fa15e002-ffd4-42b1-87c4-0e65c68b1125.png#averageHue=%23f7f4f0&clientId=u55cde1a3-e97d-4&from=paste&height=275&id=u62a6dd67&originHeight=344&originWidth=801&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=167491&status=done&style=none&taskId=u12b67e0f-d571-4066-87fe-a159af7db6a&title=&width=640.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683643561545-85fbbd4b-8532-4e37-979b-89e3045c8154.png#averageHue=%23f6f3f0&clientId=u55cde1a3-e97d-4&from=paste&height=129&id=u5b9fc447&originHeight=161&originWidth=780&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=67883&status=done&style=none&taskId=uc6b2b01a-18e3-4a6d-87fe-2f8166c2d34&title=&width=624)
 注意： 
归纳起来，抽象类可用“有得有失”4个字来描述。“得”指的 是抽象类多了一个能力：抽象类可以包含抽象方法；“失”指的是 抽象类失去了一个能力：抽象类不能用于创建实例。  
抽象方法和空方法不一样，抽象方法没有方法体，空方法的方法体为空。
 当使用abstract修饰类时，表明这个类只能被继承；当使用 abstract修饰方法时，表明这个方法必须由子类提供实现（即重 写）。而final修饰的类不能被继承，final修饰的方法不能被重写。 因此final和abstract永远不能同时使用。  
static修饰方法时，该方法可通过类调用， 但如果该方法被定义成抽象方 法，则将导致通过该类来调用该方法时出现错误（调用了一个没有方 法体的方法肯定会引起错误）  。 因此static和abstract不能同时修饰 某个方法，即没有所谓的类抽象方法。  
 abstract关键字修饰的方法必须被其子类重写才有意义，否则 这个方法将永远不会有方法体，因此abstract方法不能定义为 private访问权限，即private和abstract不能同时修饰方法  
 模板模式的一些简单规则  ：
 ➢ 抽象父类可以只定义需要使用的某些方法，把不能实现的部分 抽象成抽象方法，留给其子类去实现。
 ➢ 父类中可能包含需要调用其他系列方法的方法，这些被调方法 既可以由父类实现，也可以由其子类实现。父类里提供的方法 只是定义了一个通用算法，其实现也许并不完全由自身实现， 而必须依赖于其子类的辅助。  
## Java 9改进的接口
 接口体现的是规范和实现分离的设计哲学。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683644325993-2703454f-3ad0-4efb-812a-ec097c602d60.png#averageHue=%23e2e2e2&clientId=u55cde1a3-e97d-4&from=paste&height=170&id=u2bf2eca7&originHeight=213&originWidth=753&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=47891&status=done&style=none&taskId=u3d396380-f7c9-407c-9d0d-e6c8dcdfcef&title=&width=602.4)
 	接口里可以包含成员变量（只能是静态常量）、方法（只 能是抽象实例方法、类方法、默认方法或私有方法）、内部类（包括 内部接口、枚举）定义。  
 接口里定义的是多个类共同的公共行为规范， 因此接口里的常量、方法、内部类和内部枚举都是public访问权限。  
> 看黑马程序员里接口的笔记

	 接口里的普通方法不能有方法实现（方法体）；但 类方法、默认方法、私有方法都必须有方法实现（方法体）。  
 由于默认方法并没有static修饰， 因此不能直接使用接口来调用默认方法，需要使用接口的实现类的实 例来调用这些默认方法。  
 类方法可以直接使用接口来调用。  
私有方法： 当两个默认方法（或类方法）中包含一段相同的实现 逻辑时，程序必然考虑将这段实现逻辑抽取成工具方法，而工具方法 是应该被隐藏的，这就是Java 9增加私有方法的必然性。  
从某个角度来看，接口可被看作一个特殊的类，因此同类一样，一个java源文件里最多只能有一个public接口，且该public接口名为文件名
### 接口的继承
子接口可以通过接口名.成员变量名来访问父接口的成员变量。
模拟多继承：类1实现了接口1、接口2的接口，创建类1对象即可直接赋给接口1、接口2变量
## 内部类
看黑马的内部类笔记
内部类---成员内部类---非静态内部类
    ----静态内部类
   ---局部内部类
   ---匿名内部类
 成员内部类是一种与成员变量、方法、构造器和初始化块相 似的类成员；局部内部类和匿名内部类则不是类成员。  
 因为内部类作为其外部类的成员，所以可以使用任意访问控制符 如private、protected和public等修饰。  
### 非静态内部类
使用变量如果重名：
外部类的实例变量：Outer.this.变量名
内部类的实例变量：this.变量名
局部变量：变量名
非静态内部类对象能访问外部类变量，而外部类对象不能访问非静态内部类成员，因为有内部类一定有外部类，所有可直接访问外部类。而又外部类对象里不一定寄生了非静态内部类对象
不能在非静态内部类里定义静态成员（静态方法，静态成员变量，静态初始化块）
### 静态内部类
>  static关键字不可修饰外部 类，但可修饰内部类原因：
>  外部类 的上一级程序单元是包，所以不可使用static修饰；而内部类的上 一级程序单元是外部类，使用static修饰可以将内部类变成外部类 相关，而不是外部类实例相关。  

 静态内部类可以包含静态成员，也可以包含非静态成员。  
> 静态内部类不能访问外部类的实 例成员，只能访问外部类的类成员原因：
>  静态内部类对象不是寄生在外部类的实例中，而是寄 生在外部类的类本身中  。 当静态内部类对象存在时，并不存在一个被 它寄生的外部类对象，静态内部类对象只持有外部类的类引用，没有 持有外部类对象的引用。   如果允许静态内部类的实例方法访问外部类 的实例成员，但找不到被寄生的外部类对象，这将引起错误。  

 外部类依然不能直接访问静态内部类的成员，但可以使用静态内 部类的类名作为调用者来访问静态内部类的类成员，也可以使用静态 内部类对象作为调用者来访问静态内部类的实例成员。  
 Java还允许在接口里定义内部类，接口里定义的内部 类默认使用public static修饰，也就是说，接口内部类只能是静态内 部类  
 接口里能定义内部接口， 接口里的内部接口是接口的成员，因此系统默认添加 public static两个修饰符。如果定义接口里的内部接口时指定访问 控制符，则只能使用public修饰符。  
### 使用内部类
内部类用法：
 1.在外部类内部使用内部类  
 2.在外部类以外使用非静态内部类  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683728675540-fae938af-ac50-4c43-b7e1-99ea73a099e3.png#averageHue=%23f4f3f1&clientId=u58f401fc-9aae-4&from=paste&height=89&id=u71ceca13&originHeight=111&originWidth=877&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=34199&status=done&style=none&taskId=u24ff3a56-f696-40a3-a86f-78883b08e54&title=&width=701.6)
 在外部类以外的地方使用内部类时， 内部类完整的类名应该是OuterClass.InnerClass。如果外部类有包 名，则还应该增加包名前缀。  ![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683728827425-39ee8272-0b21-4a7a-801a-87cbf5009d69.png#averageHue=%23dfdfdf&clientId=u58f401fc-9aae-4&from=paste&height=349&id=u83d3a7e8&originHeight=436&originWidth=708&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=106575&status=done&style=none&taskId=u4b52e52a-8701-401d-817f-c127b26ca01&title=&width=566.4)
创建非静态内部类子类的前提知识： 
①非静态内部类的构造器必须通过其外部类对象来 调用。
②创建子类时，子类构造器总会调用父类构造器
创建非静态内部类子类：  
创建非静态内部类的子类时，，子类构造器需要调用费静态内部类的构造器，调用非静态内部类的构造器时，必须存在一个外部类对象。
下例为继承了Out类的In类的子类：
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683729516270-67ea8b7b-45fa-49db-84bd-c8d1942ce79a.png#averageHue=%23e3e3e3&clientId=u58f401fc-9aae-4&from=paste&height=200&id=ud2a17100&originHeight=250&originWidth=808&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=40216&status=done&style=none&taskId=u06db6874-aac6-4c94-b09a-ad0283ec45f&title=&width=646.4)
 非静态内部类In类的构造器必须使用外部类对象来调用，代码中super代表调用 In类的构造器，而out则代表外部类对象  
 非静态内部类In对象和SubClass对象都必须持有指向Outer对象的 引用，区别是创建两种对象时传入Out对象的方式不同：当创建非静态 内部类In类的对象时，必须通过Outer对象来调用new关键字；当创建 SubClass类的对象时，必须使用Outer对象作为调用者来调用In类的构 造器。  
Tip:
 非静态内部类的子类不一定是内部类，它可以是一个外部类。 但非静态内部类的子类实例一样需要保留一个引用，该引用指向其 父类所在外部类的对象。也就是说，如果有一个内部类子类的对象 存在，则一定存在与之对应的外部类对象。  
 3.在外部类以外使用静态内部类  
 在外部类以外的地方创建静态内部类实例的语 法如下：  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683729773278-0e45c87c-d38d-4c36-85d0-a5cf5c25ae95.png#averageHue=%23ececec&clientId=u58f401fc-9aae-4&from=paste&height=35&id=ua09154af&originHeight=44&originWidth=822&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=7576&status=done&style=none&taskId=ub1713769-08d5-4197-8d34-07930481a2f&title=&width=657.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683729812590-47a20a7d-41a8-43ca-a5b5-55b3f4fd7bba.png#averageHue=%23e2e2e2&clientId=u58f401fc-9aae-4&from=paste&height=561&id=ua232dc51&originHeight=701&originWidth=809&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=153198&status=done&style=none&taskId=u7544e5df-b53d-4170-8a1b-c9c70a85e31&title=&width=647.2)
 下面代码就为静态内部类StaticIn类 定义了一个空的子类。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683729891375-4c077227-9bfd-4a43-9897-c3c860616b78.png#averageHue=%23dfdfdf&clientId=u58f401fc-9aae-4&from=paste&height=24&id=uaadf82ed&originHeight=30&originWidth=758&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=11842&status=done&style=none&taskId=u4cd41ed0-faed-43b1-8897-8dee70c7d5c&title=&width=606.4)
 当定义一个静态内部类时，其外部类非 常像一个包空间。  
### 局部内部类
 	由于局部内部类不能在外部 类的方法以外的地方使用，因此局部内部类也不能使用访问控制符和 static修饰符修饰。  
Tip: 
对于局部成员而言，不管是局部变量还是局部内部类，它们的 上一级程序单元都是方法，而不是类，使用static修饰它们没有任 何意义。因此，所有的局部成员都不能使用static修饰。不仅如 此，因为局部成员的作用域是所在方法，其他程序单元永远也不可 能访问另一个方法中的局部成员，所以所有的局部成员都不能使用 访问控制符修饰。  
 如果需要用局部内部类定义变量、创建实例或派生子类，那么都 只能在局部内部类所在的方法内进行。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683730143184-af80eafa-0fad-47e3-8143-328904e65247.png#averageHue=%23e2e2e2&clientId=u58f401fc-9aae-4&from=paste&height=462&id=u7e48e940&originHeight=577&originWidth=797&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=92619&status=done&style=none&taskId=u78a919cd-5c28-4ee4-a642-d80c776bb6b&title=&width=637.6)
 编 译 上 面 程 序 ， 看 到 生 成 了 三 个 class 文 件 ： LocalInnerClass.class 、 LocalInnerClass$1InnerBase.class 和 LocalInnerClass$1InnerSub.class，这表明局部内部类的class文件 总是遵循如下命名格式：OuterClass$NInnerClass.class。注意到局 部内部类的class文件的文件名比成员内部类的class文件的文件名多 了一个数字，这是因为同一个类里不可能有两个同名的成员内部类， 而同一个类里则可能有两个以上同名的局部内部类（处于不同方法 中），所以Java为局部内部类的class文件名中增加了一个数字，用于 区分。  
### 匿名内部类
>  关于匿名内部类还有如下两条规则。 
> ➢ 匿名内部类不能是抽象类，因为系统在创建匿名内部类时，会 立即创建匿名内部类的对象。因此不允许将匿名内部类定义成 抽象类。
>  ➢ 匿名内部类不能定义构造器。由于匿名内部类没有类名，所以 无法定义构造器，但匿名内部类可以定义初始化块，可以通过 实例初始化块来完成构造器需要完成的事情。  

当接口无法实例，而参数需要传入一个接口是，可创建接口实现类的对象传入该方法。以上操作如果需重复使用时，应将该实现类定义为一个独立类，否则定义为匿名类
构造器继承：
 当通过实现接口来创建匿名内部类时，匿名内部类不能显式地定 义构造器，因此匿名内部类只有一个隐式的无参数构造器，故new接口 名后的括号里不能传入参数值。
 但如果通过继承父类来创建匿名内部类时，匿名内部类将拥有和 父类相似的构造器，此处的相似指的是拥有相同的形参列表。    
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683730662227-8a570a09-a081-48fc-8439-ed27ec0667d1.png#averageHue=%23e3e3e3&clientId=u58f401fc-9aae-4&from=paste&height=203&id=ufd778a87&originHeight=254&originWidth=711&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=52075&status=done&style=none&taskId=u3cf45e38-292b-4078-98b3-849a34e1c25&title=&width=568.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683730696296-8ebfd1e2-5936-4381-a04f-f13f4f6e93e5.png#averageHue=%23e2e2e2&clientId=u58f401fc-9aae-4&from=paste&height=310&id=u769bd8bb&originHeight=388&originWidth=791&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=95155&status=done&style=none&taskId=uf1162018-1be2-43c1-8844-133fde3b908&title=&width=632.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683730742676-703add14-f088-4732-8937-95b6275477c4.png#averageHue=%23e1e1e1&clientId=u58f401fc-9aae-4&from=paste&height=368&id=ua44d7c0d&originHeight=460&originWidth=709&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=88467&status=done&style=none&taskId=u2e9789a0-132d-4953-9337-a5da4b04015&title=&width=567.2)
 Java 8更 加智能：如果局部变量被匿名内部类访问，那么该局部变量相当于自 动使用了final修饰。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683730861287-3c57c6bc-264c-4185-b380-402d13149c11.png#averageHue=%23e3e3e3&clientId=u58f401fc-9aae-4&from=paste&height=450&id=uf0226e69&originHeight=562&originWidth=810&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=87702&status=done&style=none&taskId=uc55e71db-12a1-4b49-bc07-33a0a0c38d3&title=&width=648)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683730901829-8c896c33-abc6-4b2d-b0d0-32906be677f1.png#averageHue=%23ebeaea&clientId=u58f401fc-9aae-4&from=paste&height=116&id=u86d1896b&originHeight=145&originWidth=853&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=40598&status=done&style=none&taskId=ufede78ef-bac7-4695-813e-6325e6450ab&title=&width=682.4)
## Lambda
```
package com.liu.Lamabda;

public class LambdaQs {
    public void eat(Eatable e){
        System.out.println(e);
        e.taste();
    }
    public void drive(Flyable f){
        System.out.println("我正在驾驶"+f);
        f.fly("[碧空如洗的晴日]");
    }
    public void test(Addable add){
        System.out.println("5和3的和为："+add.add(5,3));
    }

    public static void main(String[] args) {
        LambdaQs lq=new LambdaQs();

        //Lambda表达式的代码块只有一条语句，可以省略花括号
        lq.eat(()-> System.out.println("苹果的味道不错！"));

        //Lambda表达式的形参只有一个形参时，可以省略圆括号
         lq.drive(weather->{
             System.out.println("今天天气是："+weather);
            System.out.println("直升飞机平稳飞行");
        });

         //Lambda表达式的代码块只有一条语句，可以省略花括号
        //代码块中只有一条语句，即使该表达式需要返回值，也可省略return
        lq.test((a,b)->a+b);

    }
}
interface Eatable{
    void taste();
}
interface Flyable{
    void fly(String weather);
}
interface Addable{
    int add(int a,int b);
}
```
### Lamda表达式与函数式接口
Lambda表达式的类型，也被称为“目标类型”，Lambda表达式的目标类型必须是“函数式接口”，函数式接口代表只包含一个抽象方法的接口。
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683799634764-b19cd89a-1dd7-4c14-ba9e-f3c447409c37.png#averageHue=%23e0e0e0&clientId=u5787d6b1-7953-4&from=paste&height=202&id=u2855abee&originHeight=252&originWidth=784&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=67505&status=done&style=none&taskId=uf2c95529-f072-43c4-ab5e-a803c9710c2&title=&width=627.2)
 为了保证Lambda表达式的目标类型是一个明确的函数式接口，可 以有如下三种常见方式。
 ➢ 将Lambda表达式赋值给函数式接口类型的变量。
 ➢ 将Lambda表达式作为函数式接口类型的参数传给某个方法。
 ➢ 使用函数式接口对Lambda表达式进行强制类型转换。 因此，只要将上面代码改为如下形式即可（程序清单同上）。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683799788716-5522a731-9acf-4f53-8b4b-6575fea6c3eb.png#averageHue=%23e6e6e6&clientId=u5787d6b1-7953-4&from=paste&height=138&id=u265014e5&originHeight=173&originWidth=806&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=18461&status=done&style=none&taskId=u3acbd0b0-d5e8-46db-8ef8-bc3bd4e86e6&title=&width=644.8)
当上例没有强制转换时，Lambda表达式赋值给Object变量，编译器只能确定Lambda表达式的类型为Object，而Object并不是函数式接口
当函数式接口形参相同时，可写成其他类型的接口
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683800120988-692fb77d-edf7-4dee-9074-1963bc93e8a4.png#averageHue=%23e7e7e7&clientId=u5787d6b1-7953-4&from=paste&height=116&id=u5ca88bf6&originHeight=145&originWidth=788&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=12993&status=done&style=none&taskId=u13a0b651-de42-4c12-9466-36b0ec9fcd8&title=&width=630.4)![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683800028892-9c1ccbb2-39f2-46b5-b584-cc91475dd59d.png#averageHue=%23e0e0e0&clientId=u5787d6b1-7953-4&from=paste&height=176&id=u7b65f0a2&originHeight=220&originWidth=788&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=60586&status=done&style=none&taskId=u1db5abdc-4f81-44f5-8cdd-04221cfcc49&title=&width=630.4) 此使用Lambda表达式对var定 义的变量赋值时，必须明确指定Lambda表达式的目标类型。例如如上两例
### 方法引用和构造器引用
1、引用类方法
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683805607211-a258aa57-f20a-4f3e-94b8-674fc418567e.png#averageHue=%232d2c2b&clientId=u5787d6b1-7953-4&from=paste&height=471&id=u35bd8acb&originHeight=589&originWidth=690&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=49386&status=done&style=none&taskId=u1b923b96-3a36-41d0-b567-f923ecfdffe&title=&width=552)
上面类方法引用,调用Integer类的valueOf()类方法来实现Converter函数式接口中唯一的抽象方法，当调用Converter接口中的唯一抽象方法，调用参数将会传给Integer类的valueOf()类方法
2、引用特定对象的实例方法
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683806845663-221ac5fc-5a78-445d-99d8-2a169bbbab70.png#averageHue=%232d2c2c&clientId=u5787d6b1-7953-4&from=paste&height=186&id=u352aaf17&originHeight=233&originWidth=682&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=25315&status=done&style=none&taskId=u8c98fada-7601-4e69-b100-e6dccbe890e&title=&width=545.6)
 对 于 上 面 的 实 例 方 法 引 用 ， 也 就 是 调 用 "fkit.org" 对 象 的 indexOf()实例方法来实现Converter函数式接口中唯一的抽象方法， 当调用Converter接口中的唯一的抽象方法时，调用参数将会传 给"fkit.org"对象的indexOf()实例方法。  
3、引用某类对象的实例方法
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683807430679-aaa92dc3-868e-4962-82f2-a0fb9930efd6.png#averageHue=%232d2c2b&clientId=u5787d6b1-7953-4&from=paste&height=387&id=u6aa2133f&originHeight=484&originWidth=779&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=44902&status=done&style=none&taskId=ucd8abeae-bc19-47c5-b3ed-9826c4d57c5&title=&width=623.2)
 对 于 上 面 的 实 例 方 法 引 用 ， 也 就 是 调 用 某 个 String 对 象 的 substring()实例方法来实现MyTest函数式接口中唯一的抽象方法，当 调用MyTest接口中的唯一的抽象方法时，第一个调用参数将作为 substring()方法的调用者，剩下的调用参数会作为substring()实例 方法的调用参数。  
4、引用构造器
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683807847396-e75f412f-1051-4b4c-8351-1213b2d60b61.png#averageHue=%232d2c2b&clientId=u5787d6b1-7953-4&from=paste&height=397&id=u55fb90cc&originHeight=496&originWidth=779&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=42618&status=done&style=none&taskId=u09652ded-ff90-4578-8091-acd50e725b8&title=&width=623.2)
 对于上面的构造器引用，也就是调用某个JFrame类的构造器来实 现YourTest函数式接口中唯一的抽象方法，当调用YourTest接口中的 唯一的抽象方法时，调用参数将会传给JFrame构造器。从上面程序中 可以看出，调用YourTest对象的win()抽象方法时，实际只传入了一个 String类型的参数，这个String类型的参数会被传给JFrame构造器— 这就确定了是调用JFrame类的、带一个String参数的构造器。  
### Lambda表达式和匿名内部类的联系和区别
相似：
 ➢ Lambda 表 达 式 与 匿 名 内 部 类 一 样 ， 都 可 以 直 接 访 问 “effectively final”的局部变量，以及外部类的成员变量 （包括实例变量和类变量）。
 ➢ Lambda表达式创建的对象与匿名内部类生成的对象一样，都可 以直接调用从接口中继承的默认方法。  （使用已建立的对象调用默认方法，而不可以在Lambda表达式块内调用默认方法）
区别：
 	➢ 匿名内部类可以为任意接口创建实例—不管接口包含多少个抽 象方法，只要匿名内部类实现所有的抽象方法即可；但Lambda 表达式只能为函数式接口创建实例。 
➢ 匿名内部类可以为抽象类甚至普通类创建实例；但Lambda表达 式只能为函数式接口创建实例。 
➢ 匿名内部类实现的抽象方法的方法体允许调用接口中定义的默 认方法；但Lambda表达式的代码块不允许调用接口中定义的默 认方法。 
### 使用Lambda表达式调用Arrarys的类方法
## 枚举类 Enum
枚举类与普通类的区别
 ➢ 枚举类可以实现一个或多个接口，使用enum定义的枚举类默认 继承了java.lang.Enum类，而不是默认继承Object类，因此枚 举类不能显式继承其他父类。其中java.lang.Enum类实现了 java.lang.Serializable和java.lang.Comparable两个接口。
 ➢ 使用enum定义、非抽象的枚举类默认会使用final修饰。
 ➢ 枚举类的构造器只能使用private访问控制符，如果省略了构 造器的访问控制符，则默认使用private修饰；如果强制指定访 问控制符，则只能指定private修饰符。由于枚举类的所有构造 器都是private的，而子类构造器总要调用父类构造器一次，因 此枚举类不能派生子类。 
➢ 枚举类的所有实例必须在枚举类的第一行显式列出，否则这个 枚举类永远都不能产生实例。列出这些实例时，系统会自动添 加public static final修饰，无须程序员显式添加。  
 枚举类默认提供了一个values()方法，该方法可以很方便地遍历 所有的枚举值  
```java
public enum SeasonEnum {
    //定义时显式列出所有枚举类
    SPRING,SUMMER,FALL,WINTER;

}
class EnumTest{
    public void judge(SeasonEnum s){
        switch(s)
            {
                case SPRING:
                    System.out.println("春");
                    break;
                case SUMMER:
                    System.out.println("夏");
                    break;
                case FALL:
                    System.out.println("秋");
                    break;
                case WINTER:
                    System.out.println("冬");
                    break;
            }
    }

    public static void main(String[] args){
        //枚举类默认有一个values()方法，返回该枚举类的所有实例
        for(SeasonEnum s:SeasonEnum.values()){
            System.out.println(s);
        }
        //使用该枚举类的某个实例，则可使用EnumClass.variable的形式
        new EnumTest().judge(SeasonEnum.SPRING);
    }
}
```

![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683811472036-6da44207-44b4-4c13-bc6b-56221c85cd75.png#averageHue=%23f7f4f1&clientId=u5787d6b1-7953-4&from=paste&height=634&id=ua122d6f3&originHeight=793&originWidth=881&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=381383&status=done&style=none&taskId=u3b274977-cb0d-4bc2-ba62-a5717ddf70b&title=&width=704.8)
枚举类的成员变量、方法、构造器
 枚举类的实例只能是枚举 值，而不是随意地通过new来创建枚举类对象。  
 建议将枚举类的成员变量都使用private final修 饰。   建议将枚举类的成员变量都使用private final修 饰。  
 在枚举类中列出枚举值时，实际上就是调用构造 器创建枚举类对象，只是这里无须使用new关键字，也无须显式调用构 造器。前面列出枚举值时无须传入参数，甚至无须使用括号，仅仅是 因为前面的枚举类包含无参数的构造器。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683813261388-e922d641-03d9-4bc6-bb22-e4fd926a8e0c.png#averageHue=%23e2e2e2&clientId=u5787d6b1-7953-4&from=paste&height=318&id=u505a32e3&originHeight=398&originWidth=798&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=73167&status=done&style=none&taskId=u17653dac-bb1c-457d-9e81-f77a5a49635&title=&width=638.4)
### 实现接口的枚举类
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683813393072-486acc23-1aa7-4096-9233-bc8554cfae0a.png#averageHue=%23e6e6e6&clientId=u5787d6b1-7953-4&from=paste&height=91&id=u1a4874b9&originHeight=114&originWidth=785&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=10027&status=done&style=none&taskId=u83cc5048-c20b-489b-9862-a19cd9ea577&title=&width=628)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683813399975-eabbd8ea-1f3d-4a55-8a99-96a1f3e4f70c.png#averageHue=%23e2e2e2&clientId=u5787d6b1-7953-4&from=paste&height=238&id=ub081552b&originHeight=298&originWidth=809&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=70724&status=done&style=none&taskId=ud2a7fce7-dad4-4a6e-9f71-fcb4f3f0aeb&title=&width=647.2)
 如果需要每个枚举 值在调用该方法时呈现出不同的行为方式，则可以让每个枚举值分别 来实现该方法，每个枚举值提供不同的实现方式，从而让不同的枚举 值调用该方法时具有不同的行为方式  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683814221070-8ff7b136-7786-424b-9c91-907efb2da3cc.png#averageHue=%232d2c2b&clientId=u5787d6b1-7953-4&from=paste&height=446&id=u45960327&originHeight=558&originWidth=671&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=56667&status=done&style=none&taskId=u61abc955-5813-45b0-8a3f-fd94f159db6&title=&width=536.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683814230847-08ff21ae-ce57-4004-b905-e9839b6d1faa.png#averageHue=%232c2c2b&clientId=u5787d6b1-7953-4&from=paste&height=338&id=u87536f88&originHeight=422&originWidth=611&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=20731&status=done&style=none&taskId=u3b40f64c-489d-4bc0-8250-5463731c4a7&title=&width=488.8)
 花括号部分实际上就是一个类体部分，在这种 情况下，当创建MALE、FEMALE枚举值时，并不是直接创建Gender枚举 类的实例，而是相当于创建Gender的匿名子类的实例。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683814495725-a40faf71-3902-4f8e-aa0b-6bfe12c42f4e.png#averageHue=%23f2f1ef&clientId=u5787d6b1-7953-4&from=paste&height=62&id=u3bbbdd88&originHeight=77&originWidth=817&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=23440&status=done&style=none&taskId=uf898d035-5af9-4aa3-8587-287e330ce53&title=&width=653.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683814521445-6f1c3c97-519b-49e0-aabd-d32042e0f540.png#averageHue=%23f5f3f1&clientId=u5787d6b1-7953-4&from=paste&height=152&id=u47b90d6f&originHeight=190&originWidth=818&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=73670&status=done&style=none&taskId=u64f052cb-3d29-493e-8bef-f5c86b4a23b&title=&width=654.4)
### 包含抽象方法的枚举类
```java
public enum Operation {
    PLUS{
        @Override
        public double eval(double x, double y) {
            return x+y;
        }
    },
    MINUS{
        @Override
        public double eval(double x, double y) {
            return x-y;
        }
    },
    TIMES{
        @Override
        public double eval(double x, double y) {
            return x*y;
        }
    },
    DIVIDE{
        @Override
        public double eval(double x, double y) {
            return x/y;
        }
    };
    //为枚举定义一个抽象方法
    //这个抽象方法由不同的枚举值提供不同的实现
    public abstract double eval(double x,double y);

    public static void main(String[] args) {
        System.out.println(Operation.PLUS.eval(3,4));
        System.out.println(Operation.MINUS.eval(5,4));
        System.out.println(Operation.TIMES.eval(5,4));
        System.out.println(Operation.DIVIDE.eval(5,4));
    }
}
```
 枚举类里定义抽象方法时不能使用abstract关键字将枚举类定义 成抽象类（因为系统自动会为它添加abstract关键字），但因为枚举 类需要显式创建枚举值，而不是作为父类，所以定义每个枚举值时必 须为抽象方法提供实现，否则将出现编译错误  
## 对象与垃圾回收
 垃圾回收机制具有如下特征。
 ➢ 垃圾回收机制只负责回收堆内存中的对象，不会回收任何物理 资源（例如数据库连接、网络IO等资源）。 
➢ 程序无法精确控制垃圾回收的运行，垃圾回收会在合适的时候 进行。当对象永久性地失去引用后，系统就会在合适的时候回 收它所占的内存。 
➢ 在 垃 圾 回 收 机 制 回 收 任 何 对 象 之 前 ， 总 会 先 调 用 它 的 finalize()方法，该方法可能使该对象重新复活（让一个引用 变量重新引用该对象），从而导致垃圾回收机制取消回收。  
### 对象在内存中的状态
 当一个对象在堆内存中运行时，根据它被引用变量所引用的状 态，可以把它所处的状态分成如下三种。 
➢ 可达状态：当一个对象被创建后，若有一个以上的引用变量引 用它，则这个对象在程序中处于可达状态，程序可通过引用变 量来调用该对象的实例变量和方法。 
➢ 可恢复状态：如果程序中某个对象不再有任何引用变量引用 它，它就进入了可恢复状态。在这种状态下，系统的垃圾回收 机制准备回收该对象所占用的内存，在回收该对象之前，系统 会调用所有可恢复状态对象的finalize()方法进行资源清理。 如果系统在调用finalize()方法时重新让一个引用变量引用该 对象，则这个对象会再次变为可达状态；否则该对象将进入不 可达状态。 
➢ 不可达状态：当对象与所有引用变量的关联都被切断，且系统 已经调用所有对象的finalize()方法后依然没有使该对象变成 可达状态，那么这个对象将永久性地失去引用，最后变成不可 达状态。只有当一个对象处于不可达状态时，系统才会真正回 收该对象所占有的资源。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683815412136-8354b2c3-0f0e-4dc7-b06a-26d4d2a90951.png#averageHue=%23fbfbfb&clientId=u5787d6b1-7953-4&from=paste&height=351&id=u9afc1759&originHeight=439&originWidth=783&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=80848&status=done&style=none&taskId=u245a4acd-6ab0-4566-bd80-c83a45240a8&title=&width=626.4)
 一个对象可以被一个方法的局部变量引用，也可以被其他类的类 变量引用，或被其他对象的实例变量引用。
当某个对象被其他类的类 变量引用时，只有该类被销毁后，该对象才会进入可恢复状态；当某 个对象被其他对象的实例变量引用时，只有当该对象被销毁后，该对 象才会进入可恢复状态。  、
### 强制垃圾回收
强制垃圾回收只是通知系统进行垃圾回收，系统不一定进行了垃圾回收。 大部分时候，程序强制系统垃圾回收后总会有 一些效果。  
 强制系统垃圾回收有如下两种方式。 
➢ 调用System类的gc()静态方法：System.gc()。
 ➢ 调 用 Runtime 对 象 的 gc() 实 例 方 法 ： Runtime.getRuntime().gc()。  
### finalize方法
 在垃圾回收机制回收某个对象所占用的内存之前，通常要求程序 调用适当的方法来清理资源，在没有明确指定清理资源的情况下， Java提供了默认机制来清理该对象的资源，这个机制就是finalize() 方法。
 该方法是定义在Object类里的实例方法，方法原型为：  
protected void finalize() throws Throwable
   当finalize()方法返回后，对象消失，垃圾回收机制开始执行。 方法原型中的throws Throwable表示它可以抛出任何类型的异常  
 任何Java类都可以重写Object类的finalize()方法，在该方法中 清理该对象占用的资源。如果程序终止之前始终没有进行垃圾回收， 则不会调用失去引用对象的finalize()方法来清理资源。
当程序需要更多额外内存时，垃圾回收机制才会进行垃圾回收
 finalize()方法具有如下4个特点。 
➢ 永远不要主动调用某个对象的finalize()方法，该方法应交给 垃圾回收机制调用。 
➢ finalize()方法何时被调用，是否被调用具有不确定性，不要 把finalize()方法当成一定会被执行的方法。 
➢ 当JVM执行可恢复对象的finalize()方法时，可能使该对象或 系统中其他对象重新变成可达状态。 
➢ 当JVM执行finalize()方法时出现异常时，垃圾回收机制不会 报告异常，程序继续执行。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683817957394-b28aded4-bfd1-4f61-afd6-83b71e901fe6.png#averageHue=%23e0e0e0&clientId=u5787d6b1-7953-4&from=paste&height=514&id=ue5fedc03&originHeight=643&originWidth=790&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=163295&status=done&style=none&taskId=u26ae8fd0-2110-422b-b6b0-d3f20ee91c9&title=&width=632)
### 对象的软、弱、虚引用
 程序里会有一个引用变量引用该对象，这是 最常见的引用方式。 
 java.lang.ref包下提供了三个类： SoftReference、PhantomReference和WeakReference，它们分别代表 了系统对对象的三种引用方式：软引用、虚引用和弱引用。   
强引用：创建一个对象，并把对象赋给一个引用变量，通过引用变量来操作实际对象，如对象、数组
软引用：  对于只有软引用的对象而言，当 系统内存空间足够时，它不会被系统回收，程序也可使用该对象；当 系统内存空间不足时，系统可能会回收它。  软引用通常用于对内存敏 感的程序中  
弱引用：垃圾回收机制运行时， 不管系统内存是否足够，总会回收该对象所占用的内存。  
虚引用： 如果一个对象只有一个虚引用时，那么它和没有引用的效果大致 相同。虚引用主要用于跟踪对象被垃圾回收的状态，虚引用不能单独 使用，虚引用必须和引用队列（ReferenceQueue）联合使用。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683895926844-c930bcda-c1cc-4542-a99b-3071ab7e34d5.png#averageHue=%23f0f0f0&clientId=uc1ef99f2-6f48-4&from=paste&height=611&id=u4791dcd5&originHeight=764&originWidth=1189&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=132929&status=done&style=none&taskId=u664d4a3a-cfd3-42e9-b38a-62779906ad6&title=&width=951.2)
# 第6章 java基础类库
## 与用户互动
public static void main(String [] args){}
public:JVM自由调用main()方法
static:JVM调用主方法时，直接通过对该类来调用主方法
void:主方法返回值返回给JVM无意义
### Scanner
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684056021714-9ae91947-bad1-49fd-8d86-5b86a8f30c6b.png#averageHue=%23f9f8f5&clientId=u30ec6c14-5fde-4&from=paste&height=228&id=u3cd8d9f6&originHeight=285&originWidth=857&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=93232&status=done&style=none&taskId=ub9f1fe13-e7bd-48d7-9576-b09721980f6&title=&width=685.6)
默认情况下，Scanner使用空白（包括空格、Tab空白、回车）作为多个输入项之间的分隔符
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684056145472-1e5b33a8-a77c-4797-91ec-54f09f26f1cc.png#averageHue=%23e2e2e2&clientId=u30ec6c14-5fde-4&from=paste&height=430&id=u9e69319e&originHeight=537&originWidth=863&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=107878&status=done&style=none&taskId=uf3963047-51bf-47be-b5c2-0d7edde194f&title=&width=690.4)
读取文件输入
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684056180102-38d94f1f-6a84-4d7b-a05c-8fb34cbbd568.png#averageHue=%23e2e2e2&clientId=u30ec6c14-5fde-4&from=paste&height=386&id=uc58d67cc&originHeight=482&originWidth=893&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=119725&status=done&style=none&taskId=u76190d0a-207a-4244-b020-ad485453393&title=&width=714.4)
## 系统相关
### System
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684057348847-33a60ce1-c90c-4d8c-a1db-32ec64561718.png#averageHue=%23f5f1e8&clientId=u30ec6c14-5fde-4&from=paste&height=454&id=u4ee2c044&originHeight=568&originWidth=1451&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=259143&status=done&style=none&taskId=ue92b85e3-e811-48e5-917a-dfd1d0a516d&title=&width=1160.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684056397719-919bab1f-90b6-4519-a52e-f6a5f8e142ac.png#averageHue=%23f4f3f2&clientId=u30ec6c14-5fde-4&from=paste&height=607&id=ud08c220d&originHeight=759&originWidth=1567&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=254951&status=done&style=none&taskId=u5d2e9499-2424-4b3e-9b21-69827498182&title=&width=1253.6)
arraycopy() 细节：
1、如果数据原数组和目的地数组都是基本数据类型，那么两者类型必须保持一致，否则会报错
2、如果数据原数组和目的地数组都是引用数据类型，那么子类类型可以赋值给父类类型
3、在拷贝的时候需要考虑数组长度，如果超出范围也会报错
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684057515517-8f6ad234-25ea-44f4-831e-b5d4fc7e9eed.png#averageHue=%23f7f7f7&clientId=u30ec6c14-5fde-4&from=paste&height=519&id=u0b26322a&originHeight=649&originWidth=1162&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=146064&status=done&style=none&taskId=u5003b470-0cff-4d1e-a484-979c524531c&title=&width=929.6)

System.identityHashCode(Object x)
返回对象的精准hushCode()值。当某个对象的hushCode被重写，但是其identityHushCode()返回的hushCode值是根据对象的地址算得的hashCode。 所以，如果两个对象的identityHashCode 值相同，则两个对象绝对是同一个对象。如下程序所示。  
### RunTime
表示当前虚拟机运行的环境
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684058049900-a0bc4b0f-5918-426f-a5e9-256bdb7dbf7b.png#averageHue=%23f4ede1&clientId=u30ec6c14-5fde-4&from=paste&height=573&id=u9c2b489d&originHeight=716&originWidth=1500&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=422368&status=done&style=none&taskId=u3f598f99-79ec-4f73-b54c-18820c39d82&title=&width=1200)
```java
package com.liu.Runtime;

import java.io.IOException;

public class Runtime {
    public static void main(String[] args) throws IOException {
        //1、获取Runtime对象
        //Runtime只有一个对象，不能通过new创建，其构造方法是私有的
        java.lang.Runtime r1=java.lang.Runtime.getRuntime();
        java.lang.Runtime r2= java.lang.Runtime.getRuntime();
        System.out.println(r1==r2);//true获取的对象相同

        //exit

        //java.lang.Runtime.getRuntime().exit(0);

        //获取CPU的线程数
        System.out.println(java.lang.Runtime.getRuntime().availableProcessors());

        //总内存大小，单位byte字节
        System.out.println(java.lang.Runtime.getRuntime().maxMemory()/1024/1024);//3470M,3G

        //已经获取的总内存大小，单位byte
        System.out.println(java.lang.Runtime.getRuntime().totalMemory()/1024/1024);

        //剩余内存大小
        System.out.println(java.lang.Runtime.getRuntime().freeMemory()/1024/1024);

        //运行cmd
        //shutdown:关机
        //加上参数才能执行
        //-s:默认在一分钟之后关机
        //-s-t指定时间： 指定关机时间
        //-a:取消关机操作
        //-r:关机并重启
        //java.lang.Runtime.getRuntime().exec("notepad");
        java.lang.Runtime.getRuntime().exec("shutdown -a");
    }
}
```
 	通过exec启动平台上的命令之后，它就变成了一个进程，Java使 用Process来代表进程。  
ProcessHandle接口 Java9后
 通 过该接口可获取进程的ID、父进程和后代进程；通过该接口的 onExit()方法可在进程结束时完成某些行为。  
 ProcessHandle还提供了一个ProcessHandle.Info类，用于获取进 程的命令、参数、启动时间、累计运行时间、用户等信息。 
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684064500522-df905207-47e1-42e7-8f23-26ecf731abee.png#averageHue=%23e0e0e0&clientId=u87893a3f-bb75-4&from=paste&height=590&id=u23ef1ab0&originHeight=738&originWidth=834&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=285295&status=done&style=none&taskId=ud4b9cc57-54ca-4595-944c-e579474b82f&title=&width=667.2)
## 常用类
### Object
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684064775670-1a4edd7e-9a34-4a71-9c67-e5252c6982b5.png#averageHue=%23fafbcd&clientId=u87893a3f-bb75-4&from=paste&height=598&id=udcf7e35f&originHeight=747&originWidth=1398&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=181098&status=done&style=none&taskId=u7ed3253c-dbd4-4591-850b-408808f4912&title=&width=1118.4)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684066935644-bda8b3b5-8377-4780-9446-6b95db3e9dd2.png#averageHue=%23f1ece2&clientId=u87893a3f-bb75-4&from=paste&height=402&id=u5cd29365&originHeight=502&originWidth=1508&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=214650&status=done&style=none&taskId=u3969c266-b4d9-4e2d-b31a-2ee9f22a04f&title=&width=1206.4)
toStirng方法的结论：
如果我们打印一个对象，想要看到属性值得话，那么就重写toString方法
equals结论
1、如果没有重写equals方法，那么默认使用Object中的方法进行比较，比较的是地址值
2、一般地址值意义不大，所以重写后的equals方法比较的就是对象的内部属性值了
常见方法：
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684067017383-b10dc334-b637-445f-ab65-8b4b1550d113.png#averageHue=%23f8f5f2&clientId=u87893a3f-bb75-4&from=paste&height=582&id=ua6d5fbba&originHeight=727&originWidth=968&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=370960&status=done&style=none&taskId=ubec2a80d-ee45-480a-b3d1-10ba5522e1c&title=&width=774.4)
clone（）
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684067678989-714bc37c-f327-4d16-90e4-1f998b3c5a7b.png#averageHue=%23f8f6f3&clientId=u949cd268-0950-4&from=paste&height=236&id=udd1aeb6e&originHeight=295&originWidth=898&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=123287&status=done&style=none&taskId=ua20058ba-dce9-4b6e-8f3d-30320030403&title=&width=718.4)
```java
package com.liu.Object;

public class CloneTest {
    public static void main(String[] args) throws CloneNotSupportedException {
        User u1= new User(29);
        User u2=u1.clone();
        System.out.println(u1==u2);//false
        //==代表比较双方是否相同，若是基本类型则表示值相等，如果是引用类型则表示地址相等即是同一个类。
        System.out.println(u1.address==u2.address);//true
        //比较u1,u2的地址值
    }
}
class Address{
    String detail;

    public Address(String detail) {
        this.detail = detail;
    }
}
//自定义类实现Cloneable接口。这个标记性接口内没有方法
class User implements Cloneable{
    int age;
    Address address;

    public User(int age) {
        this.age = age;
        address = new Address("广州天河");
    }
    //自定义类实现自己的clone()方法
    public User clone() throws CloneNotSupportedException {
        //调用Object实现的clone()方法来得到该对象的副本，并返回该副本
        return (User)super.clone();    
    }
}
```
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684067863160-c72fb96e-fb0e-4300-8c2e-c039e98b2810.png#averageHue=%23f4f4f4&clientId=u949cd268-0950-4&from=paste&height=338&id=udabe1ab2&originHeight=423&originWidth=779&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=108041&status=done&style=none&taskId=u6459af17-838f-4d88-9100-ad8aa9d408b&title=&width=623.2)
浅克隆：
```java
//1、先创建一个对象
int[] data={1,2,3,4};
User u1=new User(1,"zhangsan","123","girl2",data);
//2、克隆对象
//细节：方法在底层会帮我们创建一个对象，并把原对象中的数据拷贝过去
//书写细节：
//1、重写Object中的clone方法
//2、让javabean类实现Cloneable接口
//3、创建原对象并调用clone就可以了

User u2=(User)u1.clone();
int[] arr=u1.getData();
arr[0]=10;
System.out.println(u1);
System.out.println(u2);
```
```java
public Object clone() throws CloneNotSupportedException {
    //        //调用父类中的clone方法
    //        //让Java帮我们克隆一个对象，并把克隆的对象返回出去
    //        return super.clone();
    }
```

![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684069593587-bf8a1738-8689-4640-afe7-622c8c93a9f1.png#averageHue=%23cce1c2&clientId=u949cd268-0950-4&from=paste&height=602&id=u78107dc4&originHeight=753&originWidth=1434&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=298784&status=done&style=none&taskId=u5988f427-4906-4f70-b762-7bb00661b08&title=&width=1147.2)
深克隆：
```
public Object clone() throws CloneNotSupportedException {
//        //调用父类中的clone方法
//        //让Java帮我们克隆一个对象，并把克隆的对象返回出去
//        return super.clone();
        //调用父类中的clone方法
        //让Java帮我们克隆一个对象，并把克隆的对象返回出去

        //先把被克隆的对象中的数组获取出来
        int[] data=this.data;
        //创建新数组
        int[] newdata=new int[data.length];
        //拷贝数组中的数据
        for (int i = 0; i < newdata.length; i++) {
            newdata[i]=data[i];
        }
        //调用父类中的方法克隆对象
        User u=(User)super.clone();
        //因为父类中的克隆是浅克隆，替换克隆出来对象中数组地址值
        u.data=newdata;
        return u;
    }
```

![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684069682564-4909eab9-ad59-4df6-8061-3791ced045b7.png#averageHue=%23aaceab&clientId=u949cd268-0950-4&from=paste&height=564&id=u1fe9b3bc&originHeight=705&originWidth=1377&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=368038&status=done&style=none&taskId=udd60e4b1-a476-4a71-8be6-02f9ab49596&title=&width=1101.6)

 Object类提供的clone()方法不仅能简单地处理“复制”对象的问 题，而且这种“自我克隆”机制十分高效。比如clone一个包含100个 元素的int[]数组，用系统默认的clone方法比静态copy方法快近2倍。  
clone()为浅克隆， 它只克隆该对象的所有成员变量值，不会对引 用类型的成员变量值所引用的对象进行克隆。  
如要进行深克隆，则需自己进行递归克隆
### Objects
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684072504709-eff60dd3-f59b-4f59-80ec-653a993d8faa.png#averageHue=%23fdfbfb&clientId=u949cd268-0950-4&from=paste&height=446&id=u552dfe53&originHeight=557&originWidth=1506&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=208782&status=done&style=none&taskId=ua42c44a4-75ac-42b3-a42c-2a1b848bafd&title=&width=1204.8)
```
package com.liu.Objects;

import java.util.Objects;

public class Test {
    public static void main(String[] args) {
        Student s1=null;
        Student s2=new Student("zhangsan","nv");
        //当s1为null时不能调用方法
        //System.out.println(s1.equals(s2));

        //1、方法的底层判断s1是否为null，如果为null，直接返回false
        //2、如果s1不为null，那么就利用s1再次调用equals方法
        //3、此时s1是Student类型，所以最终还是会调用Student中的equals方法
        //如果没有重写，比较地址值，如果重写了，就比较属性值
        System.out.println(Objects.equals(s1,s2));

        //isNull
        System.out.println(Objects.isNull(s1));
        System.out.println(Objects.isNull(s2));

        System.out.println(Objects.nonNull(s1));
        System.out.println(Objects.nonNull(s2));
    }

}
```
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684072679770-b74d7337-b632-4c68-b560-e93bb6646924.png#averageHue=%23f5f4f3&clientId=u949cd268-0950-4&from=paste&height=125&id=u03a422a7&originHeight=156&originWidth=851&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=43973&status=done&style=none&taskId=uf1dd580c-f813-493e-96f5-0406e65393e&title=&width=680.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684072703269-b3754713-196a-42a1-9bf3-942b262cf009.png#averageHue=%23e0e0e0&clientId=u949cd268-0950-4&from=paste&height=364&id=udc0c9588&originHeight=455&originWidth=855&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=136958&status=done&style=none&taskId=u1287f840-41b3-4657-a90a-76513dd71f3&title=&width=684)
### String、StringBuffer、StringBuilder
**String**
 内容不可变
**StringBuffer**:
字符串序列可变的字符串， 通 过 StringBuffer 提 供 的 append() 、 insert()、reverse()、setCharAt()、setLength()等方法可以改变这 个字符串对象的字符序列。 最后  调用它的toString()方法将其转换为一个String对 象。  
S**tringBuilder**:
类似StringBuffer. 不同的是，StringBuffer是线程安全的，而 StringBuilder则没有实现线程安全功能，所以性能略高。因此在通常 情况下，如果需要创建一个内容可变的字符串对象，则应该优先考虑 使用StringBuilder类。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684072936446-d7bdfe2d-e0c6-4175-b26b-8a961fd0de47.png#averageHue=%23f7f5f4&clientId=u946e9362-2524-4&from=paste&height=122&id=uca6bd4a6&originHeight=152&originWidth=854&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=38369&status=done&style=none&taskId=u14d03fd0-d078-4326-bc59-abf6fe49c2d&title=&width=683.2)
方法：
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684073685109-825223e8-d605-4946-a4e2-abf054e9c161.png#averageHue=%23f8f5f3&clientId=u946e9362-2524-4&from=paste&height=82&id=u81a60f3c&originHeight=103&originWidth=843&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=37058&status=done&style=none&taskId=u61df9065-6835-4bf5-8ef2-50b07d3bb52&title=&width=674.4)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684073839618-98b34601-5dae-4cc6-b706-1d5bfb276a0a.png#averageHue=%23edebea&clientId=u946e9362-2524-4&from=paste&height=363&id=u5255555b&originHeight=454&originWidth=849&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=165506&status=done&style=none&taskId=ub56cc95a-1b02-4fc4-b862-aec12d1ef61&title=&width=679.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684073967170-80f7bf60-2010-4b7a-83a9-9a05b05e375f.png#averageHue=%23f8f6f3&clientId=u946e9362-2524-4&from=paste&height=461&id=u7f9f6ffe&originHeight=576&originWidth=845&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=198514&status=done&style=none&taskId=u915ac455-5801-4dbd-94b5-1375114ea0f&title=&width=676)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684074012359-7fee59d0-4ec0-4b6b-aab6-1a25e8bcd698.png#averageHue=%23f4f3f1&clientId=u946e9362-2524-4&from=paste&height=318&id=u70e5bd56&originHeight=397&originWidth=874&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=118306&status=done&style=none&taskId=u0d844b69-b653-4623-a62b-dd288ff0406&title=&width=699.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684074072449-1f782de3-c477-49a1-a7d2-8dece8ea4bd7.png#averageHue=%23f0eeed&clientId=u946e9362-2524-4&from=paste&height=275&id=u1ba068ef&originHeight=344&originWidth=884&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=94657&status=done&style=none&taskId=udd854371-805b-48c4-84b1-57096097c40&title=&width=707.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684074187345-85ca0784-921d-489d-a6ca-843d549ffd6c.png#averageHue=%23f2f0ee&clientId=u946e9362-2524-4&from=paste&height=353&id=u95ba95c2&originHeight=441&originWidth=861&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=154536&status=done&style=none&taskId=uca93b618-06e9-41a6-91ea-f1746f8ef6e&title=&width=688.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684074197164-10620006-f9be-4b71-ac24-3fc47c27316b.png#averageHue=%23f0f0f0&clientId=u946e9362-2524-4&from=paste&height=131&id=u8171d14a&originHeight=164&originWidth=850&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=18527&status=done&style=none&taskId=ub9a3a153-ef68-411d-a4d5-1bf96d998a7&title=&width=680)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684074284604-338fb12f-590a-44e4-9807-95511b0df464.png#averageHue=%23f6f5f3&clientId=u946e9362-2524-4&from=paste&height=630&id=u672b2efe&originHeight=787&originWidth=1080&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=269971&status=done&style=none&taskId=u32369ad5-1092-402d-aa60-52f7b37cdaa&title=&width=864)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684074311128-1cbf87c3-9251-4563-b0af-54ea30c02838.png#averageHue=%23f9f7f4&clientId=u946e9362-2524-4&from=paste&height=212&id=ud1f7e5e2&originHeight=265&originWidth=855&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=87536&status=done&style=none&taskId=uba7d619d-4e97-4b58-bc0a-6bce1614da5&title=&width=684)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684074341410-f338afb3-cd60-416a-8055-d72d7b4cec51.png#averageHue=%23f1f0f0&clientId=u946e9362-2524-4&from=paste&height=290&id=u64dc2ed5&originHeight=362&originWidth=923&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=100350&status=done&style=none&taskId=u3ae80493-868a-4e9c-99cd-edc4363eb33&title=&width=738.4)
### Math
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684076361884-d36ba0bd-5480-4a12-8ff2-7467cd7d3a31.png#averageHue=%23f9f8ea&clientId=u946e9362-2524-4&from=paste&height=274&id=uc4a16c28&originHeight=343&originWidth=1005&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=198717&status=done&style=none&taskId=u36d66cfc-5cdb-4603-8f40-0566c16d252&title=&width=804)
获取1~100之间的随机数
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684076595979-98864e00-6b4f-4a25-91ca-e40bd254c5bd.png#averageHue=%23faf6e6&clientId=u946e9362-2524-4&from=paste&height=202&id=u50b87525&originHeight=252&originWidth=808&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=80212&status=done&style=none&taskId=u199542ff-982e-4756-aa6b-4597c4d28bf&title=&width=646.4)
### ThreadLocalRandom、Random
这两种生成随机数的方法比Math.random()多
 	当两个Random对象种 子相同时，它们会产生相同的数字序列。值得指出的，当使用默认的 种子构造Random对象时，它们属于同一个种子。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684078951184-ae9d06ea-bfa2-47f8-931a-7594621e1ced.png#averageHue=%23f2f0ee&clientId=u946e9362-2524-4&from=paste&height=98&id=uda5e3df2&originHeight=122&originWidth=852&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=51103&status=done&style=none&taskId=u1caa8c99-caa7-40ce-97de-d3fd29da41f&title=&width=681.6)
### BigInteger
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684150497580-864d553a-8cba-4cff-badd-cf9143c32b01.png#averageHue=%23f5f0e8&clientId=ubf520e71-8939-4&from=paste&height=593&id=u94080948&originHeight=741&originWidth=1599&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=356346&status=done&style=none&taskId=u5a8f5fa3-7f48-4f2a-8e55-eac95b0870a&title=&width=1279.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684151776884-32ace4c1-0184-44bf-8d71-de80cb9be9f3.png#averageHue=%23f5f5f5&clientId=ubf520e71-8939-4&from=paste&height=410&id=u74e061b6&originHeight=513&originWidth=1366&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=197886&status=done&style=none&taskId=u95e2cd57-dfa5-4bff-8641-8bf9e1b7866&title=&width=1092.8)
```java
package com.liu.BigInteger;

import java.math.BigInteger;
import java.util.Random;

public class Test {
    public static void main(String[] args) {

        //1、获取一个随机的大整数
        BigInteger bd1=new BigInteger(4,new Random());
        System.out.println(bd1);//[0,2^4-1]

        //2、获取一个指定的大数
        //细节：字符串中必须是整数，否则会报错
        BigInteger bd2=new BigInteger("9999999999999999999999");
        System.out.println(bd2);

        //3、获取指定进制的大整数
        //细节：字符串中必须是整数，否则会报错
        //字符串中的数字必须要跟进制吻合
        //比如二进制中那只能是0,1,写其他的就报错
        BigInteger bd3=new BigInteger("10",2);//以radix进制转化成10进制
        System.out.println(bd3);

        //4、静态方法获取BigInteger的对象,内部有优化
        //细节：
        //1、能表示范围比较小，只能在long的取值范围内，如果超出long的取值范围就不行了
        //2、在内部对常用的数字，-16~16进行了优化
        // 提前把-16~16先创建好BigInteger对象，如果多次获取不会重新创建新的
        BigInteger bd4=BigInteger.valueOf(16);
        BigInteger bd5=BigInteger.valueOf(16);
        System.out.println(bd4==bd5);//true
        BigInteger bd6=BigInteger.valueOf(17);
        BigInteger bd7=BigInteger.valueOf(17);
        System.out.println(bd6==bd7);//false

        //5、对象一旦创建内部的数据不能发生改变
        BigInteger bd9=BigInteger.valueOf(1);
        BigInteger bd10=BigInteger.valueOf(2);
        BigInteger result=bd9.add(bd10);
        System.out.println(result);
        //此时，不会修改参与计算的BigInteger对象中的值，而是产生了一个新的BigInteger记录3



    }
}
```
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684151844051-631988e7-a4b6-4154-8e58-d2b56fbe939b.png#averageHue=%23f2e9d8&clientId=ubf520e71-8939-4&from=paste&height=624&id=ue58ed3e9&originHeight=780&originWidth=1632&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=659424&status=done&style=none&taskId=u9ec91139-5d92-4c9f-84d3-2f9d5707dd1&title=&width=1305.6)
```java
package com.liu.BigInteger;

import java.math.BigInteger;

public class TestMethod {
    public static void main(String[] args) {
        //1、创建两个BigInteger对象
        BigInteger bd1=BigInteger.valueOf(10);
        BigInteger bd2=BigInteger.valueOf(3);

        //2、加法
        BigInteger bd3 = bd1.add(bd2);
        System.out.println(bd3);

        //3、除法：获取商和余数
        BigInteger[] arr = bd1.divideAndRemainder(bd2);
        System.out.println(arr[0]);
        System.out.println(arr[1]);

        //4、比较是否相同
        boolean result=bd1.equals(bd2);
        System.out.println(result);

        //5、次幂
        BigInteger bd4=bd1.pow(2);
        System.out.println(bd4);

        //6、max
        BigInteger bd5=bd1.max(bd2);

        //7、转为int类型，超出数据范围则有误
        BigInteger bd6=BigInteger.valueOf(1223);
        System.out.println(bd6);


    }
}
```
### BigDecimal
构造方法：
 BigDecimal(double val)  ：不推荐，具有一定的不可预知行， 当程序使用new BigDecimal(0.1)来创建一个 BigDecimal对象时，它的值并不是0.1，它实际上等于一个近似0.1的 数 。  
 BigDecimal(String val)  ：可预知的
```java
package com.liu.BigDecimal;

import java.math.BigDecimal;

public class ConstructerTest {
    public static void main(String[] args) {
        //1、通过传递double类型的小数来创建对象
        //细节：
        //这种方式有可能是不精确的，所以不推荐使用
        BigDecimal bd1=new BigDecimal(0.01);
        BigDecimal bd2=new BigDecimal(0.09);
        System.out.println(bd1);
        System.out.println(bd2);

        //2、通过传递字符串表示的小数来创建对象
        BigDecimal bd3=new BigDecimal("0.01");
        BigDecimal bd4= new BigDecimal("0.09");
        BigDecimal bd5 = bd3.add(bd4);
        System.out.println(bd3);
        System.out.println(bd4);
        System.out.println(bd5);

        //3、通过静态方法获取对象
        BigDecimal bd6=BigDecimal.valueOf(10.0);
        BigDecimal bd7=BigDecimal.valueOf(10.0);
        System.out.println(bd6==bd7);
        //细节
        //1、如果表示的数字不大，没有超过double的取值范围，建议使用静态方法
        //2、如果要表示的数字不大，超出了double的取值范围，建议使用构造方法
        //3、如果我们传递的是0~10之间的整数，包含0,10，那么方法会返回已经创建好的对象，不会重新new


    }
}
```
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684153545675-0af84ab4-3c43-4027-9bc0-b15b1f6b3816.png#averageHue=%23f6ecdf&clientId=ubf520e71-8939-4&from=paste&height=563&id=ua89d0f79&originHeight=704&originWidth=1599&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=556980&status=done&style=none&taskId=u9fc99af2-6404-4996-93d5-b92bceefca1&title=&width=1279.2)
```java
package com.liu.BigDecimal;

import java.math.BigDecimal;
import java.math.RoundingMode;

public class MethodTest {
    public static void main(String[] args) {
        BigDecimal bd1=BigDecimal.valueOf(10.0);
        BigDecimal bd2=BigDecimal.valueOf(3.0);
        BigDecimal bd3=bd1.add(bd2);

        //除法
        BigDecimal bd6=bd1.divide(bd2,2, RoundingMode.HALF_UP);
        //参数一：除数
        //参数二：除不尽时保留位数
        //参数三：保留模式：四舍五入
    }
}
```
进行运算时，可以为BigDecimal定义一个Arith工具类,调用该类时，先传入两个浮点数，将两个浮点数包装成BigDecimal对象，使用BigDecimal进行运算，运算结束后通过  .doubleValue()转换成浮点型
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684154586946-531ddeb5-8238-4837-8747-122744d7c7cb.png#averageHue=%23e3e3e3&clientId=ubf520e71-8939-4&from=paste&height=296&id=uabf444f2&originHeight=370&originWidth=724&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=105981&status=done&style=none&taskId=u31876af0-3b42-40d4-b5d8-cc59ce70956&title=&width=579.2)
## Java8 的日期、时间类
格林尼治时间 简称GMT
目前：时间标准时间：原子钟
中国标准时间：世界标准时间+8小时
时间换算 ：1秒=1000毫秒
  1毫秒=1000微秒
  1微秒=1000纳秒
### Date
构造方法：
 ➢ Date()：生成一个代表当前日期时间的Date对象。该构造器在 底层调用System.currentTimeMillis()获得long整数作为日期 参数。 
➢ Date(long date)：根据指定的long型整数来生成一个Date对 象。该构造器的参数表示创建的Date对象和GMT 1970年1月1日 00：00：00之间的时间差，以毫秒作为计时单位。  
普通方法：
 ➢ boolean after(Date when)：测试该日期是否在指定日期when 之后。 ➢ boolean before(Date when)：测试该日期是否在指定日期 when之前。 
➢ long getTime()：返回该时间对应的long型整数，即从GMT 1970-01-01 00：00：00到该Date对象之间的时间差，以毫秒作 为计时单位。
 ➢ void setTime(long time)：设置该Date对象的时间。  
```java
package com.liu.Date;

import java.util.Date;

public class DateTest {
    public static void main(String[] args) {
        //1、创建对象表示一个时间
        Date d1=new Date();
        System.out.println(d1);

        //2、创建对象表示一个指定的时间
        Date d2=new Date(0L);
        System.out.println(d2);

        //3、setTime 修改时间
        d2.setTime(1000L);
        System.out.println(d2);

        //4、getTime获取当前时间的的毫秒值
        long time=d2.getTime();
        System.out.println(time);
    }
}
```
### SimpleDataFormat
```
package com.liu.SingleDateFormat;

import java.text.ParseException;
import java.text.SimpleDateFormat;
import java.util.Date;

public class Test {
    public static void main(String[] args) throws ParseException {

        //1、利用空参构造创建SimpleDateFormat对象
        SimpleDateFormat sdf1=new SimpleDateFormat();
        Date d1=new Date(0L);
        String str1 = sdf1.format(d1);//70-1-1 上午8:00
        System.out.println(str1);

        //2、利用带参构造创建SimpleDateFormat对象，指定格式
        SimpleDateFormat sdf2=new SimpleDateFormat("yyyy年M月dd日 HH:mm:ss EEE");
        String str2 = sdf2.format(d1);
        System.out.println(str2);

        //3、解析
        //（1）定义一个字符串表示时间
        String str="2023-11-11 11:11:11";
        //(2)利用空参构造创建SimpleDateFormat对象
        //细节：
        //创建对象的格式要跟字符串的格式完全一致
        SimpleDateFormat sdf=new SimpleDateFormat("yyy-MM-dd HH:mm:ss");
        Date d=sdf.parse(str);
        System.out.println(d);//Sat Nov 11 11:11:11 CST 2023

    }
}
```
### Calendar
代表系统当前的日历对象，可以单独修改，获取时间中的年月日
Calendar是一个抽象类，不能直接创建对象
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684157968702-626a135d-72b1-46bf-8e7d-7a0ac016f954.png#averageHue=%23f5f6f0&clientId=ubf520e71-8939-4&from=paste&height=258&id=u900ae828&originHeight=323&originWidth=1335&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=108599&status=done&style=none&taskId=u6c47f55e-faf4-424b-ba5c-44f873c632f&title=&width=1068)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684157985590-53c6f371-5e09-4d67-a58a-6cee758a6aa2.png#averageHue=%23b0daf3&clientId=ubf520e71-8939-4&from=paste&height=586&id=u640462f8&originHeight=733&originWidth=1462&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=321888&status=done&style=none&taskId=uf1d59ca4-2070-45d9-ad22-77f322484d2&title=&width=1169.6)
add方法和roll方法的区别：
（1）add 当被修改的字段超出它允许的范围时，会发生进位，即上一级 字段也会增大  
  (2) roll 当被修改的字段超出它允 许的范围时，上一级字段不会增大。  
```java
package com.liu.Calendar;

import java.util.Calendar;
import java.util.Date;

public class Test {
    public static void main(String[] args) {
        //1、获取日历对象
        //细节1：Calendar是一个抽象类不能直接new，而是通过一个静态方法获取到一个类对象
        //底层原理：
        //会根据系统的不同时区来获取不同的日历对象，默认表示当前时间
        //会把时间中的纪元、年、月、日时分秒等放在一个数组中
        //0  :纪元
        //1  ：年
        //2  :月
        //3  ：一年中的第几周
        //4  :一月中的第几周
        //5  ：一个月中的第几天（日期）
        //...16
        //细节2：
        //月份：范围0~11 如果获取出来的是0，那么实际上是1
        //星期：在老外的眼里，星期日是一周中的第一天
        //   1（星期日） 2（星期一）  3（星期二） 4（星期三） 5（星期四）   6（星期五） 7（星期六）
        Calendar c=Calendar.getInstance();
        System.out.println(c);

        //2、修改日历代表的时间
        Date d=new Date(0L);
        c.setTime(d);
        System.out.println(c);

        c.set(Calendar.YEAR,2000);
        c.set(Calendar.MONTH,11);
        c.add(Calendar.MONTH,1);

        //java在Calendar中把索引对应的数字定义为常量
        int year=c.get(Calendar.YEAR);
        int month=c.get(Calendar.MONTH)+1;
        int date=c.get(Calendar.DAY_OF_MONTH);
        int week=c.get(Calendar.DAY_OF_WEEK);
        System.out.println(year+", "+month+", "+date+", "+getWeek(week));




    }
    //查表法
    public static String getWeek(int index){
        String [] arr={"","星期日","星期一","星期二","星期三","星期四","星期五","星期六"};
        return arr[index];
    }
}
```
setLenient()设置容错性
（）中false关闭
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684161327107-1bf7e80c-93e8-4a1e-aad0-1ed9f3dc284e.png#averageHue=%23e3e3e3&clientId=ubf520e71-8939-4&from=paste&height=346&id=ue126ccfd&originHeight=433&originWidth=833&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=93122&status=done&style=none&taskId=uf2f90030-2cbd-45f6-8737-3d39c24a7bb&title=&width=666.4)
set()延迟修改
 set(f, value)方法将日历字段f更改为value，此外它还设置了一 个内部成员变量，以指示日历字段f已经被更改。尽管日历字段f是立 即更改的，但该Calendar所代表的时间却不会立即修改，直到下次调 用get()、getTime()、getTimeInMillis()、add() 或roll()时才会重 新计算日历的时间。  
### 新的日期、时间包：
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684161773663-e8a0002b-f4ad-473c-9a5b-f2bc4da6c9b3.png#averageHue=%23eeeeee&clientId=ubf520e71-8939-4&from=paste&height=686&id=u13e5683d&originHeight=857&originWidth=1714&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=345878&status=done&style=none&taskId=ua936069f-0708-4a7a-aa5a-7dde1f2b7d7&title=&width=1371.2)
#### ZoneId:
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684161885115-3ff6efe4-4f1d-48af-af72-e3fb6e723190.png#averageHue=%23f7f6f6&clientId=ubf520e71-8939-4&from=paste&height=542&id=u6c65592d&originHeight=678&originWidth=1489&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=138859&status=done&style=none&taskId=u6e884421-a6e4-4e15-b01f-1e2b166898a&title=&width=1191.2)
```java
package com.liu.Jdk8AddTime;

import java.time.ZoneId;
import java.util.Set;

public class ZoneIdTest {
    public static void main(String[] args) {
        //1、获取所有市区的名称
        Set<String> zoneIds = ZoneId.getAvailableZoneIds();
        System.out.println(zoneIds);//Asia/Shanghai...
        System.out.println(zoneIds.size());//600

        //2、获取当前系统的默认时区
        ZoneId zoneId = ZoneId.systemDefault();//Asia/Shanghai
        System.out.println(zoneId);

        //3、获取指定时区
        ZoneId zoneId1 = ZoneId.of("America/Cuiaba");
        System.out.println(zoneId1);//America/Cuiaba
    }
}
```

#### instant
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684162752266-51f709dd-f7a0-4286-827e-86fa2c84152a.png#averageHue=%23f3f2f2&clientId=ubf520e71-8939-4&from=paste&height=618&id=u5b104bf2&originHeight=773&originWidth=1599&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=250269&status=done&style=none&taskId=uf81a7141-1e5d-489d-9f47-e49532f9082&title=&width=1279.2)
```java
package com.liu.Jdk8AddTime;
import java.time.Instant;
import java.time.ZoneId;
import java.time.ZonedDateTime;

public class InstantTest {
    public static void main(String[] args) {
        /*
static Instant now();                     获取当前时间的Instant对象（标准时间）
static Instant ofXXX(long epochMilli)     根据（秒、毫秒、纳秒）获取instant对象
ZonedDataTime atZone(ZoneId zone)          指定时区
boolean isXxx(Instant otherInstant)        判断系列的方法
Instant minusXxx(long miilsToSubtract)     减少时间系列的方法
Instant plusXxx(long millisToSubtract)     增加时间系列的方法
*/
        //1、获取当前时间的Instance对象（标准时间）
        Instant now = Instant.now();
        System.out.println(now);//2023-05-17T09:58:46.136Z

        //2、根据（秒、毫秒。纳秒)获取Instant对象
        //过去多少毫秒后的时间
        Instant instant1=Instant.ofEpochMilli(0L);
        System.out.println(instant1);//1970-01-01T00:00:00Z

        //过去多少秒后的时间
        Instant instant2=Instant.ofEpochSecond(1L);
        System.out.println(instant2);//1970-01-01T00:00:01Z

        //过去多少秒和纳秒后的时间
        Instant instant3=Instant.ofEpochSecond(1L,1000000000L);
        System.out.println(instant3);//1970-01-01T00:00:02Z

        //3、指定时区
        ZonedDateTime time=Instant.now().atZone(ZoneId.of("Asia/Shanghai"));
        System.out.println(time);//2023-05-17T21:44:49.989+08:00[Asia/Shanghai]

        //4、isXxx判断
        Instant instant4=Instant.ofEpochMilli(0L);
        Instant instant5=Instant.ofEpochMilli(1000L);
        //5、用于时间的判断
        //isBefoe: 判断调用者代表的时间是都在参数表示的时间前
        boolean result1=instant4.isBefore(instant5);
        System.out.println(result1);//true

        //6、减少时间
        Instant instant6=Instant.ofEpochMilli(3000L);
        System.out.println(instant6);//1970-01-01T00:00:03Z

        Instant instant7=instant6.minusSeconds(1);
        System.out.println(instant7);//1970-01-01T00:00:02Z
    }
}
```
#### ZoneDataTime
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684332420790-cf84aa42-e72f-4555-aea1-320dad83ae10.png#averageHue=%23f7f1ec&clientId=u7c331459-b3de-4&from=paste&height=596&id=u9a7c4ce4&originHeight=745&originWidth=1500&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=274133&status=done&style=none&taskId=uf78e0bc4-d803-4e47-a1e7-8e097402f03&title=&width=1200)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684332989474-7d29d429-99ba-4f9c-9475-4ee01b05ccc5.png#averageHue=%23fcfcfb&clientId=u7c331459-b3de-4&from=paste&height=631&id=u89dbf604&originHeight=789&originWidth=1288&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=333696&status=done&style=none&taskId=u7afb785e-dd69-443f-bff6-19e25c2f114&title=&width=1030.4)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684332939117-b6bf49d5-8b14-4c1f-8932-191ec479cda0.png#averageHue=%23fefdfc&clientId=u7c331459-b3de-4&from=paste&height=438&id=u99c25966&originHeight=547&originWidth=884&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=168448&status=done&style=none&taskId=udad616c4-6c07-4594-9702-9500cb27042&title=&width=707.2)
#### DateTimeFormat
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684333087775-c5549127-e611-4c94-98de-f4bf95180964.png#averageHue=%23f7f2ed&clientId=u7c331459-b3de-4&from=paste&height=518&id=u2487bfcf&originHeight=648&originWidth=1530&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=152564&status=done&style=none&taskId=u1abed421-0139-446b-8d7a-c6b70a89d70&title=&width=1224)
#### LocalDate、LocalTime、LocalDateTime
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684333769918-b8ae11f8-3211-4fb9-8bee-39718e6224e3.png#averageHue=%23f3f3f3&clientId=u7c331459-b3de-4&from=paste&height=644&id=u518b189d&originHeight=805&originWidth=1535&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=223860&status=done&style=none&taskId=u880fec9d-9f4d-4038-9ac9-7c581862664&title=&width=1228)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684333798409-a15f53d4-8c7f-482a-bd6a-eaf1590e33e2.png#averageHue=%23fefefc&clientId=u7c331459-b3de-4&from=paste&height=570&id=ud7c1135e&originHeight=712&originWidth=1513&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=184956&status=done&style=none&taskId=u54ecd08a-ad75-4727-b1a4-5e450735f5c&title=&width=1210.4)
## 正则表达式
正则表达式的作用：
一：校验字符串是否满足规则
二：在一段文本中查找满足要求的内容
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684240621539-52f97344-6948-407a-b8bd-068f41f29967.png#averageHue=%23f6f6e4&clientId=u538cc6a2-18cd-4&from=paste&height=712&id=u6850d726&originHeight=890&originWidth=1592&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=443490&status=done&style=none&taskId=u58187a7a-9ef3-431e-b8b5-e189dc34156&title=&width=1273.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684245231276-86782c12-8109-4193-a3e3-06554a64996a.png#averageHue=%23f3f1f0&clientId=u538cc6a2-18cd-4&from=paste&height=162&id=u00907cb5&originHeight=202&originWidth=798&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=55794&status=done&style=none&taskId=udc129c11-1e30-4a9c-84a5-923d5474213&title=&width=638.4)
正则表达式支持的数量标识符：
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684245375728-f4310b0e-590b-4b29-a63b-d400dd5e6372.png#averageHue=%23f7f4f1&clientId=u538cc6a2-18cd-4&from=paste&height=261&id=u59f4df92&originHeight=326&originWidth=821&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=155508&status=done&style=none&taskId=u7660f58a-8cac-4d0d-9d1c-5dc8550afe8&title=&width=656.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684245448380-38f2e394-dc4f-4640-8e23-b5744b35d0d7.png#averageHue=%23eeedec&clientId=u538cc6a2-18cd-4&from=paste&height=589&id=uf3a6ace1&originHeight=736&originWidth=871&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=254058&status=done&style=none&taskId=ucf04df4d-964c-4062-93b2-0d0ad6f1617&title=&width=696.8)

爬虫：
1、获取正则表达式的对象
Pattern p=Pattern.compile(正则表达式)；
2、获取文本匹配器的对象
Matcher m=p.matcher(文本);
3、利用循环获取每一个数据
while(m.find()){
sout(m.group());
}
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684245128837-78ccf483-b104-4b00-ba91-d0f1bb5a8a58.png#averageHue=%23e5ecdc&clientId=u538cc6a2-18cd-4&from=paste&height=416&id=uef033ac2&originHeight=520&originWidth=1055&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=227644&status=done&style=none&taskId=u264066f1-db95-47b5-921e-49c0a234905&title=&width=844)
Matcher提供的常用方法：![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684247366521-b135a228-53df-4a83-bba9-05c371518dbc.png#averageHue=%23f8f5f3&clientId=u538cc6a2-18cd-4&from=paste&height=334&id=u80994385&originHeight=418&originWidth=808&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=150599&status=done&style=none&taskId=u1839675e-04a6-49ca-b64f-cdddf087948&title=&width=646.4)
```java
package regex;
import java.util.regex.Pattern;
import java.util.regex.Matcher;
public class TextRegex {
    public static void main(String[] args) {
        String str="Java自从95年问世以来，经历了很多版本，目前企业中用最多的是Java8和Java11，"+
            "因为这两个是长期支持的版本，下一个长期支持的版本是Java17，相信未来不久Java17也会逐渐登上历史舞台";
        //Pattern:  表示正则表达式
        //Matcher:  文本匹配器，作用按照正则表达式的规则取读取字符串，从头开始读取
        //          在大串中取找符合匹配规则的子串

        //获取正则表达式的对象
        Pattern p=Pattern.compile("Java\\d{0,2}");
        //获取文本匹配器的对象
        //m:文本匹配器的对象
        //str:大串
        //p:规则
        //m要在str中找符合p规则的小串
        Matcher m=p.matcher(str);

        //拿着文本匹配器从头开始读取，寻找是否有满足规则的子串
        //如果没有，方法返回false
        //如果有，返回true。在底层记录了子串的起始索引和结束索引+1
        //0,4
        //        boolean b=m.find();

        //方法底层会根据find方法记录的索引进行截取
        //subString (起始索引，结束索引); 包头不包尾
        //（0,4）但是不包含4索引
        //会把截取到的小串进行返回
        //        String s1=m.group();
        //        System.out.println(s1);

        //第二次再调用find时，会继续读取后面的内容
        //读取到第二个满足要求的子串，方法会继续返回true
        //并把第二个子串的起始索引和结束索引+1，进行记录


        while(m.find()){
            String str=m.group();
            System.out.println(str);
        }




    }
}
```
## 变量处理和方法处理
### Java9新增MethodHandle
### Java9新增的VarHandle

# 第7章 java集合
## 概述
 	集合类主要负责保存、盛装 其他数据，因此集合类也被称为容器类。  
数组可以保存基本类型的值和对象的引用变量
集合只能保存对象的引用变量，要保存基本数据类型，只能保存其包装类
Java集合类主要由两个接口派生：Collection和Map
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684403000172-f0fbe745-7de9-4597-9b69-e004af829886.png#averageHue=%23f3f3f0&clientId=ub9738d7d-9b60-4&from=paste&height=470&id=u2350726c&originHeight=587&originWidth=879&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=203566&status=done&style=none&taskId=ue6beca74-5d9e-47cc-a87f-fae13c92618&title=&width=703.2)
Map实现类用于保存具有映射关系的数据
功能特征： Map保存的每项数据都是 key-value对，也就是由key和value两个值组成。  
包含元素特点：
 其中Set集合类似于一个罐子，把一个对象添加到Set集合 时，Set集合无法记住添加这个元素的顺序，所以Set里的元素不能重 复（否则系统无法准确识别这个元素）；List集合非常像一个数组， 它可以记住每次添加元素的顺序、且List的长度可变。Map集合也像一 个罐子，只是它里面的每项数据都由两个值组成。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684403598284-e2c5e2bb-2891-4cc5-ab32-6c8ec4ab0ba7.png#averageHue=%23f1f0ec&clientId=ub9738d7d-9b60-4&from=paste&height=446&id=uf578d433&originHeight=558&originWidth=854&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=174691&status=done&style=none&taskId=u4ef5b780-585d-4890-b1aa-e843f6bc86b&title=&width=683.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684403607977-d412be6b-4118-4319-97d1-548d87a90bc3.png#averageHue=%23f5f5f5&clientId=ub9738d7d-9b60-4&from=paste&height=244&id=uaa46e8a4&originHeight=305&originWidth=706&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=87389&status=done&style=none&taskId=u14bcbb17-a173-4deb-99f7-d465b88d52d&title=&width=564.8)
访问元素特点区别： 
如果访问List集合中的元素，可以直接根据 元素的索引来访问；如果访问Map集合中的元素，可以根据每项元素的 key来访问其value；如果访问Set集合中的元素，则只能根据元素本身 来访问（这也是Set集合里元素不允许重复的原因）。  
## Java11增强的Collection和Iterator接口
**看黑马笔记**
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684413185543-ad98927f-b9d7-48cd-b7c5-b049738a7e6f.png#averageHue=%23f2f0ef&clientId=u86d06547-28e3-4&from=paste&height=378&id=u80c23a35&originHeight=473&originWidth=388&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=42054&status=done&style=none&taskId=uff23d520-a050-4c62-bbd0-03214263940&title=&width=310.4)
Lambda遍历集合
Iterator遍历集合元素
Lambda遍历Iterator
foreach遍历集合元素
注意：
 	Iterator必须依附于Collection对象，若有一个Iterator对 象，则必然有一个与之关联的Collection对象。Iterator提供了两 个方法来迭代访问Collection集合里的元素，并可通过remove()方 法来删除集合中上一次next()方法返回的集合元素。 
### 使用Predicate操作集合
removeIf（Predicate filter）：批量删除符合filter条件的所有元素。 Predicate也是函数式 接口，因此可使用Lambda表达式作为参数。  
```java
package com.itheima.Predicate;

import java.util.HashSet;

public class PredicateTesst {
    public static void main(String[] args) {
        HashSet<Object> books = new HashSet<>();
        books.add("123456");
        books.add("12345");
        books.add("1234567890");
        books.add("123456789");
        //使用Lambda表达式（目标类型是Predicate）过滤集合
        books.removeIf(ele->((String)ele).length()<9);
        System.out.println(books);//[1234567890, 123456789]
    }
}
```
### 使用Stream操作集合
 独立使用Stream的步骤如下： 
①使用Stream或XxxStream的builder()类方法创建该Stream对应 的Builder。 
②重复调用Builder的add()方法向该流中添加多个元素。
 ③调用Builder的build()方法获取对应的Stream。
 ④调用Stream的聚集方法。  
 对于大部分聚集方法而言，每个Stream只能执 行一次。  
 Stream提供了大量的方法进行聚集操作，这些方法既可以是“中 间的”（intermediate），也可以是“末端的”（terminal）。 	➢ 中间方法：中间操作允许流保持打开状态，并允许直接调用后 续方法。上面程序中的map()方法就是中间方法。中间方法的返 回值是另外一个流。
 	➢ 末端方法：末端方法是对流的最终操作。当对某个Stream执行 末端方法后，该流将会被“消耗”且不再可用。上面程序中的 sum()、count()、average()等方法都是末端方法。  
## Set
### HashSet
 HashSet具有以下特点。
 ➢ 不能保证元素的排列顺序，顺序可能与添加顺序不同，顺序也 有可能发生变化。
 ➢ HashSet不是同步的，如果多个线程同时访问一个HashSet，假 设有两个或者两个以上线程同时修改了HashSet集合时，则必须 通过代码来保证其同步。 
➢ 集合元素值可以是null。  
 HashSet集合判断两个元素相等的标准是两个对象通过 equals()方法比较相等，并且两个对象的hashCode()方法返回值也相 等。  
 	如果 两个对象通过equals()方法比较返回true，这两个对象的hashCode值 也应该相同。  
### HashLinkedSet
### TreeSet
 	大部分类在实现compareTo(Object obj)方法 时，都需要将被比较对象obj强制类型转换成相同类型，因为只有相同 类的两个实例才会比较大小。  
 	如果向TreeSet中添加的对象是程序员自定义类的对象，则可以向 TreeSet 中 添 加 多 种 类 型 的 对 象 ， 前 提 是 用 户 自 定 义 类 实 现 了 Comparable接口，且实现compareTo(Object obj)方法没有进行强制类 型转换。但当试图取出TreeSet里的集合元素时，不同类型的元素依然 可能发生ClassCastException异常。
TreeSet判断两对象是否相等：compareTo(Object obj)的返回值是否为0
 如果两个对象通过equals()方法 比较返回true时，这两个对象通过compareTo(Object obj)方法比较应 返回0。 
### EnumSet
EnumSet中都所有都必须是指定枚举类型的枚举值，集合元素有序，以枚举Enum类内的定义顺序来决定集合元素的顺序
Enum不允许加入null元素。
EnumSet类没有暴露任何构造器创建该类的实例，程序应该通过它提供的类方法来创建EnumSet对象
```java
package com.itheima.set.enumset;

import java.util.ArrayList;
import java.util.EnumSet;
import java.util.HashSet;

enum Season{
    SPRING,SUMMER,FALL,WINTER;
}
public class EnumSetTest {
    public static void main(String[] args) {
        //创建一个EnumSet集合，集合元素就是Season枚举类的全部枚举值
        EnumSet<Season> es1 = EnumSet.allOf(Season.class);
        System.out.println(es1);//[SPRING, SUMMER, FALL, WINTER]

        //创建一个EnumSet空集合，指定其集合元素使Season类的枚举值
        EnumSet<Season> es2 = EnumSet.noneOf(Season.class);
        System.out.println(es2);//[]
        //手动添加两个元素
        es2.add(Season.WINTER);
        es2.add(Season.SPRING);
        System.out.println(es2);//[SPRING, WINTER]

        //以指定枚举值创建EnumSet集合
        EnumSet<Season> es3 = EnumSet.of(Season.SUMMER, Season.WINTER);
        System.out.println(es3);//[SUMMER, WINTER]

        EnumSet<Season> es4=EnumSet.range(Season.SUMMER,Season.WINTER);
        System.out.println(es4);//[SUMMER, FALL, WINTER]

        //es5集合元素+es4集合元素 = Season枚举类的全部枚举值
        EnumSet<Season> es5 = EnumSet.complementOf(es4);
        System.out.println(es5);//[SPRING]

        //复制Collection集合中的所有元素来创建EnumSet集合
        HashSet<Season> hs=new HashSet<>();
        hs.add(Season.SUMMER);
        hs.add(Season.FALL);
        EnumSet<Season> es6 = EnumSet.copyOf(hs);
        System.out.println(es6);//[SUMMER, FALL]


    }
}
```
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684659483843-18bbb115-5577-49d5-882c-8d329bc1f6d5.png#averageHue=%23f6f5f4&clientId=u20decc27-6bcc-4&from=paste&height=173&id=uc5fff38f&originHeight=216&originWidth=932&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=56541&status=done&style=none&taskId=u4b9cc6fd-16f7-4399-858d-adbaf1c5a7a&title=&width=745.6)
 EnumSet是所有Set实现类中性能最好的，但它只能保存同一个枚 举类的枚举值作为集合元素。  
## List
### vector
 	 Vector还提供了一个Stack子类，它用于模拟“栈”这种数据结 构，“栈”通常是指“后进先出”（LIFO）的容器。   与Java中的其他集合一样，进栈出 栈的都是Object，因此从栈中取出元素后必须进行类型转换  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684660247811-857d098d-e0d5-414f-b2df-1a4f7d9a3b42.png#averageHue=%23f5f2ef&clientId=u8cc87868-91a9-4&from=paste&height=132&id=uea80cf85&originHeight=165&originWidth=949&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=93494&status=done&style=none&taskId=u7f26abb5-ac7b-4b1f-9369-3ba38d85349&title=&width=759.2)
### 固定长度的List
工具类Arrays提供了asList(Object...a)方法，把数组或指定个数的对象转换为List集合，List集合不是ArrayList实现类的实例，也不是Vector实现类的实例，而是Arrays的内部类ArrayList的实例
 Arrays.ArrayList是一个固定长度的List集合，程序只能遍历访 问该集合里的元素，不可增加、删除该集合里的元素。  
```java
package com.itheima.List.Arrays.ArrayList;

import java.util.Arrays;
import java.util.List;

public class FixedSizeList {
    public static void main(String[] args) {
        List<String> fixedList = Arrays.asList("aa", "bb");
        //获取fixedList的实现类
        System.out.println(fixedList.getClass());//class java.util.Arrays$ArrayList
        //使用方法引用遍历集合元素
        fixedList.forEach(s-> System.out.println(s));
        //UnsupportedOperationException
        //fixedList.add("cc");
        //fixedList.add("dd");
    }
}
```
## Queue
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684660892039-a480518c-8c9e-452f-801a-e5dbf3670ee8.png#averageHue=%23f9f7f4&clientId=u6507549e-6ddd-4&from=paste&height=418&id=u04aa46b8&originHeight=522&originWidth=924&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=200656&status=done&style=none&taskId=ubc45a632-b6f8-48f4-8a5a-65c68450f43&title=&width=739.2)
### PriorityQueue实现类
PriorityQueue是比较标准的队列实现类，其保存队列元素的顺序是按队列元素的大小重新排序。
PriorityQueue不允许插入null元素
排序方式：
1、自然排序：集合中的元素实现Comparable接口，且元素是同一类的多个实例
2、定制排序：创建队列时，传入Comparator对象，该对象负责排序
```java
package com.itheima.Queue.PriorityQueue;

import java.util.PriorityQueue;

public class PriorityQueueTest {
    public static void main(String[] args) {
        PriorityQueue<Integer> pq = new PriorityQueue<>();
        pq.offer(6);
        pq.offer(-3);
        pq.offer(20);
        pq.offer(18);
        pq.offer(18);
        System.out.println(pq);//[-3, 6, 20, 18, 18]
        //获取头部元素
        System.out.println(pq.poll());//-3
    }
}
```
### Deque接口
 Deque接口是Queue接口的子接口，它代表一个双端队列  ，通过方法允许从两端来操作队列元素
 Deque不仅可以当成双端队列使用，而且 可以被当成栈来使用，因为该类里还包含了pop（出栈）、push（入 栈）两个方法。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684661675033-c7a442fe-ecc9-4a96-b2c5-e2498da9bd43.png#averageHue=%23ececec&clientId=u6507549e-6ddd-4&from=paste&height=426&id=ufeece7ce&originHeight=533&originWidth=938&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=125289&status=done&style=none&taskId=u9c88e023-0520-4a62-9f56-0ca1628de68&title=&width=750.4)
#### ArrayDeque(栈、队列)
Deque的实现类ArrayDeque，基于数组实现的双端队列
 ArrayDeque不仅可以作为栈使用， 也可以作为队列使用。  
ArrayDeque作为栈使用：
```java
package com.itheima.Queue.ArrayDequqStack;

import java.util.ArrayDeque;

public class ArrayDequeStack {
    public static void main(String[] args) {
        ArrayDeque<String> stack=new ArrayDeque<>();
        stack.push("aaa");
        stack.push("bbb");
        stack.push("ccc");
        System.out.println(stack);//[ccc, bbb, aaa]
        System.out.println(stack.peek());//ccc
        System.out.println(stack);//[ccc, bbb, aaa]
        System.out.println(stack.pop());//ccc
        System.out.println(stack);//[bbb, aaa]
    }
}
```
ArrayDeque可以作为栈，因此使用数据结构栈时，尽量使用ArrayDeque,避免使用性能较差的Stack集合
ArrayDeque作为队列使用：
```java
package com.itheima.Queue.ArrayDequq;

import java.util.ArrayDeque;

public class ArrayDequeQueue {
    public static void main(String[] args) {
        ArrayDeque<String> queue=new ArrayDeque();
        queue.offer("aaa");
        queue.offer("bbb");
        queue.offer("ccc");
        System.out.println(queue);//[aaa, bbb, ccc]
        System.out.println(queue.peek());//aaa
        System.out.println(queue);//[aaa, bbb, ccc]
        System.out.println(queue.poll());//aaa
        System.out.println(queue);//[bbb, ccc]
    }
}
```
#### LinkedList
LinkedList不仅实现了List接口，还实现了Deque接口
因此即可以根据索引来访问集合中的元素，也可以被当成双端队列来使用（栈、队列）
```java
package com.itheima.Queue.LinkedList;

import java.util.LinkedList;

public class LinkedListTest {
    public static void main(String[] args) {
        LinkedList<String> ll=new LinkedList<>();
        //在队列的尾部加入字符串
        ll.offer("aaa");
        //在栈的顶部加入字符串
        ll.push("bbb");
        //在队列的头部（栈的顶部）加入字符串
        ll.offerFirst("ccc");
        System.out.println(ll);//[ccc, bbb, aaa]
        //访问不删除栈顶元素
        System.out.println(ll.peekFirst());//ccc
        //访问不删除队尾元素
        System.out.println(ll.peekLast());//aaa
        //弹出栈顶元素
        System.out.println(ll.pop());//ccc
        System.out.println(ll);//[bbb, aaa]
        //删除队尾元素
        System.out.println(ll.pollLast());//aaa
        System.out.println(ll);//[bbb]
    }
}
```
 	LinkedList内部以链表的形式 来保存集合中的元素，因此随机访问集合元素时性能较差，但在插 入、删除元素时性能比较出色（只需改变指针所指的地址即可）。  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684663404963-d094dc55-2a04-4333-bb85-a72fe46e8f31.png#averageHue=%23f5f3f1&clientId=u6507549e-6ddd-4&from=paste&height=174&id=u61d45cd8&originHeight=218&originWidth=924&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=78081&status=done&style=none&taskId=u28a3e96b-8734-4c02-b1df-32015298d1e&title=&width=739.2)
## 各种线性表性能分析
数组在随机访问时性能最好，所以内部以数组作为底层实现的集合在随机访问时性能比较好
内部以链表作为底层实现的集合在执行插入和删除操作时性能较好
总体来说ArrayList性能比LinkedList性能好，因此大部分时候考虑ArrayList
Tip:

   - 如果遍历List集合元素，对于ArrayList、Vector集合，应使用随机访问方法（get）遍历元素，对于LinkedList集合，则应采用迭代器（Iterator）来遍历
   - 经常执行插入删除使用LinkedList
   - 使用多线程同时访问List集合中元素，考虑用Collections将集合包装成线程安全的集合
## Map
 从Java源码来看，Java是先实现了Map，然后通过包装一个所 有value都为空对象的Map就实现了Set集合。
  Map接口提供了大量的实现类，Map中包括一个内部类Entry，里面封装了key-value对
所有的Map实现类都重写了toString（）方法，调用Map对象的toString()方法总是返回 字符串：{key1=value1，key2=value2...}  
### HashMap
HashMap里最多有一对键值对的key为null，但可以有无数多个ktey-value的value为null
HashMap必须重写hashCode()方法和equals（）方法

# 第8章 泛型
编译时不检查类型的异常

# 小项目 拼图
图形化界面 GUI 采用图形化的方式显示操作界面
## 主页面
组件
JFrame 最外层窗体
JMenuBar 最上层的菜单
对应JMenu小选项
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683981877851-71430395-87db-48d0-9e31-954fdc565fc8.png#averageHue=%23ede9e4&clientId=u5c4e4d67-748c-4&from=paste&height=378&id=ub5b83ef6&originHeight=473&originWidth=1104&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=80267&status=done&style=none&taskId=uf9252dd3-84fe-4c19-bf37-7ee9dc32f50&title=&width=883.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683981927417-ebdbf789-245d-4a5b-8ef2-9f384132472f.png#averageHue=%23fefefe&clientId=u5c4e4d67-748c-4&from=paste&height=552&id=ua61f0cb3&originHeight=690&originWidth=1400&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=126923&status=done&style=none&taskId=u0288500a-41be-4354-af0f-3ca25ee89ad&title=&width=1120)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683983712527-7cce2d12-b989-4771-a600-ad878f6dd811.png#averageHue=%23d3dcda&clientId=u5c4e4d67-748c-4&from=paste&height=439&id=u9ff00ac9&originHeight=549&originWidth=883&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=49472&status=done&style=none&taskId=ub7004d4c-8ebf-4626-9e90-033fe27bdb1&title=&width=706.4)
JLabel 管理文字和图片的容器
### 事件
就是可以被组件识别的操作
对组件干了某事，就会执行对应的代码
事件源：按钮 图片 窗体
事件：某些操作
如：鼠标单击、鼠标划入
绑定监听：当事件源上发生了某个事件，则执行某段代码
KeyListener 键盘监听  MouseListener 鼠标监听  ActionLister 动作监听
鼠标监听机制：
划入动作
按下动作-----|
--------单击动作
松开动作-----|
划出动作
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684939253990-a78b1cb6-efd5-492c-8537-1587480503c9.png#averageHue=%23dadfdc&clientId=uaf3048c1-df73-4&from=paste&height=516&id=u3090ab48&originHeight=645&originWidth=1505&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=268260&status=done&style=none&taskId=u57dc2771-5281-4876-9145-ef44df528ec&title=&width=1204)
想监听一个按钮的单击事件，有几种方式？

   - 动作监听
   - 鼠标监听中的单击事件
   - 鼠标监听中的松开事件

键盘监听
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684939287091-8cdfa846-09c7-4da7-b0f5-9648c49bfe3c.png#averageHue=%23dde1dd&clientId=uaf3048c1-df73-4&from=paste&height=538&id=ubee317d6&originHeight=672&originWidth=1568&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=220347&status=done&style=none&taskId=ufcb3d951-dfe4-4b1e-98d5-a2f8f7dbcae&title=&width=1254.4)
### 美化
将小图片移动到中下方、
添加背景、
添加边框  jLable.setBorder(new BevelBorder(1))、
优化路径为绝对路径
### 移动图片
1、添加键盘监听，实现接口并重写方法
2、记录空白图片即索引为0的x,y
3、在keyReleased对键盘上下左右判断 ，并对数组越界处理
4、在初始化图片函数，清空并刷新图片
### 快捷键
将图片加载路径改成path变量来记录
#### 加载完整图片
1、在keyPressed对加载完整图片和背景图片，清空刷新
2、在keyReleased重新加载拼图图片
#### 作弊码
将data数组按顺序排列
重新加载图片
### 判断胜利
1、定义一个正确的二维数组win
2、在加载图片前，先判断二维数组中的数字跟win数组中是否相同
3、如果相同则展示正确图标
4、如果不同则不展示正确图标
5、胜利后，再松开按键直接返回空
### 加载步数
1、定义步数变量
2、创建步数容器
3、每按上下左右步数自增一次
### 重新开始
1、给重新游戏绑定点击事件
2、计步器清零
3、重新打乱二维数组中的数字
4、加载图片
关闭游戏
1、给关闭游戏绑定事件
2、结束虚拟机，关闭所有
关于我们
1、绑定事件
2、弹出弹框 jDialog，在ImageIcon由JLabel管理，JLabel放在jDialog上面
## 主函数
new GameJFrame
### GameJframe
创建二维数组，存储图片数据
显示界面 .setVisible()
#### 初始化界面
设置窗口大小、界面标题、界面置顶、界面居中、关闭模式
取消默认居中放置
#### 初始化菜单
创建菜单对象JMenuBar（jMenuBar）  ->
创建选项JMenu  (functionJMenu、aboutJMenu) ->
创建选项对应条目对象JMenuItem  (replayItem、reLoginItem、closeItem  ， accountItem )
将条目添加到选项   .add（）
将选项添加到菜单
给界面设置菜单 .setJMenuBar（）
#### 初始化数据（打乱）
创建一维数组，并打乱数字，填入二维数组
#### 初始化图片
双层循环里嵌套
创建图片对象 new ImageIcon(filename)
创建JLable对象（放入图片）
指定图片位置 .setBounds（）
把管理容器添加到界面 .getContentPane().add()
添加功能
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685006431085-d590232b-9bd7-4846-9fe5-7adab0c262ef.png#averageHue=%23f9f8f8&clientId=ue64b92b6-43df-4&from=paste&height=364&id=u0d6862d7&originHeight=455&originWidth=1041&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=188814&status=done&style=none&taskId=u94bdccf2-4a02-480d-90b9-690c27ec4e2&title=&width=832.8)

# CMD
## 打开CMD
1.Win+R
2.输入CMD
3.按下回车键
## CMD命令
盘符名称+冒号            盘符切换
dir                              查看当前路径下的内容
cd+空格+目录            进入单级目录
cd..                             退回上一级 
cd                               目录1\目录2\...
cd \                             回退到盘符目录
cls                               清屏
exit                              终止 
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1682780645452-fab8a30e-990b-4aca-b33d-c07bb2d8fee2.png#averageHue=%232d2d2d&clientId=uc3e3681f-0db9-4&from=paste&height=170&id=uf2fcbafd&originHeight=213&originWidth=800&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=20232&status=done&style=none&taskId=u33947b73-f1b2-41f4-b739-92e003faf31&title=&width=640)
# 基础知识
## 字面量
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1682826249526-c6dc8133-6ea5-4abe-af08-cc8a03a0a58d.png#averageHue=%23f5f5f2&clientId=uc3e3681f-0db9-4&from=paste&height=566&id=u648aa816&originHeight=707&originWidth=1621&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=215611&status=done&style=none&taskId=u619bf1f1-edaa-4d14-a9dd-879f761e3df&title=&width=1296.8)
# 字符串
## String
1、String类不需要导包
2、字符串不可变，他们的值被创建后不可能被更
### 字符串赋值：
    1、双引号直接赋值时，系统会先检查该字符串在串池中是否存在
        不存在：创建新的
        存在：复用
赋值方式：
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683985622681-b505832d-a0db-438c-b6fb-d521465f6ce0.png#averageHue=%23e8ecbe&clientId=ub97a8c0f-e10d-4&from=paste&height=578&id=udd83b80c&originHeight=723&originWidth=1583&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=256710&status=done&style=none&taskId=uc93e1769-24ae-42f9-b96b-40a9559c1da&title=&width=1266.4)
双引号内存模型：
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683986537604-3d2782d7-1bb4-48c3-b31c-13020edb56c3.png#averageHue=%23f4f1d6&clientId=ub97a8c0f-e10d-4&from=paste&height=574&id=u85df8abd&originHeight=717&originWidth=1655&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=263176&status=done&style=none&taskId=u84eb322e-3585-4953-b9b2-577461298ed&title=&width=1324)
new内存模型：![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683986527870-42ff4f1f-ac9d-4fdb-882d-dcf86a222deb.png#averageHue=%23f6f7e4&clientId=ub97a8c0f-e10d-4&from=paste&height=503&id=ud7e019bd&originHeight=629&originWidth=1574&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=170074&status=done&style=none&taskId=uac9034d3-3f1b-4adb-b3c4-be8c8a142d1&title=&width=1259.2)
### 字符串比较函数
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683986582842-65fda047-07b6-46ae-8352-9ce51d6c7d0c.png#averageHue=%23275939&clientId=ub97a8c0f-e10d-4&from=paste&height=321&id=u831d7750&originHeight=401&originWidth=1317&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=117679&status=done&style=none&taskId=ub174b4ed-92b4-4f82-abe1-c023b12c8c9&title=&width=1053.6)
## Stringbuild
提高String字符串拼接速度
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683987971187-f27cc928-84e1-45e2-86b5-37d1d90efff2.png#averageHue=%23f4f6d7&clientId=udb06a184-3034-4&from=paste&height=499&id=u690f770f&originHeight=624&originWidth=1341&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=146739&status=done&style=none&taskId=uec73e3e0-270c-44f4-8bb5-7949605224c&title=&width=1072.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683988023696-d12a2bd9-7ca4-44c2-a578-b971633ea443.png#averageHue=%23fefefb&clientId=udb06a184-3034-4&from=paste&height=488&id=u5c9bda9f&originHeight=610&originWidth=1395&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=186719&status=done&style=none&taskId=u86d04ac9-cf1b-45e5-afa8-c98b159e272&title=&width=1116)
使用StringBuilder场景：
1、字符串拼接
2、字符串反转
## StringJoiner
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683989307985-93109d54-dfca-45cb-9177-a1b20beca22a.png#averageHue=%23f6f6f6&clientId=udb06a184-3034-4&from=paste&height=337&id=u03ad779b&originHeight=421&originWidth=1247&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=84683&status=done&style=none&taskId=u7b9a8fa3-1fa9-4979-922d-b482898987a&title=&width=997.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683989327198-7794215d-fd0e-42f5-bc89-ddb1190af008.png#averageHue=%23f4f5f0&clientId=udb06a184-3034-4&from=paste&height=378&id=ub5458a2f&originHeight=473&originWidth=1368&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=125154&status=done&style=none&taskId=uafa3184f-a1c9-4448-a461-571fa562070&title=&width=1094.4)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683989373494-ba43841f-6655-47ae-9485-02ad2ff0ba08.png#averageHue=%23eceeec&clientId=udb06a184-3034-4&from=paste&height=361&id=u0fcb9e66&originHeight=451&originWidth=1319&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=131166&status=done&style=none&taskId=u3e74f566-c3d1-4808-9f8e-6e6809761e6&title=&width=1055.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683989595134-c5c130cf-945e-4f9c-b7d0-71745610e00a.png#averageHue=%23fbf8f7&clientId=udb06a184-3034-4&from=paste&height=424&id=u1623a47c&originHeight=530&originWidth=1441&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=255749&status=done&style=none&taskId=u8f608cf9-8fb7-467b-a666-cbef28992a8&title=&width=1152.8)
区别演示：
Tip:在添加的时候只能添加字符串
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684766221456-c7af8a6f-f1c9-4094-abfd-f42002638f32.png#averageHue=%23dce1e6&clientId=u042fefcc-0abf-4&from=paste&height=227&id=uc32d4b71&originHeight=284&originWidth=872&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=154819&status=done&style=none&taskId=ufef0eb13-ff2d-4426-a4b7-fabec332642&title=&width=697.6)
## 底层逻辑
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683989797381-6baa843f-b258-435e-9cab-f2b55b1e92c9.png#averageHue=%23f5f8cb&clientId=udb06a184-3034-4&from=paste&height=593&id=ud6cb33c6&originHeight=741&originWidth=1516&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=253232&status=done&style=none&taskId=u01655fb0-3182-4645-8fbb-034fcb226ca&title=&width=1212.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683989895818-a1c2919b-2240-42b9-b4b0-20bdc51ad34d.png#averageHue=%23fdfdf5&clientId=udb06a184-3034-4&from=paste&height=426&id=uf975ddf3&originHeight=533&originWidth=1255&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=170562&status=done&style=none&taskId=u4afaa2c1-6805-4640-85e4-eab1a7b2dc9&title=&width=1004)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683990005562-c8360158-4f6e-455d-9050-64b8da63a4b8.png#averageHue=%23fcfbf1&clientId=udb06a184-3034-4&from=paste&height=494&id=ue436c6f3&originHeight=618&originWidth=1381&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=277611&status=done&style=none&taskId=ube4f4f9d-43f0-4a7c-b53b-7c43391da7c&title=&width=1104.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683990048466-e599e6bd-c364-4e6b-8fdd-af5a8051ea4b.png#averageHue=%23fbf9ed&clientId=udb06a184-3034-4&from=paste&height=415&id=ufbd22d19&originHeight=519&originWidth=1102&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=152823&status=done&style=none&taskId=ufd5dcc0c-dc88-453a-9c8c-60037e394e9&title=&width=881.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683990069686-9fd01f68-9c21-4ca6-a380-9f0399906d07.png#averageHue=%23fefdfd&clientId=udb06a184-3034-4&from=paste&height=295&id=ue5238da9&originHeight=369&originWidth=1438&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=207285&status=done&style=none&taskId=u97215244-50dc-4e36-b7e0-5dacfaa586c&title=&width=1150.4)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683990160838-6b56b46e-a93e-42da-9ffa-ff16adda56c0.png#averageHue=%23f6e6e3&clientId=udb06a184-3034-4&from=paste&height=293&id=uf648c849&originHeight=366&originWidth=830&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=123292&status=done&style=none&taskId=u5c3c4ba7-4195-465e-8081-52b4f2dd9c3&title=&width=664)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683990475838-f37a9c20-05e1-4baa-a9eb-f3765c84dc7f.png#averageHue=%23f6e3e0&clientId=udb06a184-3034-4&from=paste&height=600&id=ueca085ac&originHeight=750&originWidth=1501&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=441206&status=done&style=none&taskId=u7b35c1db-2d0a-4d0a-82e7-aadcc732860&title=&width=1200.8)

# 多态
## 基础
1、概念：同类型的对象，表现出的不同形态
2、表现形式：父亲类型 对象名称=子类对象
3、前提：
   （1）有继承关系
   （2）有父类引用指向子类对象
   （3）有方法重写
4、好处：
    使用父类作为形参，可以接收所有子类对象，体现多态的扩展性与便利性
    Test1
 5、多态中调用成员的特点：**Test2**
调用成员变量：编译看左边，运行看左边
调用成员方法：编译看左边，运行看右边
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683044043543-823a37f9-17bb-484e-ab0c-d840739823ca.png#averageHue=%23f3f5cd&clientId=u4b9a6e21-defe-4&from=paste&height=685&id=ubcf867a3&originHeight=856&originWidth=1706&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=498503&status=done&style=none&taskId=uef81f2e5-6806-4c46-ae03-f68cdd86d27&title=&width=1364.8)
6、多态的优势和弊端：
(a）优势：
（1)在多态形式下，右边对象可以实现解耦合，便于扩展和维护  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683044270423-044e0334-9d33-4adb-807e-4de9daaf890e.png#averageHue=%23ede9d3&clientId=u4b9a6e21-defe-4&from=paste&height=126&id=u876490a9&originHeight=158&originWidth=931&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=73847&status=done&style=none&taskId=ubb065d3f-fc70-4612-82ec-7399c559aaa&title=&width=744.8)
（2）定义方法的时候，使用父类作为参数，可以接收所有子类对象，体现多态扩展性和便利  ** Test1**
(b)弊端：
不能调用子类的特有功能 **Test3**
报错的原因：当调用成员方法时，编译看左边，运行看右边
那么在编译时会先检查左边的父类中有没有这个方法，如果没有直接报错 
```java
解决方法：
（1）转换回子类型
    细节：转换时不能瞎转，如果转成其他类的类型会报错
    Dog d=(Dog)a;
	d.lookHome();
（2）条件判断
    if(a instanceof Dog){
    	Dog d=(Dog)a;
   	 	d.lookHome();
	}else if(a instanceof Cat){
    	Cat c=(Cat) a;
    	c.catchMouse();
	}else{
    	System.out.println("没有这个类型，无法转换");
	}
```
类型转换的方式：
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683045760283-63bc0ca8-740a-4d71-99fa-ebe55a19574d.png#averageHue=%23edede2&clientId=u4b9a6e21-defe-4&from=paste&height=104&id=u904350fc&originHeight=130&originWidth=578&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=39890&status=done&style=none&taskId=udb809525-0715-474b-92ba-458f2761246&title=&width=462.4)
## 包
包：
就是文件夹。用来管理各种不同功能的java类，方便后期代码维护
包名的规则：公司域名反写+包的作用，需要全部英文小写，见名知意
    eg:com.itheima.domain
全类名：com.itheima.domain.Student
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683086624967-6ae1a503-7d35-48b8-952a-bd4dca7d8566.png#averageHue=%23f9f8ea&clientId=uf560a116-711a-4&from=paste&height=260&id=uf9c3d446&originHeight=325&originWidth=834&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=61091&status=done&style=none&taskId=u603749f6-9400-4620-88f5-f659246bd32&title=&width=667.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683086678760-d51e27f3-e7f6-4dcd-a779-87b5a25a5d84.png#averageHue=%23faf9e2&clientId=uf560a116-711a-4&from=paste&height=306&id=uc0a3ed3c&originHeight=382&originWidth=722&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=79120&status=done&style=none&taskId=u19fb7b93-39c1-45cb-9854-fd56c0f0e08&title=&width=577.6)
使用其他类的规则：
（1）使用同一个包中的类时，不需要导包
（2）使用java.lang包中的类时，不需要导包
（3）其他情况都需要导包
（4）如果同时使用两个包中的同名类，需要用全类名
## final
修饰方法：表明该方法是最终方法，不能被重写
修饰类：表明该类是最终类，不能被继承
修饰变量：叫做常量，只能被赋值一次
常量：
    实际开发中，常量一般作为系统的配置信息，方便维护，提高可读性
    常量的命名规则：
    （1）单个单词：全部大写
    （2）多个单词：全部大写，单词之间用下划线隔开
    细节：
    final修饰的变量是基本类型：那么变量存储的数据值不能发生改变
    final修饰的变量是引用类型，那么变量存储的地址值不能发生改变，对象内部的可以改变
**Test4**
## 权限修饰符
权限修饰符：
   用来控制一个成员能够被访问的范围的
   可以修饰成员变量、方法、构造方法、内部类
**   demo1 demo2**
实际开发中，一般只用private和public
（1）成员变量私有
（2）方法公开
特例：如果方法中的代码是抽取其他方法中共性代码，这个方法一般也私有
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683116661237-7d893612-88fd-4cd0-978b-9bf1406a62b1.png#averageHue=%23f5f9f7&clientId=uf560a116-711a-4&from=paste&height=554&id=c3qGv&originHeight=692&originWidth=1488&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=168332&status=done&style=none&taskId=u01acdea5-34aa-4424-bf4a-812fcadc9c5&title=&width=1190.4)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683116736549-a0cd2386-6453-4074-bb98-2ffda1a0ec4c.png#averageHue=%23f4d8d8&clientId=uf560a116-711a-4&from=paste&height=343&id=ud4dc5f51&originHeight=429&originWidth=1389&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=101586&status=done&style=none&taskId=uca7f16f8-4bcf-4fde-805b-74521a7aee2&title=&width=1111.2)
代码块：
（1)局部代码块：
    写在方法里单独的大括号
    作用：提前结束变量的生命周期
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683117995486-2d691cf2-c5a6-4c4f-b487-efff052d57f3.png#averageHue=%23faf7df&clientId=uf560a116-711a-4&from=paste&height=374&id=ue37054c7&originHeight=373&originWidth=630&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=45583&status=done&style=none&taskId=uc9d4d07f-04d8-4994-8ab6-4c9ff5b4929&title=&width=631)
(2)构造代码块：
    写在成员位置的代码块
    作用：可以把多个构造方法中重复的代码抽取出来
    执行时机：我们在创建本类对象的时候会先执行构造代码块再执行构造方法
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683118023749-78705d82-5acf-434c-a070-d473d4d6b9c2.png#averageHue=%23faf9df&clientId=uf560a116-711a-4&from=paste&height=614&id=u3209f567&originHeight=768&originWidth=1097&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=145997&status=done&style=none&taskId=ufeb3b684-b915-413f-ac01-2fd8155d28b&title=&width=877.6)

当两个构造方法使用重复语句，而另一个构造方法不想使用该语句可以：
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683118294746-3dba2746-3958-4cff-ae65-e804e73274dc.png#averageHue=%23f9f9cb&clientId=uf560a116-711a-4&from=paste&height=457&id=u864ab524&originHeight=571&originWidth=1634&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=237499&status=done&style=none&taskId=u2fe8e867-48eb-48f8-bc75-64927a61944&title=&width=1307.2)
（3）静态代码块：
    格式：static{}
    特点：需要通过static关键字修饰，随着类的加载而加载，并且自动触发，只执行一次
    使用场景：在程序刚开始时，进行数据初始化，且初始化一次
主函数也可被手动多次调用

# 接口
## 基础：
### 1、接口的定义和使用：
    （1）接口用关键字interface来定义
        public interface 接口名{}
    （2）接口不能实例化
    （3）接口和类之间是实现关系，通过implements关键字表示
        public class类名 implements 接口名{}
    （4）接口的子类（实现类）
        要么重写接口中的所有抽象方法
        要么是抽象类
注意1：接口和类的实现关系，可以单实现，也可以多实现
        public class 类名 implements 接口1，接口2{}
注意2：实现类还可以在继承一个类的同时实现多个接口
        public class 类名 extends 父类 implements 接口1，接口2{}
  **  test1**
### 2、接口中成员的特点：
（1）成员变量
只能是常量
默认修饰符：public static final
（2）构造方法
没有
（3）成员方法
只能是抽象方法
默认修饰符：public abstract
jdk7以前：接口中只能定义抽象方法
### 3、接口和类之间的关系
（1）类和类的关系：
继承关系，只能单继承，不能多继承，但是可以多层继承
（2）类和接口的关系：
实现关系，可以单实现，也可以多实现，还可以在继承一个类的同时实现多个接口
实现多个接口，所有的方法都必须重写
（3）接口和接口的关系
继承关系，可以单继承，也可以多继承
实现类实现最下面子接口，需要重写这个体系中所有抽象方法
### 4、接口中的技巧
（1）JDK8以后接口中新增的方法：
 	a.默认方法：
            允许在接口中定义默认方法，需要使用关键字defult修饰
            作用：解决接口升级的问题
        接口中默认方法的定义格式：
            格式：public default 返回值类型 方法名（参数列表）{}
            范例：public default void show(){}
        接口中默认方法的注意事项：
            默认方法不是抽象方法，所以不强制被重写。但如果被重写，重写的时候去掉default关键字
            public 可以省略，default不能省略
            如果实现了多个接口，多个接口中存在相同名字的默认方法，子类就必须对该方法进行重写
    b.静态方法：
        允许在接口中定义静态方法，需要用static修饰
        接口中静态方法的定义格式：
            格式：public static 返回值类型 方法名（参数列表）{}
            范例：public static void show(){}
        接口中静态方法的注意事项：
            静态方法只能通过接口名调用，不能通过实现类名或许对象名调用
            public 可以省略，static 不可以省略
JDK9新增的方法：
    接口中私有方法的定义格式：
    格式1：private 返回值类型 方法名（参数列表）{}
    范例1：private void show(){}

    格式2：private static 返回值类型 方法名（参数列表）{}
    范例2：private static void method(){}![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683205765252-4aa94f4d-8cce-4d09-b4c4-82069d41cc35.png#averageHue=%23fafaf9&clientId=u1d123841-4232-4&from=paste&height=521&id=ua00cb55d&originHeight=651&originWidth=984&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=170130&status=done&style=none&taskId=ub28a8e87-4506-4bb2-94e9-c14ab76514b&title=&width=787.2)![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683205825403-e0612a6c-b7b3-45a1-95c2-30f401d104f1.png#averageHue=%23c5c5c5&clientId=u1d123841-4232-4&from=paste&height=362&id=u23a81e2e&originHeight=453&originWidth=904&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=111987&status=done&style=none&taskId=u1b5da7f0-668f-459e-a440-6c87412dfd1&title=&width=723.2)
（2）接口的应用：
    （1）接口代表规则，是行为的抽象，想要让哪个类拥有一个行为，就让这个类实现对应接口就可以了
    （2）当一个方法的参数是接口时，可以传递接口所有实现类的对象，这种方式称为接口多态
（3）适配器设计模式：
    解决接口与接口实现类之间的矛盾问题
    1、当一个接口中抽象方法过多，但事实我只要使用其中一部分的时候，就可以适配器设计模式
    2、书写步骤：
        编写中间类XXXAdapter,实现对应接口
        对接口中的抽象方法进行空实现
        让真正的实现类继承中间类，并重写需要用的方法
        为了避免其它类创建适配器对象，中间的适配器类用aabstract进行修饰
    test5

# 内部类
## 内部类介绍
意义：
内部类表示的事物是外部类的一部分，内部类单独出现没有任何意义
内部类的访问特点：
内部类可以直接访问外部类的成员，包括私有
外部类要访问内部类的成员，必须创建对象
    **t1**

## 成员内部类
    写在成员位置的，属于外部类的成员
    成员内部类可以被一些修饰符修饰
    在成员内部类里，JDK16以后可以定义静态变量
获取成员内部类对象：
    在外部类编写方法，对外提供内部类的对象
    直接创建：外部类名.内部类名 对象名=外部类对象.内部类对象;
Outer.Inner oi=new Outer().new Inner();
**    t2**
当外部类和内部类重名时：
    Sout（Outer.this.变量名）
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683722718803-19bb32a6-05fd-4dcc-9211-61b67af50b17.png#averageHue=%23f4f5cd&clientId=u5b830c3b-c772-4&from=paste&height=587&id=u88235f21&originHeight=734&originWidth=1583&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=364100&status=done&style=none&taskId=u95ab4753-9332-4e7c-87a9-3fdd6be920f&title=&width=1266.4)

## 静态内部类：
    静态内部类只能访问外部类总的静态变量和静态方法
    如果需要访问非静态的需要创建对象
    创建静态内部类对象的格式：外部类名.内部类名 对象名=new 外部类名.内部类名（）;
                            Outer.Inner oi=new Outer,Inner();
    调用非静态方法：先创建对象，用对象调用
                    Outer Inner oi=new Outer.Inner();
                    oi.show();
    调用静态方法的格式：外部类名.内部类名.方法名（）
                        Outer.Inner.show()
 
## 局部内部类：
    将内部类定义在方法里面就叫做局部内部类，类似于方法里面的局部变量
    外界无法直接使用，需要在方法内创建对象并使用
    该类可以直接访问外部类的成员，也可以直接访问方法内的局部变量
 

## 匿名内部类:
    本质上就是隐藏了名字的内部类,可以写在成员位置，也可以写在局部位置
    格式：
        new 类名或者接口名(){
            重写方法；
        };
    格式的细节：
        包含了继承或实现，方法重写，创建对象
        整体就是一个类的子类对象或接口的实现类对象
    使用场景：
        当方法的参数是接口或者类时
        以接口为例，可以传递这个接口的实现类对象
        如果实现类只要使用一次，就可以用匿名内部类简化代码
 */


![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683725282306-0759b3f9-8d33-4752-a0e6-5f2f95db7d83.png#averageHue=%23fafaf9&clientId=u5b830c3b-c772-4&from=paste&height=492&id=u26276cf3&originHeight=615&originWidth=1540&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=263014&status=done&style=none&taskId=u12a320c3-20b9-4061-9194-ec26ccb31fc&title=&width=1232)
匿名内部类 反编译
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1683725672115-c2133979-e7a9-47fb-80b1-42eb80eebf48.png#averageHue=%23878787&clientId=u5b830c3b-c772-4&from=paste&height=633&id=udc00fa9f&originHeight=791&originWidth=1428&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=115755&status=done&style=none&taskId=u7389adbc-1c77-424a-87b8-9c29ce008cc&title=&width=1142.4)
# 集合
## 集合
集合和数组对比：
（1）长度
    数组长度固定，集合长度可变
（2）存储类型
    数组可以存基本数据类型和引用数据类型
    集合可以存引用数据类型，基本数据类型需要包装
### 1、创建集合对象
    泛型：限定集合中存储数据的类型
    ArrayList<String> list=new ArryList<>();
    //打印对象不是地址值，是集合中存储数据内容
    //在展示时会拿[]把所有数据进行包裹
    sout(list)
    结果：
    []
### 2、增删改查
   ** test1**
## Collection
### Collection的系统图
单列集合顶层接口Collection
有序：存和取的顺序是一样的
可重复：可存放相同的元素
有索引：可以通过索引查找元素
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684370954294-c1a4c86f-566b-47ae-91c2-4ba3a5ac12a0.png#averageHue=%23fbfbf6&clientId=ue92e0f6d-720c-4&from=paste&height=401&id=u522caaf6&originHeight=501&originWidth=852&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=148988&status=done&style=none&taskId=uebe6f7d0-27c1-4a3a-8d52-b7ed45b0e04&title=&width=681.6)
Vector被淘汰，基本不用
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684505209916-71a468cc-a69f-4e4d-8f37-1a04d5aef7cb.png#averageHue=%23f1994f&clientId=ue3c4ec11-c744-4&from=paste&height=601&id=uf479f209&originHeight=751&originWidth=1178&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=217446&status=done&style=none&taskId=u718158c1-f6e9-4fb5-b102-52adf1e041b&title=&width=942.4)
### 普通方法
Collection是所有单列集合的顶层接口，所有的方法被List和Set系列集合共享
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684371011869-4081912f-18c7-4a4d-aa90-1f26dbfaba40.png#averageHue=%23e7dddd&clientId=ue92e0f6d-720c-4&from=paste&height=574&id=u64d2d2da&originHeight=717&originWidth=1452&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=257035&status=done&style=none&taskId=ud12ade61-12e3-4000-a581-55b339c7bdf&title=&width=1161.6)
D:\程序代码\Java\basic.code\ArryList\src\com\itheima\Collection\CollectionMethodTest.java
```java
package com.itheima.Collection;

import java.util.ArrayList;
import java.util.Collection;

public class CollectionMethodTest {
    public static void main(String[] args) {
        //注意：
        //Collection是一个接口，不能直接创建它的对象
        //所以在学习它的方法时，只能创建它实现类的对象
        //实现类：ArrayList

        Collection<String > coll=new ArrayList<>();

        //1、添加元素
        /*
细节：如果在List系列集合中添加数据，表示方法返回true,因为List系列是允许元素重复
如果在Set系列集合中添加数据,如果当前要添加的元素不存在，方法返回true，表示添加成功
如果当前要添加的元素存在，方法返回false，表示添加失败
因为Set系列的集合不允许重复
*/
        coll.add("aaa");
        coll.add("bbb");
        System.out.println(coll);

        //2、清空
        // coll.clear();
        //System.out.println(coll);

        //3、删除
        /*
因为Collection里面定义的是特性的方法，所以不能通过索引进行删除，只能通过元素的对象进行删除
方法会有一个布尔类型的返回值，删除成功返回true，删除失败返回false\
如果删除的元素不存在，则返回flase
*/
        coll.remove("aaa");
        System.out.println(coll);

        //4、判断元素是否包含
        /*
细节：底层是依赖equals方法进行判断是否存在
所以如果集合中存储的是自定义对象，也想通过contains方法来判断是否包含，那么javabean类中，一定要重新写equals方法
如果存储的是自定义对象，没有重写equals方法，那么默认使用Object类中的equals方法进行判断，而Object类中的equals方法，依赖地址值进行判断

*/
        boolean result=coll.contains("aaa");
        System.out.println(result);

        //5、判断集合是否为空
        boolean result2=coll.isEmpty();
        System.out.println(result2);

        //6、获取集合的长度
        int size=coll.size();
        System.out.println(size);
    }
}
```
### Collection的遍历方式
> 迭代器遍历：在遍历过程中需要删除元素，请使用迭代器
>    Iterator<String> it=coll.iterator();
>         while(it.hasNext()){
>             String str=it.next();
>             System.out.println(str);
>         }
> 增强for遍历       for(String s:coll)                                  仅仅想遍历使用for和Lambda    
> Lambda表达式遍历     coll.forEach(s->sout(s))        


#### 迭代器遍历
迭代器不依赖索引
迭代器在java类是Iterator,迭代器是集合专用的遍历方式
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684373082952-86a6c176-838e-4e7d-9e82-c0154b9fa6d8.png#averageHue=%23e9d2d1&clientId=ue92e0f6d-720c-4&from=paste&height=342&id=ud22777c3&originHeight=427&originWidth=1032&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=132868&status=done&style=none&taskId=uf71518c2-10d4-41db-92b2-e5be6fe2654&title=&width=825.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684373314734-ac63f145-fbc4-4756-9d21-7120a3dd8488.png#averageHue=%23f0ede7&clientId=ue92e0f6d-720c-4&from=paste&height=452&id=ud44a9ccc&originHeight=565&originWidth=1028&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=124209&status=done&style=none&taskId=u32cce2f2-48b1-4942-ad87-fea63c1f216&title=&width=822.4)
细节：
  （1）报错NoSuchElementException  
迭代器已到最后一个后面，再抢行调用next会报错
报错报的是没有这个元素异常，而不是索引越界，是因为迭代器不是使用索引遍历
    (2)迭代器变遍历完毕，指针不会复位
 	如果还想再次遍历，重新构迭代器，遍历
   （3）循环中只能用一次next方法
    （4）迭代器遍历时，不能用 集合 的方法进行增删
      如果必须删除，则使用迭代器提供的remove删除
添加暂时没办法	
```java
package com.itheima;

import java.util.ArrayList;
import java.util.Collection;
import java.util.Iterator;

public class iterator {
    public static void main(String[] args) {

        //1、创建集合并添加元素
        Collection<String> coll=new ArrayList<>();
        coll.add("aaa");
        coll.add("bbb");

        //2、获取迭代器对象
        //迭代器就好比是一个箭头，默认指向集合的0索引处
        Iterator<String> it=coll.iterator();

        //3、利用循环不断地去获取集合中的每一个元素
        while(it.hasNext()){
            //next方法的两件事，获取元素并移动指针
            String str=it.next();
            System.out.println(str);
        }
        //当上面循环结束之后，迭代器的指针已经指向了最后没有元素的位置
        // System.out.println(it.next());//NoSuchElement

        //迭代遍历完毕，指针不会复位
        System.out.println(it.hasNext());
        System.out.println(it.hasNext());//false

        //如果我们要继续第二次遍历集合，只能再获取一个新的迭代器
        Iterator<String> it2= coll.iterator();
        while(it2.hasNext()){
            String str= it2.next();
            System.out.println(str);
        }
    }
}
```
#### 增强for遍历
增强for的底层就是迭代器，为了简化迭代器的代码书写
是JDK5以后出现，内部原理就是一个Iterator迭代器
所有的单列集合和数组才能用到增强for遍历
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684399902274-4f8ac2fe-ca2a-4651-8605-497642d825c1.png#averageHue=%23f9f5e0&clientId=u41708a57-2ae9-4&from=paste&height=290&id=uecd6ff23&originHeight=363&originWidth=1598&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=108924&status=done&style=none&taskId=u9308498b-1147-4cf0-9d06-d510671ac4f&title=&width=1278.4)

Tip:修改增强for中的变量，不会集合中原本的数据
```java
package com.itheima.strenghfor;

import java.util.ArrayList;
import java.util.Collection;

public class StrengthFor {
    public static void main(String[] args) {
        //1、创建集合并添加元素
        Collection<String> coll=new ArrayList<>();
        coll.add("zhangsan");
        coll.add("lisi");
        coll.add("wangwu");

        //2、利用增强for进行遍历
        //快速生成方式，集合名字+for 回车
        //注意点：s其实就是一个第三方工具，在循环过程中依次表示集合中的每一个元素
        for(String s:coll){
            System.out.println(s);
        }

    }
}
```

#### Lamabda表达式遍历
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684401370800-4670ea10-0fa7-4968-99b0-d44edb6c6f6f.png#averageHue=%23f2e2d9&clientId=u41708a57-2ae9-4&from=paste&height=369&id=ub5fc1d94&originHeight=461&originWidth=1566&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=165219&status=done&style=none&taskId=u69972284-199a-4d58-be94-ed4d363bdd5&title=&width=1252.8)
```java
package com.itheima.foreach;

import java.util.ArrayList;
import java.util.Collection;
import java.util.Iterator;
import java.util.function.Consumer;

public class ForEachTesst {
    public static void main(String[] args) {
        Collection<Integer> c1=new ArrayList<>();
        c1.add(1);
        c1.add(2);
        for (Integer integer : c1) {
            System.out.println(integer);
        }
        Collection<String> coll=new ArrayList<>();
        coll.add("zhangsan");
        coll.add("wangwu");
        coll.add("lisi");

        //2、利用匿名内部类的形式
        /*
        底层原理：
        其实也会自己遍历集合，依次得到每个元素
        把得到的每个元素，传递给下面的accept方法

         */
//        coll.forEach(new Consumer<String>() {//new一个类实现Consumer接口重写accept方法
//            @Override
//            //s依次表示集合中的每一个数据
//            public void accept(String s) {
//                System.out.println(s);
//            }
//        });

        //lambda表达式遍历Iterator
        Iterator<String> it1 = coll.iterator();
        it1.forEachRemaining(obj-> System.out.println("迭代集合元素："+obj));

        //lambda表达式遍历集合
        //()->{}

        coll.forEach(s-> System.out.println(s));

    }
}

```
## List
Collection的方法List都继承了
List集合因为有索引，所以多了很多索引操作的方法
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684417674968-2e5e4a2d-b25b-44ac-a14a-48630424ae95.png#averageHue=%23ecede6&clientId=u068c9422-3049-4&from=paste&height=576&id=u63893d8a&originHeight=720&originWidth=1460&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=284227&status=done&style=none&taskId=u29c0a2c7-ad6a-45ab-bf40-6fd8bffa1eb&title=&width=1168)
普通方法
```java
package com.itheima.List.MethodTest;

import java.util.ArrayList;
import java.util.List;

public class MethodTest {
    public static void main(String[] args) {
        List<String> list=new ArrayList<>();
        list.add("aaa");
        list.add("bbb");
        list.add("ccc");

        //1、添加指定位置元素
        //        list.add(1,"QQQ");

        //2、删除
        //        String remove = list.remove(0);
        //        System.out.println(remove);

        //3、修改
        //        String result = list.set(0, "QQQ");
        //        System.out.println(result);


        //获得元素
        String s = list.get(0);
        System.out.println(s);
        System.out.println(list);
    }
}
```
### 遍历方法
:::warning
迭代器遍历                         在遍历过程中需要删除元素
列表迭代器遍历                   在遍历过程中需要添加元素
增强for遍历		         
  仅仅想遍历，那么使用增强for或Lambda
Lambda表达式遍历	
普通for循环（因为List集合存在索引）  遍历时想操作索引
:::
#### 列表迭代器遍历
```java
//额外添加了一个方法：在遍历的过程中，可以添加元素
//①对象类型不同
ListIterator<String> it= list.listIterator();
//注意上处是创建的ListIterator对象而不是Iterator
while(it.hasNext()){
    String str=it.next();
    //②可以增加元素
    if("bbb".equals(str)){
        it.add("qqq");
    }
}
//③打印循环外打印，否则str仅仅是第三方工具，不会对它进行改变
System.out.println(list);
```
## ArraList
### 底层原理
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684419871835-e85c503a-e170-40d9-b7bb-422452c4aeec.png#averageHue=%23fbf8f8&clientId=u068c9422-3049-4&from=paste&height=632&id=u275e361c&originHeight=790&originWidth=1662&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=304748&status=done&style=none&taskId=u6139baee-fdf5-4008-8919-4969322b443&title=&width=1329.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684420510991-f02180c3-3d97-4cf3-80fd-ef0dca94b25a.png#averageHue=%23ebe4dc&clientId=u068c9422-3049-4&from=paste&height=605&id=u8caa8bd5&originHeight=756&originWidth=1612&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=518159&status=done&style=none&taskId=uec3232d3-e341-415d-a43d-59aafa47925&title=&width=1289.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684420488456-1e21b117-ff67-4a30-9a38-26e3224f1878.png#averageHue=%23f0eee5&clientId=u068c9422-3049-4&from=paste&height=628&id=u3ce7a279&originHeight=785&originWidth=1669&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=659082&status=done&style=none&taskId=u9dc5317b-d952-4679-a116-24e31287737&title=&width=1335.2)
## Vector
 	 Vector还提供了一个Stack子类，它用于模拟“栈”这种数据结 构，“栈”通常是指“后进先出”（LIFO）的容器。   与Java中的其他集合一样，进栈出 栈的都是Object，因此从栈中取出元素后必须进行类型转换  
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684660247811-857d098d-e0d5-414f-b2df-1a4f7d9a3b42.png#averageHue=%23f5f2ef&clientId=u8cc87868-91a9-4&from=paste&height=132&id=DEHS0&originHeight=165&originWidth=949&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=93494&status=done&style=none&taskId=u7f26abb5-ac7b-4b1f-9369-3ba38d85349&title=&width=759.2)
## LinkedList
底层数据结构是双链表，查询慢，增删快，但是如果操作是首位元素，速度也极快
LinkedList本省多了很多直接操作首位元素的API
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684421370094-f9a8839e-c72d-4332-b814-79a75f60b5a3.png#averageHue=%23f9fefd&clientId=u068c9422-3049-4&from=paste&height=547&id=ub1969eda&originHeight=684&originWidth=1418&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=331063&status=done&style=none&taskId=u45c480cf-9b3f-4248-9cfa-08a053721a3&title=&width=1134.4)
### LinkedList底层分析原理
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684422572480-ee2c3379-5e34-4748-9ac2-cf634e9ecba5.png#averageHue=%23f9f9f9&clientId=u068c9422-3049-4&from=paste&height=690&id=u942b375b&originHeight=862&originWidth=1851&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=398586&status=done&style=none&taskId=u207d9069-a69d-423c-a129-8419c7341c8&title=&width=1480.8)
### 迭代器底层分析原理
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684422500960-9d87733d-7e22-4d7b-b9c5-624214782c21.png#averageHue=%23e9d5c9&clientId=u068c9422-3049-4&from=paste&height=597&id=ud3cd09a0&originHeight=746&originWidth=1903&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=641869&status=done&style=none&taskId=uc0fa05fe-ab1b-4849-9b73-bdd7533655f&title=&width=1522.4)
## 泛型深入
泛型：是JDK5中引入的特性，可以在编译阶段约束操作的数据类型，并进行检查
泛型的格式：<数据类型>
注意：泛型只支持引用类型
如果给集合没有指定类型，默认所有数据类型都是Object型，坏处在获取数据时，无法使用它的特有行为
泛型的好处：
统一数据类型
把运行时期的问题提前到编译期间，避免了强制类型转换可能出现的异常，因为在编译阶段类型就能确定下来
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684499700178-36c4439f-59be-4f92-b59d-1af53c1a1af5.png#averageHue=%23f7f0df&clientId=ue3c4ec11-c744-4&from=paste&height=318&id=u4370ef91&originHeight=398&originWidth=1556&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=125710&status=done&style=none&taskId=uf732ca9a-7102-45aa-b499-05c301c05cc&title=&width=1244.8)
细节：

- 泛型中不能写基本数据类型
- 指定泛型的具体类型后，传递数据，可以传入该类型或其子类类型

![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684499883421-f8d470b1-47de-4700-8eb2-a0f4451c6d11.png#averageHue=%23f4edcf&clientId=ue3c4ec11-c744-4&from=paste&height=244&id=u9219b379&originHeight=305&originWidth=723&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=90445&status=done&style=none&taskId=u8a44ad48-d091-4ede-934b-53776b412ae&title=&width=578.4)

- 如果不写泛型，类型默认是Object
### 泛型类
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684500020936-9ae82b3d-cbcd-47cb-8fdc-f3341970df4a.png#averageHue=%23f2f9f3&clientId=ue3c4ec11-c744-4&from=paste&height=565&id=u79d4e61b&originHeight=706&originWidth=1598&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=308703&status=done&style=none&taskId=u23694e3d-57e2-4162-ba2d-5b2a3c2f04b&title=&width=1278.4)
```java
package com.itheima.List.myarraylist;

import java.util.Arrays;

public class MyArrayList<E> {
    Object[] obj=new Object[10];
    int size;

    public boolean add(E e){
        obj[size]=e;
        size++;
        return true;
    }
    public E get(int index){
        return (E)obj[index];
    }

    @Override
    public String toString() {
        return Arrays.toString(obj);
    }
}
public class Test {
    public static void main(String[] args) {
        MyArrayList<String> list=new MyArrayList<>();
        list.add("aaa");
        list.add("bbb");
        list.add("ccc");
        System.out.println(list);
    }
}

```
### 泛型方法：
方法中形参类型不确定时：
①使用类名后定义的泛型                      所有方法都能用
②在方法申明上定义自己的泛型		只有本方法能用
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684500887813-882c568a-e07d-4b56-b1d7-b2b0bf617bac.png#averageHue=%23edecdd&clientId=ue3c4ec11-c744-4&from=paste&height=352&id=uc235ef3b&originHeight=440&originWidth=1571&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=149497&status=done&style=none&taskId=u52d8a6ee-0223-44f5-8c56-a52839e1f76&title=&width=1256.8)
```java
package com.itheima.List.myarraylist2;

import java.util.ArrayList;

class MyArrayList2 {
    private MyArrayList2() {

    }
    public static<E> void add(ArrayList<E> list,E ...e){
        for (E e1 : e) {
            list.add(e1);
        }
    }
}

public class Test {
    public static void main(String[] args) {
        ArrayList<String> list=new ArrayList<>();
        MyArrayList2.add(list,"aaa","bbb","ccc","ddd");
        System.out.println(list);

    }
}

```
泛型接口
使用带泛型的接口的使用方式：
①在接口处直接指定泛型
②实现类也不确定，在创建该类对象的时候，实现类就可以把泛型延续下来，再建立实现类对象的时候再确定类型
如何使用带泛型的接口：
①实现类给出具体类型
public class MyArrayList implements List<String>{}
psvm{
MyArrayList list=new MyArrayList();
}
②实现类延续泛型，创建对象时再确定
public class MyArrayList<E> implements List<E >{}
psvm{
MyArrayList<String> list=new MyArrayList();
}
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684502259794-00b9310f-b028-4a78-98e4-fb695f053e75.png#averageHue=%23f9f7e1&clientId=ue3c4ec11-c744-4&from=paste&height=235&id=ua34179e1&originHeight=294&originWidth=1501&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=100862&status=done&style=none&taskId=ua3f683c7-8b9a-420c-a6bf-85b0a28e449&title=&width=1200.8)
泛型Tip:
泛型不具备继承性，但是数据具备继承性
```java
package com.itheima.List;

import java.util.ArrayList;

public class ExtendsTest {

    public static void main(String[] args) {
        /*
* 泛型不具备继承性，但是数据具备继承性
*
* */

        //创建集合的对象
        ArrayList<Ye> list1=new ArrayList<>();
        ArrayList<Fu> list2=new ArrayList<>();
        ArrayList<Zi> list3=new ArrayList<>();

        //调用method方法
        //        method(list1);
        //        method(list2);//报错
        //        method(list3);//报错

        list1.add(new Ye());
        list1.add(new Fu());
        list1.add(new Zi());

    }
    /*
此时，泛型里面写的是什么类型，那么只能传递什么类型的数据
*/
    public static void method(ArrayList<Ye> list){

    }
}
class Ye{}
class Fu extends Ye{}
class Zi extends Fu{}
```
### 泛型通配符
泛型弊端：
    利用泛型方法有一个小弊端，此时他可以接收任意的数据类型
    Ye Fu Zi Student
希望：本方法虽然不确定类型，但希望只传递Ye Fu Zi
此时我们可以使用泛型的通配符：
        ？也表示不确定的类型
        表示类型的限定
        **？ extends E**:表示可以传递E或E所有子类类型
        **？supper E**：表示可以传递E或者E所有的父类类型
应用场景：
    1、如果我们在定义类、方法、接口的时候，如果类型不确定就可以定义泛型类、泛型方法、泛型接口
    2、如果类型不确定，但是能知道以后只能传递某个继承体系中的，就可以泛型的通配符
泛型通配符：
    关键点：可以限定泛型的范围
```java
package com.itheima.List.通配符;

import java.util.ArrayList;

public class Test {

    public static void main(String[] args) {
        /*
* 泛型不具备继承性，但是数据具备继承性
*
* */

        //创建集合的对象
        ArrayList<Ye> list1=new ArrayList<>();
        ArrayList<Fu> list2=new ArrayList<>();
        ArrayList<Zi> list3=new ArrayList<>();

        //调用method方法
        method(list1);
        method(list2);
        method(list3);


    }

    public static void method(ArrayList<? extends Ye> list){

    }
}
class Ye{}
class Fu extends Ye {}
class Zi extends Fu {}
class Student{}
```
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684505042512-2eb137ef-0e49-4af4-bd34-e8234900d37f.png#averageHue=%23f9f5f4&clientId=ue3c4ec11-c744-4&from=paste&height=578&id=ucb929377&originHeight=723&originWidth=1606&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=394979&status=done&style=none&taskId=u58422946-d973-4687-ae9e-8017f8f3cce&title=&width=1284.8)

![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684505092270-9ee8ceac-0a53-4113-a214-dbe16f8f4f3a.png#averageHue=%23f7f1f0&clientId=ue3c4ec11-c744-4&from=paste&height=586&id=u21da70ad&originHeight=732&originWidth=1588&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=467084&status=done&style=none&taskId=uf7f39651-951c-4d3e-8341-82faf73ff02&title=&width=1270.4)
## 平衡二叉树旋转：
右旋左旋的选择：
确定支点：从添加的节点开始，不断往父节点找不平衡的点

![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684637035056-9f2dc047-94d9-4dff-b61c-19df4d88fe4c.png#averageHue=%23fefcfc&clientId=ua8da06cb-38a0-4&from=paste&height=215&id=u856e9a1b&originHeight=477&originWidth=456&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=45627&status=done&style=none&taskId=ub50662af-1f4c-4e78-8cc6-f8006ec14d8&title=&width=205.80001831054688)![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684637052642-451b7de1-634d-484a-b2dc-52ccb16c30bf.png#averageHue=%23fdfbfa&clientId=ua8da06cb-38a0-4&from=paste&height=225&id=uce683147&originHeight=431&originWidth=348&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=44428&status=done&style=none&taskId=uff84df38-6e63-432e-bde7-a482a74e49d&title=&width=181.40000915527344)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684637159627-3fe500e3-d073-448c-ae74-b40b01794d59.png#averageHue=%23fefaf9&clientId=ua8da06cb-38a0-4&from=paste&height=331&id=u6b9fb4e0&originHeight=440&originWidth=578&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=66735&status=done&style=none&taskId=u23fa1491-705c-47c5-9ce8-7afe87b6228&title=&width=435.3999938964844)
左左：当根节点左子树的左子树有节点插入
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684636890777-b67b2a65-18e3-40bf-9aa9-6a840ab072b5.png#averageHue=%23f8f2f2&clientId=ua8da06cb-38a0-4&from=paste&height=232&id=u68870780&originHeight=390&originWidth=441&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=45431&status=done&style=none&taskId=u7c31b18e-14e2-4f50-8842-7e8d80a2266&title=&width=262.8000183105469)![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684636903068-c3ba406c-db9e-476f-8188-ef0017cd5033.png#averageHue=%23fcf4f4&clientId=ua8da06cb-38a0-4&from=paste&height=215&id=ubb8cfb49&originHeight=331&originWidth=405&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=44969&status=done&style=none&taskId=u14e85f4c-d61c-416f-840d-0cb1f8b191b&title=&width=263)
一次右旋
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684636936317-1a95d6c5-9faa-4b27-ac62-8422a53677a6.png#averageHue=%23efe8e3&clientId=ua8da06cb-38a0-4&from=paste&height=205&id=uee97e811&originHeight=337&originWidth=440&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=54096&status=done&style=none&taskId=u8febb502-9a77-4100-9002-5cbd20e6c32&title=&width=268)![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684636955037-c864ec37-0234-46de-a302-b1179785909d.png#averageHue=%23fdfcfc&clientId=ua8da06cb-38a0-4&from=paste&height=234&id=u065e2ffe&originHeight=292&originWidth=387&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=50718&status=done&style=none&taskId=u136af3a7-5c01-4805-a66b-e7af187bbbe&title=&width=309.6)
左右：当根节点左子树的右子树有节点插入
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684636672219-f499da02-de1d-480a-976c-48b454c5bf5f.png#averageHue=%23fefdfc&clientId=ua8da06cb-38a0-4&from=paste&height=241&id=u3b33a9ab&originHeight=451&originWidth=780&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=93193&status=done&style=none&taskId=uc6da7836-1566-4653-b769-99858eb09fd&title=&width=417)左右变左左
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684636746416-35cd4247-5415-48ed-b38d-0bddcccdc0dc.png#averageHue=%23fefdfd&clientId=ua8da06cb-38a0-4&from=paste&height=194&id=uaa93a78f&originHeight=483&originWidth=1120&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=100243&status=done&style=none&taskId=ubccef2ca-29d3-4557-955c-d1102f905c6&title=&width=451)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684636772642-1d6c371c-1ee7-408e-b231-e65d7371dd74.png#averageHue=%23fefcfc&clientId=ua8da06cb-38a0-4&from=paste&height=190&id=ud2879d4f&originHeight=464&originWidth=1229&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=119591&status=done&style=none&taskId=uc8ee9c6e-bb81-441e-84ed-50ba2580f70&title=&width=503)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684637234445-e8d58dc7-b1fd-4ebf-9397-05be13271bf4.png#averageHue=%23fbf5f5&clientId=ua8da06cb-38a0-4&from=paste&height=476&id=u01a830e6&originHeight=595&originWidth=1055&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=201952&status=done&style=none&taskId=ue047afeb-5b1f-4981-bd65-89d738800a3&title=&width=844)
### 总结：
二叉树（数据没有规律，查询效率低）->二叉搜索树（有规律小左大有，但容易出现长短腿）->平衡二叉树（左右子树高度差不超过1，查询效率高）
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684637405098-ab2844bd-a8d9-4738-80a2-af0da9f6f80b.png#averageHue=%23fdfaf9&clientId=ua8da06cb-38a0-4&from=paste&height=464&id=u40d71653&originHeight=580&originWidth=1531&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=210195&status=done&style=none&taskId=u283f81fe-197e-4d8d-ae8c-76fe8de69d1&title=&width=1224.8)
平衡二叉树，添加元素规则：同二叉搜索树，小左大右
## 红黑树：
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684587962647-725697f6-9758-4367-a7a2-04b0ec2daaf4.png#averageHue=%23e9b9b1&clientId=u83b97750-0aea-4&from=paste&height=356&id=u33ccebdf&originHeight=445&originWidth=1634&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=295270&status=done&style=none&taskId=uf54b680d-e26d-45f6-907a-8306694f116&title=&width=1307.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684588524921-38d8026e-0510-4737-8815-e859a0898395.png#averageHue=%23f7c69c&clientId=u83b97750-0aea-4&from=paste&height=621&id=uc3baa3e4&originHeight=776&originWidth=1567&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=472785&status=done&style=none&taskId=u543ce326-7739-4a40-93c7-77ec532f8ce&title=&width=1253.6)
## Set
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684588676164-8818261e-8e17-4589-8d1d-1afb66d5f7e9.png#averageHue=%23fdfbfa&clientId=u83b97750-0aea-4&from=paste&height=599&id=ued67e889&originHeight=749&originWidth=1464&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=273119&status=done&style=none&taskId=ueef224af-32e0-46df-892c-68cc977d833&title=&width=1171.2)


![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684588771204-d5f0f970-ae7a-4d80-a77a-9285f752d92f.png#averageHue=%23d6d8d5&clientId=u83b97750-0aea-4&from=paste&height=600&id=u5100cfb0&originHeight=750&originWidth=1523&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=340715&status=done&style=none&taskId=ua3ac2299-5f56-4c60-9667-11a7947b0c1&title=&width=1218.4)
```java
//1、创建Set对象
Set<String> s=new HashSet<>();

//2、添加元素
//如果当前元素使第一次添加，那么可以添加成功，返回true
//如果当前元素是第二次添加，那么添加失败，返回false
s.add("aaa");
s.add("aaa");//未添加成功
s.add("bbb");
s.add("ccc");
```
## HashSet
没有额外的新方法，只需要研究底层原理

- HashSet集合底层采取哈希表的存储数据
- 哈希表是一种对于增删改查数据性能都较好的结构

1、HashSet集合的底层数据结构
哈希表的组成
JDK8之前：数组+链表
JDK8开始：数组+链表+红黑树
哈希值：对象的整数表现形式
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684590565664-7ef78f58-493e-4819-822d-1567aa83a015.png#averageHue=%23fcf6ee&clientId=u83b97750-0aea-4&from=paste&height=201&id=uefe48658&originHeight=251&originWidth=1047&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=127092&status=done&style=none&taskId=u400633da-85e9-406a-9058-3f3c429ec37&title=&width=837.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684590578025-9c67d8b5-7e44-4c93-80fb-87b7448fc8a6.png#averageHue=%23f9efe6&clientId=u83b97750-0aea-4&from=paste&height=218&id=u7511798a&originHeight=272&originWidth=1298&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=168720&status=done&style=none&taskId=u4506cf38-811e-49b7-82fb-013bddde37e&title=&width=1038.4)
2、HashSet添加元素的过程
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684591009653-bf09c13c-d371-4a01-a899-87722cd0ec46.png#averageHue=%23fdfbfb&clientId=u83b97750-0aea-4&from=paste&height=608&id=ZYNc9&originHeight=760&originWidth=1634&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=319061&status=done&style=none&taskId=ue395515c-641d-48ed-b3e0-a87f37ac2b8&title=&width=1307.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684591045749-bcd9d41e-a53e-4582-ac7f-c2fd1c6c4d10.png#averageHue=%23e8f0ed&clientId=u83b97750-0aea-4&from=paste&height=379&id=ue5f52d21&originHeight=474&originWidth=1420&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=184093&status=done&style=none&taskId=u1757494c-a53f-4df8-b16f-34e3596bc4a&title=&width=1136)
3、HashSet存和取的顺序为什么不一样：
存是根据index=(数组长度-1)&哈希值计算存放的数组下标，而取是从数组的前到后遍历
4、HashSet为什么没有索引？
HashSet的一个数组元素下可能挂着链表或红黑树，这些元素的数组下标相同，所以取消索引
5、HashSet利用什么机制保证去重？
HashCode方法、equals方法
通过HashCode得到哈希值，根据哈希值得到元素添加在数组的哪个位置，再调用对象内部的equals方法去比较对象的属性值是否相同，如果是自定义对象一定要重写HashCode和equals方法
应用：对象去重
## LinkedHashSet
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684592175361-3a6705b9-2440-401b-b1ba-e4ba7eb39cc3.png#averageHue=%23fdfaf8&clientId=u83b97750-0aea-4&from=paste&height=639&id=u0f952a2e&originHeight=799&originWidth=1585&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=288452&status=done&style=none&taskId=u561674e4-da9e-4ba3-9e5c-4eeec192989&title=&width=1268)
**在以后如果要数据去重，我们使用哪个？**
**默认使用HashSet**
**如果要求去重且存取有序，才使用LinkedHashSet**
## TreeSet
TreeSet的特点

- 不重复、无索引、可排序
- 可排序：按照元素的默认规则（由小到大）排序
- TreeSet集合底层是基于红黑树的数据结构实现排序的，增删改查性能都较好

TreeSet集合默认的规则
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684593872639-7f5015c5-5286-4185-84df-10d58e73b5f4.png#averageHue=%23fefefd&clientId=u83b97750-0aea-4&from=paste&height=587&id=u692d16fc&originHeight=734&originWidth=1146&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=167391&status=done&style=none&taskId=u49334916-87e3-4bdf-bab3-a13ad7dc8e0&title=&width=916.8)
### TreeSet的两种比较方式：
方式一：默认排序/自然排序：javabean类实现Comparable接口指定比较规则
方式二：创建TreeSet对象时候，传递比较器Comparator指定规则
使用原则：默认使用第一种，如果第一种不能满足当前的需求，就使用第二种
Tip:
1、例如字符串已定义好排序规则，但若想重写规则，则使用方式二
2、方式一方式二同时存在，使用方式二
法一：
```java
package com.itheima.set.TreeSetSort;

public class Student implements Comparable<Student>{
    private String name;
    private int age;
    //this:表示当前要添加的元素
    //o:表示已经在红黑树存在的元素

    //返回值：
    //负数：表示当前要添加的元素是小的，存左边
    //正数：表示当前要添加的元素是大的，存右边
    //0：表示当前要添加的元素已存在，舍弃
    @Override
    public int compareTo(Student o) {
        //指定排序的规则
        //我们按年龄的升序进行排序
        //年龄相同，按名字ASIC码排序
        int i= this.age-o.getAge();
        i = i == 0 ? this.getName().compareTo(o.getName()) : i;
        return i;
    }
}
```
法二：
```java
package com.itheima.set.TreeSetSort;

import java.util.Comparator;
import java.util.TreeSet;

public class SortDemo {
    public static void main(String[] args) {
        /*
            需求：存入四个字符串,"c","ab","df","qwer"
            按照长度排序，如果一样长则按照首字母排序

*/

        //o1:表示当前要添加的元素
        //o2:表示已经在红黑树存在的元素
        //返回值规则跟之前一样
        TreeSet<String> ts=new TreeSet<>(new Comparator<String>() {
            @Override
            public int compare(String o1, String o2) {
                //按照长度排序
                int i=o1.length()-o2.length();
                //如果一样长则按照首字母排序
                //如果长度相同，则按默认规则排序
                //如果长度不同，则按长度排序
                i = i == 0 ? o1.compareTo(o2) : i;
                return i;

            }
        });

        ts.add("c");
        ts.add("ab");
        ts.add("df");
        ts.add("qwer");
        System.out.println(ts);
    }
}
```
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684647745868-0d96996a-0559-4e84-ab89-e5a76ed43d29.png#averageHue=%23fcf7f6&clientId=ud84cb836-6493-4&from=paste&height=538&id=u08eb87e4&originHeight=673&originWidth=1074&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=330919&status=done&style=none&taskId=ua65ed894-03cc-4a92-89bf-a4f412a9fd2&title=&width=859.2)
## 各类集合的应用场景
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684647823535-c6fa6d05-2257-4248-8a90-005f57602060.png#averageHue=%23fbf8f8&clientId=ud84cb836-6493-4&from=paste&height=638&id=u1385f778&originHeight=797&originWidth=1509&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=400111&status=done&style=none&taskId=u715083a8-1ba9-4b36-9a7c-3da6f3acb3f&title=&width=1207.2)
## 双列集合
1、双列集合一次需要存一对数据，分别为键和值
2、键不能重复，值可以重复
3、键和值是一一对应的，每一个键只能找到自己对应的值
4、键和值这个整体 叫做“键值对”或“键值对对象”，在Java中叫做“Entry对象”
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684664236568-5631085c-5d5b-4f2a-98e6-b94508d75197.png#averageHue=%23fcfbfa&clientId=uf16089b8-e81f-4&from=paste&height=351&id=u26d8af90&originHeight=439&originWidth=584&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=67909&status=done&style=none&taskId=u7ea3f7a8-7d2a-4752-abf2-e82a0b54390&title=&width=467.2)
## Map
Map是双列集合的顶层接口，它的功能是全部双列集合都可以继承使用
### 普通方法：
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684664377656-858a54c9-97ef-4b96-b9ae-2b90aec12f66.png#averageHue=%23decfcf&clientId=uf16089b8-e81f-4&from=paste&height=416&id=u8db1785d&originHeight=520&originWidth=1366&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=216243&status=done&style=none&taskId=u7fa92eab-a662-4f71-b008-ad13d615527&title=&width=1092.8)
 put方法的细节:添加/覆盖
        在添加数据的时候，如果键不存在，那么直接把键值对对象添加到map集合当中，方法返回null
        在添加数据的时候，如果键是存在的，那么会把原有的键值对对象覆盖，会把被覆盖的值进行返回
```java
package com.itheima.Map;

import java.util.HashMap;
import java.util.Map;

public class MethodTest {
    public static void main(String[] args) {
        //1、创建Map集合的对象
        Map<String,String>m = new HashMap<>();

        //2、添加元素
        //put方法的细节:添加/覆盖
        //在添加数据的时候，如果键不存在，那么直接把键值对对象添加到map集合当中，方法返回null
        //在添加数据的时候，如果键是存在的，那么会把原有的键值对对象覆盖，会把被覆盖的值进行返回
        String value1=m.put("郭靖","黄蓉");
        //System.out.println(value1);//null
        m.put("韦小宝","沐剑屏");
        m.put("尹志平","小龙女");
        // String value2=m.put("韦小宝","双儿");
        //System.out.println(value2);//沐剑屏
        //System.out.println(m);//{韦小宝=双儿, 尹志平=小龙女, 郭靖=黄蓉}

        //3、删除 删除键 返回对应的值
        //        String result=m.remove("郭靖");
        //        System.out.println(result);//黄蓉
        //        System.out.println(m);//{韦小宝=沐剑屏, 尹志平=小龙女}

        //4、清空
        //        m.clear();
        //        System.out.println(m);//{}

        //5、判断存在
        //        boolean keyResult=m.containsKey("郭靖");
        //        System.out.println(keyResult);//true
        //        boolean valueResult=m.containsValue("小龙女2");
        //        System.out.println(valueResult);//false

        //6、判断为空
        //        boolean result=m.isEmpty();
        //        System.out.println(result);//false

        //7、长度
        int size=m.size();
        System.out.println(size);//3

    }
}
```
### 遍历方式
①键找值
②键值对
③Lambda表达式
```java
//3、通过键找值
//3、1获取所有的键，把这些键放到一个单列集合当中
Set<String> keys = map.keySet();
//3、2遍历单列集合，得到每一个键
for (String key : keys) {//装着键的单列集合使用增强for遍历
    //3、3 利用map集合中的键获取对应的值 get
    String value=map.get(key);
    System.out.println(key + " = " + value);
}
```
```java
//3、Map集合的第二种遍历方式
//通过键值对对象进行遍历
//3、1通过一个方法获取所有键值对对象，返回一个Set集合
//Entry接口是Map类的内部接口，调用Entry时使用类名.接口名
Set<Map.Entry<String, String>> entries = map.entrySet();
//3、2遍历entries这个集合，去得到里面的每一个键值对对象
//装着键值对对象的单列集合使用增强for的形式进行遍历
for (Map.Entry<String, String> entry : entries) {
    //3、3 利用entry调用get方法获取键和值
    String key = entry.getKey();
    String value= entry.getValue();
    System.out.println(key + "=" + value);
}
```
```java
map.forEach(( key, value)-> System.out.println(key + "=" + value));

```
## HashMap
特点：
1、HashMap是Map里面的一个实现类
2、没有额外需要学习的特有方法，直接使用Map里面的方法
3、特点是由键决定的：无序、不重复、无索引
4、HashMap跟HashSet底层原理一样，都是哈希表
总结：
1、HashMap底层是哈希表结构的
2、依赖hashCode方法和equals方法保证键的唯一
3、如果键存储的是自定义对象，需要重写hashCode和equals方法
如果值存储自定义对象，不需要重写hashCode和equals方法

## LinkedHashMap
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684760835665-f8abf08e-70cb-47c0-932e-92a6dfab6567.png#averageHue=%23f7f5f5&clientId=u489e4f74-f60b-4&from=paste&height=628&id=udac6daba&originHeight=785&originWidth=1579&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=228517&status=done&style=none&taskId=u8b8d1087-d8ad-4e0f-a00a-e344cfdcf2e&title=&width=1263.2)
## TreeMap
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684760974869-677e6cba-5897-4cf7-bad8-27e7b645abdf.png#averageHue=%23f9f8f7&clientId=u489e4f74-f60b-4&from=paste&height=528&id=ued545329&originHeight=660&originWidth=1224&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=216087&status=done&style=none&taskId=u83e39496-a0af-4e6f-aaa8-e68b690f92f&title=&width=979.2)
Integer Double 默认情况下按照升序排列
String 按照字母在ASCII码表中对应的数字升序进行排序
:::warning
统计思想：计数器原理
利用map集合进行统计
如果题目中没有要求对结果进行排序，默认使用HashMap
如果题目中要求对结果进行排序，默认使用TreeMap
键：表示要统计的内容
值：表示次数
:::
↑  重写的父类或接口中的方法，箭头后面是父类或接口名称
-> 该方法继承箭头后面的方法
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684844253650-09dd50d6-5210-4dfb-bec3-0369c8608150.png#averageHue=%23d0c1af&clientId=u6edf143b-b354-4&from=paste&height=47&id=ub0fa7a82&originHeight=59&originWidth=634&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=34038&status=done&style=none&taskId=u9c45073a-b211-4da5-beb7-1f2e838f6db&title=&width=507.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684844237338-778ad4a6-623c-412f-8c32-cfb2030c560e.png#averageHue=%23e4dacb&clientId=u6edf143b-b354-4&from=paste&height=558&id=u9044876c&originHeight=697&originWidth=862&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=365917&status=done&style=none&taskId=u720fa7b6-b7d0-4ff8-b807-017163942e7&title=&width=689.6)
## 可变参数
1、可变参数本质上就是一个数组
2、作用：在形参中接收多个数据
3、格式：数据类型...参数名称
int...a
4、注意事项：
形参列表中可变参数可能只有一个
可变参数必须放在形参列表的最后
```java
package com.itheima;

public class VariableArgs {
    public static void main(String[] args) {
        getsum(1,2,3,4);
    }
    public static void getsum(int...a){
        int sum=0;
        for (int i : a) {
            sum+=i;
        }
        System.out.println(sum);
    }
}
```
## Collections：
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684845410330-ed6fa0b4-cce3-48b1-b99c-413999df8130.png#averageHue=%23f0e3e2&clientId=u6edf143b-b354-4&from=paste&height=304&id=u7016ee4f&originHeight=380&originWidth=914&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=93067&status=done&style=none&taskId=uc8dccbc2-a350-47e7-ba55-705d85281db&title=&width=731.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684845450315-cfae49da-efb4-4692-9d46-6f3eb1dfbc40.png#averageHue=%23f6fbfc&clientId=u6edf143b-b354-4&from=paste&height=517&id=ue4c2291a&originHeight=646&originWidth=1595&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=475893&status=done&style=none&taskId=udda172c3-d146-45e9-82bd-1376b6145a2&title=&width=1276)
## 不可变集合
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685007362786-c232677d-b9d3-40d1-b1f7-3e491d76b8e6.png#averageHue=%23dfe0dc&clientId=u3c2e153f-7c67-4&from=paste&height=510&id=u0e60e926&originHeight=638&originWidth=1562&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=295465&status=done&style=none&taskId=u3d5cb633-c3a2-4ad1-bed4-d3c7f101910&title=&width=1249.6)
# Stream流
## 概述：
作用：
结合了Lambda表达式，简化集合、数组操作
Stream流：
1、先得到一条Stream流（流水线），并把数据放上去
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685023976946-b240db4d-40b6-431d-8012-04f3af8eb33f.png#averageHue=%23f3f6f9&clientId=u7288dde1-3d52-4&from=paste&height=301&id=u0ecf26fb&originHeight=376&originWidth=1476&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=214082&status=done&style=none&taskId=ue9223385-0704-440d-bf35-8f43c137cf8&title=&width=1180.8)
2、利用Stream流中的API进行各种操作
中间方法：方法调用完毕后还可以调用其他方法，如：过滤 转换
终结方法：最后一步，调用完毕后，不能调用其他方法，如：统计 打印
### 获取Stream流
```java
package com.heima.creatstream;

import java.util.ArrayList;
import java.util.Arrays;
import java.util.Collections;
import java.util.HashMap;
import java.util.stream.Stream;

public class StreamTest1 {
    public static void main(String[] args) {
        /*
		单列集合                Collection中的默认方法
*/
        ArrayList<String> list=new ArrayList<>();
        Collections.addAll(list,"a","b","c","d");
        //  list.stream().forEach(s-> System.out.println(s));
        /*
		双列集合                无法直接使用stream流
*/
        HashMap<String,Integer> hm=new HashMap<>();
        hm.put("aaa",111);
        hm.put("bbb",222);
        hm.put("ccc",333);
        hm.keySet().stream().forEach(s-> System.out.println(s));
        hm.entrySet().stream().forEach(s-> System.out.println(s));
        /*
		数组                   Arrays工具类中的静态方法
*/
        int[] arr={1,2,3,4,5};
        Arrays.stream(arr).forEach(s-> System.out.println(s));
        /*
		一些零散的数据          Stream接口中的静态方法
*/
        //注意：
        //Stream接口中静态方法of的细节
        //方法的形参是一个可变参数，可以传递一堆零散的数据，也可以传递数组
        //但是数组必须是引用类型的，如果传递基本类型，是会把整个数组当作一个元素，被放到Stream流中
        Stream.of(1,2,3,4).forEach(s-> System.out.println(s));
    }
}
```
### Stream流的中间方法

![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685104853159-e03fa878-9f2e-43c4-9df1-f689517ee39d.png#averageHue=%23ece1e0&clientId=uf6c2b1c3-789f-4&from=paste&height=542&id=ud4dcaec1&originHeight=677&originWidth=1537&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=249938&status=done&style=none&taskId=u9d23a90c-ee3b-4c3e-ab9f-ca9049d2892&title=&width=1229.6)
注意1：中间方法，返回新的Stream流，原来的Stream流只能使用一次，建议使用链式编程
注意2：修改Stream流中的数据，不会影响原来集合或者数组中的数据
详细注释看idea原码
```java
package com.heima.method;

import java.util.ArrayList;
import java.util.Collections;
import java.util.function.Predicate;

public class MethodTest {
    public static void main(String[] args) {
        ArrayList<String> list=new ArrayList<>();
        Collections.addAll(list,"张无忌","周芷若","赵敏",
                           "张强","张三丰","张翠山","张良","王二麻子","谢广坤");
        //filter 过滤 把张开头的留下，其余数据过滤不要
		list.stream().
            filter( s ->s.startsWith("张")).forEach(s-> System.out.println(s));

        //limit 获取前几个元素
        //skip 跳过前几个元素
        list.stream().limit(3).forEach(s-> System.out.println(s));
         list.stream().skip(4).forEach(s-> System.out.println(s));




    }
}
```
```java
package com.heima.method;

import java.util.ArrayList;
import java.util.Collections;
import java.util.stream.Stream;

public class MethodTest2 {
    public static void main(String[] args) {
        ArrayList<String> list1=new ArrayList<>();
        Collections.addAll(list1,"张无忌","张无忌","张无忌","张强","张三丰");
        ArrayList<String> list2=new ArrayList<>();
        Collections.addAll(list2,"aaa","bbb");
        //distinct     元素去重，依赖hashCode和equals方法
        //自定义类型重写hashCode和equals方法
        list1.stream().distinct().forEach(s-> System.out.println(s));
        //concat       合并a和b两个流为一个流
        //当两个流类型不一样时，合并流的类型为两个流的共同父类
        Stream.concat(list1.stream(),list2.stream()).forEach(s-> System.out.println(s));
    }
}
```
```java
package com.heima.method;

import java.util.ArrayList;
import java.util.Collections;
import java.util.function.Function;

public class MethodTest3 {
    public static void main(String[] args) {
        /*
        map        转换流中的数据类型
         */
        ArrayList<String> list=new ArrayList<>();
        Collections.addAll(list,"张无忌-15","张芷若-20","张强-14");
        list.stream()
            .map(s->Integer.parseInt(s.split("-")[1]))
            .forEach(s-> System.out.println(s));


    }
}
```
### Stream流终结方法
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685109682822-5065bc24-4296-4c8c-9036-4c404802de68.png#averageHue=%23f5f9f7&clientId=uf6c2b1c3-789f-4&from=paste&height=444&id=u09e04fc7&originHeight=555&originWidth=1498&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=164069&status=done&style=none&taskId=u010f7703-01d8-4981-a876-d156ec287b8&title=&width=1198.4)
```java
package com.heima.method;

import java.util.ArrayList;
import java.util.Arrays;
import java.util.Collections;
import java.util.function.IntFunction;

public class EndMethod {
    public static void main(String[] args) {
        ArrayList<String> list=new ArrayList<>();
        Collections.addAll(list,"张无忌","周芷若","赵敏");
        //forEaach  遍历
        list.stream().forEach(s-> System.out.println(s));

        //long count() 统计
        long count=list.stream().count();
        System.out.println(count);

        //toArray  收集流中的数据，放到数组中    
        String[] arr2=list.stream().toArray(value -> new String[value]);
        System.out.println(Arrays.toString(arr2));

    }
}
```
```java
package com.heima.method;

import com.sun.xml.internal.ws.policy.privateutil.PolicyUtils;

import java.util.*;
import java.util.function.Function;
import java.util.function.Predicate;
import java.util.stream.Collectors;

public class EndMethod2 {
    public static void main(String[] args) {
        ArrayList<String> list=new ArrayList<>();
        Collections.addAll(list,"张无忌-男-15","周芷若-女-14","赵敏-女-13","张强-男-20"
                           ,"张三丰-男-100");
        //收集到List集合中
        //需求：收集所有男性
        List<String> newList1 = list.stream()
            .filter(s -> "男".equals(s.split("-")[1]))
            .collect(Collectors.toList());

        //收集到Set里，去重
        Set<String> newList2 = list.stream()
            .filter(s -> "男".equals(s.split("-")[1]))
            .collect(Collectors.toSet());

        //收集到Map
        //需求：收集所有男性
        //键：姓名
        //值：年龄

        Map<String, Integer> map2 = list.stream()
            .filter(s -> "男".equals(s.split("-")[1]))
            .collect(Collectors.toMap(
                s->s.split("-")[0],
                s->Integer.parseInt(s.split("-")[2])));
        System.out.println(map2);


    }


}
```

![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685112857082-00a13b3a-624d-43c0-989a-73c97b4e1a3d.png#averageHue=%23fbf5f5&clientId=uf6c2b1c3-789f-4&from=paste&height=626&id=uc1c3dd1f&originHeight=783&originWidth=1373&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=435171&status=done&style=none&taskId=u79eeb784-1815-4013-89c8-19d1a75b407&title=&width=1098.4)
# 方法引用
## 概述
方法引用：
把已经有的方法拿过来用，当作函数式接口中的抽象方法的方法体
注意：
1、引用处必须是函数式接口，被引用的方法已经存在
2、被引用方法的形参和返回值需要跟抽象方法保持一致
3、被引用方法的功能要满足当前需求
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685164078897-c6467c6a-22bc-4f2c-87d4-7236565fcea3.png#averageHue=%23fbf9f9&clientId=u3b303af8-bd38-4&from=paste&height=464&id=uf0dcc815&originHeight=580&originWidth=1012&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=210767&status=done&style=none&taskId=u359d0b0d-3530-4ea9-8a4a-ec0ddd0f7ae&title=&width=809.6)
## 方法引用的分类
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685164129786-878657aa-25d2-4361-b0f0-411e7330461a.png#averageHue=%23eeded5&clientId=u3b303af8-bd38-4&from=paste&height=624&id=u7337713d&originHeight=780&originWidth=1230&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=215548&status=done&style=none&taskId=u4bd306b8-7f77-4220-9f1d-0f8772b0898&title=&width=984)
### 引用静态方法
格式：类名：：静态方法
范例：Integer::parseInt
```java
package com.itheima.staticmethod;

import java.util.ArrayList;
import java.util.Collections;

public class StaticMethodReference {
    public static void main(String[] args) {
        //将字符串类型的数字转换为数字
        ArrayList<String> list=new ArrayList<>();
        Collections.addAll(list,"1","2","3","4","5");
        list.stream()
            .map(Integer::parseInt)
            .forEach(s-> System.out.println(s));
    }
}
```
### 引用成员方法
格式：对象：：成员方法
①其他类：其他类对象：：方法名
②本类：this::方法名---------|
           --------------引用处不能是静态方法
③父类：super::方法名-------|
```java
package com.itheima.numbermethod;

public class StringOperation {
    public boolean stringJudge(String s){
        return s.startsWith("张")&&s.length()==3;
    }
}
```

```java
package com.itheima.numbermethod;

import java.util.ArrayList;
import java.util.Collections;
import java.util.function.Predicate;

public class Test {
    public static void main(String[] args) {
        ArrayList<String> list=new ArrayList<>();
        Collections.addAll(list,"张无忌","张三丰","张亮","沈娇娇");
    	//引用其他类
        //        list.stream().filter(new StringOperation()::stringJudge)
        //                .forEach(s -> System.out.println(s));

        //引用本类
        //不能用this,静态方法中是没有this的
        //要在静态方法中使用本类方法，可以使用类名：：方法名
        list.stream().filter(new Test()::stringJudge)
            .forEach(s -> System.out.println(s));
    }
    public boolean stringJudge(String s){
        return s.startsWith("张")&&s.length()==3;
    }
}
```
### 引用构造方法：
格式：类名：：new
范例：Student::new（创造了个Student类对象）
```java
package com.itheima.constructmethod;

import java.util.ArrayList;
import java.util.Collections;
import java.util.List;
import java.util.function.Function;
import java.util.stream.Collectors;
import java.util.stream.Stream;

public class ConstructorMethod {
    public static void main(String[] args) {
        ArrayList<String> list=new ArrayList<>();
        Collections.addAll(list,"张无忌,15","周芷若,14","赵敏,13","张强,20","张三丰,100");

        List<Student> newList2=list.stream().map(Student::new).collect(Collectors.toList());
        System.out.println(newList2);
    }
}
```
```java
package com.itheima.constructmethod;

public class Student {
    private String name;
    private int age;

    public Student() {
    }
    public Student (String s) {
        this.name = s.split(",")[0];
        this.age = Integer.parseInt(s.split(",")[1]);
    }
    public Student(String name, int age) {
        this.name = name;
        this.age = age;
    }

    /**
* 获取
* @return name
*/
    public String getName() {
        return name;
    }

    /**
* 设置
* @param name
*/
    public void setName(String name) {
        this.name = name;
    }

    /**
* 获取
* @return age
*/
    public int getAge() {
        return age;
    }

    /**
* 设置
* @param age
*/
    public void setAge(int age) {
        this.age = age;
    }

    public String toString() {
        return "Student{name = " + name + ", age = " + age + "}";
    }
}
```
### 其他调用方法
#### 使用类名引用成员方法
格式：类名：：成员方法
范例：String：：subString
方法引用的规则：
1、需要有函数式接口
2、被引用的方法必须已经存在了
3、被引用方法的形参需要跟抽象方法的第二份形参到最后一个形参保持一致，返回值需要保持一致，如果没有第二个参数，被引用的方法需要时无参的成员方法
4、被引用方法的功能需要满足当前的需求
抽象方法的形参详解：
第一个参数：表示被引用方法的调用者，决定了可以引用哪些类中的方法
在Stream流当中，第一个参数一般都表示流里面的每一个数据
假设流里面的数据是字符串，那么使用这种方法进行方法引用，只能引用String这个类中的方法
第二个参数到最后一个参数：跟被引用方法的形参保持一致，如果没有第二个参数，说明被应用的方法需要时无参的成员方法
局限性：
不能引用所有类中的成员方法
是跟抽象方法的第一个参数有关，这个参数是什么类型的，那么就只能引用这个类中的方法
```java
package com.itheima.elsemethod;

import java.util.ArrayList;
import java.util.Collections;
import java.util.function.Function;

public class ElseMethod {
    public static void main(String[] args) {
        /*
方法引用（类名引用成员方法）
格式
类名::成员方法
要求
集合里面一些字符串，要求变成大写后进行输出
*/
        ArrayList<String> list=new ArrayList<>();
        Collections.addAll(list,"aaa","bbb","ccc","ddd");
        //拿着流里面的每一个数据，去调用String类中的toUpperCase方法，方法的返回值就是转换之后的结果
        list.stream().map(String::toUpperCase).forEach(s-> System.out.println(s));

    }
}
```
#### 引用数组的构造方法
格式：数据类型[]：：new
范例：int[]::new
作用：创建一个数组
```java
package com.itheima.elsemethod;

import java.util.ArrayList;
import java.util.Arrays;
import java.util.Collections;
import java.util.function.IntFunction;

public class ElseMethod1 {
    public static void main(String[] args) {
        ArrayList<Integer> list=new ArrayList<>();
        Collections.addAll(list,1,2,3,4,5);
        Integer[] array = list.stream().toArray(Integer[]::new);
        System.out.println(Arrays.toString(array));
    }
}
```
技巧：
1、现在有没有一个方法符合我当前的需求
2、如果有这样的方法，这个方法是否满足引用的规则
静态
成员方法
构造方法
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685186951550-f9b6a749-4752-4632-8964-874035446336.png#averageHue=%23faf8f7&clientId=u3b303af8-bd38-4&from=paste&height=541&id=u05ebb0f3&originHeight=676&originWidth=1487&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=279086&status=done&style=none&taskId=u7b7e741d-7093-4c1f-8beb-d156afe3762&title=&width=1189.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685187017973-64734cff-6471-4a20-93e3-d39676067752.png#averageHue=%23f9ebe9&clientId=u3b303af8-bd38-4&from=paste&height=561&id=u1f8f1523&originHeight=701&originWidth=1378&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=321804&status=done&style=none&taskId=udd7c49b3-2bab-4123-929e-cf829f449fb&title=&width=1102.4)

# 异常类
## 异常概念
1、异常：
程序中可能出现的问题
2、异常体系的最上层父类为Exception，异常分为两类：编译时异常、运行时异常
3、编译时异常：没有继承RuntimeExce的异常，直接继承与Exception。编译阶段就报错，提醒程序员处理
    运行时异常：RuntimeException本身和子类
编译阶段没有错误提示，运行时出现的
一般是由于参数传递错误带来的问题

![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684226721296-e370a209-a042-4b99-ba3e-5f75e7336188.png#averageHue=%23f3f1f1&clientId=ue2a67ca2-2c74-4&from=paste&height=492&id=u132ff1b6&originHeight=615&originWidth=1590&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=168277&status=done&style=none&taskId=u4aaaffe2-f05a-4569-8ff8-ba1d2259362&title=&width=1272)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684226757760-ae263272-2c63-4f8c-84dc-3c18df4db735.png#averageHue=%23fdf6f3&clientId=ue2a67ca2-2c74-4&from=paste&height=680&id=u7f1463bc&originHeight=850&originWidth=1591&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=395520&status=done&style=none&taskId=uf2d40b2f-8011-4a44-823c-64eec62b297&title=&width=1272.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684227097404-6b2eb7f3-5873-40c0-bfee-ffd4fff1f217.png#averageHue=%23fcf5f2&clientId=ue2a67ca2-2c74-4&from=paste&height=628&id=u330620b5&originHeight=785&originWidth=1598&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=245002&status=done&style=none&taskId=ud3f3cd4d-218f-4ca9-8d05-8b94f49b833&title=&width=1278.4)
## 异常的作用：
作用一：异常是用来查询bug的关键参考信息
作用二：异常可以作为方法内部的一种特殊返回值，以便通知调用者底层的执行情况
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684227834639-cd40e465-bd5e-437b-8ef1-e4f81c05c7ba.png#averageHue=%232f2d2c&clientId=ue2a67ca2-2c74-4&from=paste&height=175&id=ued73dd3d&originHeight=219&originWidth=517&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=14609&status=done&style=none&taskId=u215b064c-706f-4f22-a9ce-48fe98f374f&title=&width=413.6)
## 异常的处理方式：
1、虚拟机默认处理异常方式
把异常信息以红色字体打印在控制台，并结束程序
2、捕获：try...catch
一般用在调用处，能让代码继续往下进行
3、抛出：throw throws
在方法中，出现异常了
方法就没有据需运行下去的意义，采取抛出处理
让该方法结束运行并告诉调用者出现了问题
细节如下：
（1）JVM默认的处理方式
把异常的名称、原因、出现位置等输出在控制台
程序停止执行，下面的代码不会再执行
（2）自己处理
目的：当代码出现异常时，可以让程序继续往下执行
try{
可能出现异常的代码；
}catch(异常类名 变量名){
异常的处理代码；
}
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684229318176-679408de-e675-4907-800e-71a887611926.png#averageHue=%23f7f4e7&clientId=ue2a67ca2-2c74-4&from=paste&height=501&id=ub7d62aaa&originHeight=626&originWidth=1276&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=335181&status=done&style=none&taskId=u2960b035-e3fe-4d3e-b5bd-7cc02ddc572&title=&width=1020.8)
①如果try中没有遇到问题，怎么执行？
会把try里面所有代码全部执行完毕，不会执行catch里面的代码
只有当出现了异常才会执行catch里面的代码
②如果try中可能会遇到多个问题，怎么执行？
会写多个catch与之对应
细节：如果我们捕获多个异常，这些异常中如果存在父子关系的话，那么父类一定要写在下面
jdk7后，可以在catch中同时捕获多个异常，中间用|进行隔开
如果出现了A异常或B异常，采取同一种方案
③如果try中遇到的问题没有被捕获，怎么执行？
相当于try...catch的代码白写了，最终还是会交给虚拟机进行处理
④如果try中遇到了问题，那么try下面的其他代码还会执行吗
下面的代码就不会执行了，直接跳转到对应的catch中，执行catch里面的语句体
但是如果没有对应的catch与之匹配，那么还是会交给虚拟机进行处理
（3）抛出默认
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684231273855-cd3629fd-3011-4282-9a1c-431f2722f345.png#averageHue=%23f2efe6&clientId=ue2a67ca2-2c74-4&from=paste&height=632&id=u122a4fef&originHeight=790&originWidth=1719&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=313897&status=done&style=none&taskId=u3baca039-3d5d-4d55-b826-59f67af0e3d&title=&width=1375.2)
```java
package throwss;

public class ThrowsTest {
    public static void main(String[] args) {
        int[] arr=null;
        int max= 0;
        try {
            max = getMax(arr);
        } catch (NullPointerException e) {
            System.out.println("空指针异常");
        }catch (ArrayIndexOutOfBoundsException e){
            System.out.println("索引越界异常");
        }
        System.out.println(max);
    }
    //此处为运行时异常，可以不用声明
    public static int getMax(int[] arr) /*throws NullPointerException,ArrayIndexOutOfBoundsException*/{
        if(arr==null){
            //手动创建一个异常对象，并把这个异常交给方法的调用者处理
            //此时方法就会结束，下面的代码不会再执行了
            throw new NullPointerException();
        }
        if(arr.length==0){
            //手动创建一个异常对象，并把这个异常交给方法的调用者处理
            //此时方法就会结束，下面的代码不会再执行了
            throw new ArrayIndexOutOfBoundsException();
        }
        System.out.println("看我执行没");
        int max=arr[0];
        for(int i=1;i<arr.length;i++){
            if(arr[i]>max){
                max=arr[i];
            }
        }
        return max;
    }
}
```

## 异常中的常见方法：
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684230516719-7e604011-8082-42fa-94b3-8975f58276e0.png#averageHue=%23fdfef9&clientId=ue2a67ca2-2c74-4&from=paste&height=434&id=u1db1c440&originHeight=542&originWidth=1508&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=177784&status=done&style=none&taskId=uc87dc0de-19cb-4107-b4cb-f582cf6502a&title=&width=1206.4)
```java
package throwable;

public class ThrowableTest {
    public static void main(String[] args) {
        int[] arr={1,2,3,4,5,6};
        try {
            System.out.println(arr[10]);
        } catch (ArrayIndexOutOfBoundsException e) {
            //            String message = e.getMessage();
            //            System.out.println(message);10

            //            String s = e.toString();
            //            System.out.println(e.toString());//java.lang.ArrayIndexOutOfBoundsException: 10

            //在底层利用SyStem,err,println进行输出
            //把异常的错误信息以红色字体输出在控制台
            //打印错误信息，程序不会停止
            e.printStackTrace();

        }
        System.out.println("看我执行没");
    }
}
```
## 自定义异常
意义：就是为了让控制台的报错信息更加见名知意
1、定义异常类
2、写继承关系
编译时异常继承Exception
运行时异常继承RuntimeExcetion
3、空参构造
4、带参构造
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684234034213-d2f740eb-f201-4a56-9045-a769c3e33290.png#averageHue=%232c2c2b&clientId=ue2a67ca2-2c74-4&from=paste&height=449&id=u00d7c80d&originHeight=561&originWidth=910&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=56366&status=done&style=none&taskId=u89fd1a4d-8d14-428d-80dd-b62bb579324&title=&width=728)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1684234046822-b7abd32b-a86b-495d-8aec-a122050b33c0.png#averageHue=%232f2e2c&clientId=ue2a67ca2-2c74-4&from=paste&height=544&id=ude07d2d6&originHeight=680&originWidth=826&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=70961&status=done&style=none&taskId=ue2b4cc92-9000-47ab-ba17-348f4d8e494&title=&width=660.8)

# File
## 概述
File:

- File对象就表示一个路径，可以是文件的路径、也可以是文件夹的路径
- 这个路径可以是存在的，也允许是不存在的
## 构造方法
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685190122286-00c912f8-65d0-4b4c-b02d-2facb28cdc74.png#averageHue=%23fcfefe&clientId=u72346d50-8490-4&from=paste&height=386&id=u8d2de7ff&originHeight=483&originWidth=1572&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=207006&status=done&style=none&taskId=u24f17abe-f25e-4120-b5ef-678990cfef1&title=&width=1257.6)
```java
import java.io.File;

public class ConstructorMethod {
    public static void main(String[] args) {
        //1、根据字符串表示的路径，变成File对象
        String str="C:\\Users\\刘煜熙\\Desktop\\a.txt";
        File f1=new File(str);
        System.out.println(f1);//C:\Users\刘煜熙\Desktop\a.txt

        //2、父级路径：C:\Users\刘煜熙\Desktop
        //子级路径：a.txt
        String parent="C:\\Users\\刘煜熙\\Desktop";
        String child="a.txt";
        File f2=new File(parent,child);
        System.out.println(f2);//C:\Users\刘煜熙\Desktop\a.txt

        //3、把一个File表示的路径和String表示路径进行拼接
        File parent2=new File("C:\\Users\\刘煜熙\\Desktop");
        String child2="a.txt";
        File f4=new File(parent2,child2);
        System.out.println(f4);//C:\Users\刘煜熙\Desktop\a.txt
    }

}
```

![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685191257546-3ec6d0bc-364b-4c27-a18a-bc27891e92c4.png#averageHue=%23f4f0e8&clientId=u72346d50-8490-4&from=paste&height=549&id=ufe83970c&originHeight=686&originWidth=1509&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=427423&status=done&style=none&taskId=ud8d0d8f1-5156-4408-b4b4-06f063a1370&title=&width=1207.2)
## 成员方法
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685192464018-e92ce377-bd33-47ed-bd15-2d7f04eeb231.png#averageHue=%23f5f8f9&clientId=u72346d50-8490-4&from=paste&height=586&id=u00362218&originHeight=733&originWidth=1434&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=472083&status=done&style=none&taskId=u0e3a6797-e59c-45ed-bc9a-399f4727b5f&title=&width=1147.2)
```java
package Method;

import java.io.File;

public class Method1 {
    public static void main(String[] args) {
        //关于判断的方法
        //1、对一个文件的路径进行判断
        File f1=new File("D:\\aaa\\a.txt");
        System.out.println(f1.isDirectory());//false
        System.out.println(f1.isFile());//true
        System.out.println(f1.exists());//true
        System.out.println("------------------------------");
        //2、对一个文件夹的路径进行判断
        File f2=new File("D:\\aaa\\bbb");
        System.out.println(f2.isDirectory());//true
        System.out.println(f2.isFile());//false
        System.out.println(f2.exists());//true
        System.out.println("------------------------------");
        //3、对一个不存在的路径进行判断
        File f3=new File("D:\\aaa\\abc.txt");
        System.out.println(f3.isDirectory());//false
        System.out.println(f3.isFile());//false
        System.out.println(f3.exists());//false
        System.out.println("------------------------------");
    }
}
```
```java
package Method;

import java.io.File;
import java.text.SimpleDateFormat;

public class Method2 {
    public static void main(String[] args) {
        //获取
        //1、length 返回文件的大小（字节数量）
        //细节：这个方法自能获取文件的大小，单位是字节
        //如果单位需求是K、M、G,不断除以1024
        //细节2：这个方法无法获取文件夹的大小
        //如果我们要获取一个文件夹的大小，需要把这个文件夹里面的所有文件大小累加
        File f1=new File("D:\\aaa\\a.txt");
        long length = f1.length();
        System.out.println(length);
        System.out.println("-------------------------");
        //2、getAbsolutePath 返回文件的绝对路径
        File f3=new File("D:\\aaa\\a.txt");
        String path1=f3.getAbsolutePath();
        System.out.println(path1);//D:\aaa\a.txt

        File f4=new File("basic.code\\a.txt");
        String path2=f4.getAbsolutePath();
        System.out.println(path2);//D:\程序代码\java\basic.code\basic.code\a.txt
        System.out.println("-------------------------");
        //3、getPath 返回定义文件时使用的路径
        File f5=new File("D:\\aaa\\a.txt");
        String path3=f5.getPath();
        System.out.println(path1);//D:\aaa\a.txt

        File f6=new File("basic.code\\a.txt");
        String path4=f6.getPath();
        System.out.println(path4);//basic.code\a.txt
        System.out.println("-------------------------");
        //4、getName 获取名字
        //细节：
        //如果获取的是文件，返回的是文件名.后缀名
        //如果获取的是文件夹,返回的是文件夹的名字
        File f7=new File("D:\\aaa\\a.txt");
        String name1 = f7.getName();
        System.out.println(name1);//a.txt

        File f8=new File("D:\\aaa\\bbb");
        String name2 = f8.getName();
        System.out.println(name2);//bbb
        System.out.println("-------------------------");
        //5、lastModified 返回文件的最后修改时间（时间毫秒值）
        File f9=new File("D:\\aaa\\a.txt");
        long time = f9.lastModified();
        System.out.println(time);//1685194038423
        SimpleDateFormat sdf=new SimpleDateFormat("yyyy年MM月dd日 HH:mm:ss");
        System.out.println(sdf.format(time));//2023年05月27日 21:27:18


    }
}
```

![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685194241544-f74739d1-ca3f-4fd9-9218-d1e3f112f4aa.png#averageHue=%23f5faf7&clientId=u72346d50-8490-4&from=paste&height=560&id=uf42e73a6&originHeight=700&originWidth=1425&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=289978&status=done&style=none&taskId=uba5cefe1-6fcb-4315-8e72-285da68b361&title=&width=1140)
```java
package Method;

import java.io.File;
import java.io.IOException;

public class Method3 {
    public static void main(String[] args) throws IOException {
        //创建和删除
        //1、creatNewFile 创建一个新的空文件
        //细节：如果当前路径表示的文件时不存在的，则创建成功，方法返回true
        //     如果当前路径表示的文件时存在的，则创建失败，方法返回false
        //细节2:如果父级路径不存在，那么方法会有异常IOException
        //细节3：creatNewFile方法创建的一定是文件，如果路径中不包含后缀名，则创建一个没有后缀名的文件
        File f1=new File("D:\\aaa\\c.txt");
        boolean b=f1.createNewFile();//true
        System.out.println(b);

        //2、mkdir    make Director 文件夹（目录）
        //细节1：windows当中路径是唯一的，如果当前路径已存在，则创建失败，返回false
        //细节2：mkdir方法只能创建单级文件夹，无法创建多级文件夹
        File  f2=new File("D:\\aaa\\ddd");
        boolean b1 = f2.mkdir();
        System.out.println(b1);

        //3、mkdirs  创建多级文件夹
        //细节： 既可以创建单级的，也可以创建多级的文件夹
        File f3=new File("D:\\aaa\\aaa\\ddd");
        boolean b2=f3.mkdirs();
        System.out.println(b2);

        //4、delete 删除文件夹、空文件夹
        //细节：如果删除的是文件，则直接删除，不走回收站
        //     如果删除的是空文件夹，则直接删除，不走回收站
        //     如果删除的是有内容的文件夹，则删除失败
    }
}
```

![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685192483793-001a9fb4-4c6f-47e3-add1-ab2d879bd47f.png#averageHue=%23fdfdf7&clientId=u72346d50-8490-4&from=paste&height=264&id=u3c839103&originHeight=330&originWidth=1410&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=114135&status=done&style=none&taskId=u2769e369-e021-44da-8063-32ee6f17eb3&title=&width=1128)
```java
package Method;

import java.io.File;

public class Method4 {
    public static void main(String[] args) {
        //获取并遍历
        File f=new File("D:\\aaa");
        File[] files = f.listFiles();
        for (File file : files) {
            System.out.println(file);
        }/*D:\aaa\a.txt
D:\aaa\aaa
D:\aaa\b.txt
D:\aaa\bbb
D:\aaa\c.txt
D:\aaa\ddd*/
    }
}
```
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685195423315-cc0da604-7ccb-46bf-aacd-08d2515450b1.png#averageHue=%23f7f2f1&clientId=u72346d50-8490-4&from=paste&height=313&id=U9ieG&originHeight=391&originWidth=1641&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=315846&status=done&style=none&taskId=ua95f3d8f-ad31-4337-a429-81df3998fb8&title=&width=1312.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685192502939-fcb1f55a-4ccf-4c4d-8ce3-1cee74f7b2f4.png#averageHue=%232e84d0&clientId=u72346d50-8490-4&from=paste&height=470&id=u2e32b71c&originHeight=587&originWidth=1450&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=370897&status=done&style=none&taskId=u1bad6005-fd32-490a-95d3-4e6f30d075d&title=&width=1160)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685195776516-a36e765c-a837-477a-8cbd-7a150ca9d274.png#averageHue=%23f5f3e5&clientId=u72346d50-8490-4&from=paste&height=591&id=uce403e4e&originHeight=739&originWidth=800&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=350187&status=done&style=none&taskId=u82a70c70-a1dd-4fab-a2f4-13cd6b1cda6&title=&width=640)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685195849044-300222fc-0dcf-4fdc-8f03-367a9610aada.png#averageHue=%23edeae1&clientId=u72346d50-8490-4&from=paste&height=228&id=ua29d6bd9&originHeight=285&originWidth=779&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=113451&status=done&style=none&taskId=u0fa1aaec-769e-4b83-b9c1-8cd7df3c8e5&title=&width=623.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685196011878-41bab5bd-4551-4bb2-a438-659969cb1d25.png#averageHue=%23f2efe1&clientId=u72346d50-8490-4&from=paste&height=434&id=u1b1f3ee0&originHeight=543&originWidth=914&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=213186&status=done&style=none&taskId=u027b7f54-6716-42d0-8886-7d374c1ed6e&title=&width=731.2)
# IO流
## 概述
IO流：
存储和读取数据的解决方案
用于读写文件中的数据（可以读写文件，或网络中的数据）
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685279094671-3b8bf519-af82-47a4-9f42-5b54531bfb57.png#averageHue=%23fcf9f8&clientId=ua1863aec-24d5-4&from=paste&height=582&id=u8620abfd&originHeight=728&originWidth=1606&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=231942&status=done&style=none&taskId=uee95837a-de0d-48e3-b7e1-b25d4de559f&title=&width=1284.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685368127568-dce547d3-5fa4-4a0d-adf4-9a4f99297cf8.png#averageHue=%23fdfbfb&clientId=u9c2785ca-38c6-4&from=paste&height=592&id=u9484869c&originHeight=740&originWidth=1604&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=231034&status=done&style=none&taskId=u7dfa063b-b820-4818-b3c5-86b3630ca96&title=&width=1283.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685279235533-3065badb-75ac-4e76-94df-1cc3cf8cbdcc.png#averageHue=%23fbf7f6&clientId=ua1863aec-24d5-4&from=paste&height=635&id=u6d19136e&originHeight=794&originWidth=1347&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=435984&status=done&style=none&taskId=u33dd027c-2fba-4c12-a698-4e137521acc&title=&width=1077.6)
## 字节流
### FIleOutputStream字节输出流
#### FIleOutputStream书写细节：
1、创建字节输出流对象
细节1：参数是字符串表示的路径或File对象都可以
细节2：如果文件不存在会创建一个新的文件
细节3、如果文件已经存在，则会清空文件
2、写数据
细节：write方法的形参是整数，但是实际上写的是本地文件中的是整数在ASCII上对应的字符
3、释放资源
细节：每次使用完流之后都要释放资源
```java
package com.heima.bytestream;

import java.io.FileNotFoundException;
import java.io.FileOutputStream;
import java.io.IOException;

public class ByteStream {
    public static void main(String[] args) throws IOException {
        /*
演示：字节输出流FileOutputStream
实现需求：写出一段文字到本地文件中
实现步骤：
创建对象
写出数据
释放资源
*/
        //1、创建对象
        //写出 输出流 OutputStream
        //本地文件 FIle
        FileOutputStream fos=new FileOutputStream("IO\\a.txt");
        //2、写出数据
        fos.write(97);
        //3、释放资源
        fos.close();
    }
}
```

#### 写数据的方法
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685281294607-5c42d026-a040-4a70-8f16-50cfab57fe45.png#averageHue=%23ead7d7&clientId=ua1863aec-24d5-4&from=paste&height=347&id=u78e4f048&originHeight=434&originWidth=1441&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=144157&status=done&style=none&taskId=u9dbc8be8-fcad-4f26-8307-48907165664&title=&width=1152.8)
```java
package com.heima.bytestream;

import java.io.FileOutputStream;
import java.io.IOException;

public class ByteStreamMethod {
    public static void main(String[] args) throws IOException {
        FileOutputStream fos=new FileOutputStream("IO\\a.txt");
        //法一
        //        fos.write(97);
        //        fos.write(98);
        //法二：
        byte[] bytes={97,98,99,100,101};
        //        fos.write(bytes);
        //法三：
        //参数一：数组   参数二：起始索引  参数三：个数
        fos.write(bytes,1,2);//bc
        fos.close();

    }
}
```
#### 换行和续写
换行写：
再次写出一个换行符
windows: \r\n
Linux: \n
Mac:\r
细节：
在windows操作系统中，java对回车换行进行了优化
虽然完整的是\r\n，但是我们写其中一个\r或者\n，java也可以实现换行，因为java在底层会补全
建议：不要省略
续写：
如果想要续写，打开续写开关即可
开关位置：创建对象的第二个参数
默认falsse：表示关闭续写，此时创建对象会清空文件
手动传递true：表示打开续写，此时创建对象不会清空文件
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685283387030-fda83137-250a-4969-88b8-85ce426299e7.png#averageHue=%23faf8f8&clientId=ua1863aec-24d5-4&from=paste&height=547&id=u612e5b0a&originHeight=684&originWidth=1360&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=241429&status=done&style=none&taskId=ub87e7498-adb8-47c1-8444-150908d2783&title=&width=1088)
### FileInputStream
#### FileInputStream书写细节
1、创建字节输入流对象
细节1：如果文件不存在，就直接报错
输出流：不存在，创建
把数据写在文件中
输入流：不存在，报错
因为创建出来的文件时没有数据的，没有任何意义
所以Java就没有设计这种无意义的逻辑，文件不存在直接报错
程序最重要的是：数据
2、读取数据
细节1：一次读一个字节，读出来的是数据在ASCII上对应的数字
细节2：读到文件末尾了，read方法返回-1
3、释放资源
细节1：每次使用完流必须要释放资源
```java
package com.heima.bytestream.fileinputstream;

import java.io.FileInputStream;
import java.io.IOException;

public class FileInputStream2 {
    public static void main(String[] args) throws IOException {
        FileInputStream fis = new FileInputStream("IO\\a.txt");
        int b;
        while((b = fis.read())!=-1){
            System.out.print((char)b);
        }
        fis.close();
    }
}
```
#### 文件拷贝
### ![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685285119831-b9935646-715a-4d36-950d-b38a20889eaf.png#averageHue=%23ece0df&clientId=ua1863aec-24d5-4&from=paste&height=553&id=ue71b0986&originHeight=691&originWidth=1540&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=192252&status=done&style=none&taskId=u25bfc3bf-f3f4-440d-86fb-3357dd59826&title=&width=1232)
### try...catch异常处理
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685363606279-fd16ed47-7d9c-43ad-bb8d-241702952f2f.png#averageHue=%23f9f2d6&clientId=u9c2785ca-38c6-4&from=paste&height=535&id=u31cfeab9&originHeight=669&originWidth=1227&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=182431&status=done&style=none&taskId=u52182759-076a-43fb-af3f-917ea4d0419&title=&width=981.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685363964614-1b0b8ca8-884c-488f-bbce-a95d4702b197.png#averageHue=%23f8f2da&clientId=u9c2785ca-38c6-4&from=paste&height=531&id=ua13e5647&originHeight=664&originWidth=1563&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=359831&status=done&style=none&taskId=uc3721754-137d-4dfd-bd4d-87f71a590fa&title=&width=1250.4)
## 字符集
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685364679186-3eee8f42-3a09-441b-ae9f-c8e8bd47a58d.png#averageHue=%23fcf9f8&clientId=u9c2785ca-38c6-4&from=paste&height=476&id=ua4166052&originHeight=595&originWidth=1307&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=238492&status=done&style=none&taskId=ub2213795-3da5-41ee-8ed5-4a8da766620&title=&width=1045.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685365102858-cdd626c5-5220-4e30-8949-1b64b09ab4b8.png#averageHue=%23fcf6f6&clientId=u9c2785ca-38c6-4&from=paste&height=227&id=u3789f8fe&originHeight=284&originWidth=1089&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=107679&status=done&style=none&taskId=u577787ea-42a9-45be-b339-96bcae537d5&title=&width=871.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685365287368-ae34781f-405c-4247-97b6-0ebe4f51332f.png#averageHue=%23fdfbfa&clientId=u9c2785ca-38c6-4&from=paste&height=231&id=ud5d8a803&originHeight=289&originWidth=781&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=66015&status=done&style=none&taskId=ue90a7f5f-ced3-41f3-9d16-2b21aa85bdf&title=&width=624.8)
### 编码解码
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685368019282-16c53f6b-66d6-4457-b6aa-efaa99991c2c.png#averageHue=%23f4f9f7&clientId=u9c2785ca-38c6-4&from=paste&height=562&id=u4a24d0f3&originHeight=702&originWidth=1485&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=280597&status=done&style=none&taskId=u0b2dcbf0-2e89-428e-a7dc-0d7c8d04408&title=&width=1188)
```java
package com.heima.charset;

import sun.nio.cs.ext.GBK;

import java.io.UnsupportedEncodingException;
import java.util.Arrays;

public class Code {
    public static void main(String[] args) throws UnsupportedEncodingException {
        //1、编码
        String str="ai你哟";
        byte[] bytes1=str.getBytes();//默认使用Unicode
        System.out.println(Arrays.toString(bytes1));

        byte[] bytes2=str.getBytes("GBK");
        System.out.println(Arrays.toString(bytes2));

        //2、解码
        String str2=new String(bytes1);
        System.out.println(str2);

        String str3=new String(bytes1,"GBK");
        System.out.println(str3);

    }
}
```
## 字符流
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685368092552-041fda83-5e05-41c2-aa16-046767d6d029.png#averageHue=%23fdf8f7&clientId=u9c2785ca-38c6-4&from=paste&height=586&id=u0d0a7451&originHeight=733&originWidth=1518&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=221242&status=done&style=none&taskId=ua7812c82-db0f-489e-a933-dd981ecb735&title=&width=1214.4)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685368200513-70c083d3-d363-4d75-876e-ad4b1354259f.png#averageHue=%23fcfdf6&clientId=u9c2785ca-38c6-4&from=paste&height=416&id=u7d20ee9d&originHeight=520&originWidth=1574&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=183707&status=done&style=none&taskId=u23863057-62fa-4eb3-86c1-e7c61d48d21&title=&width=1259.2)
### FileRead
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685368261736-56ef2a85-3183-48e1-8fe5-a47d157c5959.png#averageHue=%23e4e7e3&clientId=u9c2785ca-38c6-4&from=paste&height=363&id=u426da0e6&originHeight=454&originWidth=1415&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=198361&status=done&style=none&taskId=ue8752c1f-9758-4a5c-ab11-b0a65931528&title=&width=1132)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685368285933-d59be74f-c377-4e64-9423-1342c179ea8c.png#averageHue=%23fdfbf3&clientId=u9c2785ca-38c6-4&from=paste&height=255&id=u00d7e170&originHeight=319&originWidth=1427&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=66941&status=done&style=none&taskId=u79659cd7-ede1-46e9-be9f-27a01e641da&title=&width=1141.6)
read()细节
1、如图
2、在读取之后，方法的底层还会进行解码并转成十进制
最终把这个十进制作为返回值
这个十进制的数据也表示在字符集上的数字
英文：文件里面二进制数据  0110 0001
read方法进行读取，解码并转成十进制97
中文：文件里面的二进制数据 11100110 10110001 10001001
read方法进行读取，解码并转成十进制27721
```
package com.heima.charset;

import java.io.FileReader;
import java.io.IOException;

public class ReatTest {
    public static void main(String[] args) throws IOException {
        FileReader fr=new FileReader("IO\\a.txt");
        int ch;
        while((ch=fr.read())!=-1){
            System.out.println((char)ch);
        }
        fr.close();
    }
}
```
read（chars）细节:
读取数据、解码、强转三步合并，把强转后的字符放到数组中
空参的read+强制类型转换
```
package com.heima.charset;

import java.io.FileReader;
import java.io.IOException;

public class ReadTest2 {
    public static void main(String[] args) throws IOException {
        FileReader fr=new FileReader("IO\\a.txt");
        char[] chars = new char[2];
        int len;
        while((len=fr.read(chars))!=-1){
            System.out.print(new String(chars,0,len));
        }
        fr.close();
    }
}
```
### FileWriter
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685369269897-30e6ea99-83be-4baa-bf86-6333520313d9.png#averageHue=%23f3f8f7&clientId=u9c2785ca-38c6-4&from=paste&height=418&id=u3cdb8fcd&originHeight=523&originWidth=1530&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=249877&status=done&style=none&taskId=ud01f0b13-65b6-4ecb-9d1c-e18f083f2da&title=&width=1224)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685369290207-d78270a3-dd0d-4f09-bf8f-520c11a4fa66.png#averageHue=%23f7fefd&clientId=u9c2785ca-38c6-4&from=paste&height=449&id=uec3a12e5&originHeight=561&originWidth=1475&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=203687&status=done&style=none&taskId=ud8c985d9-9419-4074-bac4-9ac9e2eab70&title=&width=1180)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685369319701-fdc19aaf-fd5f-4d14-ac89-3f0c2c0b5c4e.png#averageHue=%23fefdfd&clientId=u9c2785ca-38c6-4&from=paste&height=617&id=ub12afc10&originHeight=771&originWidth=1470&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=298203&status=done&style=none&taskId=u8222bb5e-cd01-4f71-acb9-9ba110efbbe&title=&width=1176)
```
package com.heima.charset;

import java.io.FileWriter;
import java.io.IOException;

public class WriteTest {
    public static void main(String[] args) throws IOException {
        FileWriter fw=new FileWriter("IO\\a.txt");
        //fw.write(25105);//我
        //fw.write("我和你心连心",2,2);//你心
        char[] chars={'a','b','c','我'};
        fw.write(chars);

        fw.close();
    }
}
```
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685446314827-01ef1fbc-21fa-46bd-ae1c-36f6866c82b9.png#averageHue=%23fdfcfc&clientId=uce0c2aff-43b8-4&from=paste&height=544&id=u98b88f27&originHeight=680&originWidth=1522&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=337027&status=done&style=none&taskId=u48b027f1-c7d9-49f5-b267-f28836580d4&title=&width=1217.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685446657016-1347234b-4a16-43a3-80ac-62d227c0dc4f.png#averageHue=%23f3fdfa&clientId=uce0c2aff-43b8-4&from=paste&height=465&id=uc265c0e5&originHeight=581&originWidth=1520&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=201472&status=done&style=none&taskId=u815ecc9e-f658-44f3-ae9b-89d9b56d713&title=&width=1216)
### 字节流和字符流的使用场景
字节流：
拷贝任意类型的文件
字符流
读取纯文本文件中的数据
往纯文本文件中写入数据
## 高级流
### 缓冲流BufferedStream
#### 字节缓冲流
概述
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685450460426-8c203e3c-b1da-4194-b5ed-8b30e3507fff.png#averageHue=%23fdfafa&clientId=uf975ff3a-b353-4&from=paste&height=558&id=u616c17f5&originHeight=697&originWidth=1468&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=250872&status=done&style=none&taskId=u239fe320-8227-4bf5-947f-1be8018b82b&title=&width=1174.4)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685450514828-00b2c618-1080-46d0-80c4-92d33610b311.png#averageHue=%23edf0eb&clientId=uf975ff3a-b353-4&from=paste&height=512&id=u05028d3b&originHeight=640&originWidth=1517&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=234102&status=done&style=none&taskId=u8846d825-16cf-407d-99fa-9e4d07d6cbd&title=&width=1213.6)
```java
package com.heima.bufferedstream;

import java.io.*;

public class BufferedStreamTest {
    public static void main(String[] args) throws IOException {
        /*
		利用字节缓冲流拷贝文件
*/
        BufferedInputStream bis=new BufferedInputStream(new FileInputStream("IO\\a.txt"));
        BufferedOutputStream bos=new BufferedOutputStream(new FileOutputStream("IO\\copy.txt"));
        int b;
        while((b=bis.read())!=-1){
            bos.write(b);
        }
        bos.close();
        bis.close();
    }
}
```
一次读写多个字节
```java
package com.heima.bufferedstream;

import java.io.*;

public class BufferedStreamTest {
    public static void main(String[] args) throws IOException {
        /*
利用字节缓冲流拷贝文件
*/
        BufferedInputStream bis=new BufferedInputStream(new FileInputStream("IO\\a.txt"));
        BufferedOutputStream bos=new BufferedOutputStream(new FileOutputStream("IO\\copy.txt"));
        byte[] bytes=new byte[1024];
        //   int b;
        int len;
        while((len=bis.read(bytes))!=-1){
            bos.write(bytes,0,len);
            //bos.write(b);
        }
        bos.close();
        bis.close();
    }
}
```
字节缓冲流提高效率的原理
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685451574368-43648a5c-6dac-42bf-84d5-b5ddb0b7a4b5.png#averageHue=%23f6f6ea&clientId=uf975ff3a-b353-4&from=paste&height=552&id=u585022a4&originHeight=690&originWidth=1619&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=194062&status=done&style=none&taskId=ua7c7b3f8-b970-4b63-8270-5477893b22f&title=&width=1295.2)
#### 字符缓冲流
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685451701346-c8eb7b68-a968-4f42-b7cf-1437c8a5248e.png#averageHue=%23f6f6f6&clientId=uf975ff3a-b353-4&from=paste&height=584&id=u5e21c554&originHeight=730&originWidth=1337&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=160037&status=done&style=none&taskId=u409d3248-e9d2-4232-aa50-680e8df4021&title=&width=1069.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685451717590-97be21de-c2d4-408c-942e-9f051cd7df7d.png#averageHue=%23f2f5f1&clientId=uf975ff3a-b353-4&from=paste&height=534&id=uc0385ce3&originHeight=668&originWidth=1540&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=200794&status=done&style=none&taskId=uf825b658-8447-4250-8482-0a568f82823&title=&width=1232)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685451726298-725bfc77-f386-4915-85c9-ea0692c9c8e8.png#averageHue=%23f6f9f1&clientId=uf975ff3a-b353-4&from=paste&height=532&id=u30d92ba2&originHeight=665&originWidth=1532&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=199138&status=done&style=none&taskId=u99c2c693-ae44-4f49-b081-a3a0965fc57&title=&width=1225.6)
字符缓冲输入流
注意：
readLine方法在读取，一次读一整行，遇到回车换行结束
但是它不会吧回车换行读到内存当中
```java
package com.heima.bufferedstream;

import java.io.BufferedReader;
import java.io.FileReader;
import java.io.IOException;

public class BufferedStreamTest2 {
    public static void main(String[] args) throws IOException {
        /*
字符缓冲输入流
*/
        BufferedReader bf=new BufferedReader(new FileReader("IO\\a.txt"));
        String line;
        while((line=bf.readLine())!=null){
            System.out.println(line);
        }
        bf.close();
    }
}
```
```
package com.heima.bufferedstream;

import java.io.BufferedOutputStream;
import java.io.BufferedWriter;
import java.io.FileWriter;
import java.io.IOException;

public class BufferedStreamTest3 {
    public static void main(String[] args) throws IOException {
        BufferedWriter bw=new BufferedWriter(new FileWriter("IO\\copy2.txt"));
        bw.write("你好美");
        bw.newLine();
        bw.write("和我一样");
        bw.newLine();
        bw.close();

    }
}
```
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685452389371-1ef4d4b5-db4c-4d31-bd15-a5ea141aa7a7.png#averageHue=%23fdfbfb&clientId=uf975ff3a-b353-4&from=paste&height=654&id=u69b98238&originHeight=818&originWidth=1462&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=400376&status=done&style=none&taskId=u71e7f3f4-9010-48eb-862c-f4e576f1037&title=&width=1169.6)
### 转换流 ConvertStream
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685455105405-959088ff-4fba-4f49-bd88-ff3f13b8b14b.png#averageHue=%23fdf7f7&clientId=u5973bb3e-5753-4&from=paste&height=662&id=ub7cad32f&originHeight=827&originWidth=1488&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=277318&status=done&style=none&taskId=ufffc106e-b2ff-49b0-ac18-65a3d1f0b72&title=&width=1190.4)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685455226876-47a3b0b8-ebe6-482e-917d-f4909d718a5b.png#averageHue=%23f5f1e9&clientId=u5973bb3e-5753-4&from=paste&height=641&id=uc6c7eabf&originHeight=801&originWidth=1471&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=238946&status=done&style=none&taskId=ua9ce5f85-27ea-484e-b958-c6afb4bd128&title=&width=1176.8)
利用转换流按照指定字符编码读取
```java
package com.heima.converstream;

import java.io.FileInputStream;
import java.io.FileReader;
import java.io.IOException;
import java.io.InputStreamReader;
import java.nio.charset.Charset;

public class ConverStreamTest {
    public static void main(String[] args) throws IOException {
        /*
需求：利用转换流按照指定字符编码读取
*/
        InputStreamReader isr=new InputStreamReader(new FileInputStream("IO\\gbkfile.txt"),"GBK");
        int ch;
        while((ch=isr.read())!=-1){
            System.out.print((char)ch);
        }
        isr.close();
        //JDK11后
        /*        FileReader fr=new FileReader("IO\\gbk.txt", Charset.forName("GBK"));
int ch;
while((ch=fr.read())!=-1){
System.out.print((char)ch);
}
fr.close();*/
    }
}
```
利用转换流按照指定字符编码写出
```java
package com.heima.converstream;

import java.io.FileOutputStream;
import java.io.FileWriter;
import java.io.IOException;
import java.io.OutputStreamWriter;
import java.nio.charset.Charset;

public class ConverStreamTest2 {
    public static void main(String[] args) throws IOException {
        /*
利用转换流按照指定字符编码写出
*/
        OutputStreamWriter osw=new OutputStreamWriter(new FileOutputStream("IO\\b.txt"),"GBK");
        osw.write("你好你好");
        osw.close();

        //JBK11以后
        /*        FileWriter fw=new FileWriter("IO\\b.txt", Charset.forName("GBK"));
fw.write("你好你好");
fw.close();*/
    }
}
```
将本地文件中的GBK文件，转成UTF-8
```java
package com.heima.converstream;

import java.io.*;
import java.nio.charset.Charset;

public class ConverStreamTest3 {
    public static void main(String[] args) throws IOException {
        /*
将本地文件中的GBK文件，转成UTF-8
*/
        InputStreamReader isr=new InputStreamReader(new FileInputStream("IO\\b.txt"),"GBK");
        OutputStreamWriter osw=new OutputStreamWriter(new FileOutputStream("IO\\d.txt"),"UTF-8");
        int b;
        while((b= isr.read())!=-1){
            osw.write(b);
        }
        osw.close();
        isr.close();

        //JBK11以后
        /*        FileReader fr=new FileReader("IO\\b.txt", Charset.forName("GBK"));
FileWriter fw=new FileWriter("IO\\d.txt",Charset.forName("UTF-8"));
int b;
fw.close();
fr.close();*/
    }
}
```
猜一下，应该是读取的时候用字节流的形式读取，速度快。
最终目的是为了提高数据在硬盘和内存之间的读写效率
然后使用数据，或者说打印的时候，要一行一行的用。所以需要用到字符缓冲流里的方法
所以就成了：字节流→转换流→字符缓冲流

利用字节流读取文件中的数据，每次读一整行，而且不能出现乱码
```java
package com.heima.converstream;
import java.io.BufferedReader;
import java.io.FileInputStream;
import java.io.IOException;
import java.io.InputStreamReader;

public class ConverStreamTest4 {
    public static void main(String[] args) throws IOException {
        /*
利用字节流读取文件中的数据，每次读一整行，而且不能出现乱码
Tip:
1、字节流在读取中文的时候会出现乱码，但字符流可以搞定
2、字节流里面没有读一整行的方法，只有字符缓冲流才能搞定
*/

        /*        FileInputStream fis=new FileInputStream("IO\\a1.txt");
InputStreamReader fsr=new InputStreamReader(fis);
BufferedReader br=new BufferedReader(fsr);
String str=br.readLine();
System.out.println(str);
br.close();*/

        BufferedReader br=new BufferedReader(new InputStreamReader(new FileInputStream("IO\\a1.txt")));
        String str;
        while((str=br.readLine())!=null){
            System.out.println(str);
        }
        br.close();
    }
}
```
### 序列化流 ObjectStream
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685457680506-93b46497-e329-4c07-bf86-59131acedf3c.png#averageHue=%23fcf8f7&clientId=u5973bb3e-5753-4&from=paste&height=635&id=u148b2af2&originHeight=794&originWidth=1489&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=230403&status=done&style=none&taskId=u724fadd4-47de-4298-96d3-6e2109ab6f3&title=&width=1191.2)
#### 序列化流
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685457773232-18fe4638-f539-41b6-b110-9b4e6e519e15.png#averageHue=%23f8faf5&clientId=u5973bb3e-5753-4&from=paste&height=553&id=ubff9e42b&originHeight=691&originWidth=1470&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=227142&status=done&style=none&taskId=ubc2e77a0-1215-4440-93c0-eb7666759b4&title=&width=1176)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685457847118-f6b89202-207e-45d9-9313-6c2f6e956d9f.png#averageHue=%23fcfbf5&clientId=u5973bb3e-5753-4&from=paste&height=422&id=u6fcc6fa7&originHeight=527&originWidth=1401&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=171662&status=done&style=none&taskId=uee65c573-35cb-42f3-bd9a-2c0e945b952&title=&width=1120.8)
Serializable接口里面没有抽象方法，标记型接口
一旦实现了这个接口，那么就表示当前的Student类可以被序列化
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685458386159-795338bc-60af-4f1d-9a8d-7feb061d153d.png#averageHue=%232e2d2c&clientId=u5973bb3e-5753-4&from=paste&height=180&id=u0a297519&originHeight=225&originWidth=722&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=15802&status=done&style=none&taskId=u8b1d6c45-6838-4d6a-bcdd-70774a7d2cd&title=&width=577.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685458402971-41559062-5907-4d89-a9c6-8e00c1eaaef5.png#averageHue=%232d2c2c&clientId=u5973bb3e-5753-4&from=paste&height=527&id=ub04b7c88&originHeight=659&originWidth=1215&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=80804&status=done&style=none&taskId=u5ac186ce-2649-4c04-a788-d07665e3556&title=&width=972)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685458411885-3ec1c258-7b71-4e74-9909-d30f57cbb852.png#averageHue=%233f3130&clientId=u5973bb3e-5753-4&from=paste&height=138&id=u7aa7c74a&originHeight=173&originWidth=1536&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=18944&status=done&style=none&taskId=u15605f2d-2faa-49d5-be39-b3ae9b4e85c&title=&width=1228.8)
#### 反序列化流
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685458696908-061ee3a5-37b3-4296-a78d-a2053043bbaa.png#averageHue=%23ead6d5&clientId=u5973bb3e-5753-4&from=paste&height=566&id=u045b8e23&originHeight=708&originWidth=1492&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=203627&status=done&style=none&taskId=ueca59ac9-1065-4bd8-bd2b-8f56531a7d5&title=&width=1193.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685458980844-3026802b-adb2-4c16-8e1d-9c4d7e44f0bb.png#averageHue=%232d2c2c&clientId=u5973bb3e-5753-4&from=paste&height=567&id=u505052f5&originHeight=709&originWidth=1226&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=85622&status=done&style=none&taskId=u5a9e6f23-21c0-4f20-8999-48417a02771&title=&width=980.8)
细节：
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685459114044-d405cdf5-371e-4c23-a732-f52e987a9337.png#averageHue=%23f6f1e3&clientId=u5973bb3e-5753-4&from=paste&height=605&id=ucdf7604a&originHeight=756&originWidth=1436&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=324744&status=done&style=none&taskId=ue488a746-4e53-4ed3-965d-106f935611f&title=&width=1148.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685465215809-19bc762a-72ba-4e97-82bf-4c0a1168f358.png#averageHue=%23fefcfc&clientId=ucca47570-d786-4&from=paste&height=570&id=ub242ad53&originHeight=712&originWidth=1349&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=393470&status=done&style=none&taskId=uc2b1925c-ea1b-4b53-be3d-ed8c914ceca&title=&width=1079.2)
### 打印流 PrintStream
打印流不能读只能写，只有字符输出流
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685465807660-cc71100d-7f64-4d24-8356-a10bc4f5e15b.png#averageHue=%23fdfcfb&clientId=ucca47570-d786-4&from=paste&height=608&id=ue5882ff6&originHeight=760&originWidth=1464&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=177144&status=done&style=none&taskId=u2a74baef-53b2-4594-b85c-f419981e137&title=&width=1171.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685465878310-db061170-826b-420c-b173-662eaf1397af.png#averageHue=%23fcfbfb&clientId=ucca47570-d786-4&from=paste&height=523&id=ufa5ae24f&originHeight=654&originWidth=921&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=203249&status=done&style=none&taskId=u0d288bf7-1fe2-4127-8774-9980aa096e3&title=&width=736.8)
#### 字节打印流
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685524161276-3500b23e-923f-488e-8ad2-8f63e940f973.png#averageHue=%23f9fefe&clientId=u0699855f-3fcc-4&from=paste&height=535&id=ud47be445&originHeight=669&originWidth=1546&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=273921&status=done&style=none&taskId=u6c0acbb2-b4e6-4d66-b755-a3ad83e8040&title=&width=1236.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685524305396-89ee0f2a-1374-413e-b925-84e4c22c8c32.png#averageHue=%23f4fbfa&clientId=u0699855f-3fcc-4&from=paste&height=571&id=u4bbf188e&originHeight=714&originWidth=1586&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=299142&status=done&style=none&taskId=uaf0e44f7-ea6f-4f66-9c95-ba85ab07c0d&title=&width=1268.8)
```java
package com.heima.printstream;

import java.io.FileNotFoundException;
import java.io.FileOutputStream;
import java.io.PrintStream;
import java.io.UnsupportedEncodingException;
import java.nio.charset.Charset;

public class PrintStreamDemo {
    public static void main(String[] args) throws FileNotFoundException, UnsupportedEncodingException {
        //创建字节打印流的对象
        PrintStream ps=new PrintStream(new FileOutputStream("IO\\a.txt"),true,"UTF-8");
        ps.println(97);
        ps.print(true);
        ps.format("%s和%s","我","你");
    	ps.close();
//97
true我和你

    }
}
```

#### 字符打印流
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685524928476-44ccfd5f-ea98-4170-b7c3-abb77a2d7a42.png#averageHue=%23ebe1e1&clientId=u0699855f-3fcc-4&from=paste&height=570&id=u94972028&originHeight=713&originWidth=1535&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=199947&status=done&style=none&taskId=u54ad9269-b4d8-4f08-bc1e-90f35490185&title=&width=1228)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685524992115-cc43963e-b094-42f2-bead-b5b58b089ae5.png#averageHue=%23f7fbf8&clientId=u0699855f-3fcc-4&from=paste&height=462&id=u0f94d6d1&originHeight=577&originWidth=1431&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=218096&status=done&style=none&taskId=u060a7dd1-8626-425f-9d8b-f73044f8601&title=&width=1144.8)
标准输出流
获取打印流的对象，此打印流在虚拟机启动的时候，由虚拟机创建，默认指向控制台
特殊的打印流，系统中的标准输出流，是不能关闭的，在此系统中是唯一的
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685525229064-6f3936b7-c68b-450e-8d0d-5701bd0ee723.png#averageHue=%232d2c2b&clientId=u0699855f-3fcc-4&from=paste&height=401&id=u70b119d6&originHeight=501&originWidth=1074&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=47724&status=done&style=none&taskId=u4367e8a0-0129-452b-86d9-dcf199156e3&title=&width=859.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685525504396-00f36329-ca89-48ae-a092-afbe0a0b4f4e.png#averageHue=%232d2c2c&clientId=u0699855f-3fcc-4&from=paste&height=394&id=ue1f8d934&originHeight=493&originWidth=1045&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=61809&status=done&style=none&taskId=u38d47fd4-9a3c-471c-8d7b-936a43de704&title=&width=836)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685525614390-052382d4-10f6-4c4f-9e0f-80184018d269.png#averageHue=%23fdfbfa&clientId=u0699855f-3fcc-4&from=paste&height=463&id=uc3d45169&originHeight=579&originWidth=1499&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=233578&status=done&style=none&taskId=ufba9cc05-c16d-4dc0-948f-d420456cf56&title=&width=1199.2)
### 解压缩流/压缩流 ZipStream
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685525728836-7c0676a9-b77a-40c0-ab82-e4c5aa6cfe12.png#averageHue=%23fcfafa&clientId=u0699855f-3fcc-4&from=paste&height=611&id=ub97f7f84&originHeight=764&originWidth=1492&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=175555&status=done&style=none&taskId=u11038cb9-b910-4e95-9c35-34cc0aa785e&title=&width=1193.6)
#### 解压缩流
解压的本质：
把每一个ZipEntry按照层级拷贝到本地另一个文件夹中
将一个压缩包解压：
```java
package com.heima.zipstream;

import java.io.*;
import java.util.zip.ZipEntry;
import java.util.zip.ZipInputStream;

public class ZipStreamDemo1 {
    public static void main(String[] args) throws IOException {
        File src=new File("D:\\aaa.zip");
        File dest=new File("D:\\");
        unzip(src,dest);

    }
    public static void unzip(File src,File dest) throws IOException {
        //解压的本质 ： 把压缩包里面的每一个文件或者文件夹读取出来，按照层级拷贝到目的地当中

        //创建一个解压缩流用来读取压缩包中的数据
        ZipInputStream zip=new ZipInputStream(new FileInputStream(src));
        //要先获取到压缩包里面的每一个zipentry对象

        //表示当前在压缩包中获取到的文件或者文件夹
        ZipEntry entry;
        while((entry=zip.getNextEntry())!=null){
            System.out.println(entry);
            if(entry.isDirectory()){
                //文件夹 ： 需要在目的地dest处创建一个同样的文件夹
                File file=new File(dest,entry.getName());
                file.mkdirs();
            }else{
                //文件：需要读取到压缩包中的文件，并把它存在目的地dest文件夹中（按照层级目录进行存放）
                FileOutputStream fos=new FileOutputStream(new File(dest,entry.getName()));
                int b;
                while((b= zip.read())!=-1){
                    //写到目的地
                    fos.write(b);
                }
                fos.close();
                //表示在压缩包中的一个文件处理完毕了
                zip.closeEntry();
            }
        }
        zip.close();
    }
}
```
#### 压缩流
压缩的本质：
把每一个文件或文件夹看成ZipEntry对象放到压缩包中
将一个文件压缩：
```java
package com.heima.zipstream;

import java.io.File;
import java.io.FileInputStream;
import java.io.FileOutputStream;
import java.io.IOException;
import java.util.zip.ZipEntry;
import java.util.zip.ZipOutputStream;

public class ZipStreamDemo2 {
    public static void main(String[] args) throws IOException {
        /*
压缩流
需求：
把D:\\a.txt打包成一个压缩包
*/
        //1、创建File对象表示要压缩的文件
        File src=new File("D:\\a.txt");
        //2、创建File对象表示压缩包的位置
        File dest=new File("D:\\");
        //3、调用方法用来压缩
        toZip(src,dest);
    }
    /*
* 作用：压缩
* 参数一：表示要压缩的文件
* 参数二：表示压缩包的位置
* */
    public static void toZip(File src,File dest) throws IOException {
        //1、创建压缩流关联压缩包
        ZipOutputStream zos=new ZipOutputStream(new FileOutputStream(new File(dest,"a.zip")));
        //2、创建ZipEntry对象，表示压缩包里面的每一个文件和文件夹
        ZipEntry entry=new ZipEntry("a.txt");
        //3、把ZipEntry对象放到压缩包里
        zos.putNextEntry(entry);
        //4、把src文件中的数据写到压缩包中
        FileInputStream fis=new FileInputStream(src);
        int b;
        while((b=fis.read())!=-1){
            zos.write(b);
        }
        zos.closeEntry();
        zos.close();
    }
}
```
将一个文件夹进行压缩：
```java
package com.heima.zipstream;

import java.io.File;
import java.io.FileInputStream;
import java.io.FileOutputStream;
import java.io.IOException;
import java.util.zip.ZipEntry;
import java.util.zip.ZipOutputStream;

public class ZipStreamDemo3 {
    public static void main(String[] args) throws IOException {
        //压缩文件夹
        //1、创建File对象表示要压缩的文件夹
        File src=new File("D:\\aaa");
        //2、创建File对象表示压缩包放在哪里（压缩包的父级路径）
        File destParent=src.getParentFile();//D：\\
        //3、创建File对象表示压缩包的路径
        File dest=new File(destParent,src.getName()+".zip");
        //4、创建压缩流关联压缩包
        ZipOutputStream zos=new ZipOutputStream(new FileOutputStream(dest));
        //5、获取src里面的每一个文件，变成ZipEntry对象，放入压缩包中
        toZip(src,zos,src.getName());//aaa
        zos.close();
    }
    /*
*   作用：获取src里面的每一个文件，变成ZipEntry对象，放入压缩包中
*   参数一：数据源
*   参数二：压缩流
*   参数三：压缩所报内部的路径
* */
    public static void toZip(File src,ZipOutputStream zos,String name) throws IOException {
        //1、进入src文件夹
        File[] files = src.listFiles();
        //2、遍历数组
        for (File file : files) {
            if(file.isFile()){
                //3、判断文件，变成ZipEntry对象，放入压缩包中
                ZipEntry entry=new ZipEntry(name+"\\"+file.getName());// aaa+\\+a.txt
                zos.putNextEntry(entry);
                //读取文件中的数据，写到压缩包中
                FileInputStream fis=new FileInputStream(file);
                int b;
                while((b=fis.read())!=-1){
                    zos.write(b);
                }
                fis.close();
                zos.closeEntry();
            }else{
                toZip(file,zos,name+"\\"+file.getName());
            }

        }
    }
}
```
### Commons-io
Commons-io是apache开源基金组织提供的一组关于IO操作的开源工具包
作用：提高IO流的开发效率
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685535936425-dc2021e9-8d05-4c20-968b-f063e5764c99.png#averageHue=%23f5e5e5&clientId=u0699855f-3fcc-4&from=paste&height=348&id=uc3f1e6d7&originHeight=435&originWidth=990&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=120019&status=done&style=none&taskId=u7323e3e1-baf5-4977-89a3-d2174427f0d&title=&width=792)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685536375954-3dcdd988-78cd-4621-9085-28c627aef97a.png#averageHue=%23f9fefd&clientId=u0699855f-3fcc-4&from=paste&height=583&id=u300ecd78&originHeight=729&originWidth=1626&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=362986&status=done&style=none&taskId=ueaa94e7f-c4a6-434d-9dc7-90b8272a679&title=&width=1300.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685536391956-8b2f4ecc-0361-49b8-afce-cb295660b494.png#averageHue=%232e2d2c&clientId=u0699855f-3fcc-4&from=paste&height=384&id=u833446ee&originHeight=480&originWidth=832&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=43892&status=done&style=none&taskId=u37b9023e-ada0-40e5-bbf2-1d1eba46d8f&title=&width=665.6)
### Hutool工具包
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685536869437-4ca6a62b-523c-4da1-a157-3c9ea32f9527.png#averageHue=%23efe5e5&clientId=u0699855f-3fcc-4&from=paste&height=577&id=u23ba011f&originHeight=721&originWidth=1364&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=165807&status=done&style=none&taskId=u24eefb40-5911-45b1-8301-3d09a3e2af0&title=&width=1091.2)
```
package com.heima.hutool;

import cn.hutool.core.io.FileUtil;

import java.io.File;
import java.util.ArrayList;
import java.util.List;

public class HuToolDemo1 {
    public static void main(String[] args) {
/*        //创建file对象，可以将字符串拼接
        File file = FileUtil.file("D:\\", "aaa", "bbb", "a.txt");
        System.out.println(file);//D:\aaa\bbb\a.txt
        //可以直接创建多重文件
        File touch=FileUtil.touch(file);
        System.out.println(touch);*/

/*        ArrayList<String> list=new ArrayList<>();
        list.add("aaa");
        list.add("aaa");
        list.add("aaa");
        File file2=FileUtil.writeLines(list,"D:\\a.txt","UTF-8");
        System.out.println(file2);*/

        ArrayList<String> list=new ArrayList<>();
        list.add("aaa");
        list.add("aaa");
        list.add("aaa");
        File file3=FileUtil.appendLines(list,"D:\\a.txt","UTF-8");
        System.out.println(file3);

        List<String> list1 = FileUtil.readLines("D:\\a.txt", "UTF-8");
        System.out.println(list1);


    }
}
```

# 多线程
## 概念
线程：
线程是操作系统能够进行运算调度的最小单位，它被包含在进程之中，是进程中的实际运作单位
应用软件中互相独立，可以同时运行的功能![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685500311675-d5f1e6bd-69f0-4775-8131-b64f10813aae.png#averageHue=%23f9f7f7&clientId=ua948d8cc-a73a-4&from=paste&height=404&id=u6e54b524&originHeight=505&originWidth=751&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=98487&status=done&style=none&taskId=u8bee5189-3144-4e6b-92c9-fa1be5e5bd3&title=&width=600.8)
并发和并行
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685500450733-379821b9-3576-41d6-b3c8-e0bea576f639.png#averageHue=%23f8f5f5&clientId=ua948d8cc-a73a-4&from=paste&height=247&id=ue9424316&originHeight=309&originWidth=849&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=61928&status=done&style=none&taskId=uf0b70f85-baec-488f-adb3-3ead9d87d11&title=&width=679.2)
## 实现方式
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685503920843-38563eb8-3051-442d-9a39-8bcad64d10dc.png#averageHue=%23fafefb&clientId=ua948d8cc-a73a-4&from=paste&height=454&id=kTLwi&originHeight=567&originWidth=1530&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=231441&status=done&style=none&taskId=u47d9398b-f291-4a8a-9657-8454a895d68&title=&width=1224)
一、多线程的第一种启动方式：
    1、自己定义一个类继承Thread
    2、重写run方法
    3、创建子类的对象，并启动线程
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685502787463-5e7fbaeb-c281-485f-828f-dba6c92f6187.png#averageHue=%232d2c2b&clientId=ua948d8cc-a73a-4&from=paste&height=453&id=u32be28ea&originHeight=566&originWidth=573&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=45702&status=done&style=none&taskId=ued2e51ba-c887-4c94-a059-d71af60581e&title=&width=458.4)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685502849507-a3793f79-97e0-4a32-b200-4afc0483b3bd.png#averageHue=%232e2d2c&clientId=ua948d8cc-a73a-4&from=paste&height=272&id=u446db93e&originHeight=340&originWidth=626&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=25594&status=done&style=none&taskId=ueccf6f05-9da3-4989-afdf-1eadf04ef1e&title=&width=500.8)
二、 多线程的第二种启动方式：
1、自己定义一个类实现Runnable接口
2、重写里面的run方法
3、创建自己的类的对象
4、创建一个Thread类的对象，并开启线程
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685502929077-d9a20e56-304d-4880-8099-ffe259fda130.png#averageHue=%232e2d2c&clientId=ua948d8cc-a73a-4&from=paste&height=386&id=ufc79d138&originHeight=483&originWidth=652&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=41757&status=done&style=none&taskId=uaa39c50b-2d36-4d3d-8d8d-7603fc27f06&title=&width=521.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685502950938-749c28c9-44c1-4fc2-a15d-97bc5f74e1e0.png#averageHue=%232c2c2b&clientId=ua948d8cc-a73a-4&from=paste&height=643&id=u13c55250&originHeight=804&originWidth=905&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=84698&status=done&style=none&taskId=uc724fbcb-30e2-4097-ab38-d2bf1323e73&title=&width=724)
多线程的第三种实现方式：
  特点：可以获取到多线程运行的结果

1、创建一个类MyCallable实现Callable接口
2、重写call(是有返回值的，表示多线程的运行结果)
3、创建MyCallable对象（表示多线程要执行的任务）
4、创建FutureTask的对象（作用管理多线程运行的结果）
5、创建Thread类的对象，并启动（表示线程）
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685503970751-49cdd0c5-1ae6-435d-a6b2-70d7d4b2e863.png#averageHue=%232e2d2c&clientId=ua948d8cc-a73a-4&from=paste&height=393&id=u0205aee6&originHeight=491&originWidth=684&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=35247&status=done&style=none&taskId=uab13aa67-d76c-4bfc-bd0e-dd32b142ace&title=&width=547.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685504022236-3efdbc60-26fb-46d7-8b4c-67a34b64ef0b.png#averageHue=%232c2b2b&clientId=ua948d8cc-a73a-4&from=paste&height=610&id=u4e9c57cc&originHeight=762&originWidth=1106&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=83202&status=done&style=none&taskId=u989ef6eb-1868-469a-bb3b-24ecc37df25&title=&width=884.8)


## 常用成员方法
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685504153587-17f9d39d-01ec-4f16-a819-7e91d7feed60.png#averageHue=%23e9dede&clientId=ua948d8cc-a73a-4&from=paste&height=623&id=u5811483a&originHeight=779&originWidth=1471&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=310550&status=done&style=none&taskId=u5e5c6361-5ada-470c-a1b9-0ed565aab91&title=&width=1176.8)
setName细节：
1、如果我们没有给线程设置名字，线程也是有默认名字的
格式：Thread-X (X序号，从0开始的)
2、如果我们要给线程设置名字，可以用set方法进行设置，也可以构造方法，调用Thread的name
CurrentThread()细节：
当JVM虚拟机启动后，会自动的启动多条线程
其中有一条线程叫做main线程
它的作用就是去调用main方法，并执行里面的代码
在以前，我们写的所有代码，其实都是运行在main线程中
sleep()细节：
1、哪条线程执行到这个方法，那么哪条线程就就会在这里停留对应的时间
2、方法的参数：就表示睡眠的时间，单位是毫秒
1s=1000ms
3、当时间到了后，线程会自动醒来，继续执行下面的代码
```java
package com.heima.threadmethod;

public class MyThread extends Thread{
    public MyThread() {
    }

    public MyThread(String name) {
        super(name);
    }

    public void run(){
        for (int i=0;i<=100;i++) {
            try {
                Thread.sleep(1000);
            } catch (InterruptedException e) {
                throw new RuntimeException(e);
            }
            System.out.println(getName()+"@"+i);
        }
    }
}
```
```java
package com.heima.threadmethod;


public class ThreadMethod {
    public static void main(String[] args) {
        MyThread t1=new MyThread("飞机");
        MyThread t2=new MyThread("坦克");

        t1.start();
        t2.start();
    }
}
```
### 守护线程：
## ![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685628755437-a0b47eb9-e6b6-4cb9-8d88-17812c1485b4.png#averageHue=%23302e2c&clientId=ud74a4a25-4e1f-4&from=paste&height=287&id=u8c125e5f&originHeight=332&originWidth=589&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=26264&status=done&style=none&taskId=u49f6348d-be94-4299-9571-de290648d30&title=&width=509.20001220703125)![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685628771882-d75cd032-20a9-4feb-a9f7-86d1fec6b903.png#averageHue=%232e2d2c&clientId=ud74a4a25-4e1f-4&from=paste&height=234&id=u7d5901e2&originHeight=257&originWidth=568&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=17530&status=done&style=none&taskId=ud4b5f9f4-4a18-432b-b609-68ecaf1328d&title=&width=516.3999938964844)
```java
package com.heima.threadmethod3;

public class ThreadDemo {
    public static void main(String[] args) {
        /*
细节：
当其他的非守护线程执行完毕后，守护线程陆陆续续地结束
通俗易懂：
当女神线程结束了，那么备胎线程也没有存在的必要了
*/
        MyThread1 t1=new MyThread1();
        MyThread2 t2=new MyThread2();

        t1.setName("女神");
        t2.setName("备胎");

        //把第二个线程设置为守护线程（备胎线程）
        t2.setDaemon(true);

        t1.start();
        t2.start();
    }
}
```
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685628814175-d7d42c90-e74e-4016-8992-af7a8ad9a839.png#averageHue=%232d2d2c&clientId=ud74a4a25-4e1f-4&from=paste&height=336&id=ub8fd1184&originHeight=420&originWidth=585&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=24097&status=done&style=none&taskId=u6cd15319-5b9e-4ea8-9fde-38074e2a0a4&title=&width=468)
## 线程的生命周期
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685709887121-ccefaf33-5832-415d-8ba2-44ab9170f3b9.png#averageHue=%23f9e6e4&clientId=u1c629a0e-96ea-4&from=paste&height=474&id=u00355712&originHeight=593&originWidth=1503&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=297662&status=done&style=none&taskId=ue2869587-a1d2-451e-b964-07c3df8f37d&title=&width=1202.4)
sleep方法让线程睡眠，睡眠时间到了之后，不会立马执行下面的代码，会重新先抢CPU执行权
## 同步 synchronized
1、循环
2、同步代码块
3、判断共享数据是否到了末尾（到了末尾）
4、判断共享数据是否到了末尾（没到末尾，执行核心逻辑）
### 同步代码块
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685710442993-b8302082-76be-44ab-a287-9e680c51955d.png#averageHue=%23f2f1f1&clientId=u1c629a0e-96ea-4&from=paste&height=556&id=u99b7bb36&originHeight=695&originWidth=1589&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=171756&status=done&style=none&taskId=u6a6263e7-d005-4bed-91e0-85445e1c211&title=&width=1271.2)
当创建了一个Mythread类后，在一个线程进入run后睡眠时，该线程被阻塞，没有CPU执行权，因此其他线程开始抢夺CPU的执行权，当第二个线程抢到时也开始执行run（），为防止多个线程同时执行run，因此使用synchronized锁住代码块
读音：sin 抠 耐子的
细节：
锁对象可以是任意的，但必须是唯一的，可以使用static确保唯一性
锁对象也可以写成MyThread.class，因为自解码文件一定是唯一的
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685711954946-eec11ce9-027f-401f-bb18-cc29d0b2fd61.png#averageHue=%232c2c2b&clientId=u1c629a0e-96ea-4&from=paste&height=674&id=u91a537e4&originHeight=843&originWidth=1082&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=83205&status=done&style=none&taskId=u0dbc9f8a-d1dc-4567-bd2f-eb2e210f072&title=&width=865.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685711971959-19d09cb4-232c-4862-982a-acade0de7041.png#averageHue=%232d2c2b&clientId=u1c629a0e-96ea-4&from=paste&height=383&id=u840733ba&originHeight=479&originWidth=785&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=34434&status=done&style=none&taskId=u344ddd4d-bfbf-459c-931a-7877b745d62&title=&width=628)
### 同步方法
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685712319223-68fd4b96-497b-45e9-a213-3982feb5f98c.png#averageHue=%23eeecec&clientId=u1c629a0e-96ea-4&from=paste&height=647&id=u59edbeca&originHeight=809&originWidth=1255&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=212073&status=done&style=none&taskId=u4da663f8-bcc8-449a-9892-c26e648302b&title=&width=1004)
同步方法书写技巧：
先写同步代码块，再把同步代码块的内容抽取成同步方法
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685713717771-c7ec4b7a-eadf-44b7-8af1-4038c8a4879a.png#averageHue=%232d2c2b&clientId=u1c629a0e-96ea-4&from=paste&height=680&id=u49a754c9&originHeight=850&originWidth=1022&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=85562&status=done&style=none&taskId=u307055c6-7fd8-4f5f-9d83-71217df5818&title=&width=817.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685713732549-5df36a73-306c-47cf-9214-367be664be8a.png#averageHue=%232c2c2b&clientId=u1c629a0e-96ea-4&from=paste&height=501&id=ua0b95e4c&originHeight=626&originWidth=776&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=47236&status=done&style=none&taskId=u30b983fe-d5c8-4245-92e5-d5d5f9839a5&title=&width=620.8)
## StringBuilder和StringBuffer的区分
如果代码是单线程的，不需要考虑多线程的数据安全的情况，则用StringBuilder
如果代码是多线程的，需要考虑多线程的数据安全的情况，则用StringBuffer
## Lock锁
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685713783859-a3e70607-4426-4217-9e75-b2722caaddcc.png#averageHue=%23f4f0f0&clientId=u1c629a0e-96ea-4&from=paste&height=606&id=u38688211&originHeight=758&originWidth=1311&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=293559&status=done&style=none&taskId=u6ed6cbe9-82f7-45f0-a3fc-dfabbc4495e&title=&width=1048.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685714381044-330e183b-0508-4913-90f8-ff6df63207ae.png#averageHue=%232e2c2b&clientId=u1c629a0e-96ea-4&from=paste&height=711&id=ua2b5cda0&originHeight=889&originWidth=973&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=84083&status=done&style=none&taskId=u3c836405-250a-4655-984a-8b207927feb&title=&width=778.4)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685714446661-7f1e72a4-cb47-46a7-882f-9086238dae33.png#averageHue=%232d2c2c&clientId=u1c629a0e-96ea-4&from=paste&height=432&id=uf2cd837a&originHeight=540&originWidth=829&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=41848&status=done&style=none&taskId=uf94a72ef-e2e3-4ab0-b3fc-9b26ba2d75f&title=&width=663.2)
注意：
写代码时不要写双重锁的嵌套，容易产生死锁
写代码时不要写成死锁
## 生产者和消费者（等待唤醒机制）
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685714883646-d4a7d54b-e24c-4ead-bda5-4ef1410e2d57.png#averageHue=%23f9fefb&clientId=u1c629a0e-96ea-4&from=paste&height=440&id=ub2deafea&originHeight=550&originWidth=1517&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=141290&status=done&style=none&taskId=u2992ba71-aa1d-4bec-9599-d5def1e22a2&title=&width=1213.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685714930914-149a1753-f176-4944-ae14-fda8b052b48c.png#averageHue=%23f8f3f1&clientId=u1c629a0e-96ea-4&from=paste&height=627&id=ubca3b37b&originHeight=784&originWidth=1438&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=368304&status=done&style=none&taskId=ud2e64064-6828-4b6b-a9a7-cbbb21b4f1b&title=&width=1150.4)
```java
package com.heima.a12waitandnotify;

public class Desk {
    /*
* 作用：控制生产者和消费者的执行
* */

    //是否有面条      0:没有面条   1：有面条
    public static int foodFlag = 0;

    //总个数
    public static  int count = 10;

    //锁对象
    public static Object lock = new Object();


}
```
```java
package com.heima.a12waitandnotify;

public class Foodie extends Thread{
    @Override
    public void run() {
        /*
1、循环
2、同步代码块
3、判断共享数据是否到了末尾（到了末尾）
4、判断共享数据是否到了末尾（没到末尾，执行核心逻辑）
*/
        while(true){
            synchronized (Desk.lock){
                if(Desk.count == 0){
                    break;
                }else{
                    //先判断桌子上是否有面条
                    if(Desk.foodFlag==0){
                        //没有面条就等待
                        try {
                            Desk.lock.wait();//让当前线程跟锁进行绑定
                        } catch (InterruptedException e) {
                            throw new RuntimeException(e);
                        }
                    }else{
                        //有面条就吃
                        //吃的总数-1
                        Desk.count--;
                        System.out.println("吃货在吃面条，还剩"+Desk.count+"碗");
                        //唤醒厨师
                        Desk.lock.notifyAll();//唤醒绑定在这把锁上的所有线程
                        //修改桌子状态
                        Desk.foodFlag = 0;
                    }




                }
            }
        }
    }
}
```
```java
package com.heima.a12waitandnotify;

public class Cook extends Thread{
    @Override
    public void run() {
        /*
1、循环
2、同步代码块
3、判断共享数据是否到了末尾（到了末尾）
4、判断共享数据是否到了末尾（没到末尾，执行核心逻辑）
*/
        while(true){
            synchronized (Desk.lock){
                if(Desk.count==0){
                    break;
                }else{
                    //判断桌子上有没有食物
                    if(Desk.foodFlag==1){
                        //如果有就等待
                        try {
                            Desk.lock.wait();
                        } catch (InterruptedException e) {
                            throw new RuntimeException(e);
                        }
                    }else{
                        //如果没有，就制作
                        System.out.println("厨师做了一碗面条");
                        //修改桌子上的食物状态
                        Desk.foodFlag=1;
                        //叫醒等待的消费者开吃
                        Desk.lock.notifyAll();
                    }
                }
            }
        }

    }
}
```
```java
package com.heima.a12waitandnotify;

public class ThreadDemo {
    public static void main(String[] args) {
        /*
需求：完成生产者和消费者（等待唤醒机制）的代码
实现线程轮流交替执行的效果
*/

        //创建线程对象
        Cook c=new Cook();
        Foodie f=new Foodie();

        //给线程设置名字
        c.setName("厨师");
        f.setName("吃货");

        //开启线程
        c.start();
        f.start();
    }
}
```

等待唤醒机制（阻塞队列的实现方式）
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685716559170-97e9ce0e-3afd-492e-8c87-46e334ed939f.png#averageHue=%23f5eeeb&clientId=u1c629a0e-96ea-4&from=paste&height=511&id=u4bf78421&originHeight=639&originWidth=1487&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=381305&status=done&style=none&taskId=ud4e86ec3-5350-449d-99d0-11adf20bb24&title=&width=1189.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685716690857-f320e911-5b98-4bbe-bcd3-bd9acf9e43fd.png#averageHue=%23fdfaf9&clientId=u1c629a0e-96ea-4&from=paste&height=658&id=u8288be79&originHeight=823&originWidth=1497&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=228724&status=done&style=none&taskId=ue1cedd1c-6e49-4544-bdcb-a90611c574b&title=&width=1197.6)
```
package com.heima.a13waitandnotify;

import java.util.concurrent.ArrayBlockingQueue;

public class Cook extends Thread{
    ArrayBlockingQueue<String> queue;

    public Cook(ArrayBlockingQueue<String> queue) {
        this.queue = queue;
    }

    @Override
    public void run() {
        while(true){
            //不断的把面条放到阻塞队列中
            try {
                queue.put("面条");
                System.out.println("厨师放了一碗面条");
            } catch (InterruptedException e) {
                throw new RuntimeException(e);
            }

        }
    }
}
```
```
package com.heima.a13waitandnotify;

import java.util.concurrent.ArrayBlockingQueue;

public class Foodie extends Thread{
    ArrayBlockingQueue<String> queue;

    public Foodie(ArrayBlockingQueue<String> queue) {
        this.queue = queue;
    }

    @Override
    public void run() {
        while(true){
            //不断从阻塞队列中获取面条
            try {
                String food = queue.take();
                System.out.println(food);
            } catch (InterruptedException e) {
                throw new RuntimeException(e);
            }

        }
    }
}
```
```
package com.heima.a13waitandnotify;


import java.util.concurrent.ArrayBlockingQueue;

public class ThreadDemo {
    public static void main(String[] args) {
        /*
            需求：利用阻塞队列完成生产者和消费者（等待唤醒机制的代码）
            细节：
                生产者和消费者必须使用同一个阻塞队列
         */
        //创建阻塞队列的对象
        ArrayBlockingQueue<String> queue = new ArrayBlockingQueue<>(1);//队列中只能放一个
        //创建线程的对象，并把阻塞队列传递过去
        Cook c=new Cook(queue);
        Foodie f=new Foodie(queue);
        //开启线程
        c.start();
        f.start();

    }

}
```

## 线程的六种状态
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685717729266-d81de65e-1e83-4609-8549-e9a948645c3a.png#averageHue=%23fae7e5&clientId=u1c629a0e-96ea-4&from=paste&height=600&id=u3d9b70c1&originHeight=750&originWidth=1487&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=336998&status=done&style=none&taskId=u6a4b1e49-2aa5-4ff5-91ea-21fdb01f4af&title=&width=1189.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1685717718383-68464da7-9ac0-43ee-ba37-27f4afe5cbbd.png#averageHue=%23f8f7f7&clientId=u1c629a0e-96ea-4&from=paste&height=622&id=u84a8dbec&originHeight=777&originWidth=1154&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=158613&status=done&style=none&taskId=u6ee4068d-912d-466e-9206-0be96427205&title=&width=923.2)
## 线程池
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1686143728056-e3aa2415-0a17-4fd6-8231-1c1f10936c73.png#averageHue=%23fbeeec&clientId=u74305d4e-dac9-4&from=paste&height=567&id=uce20baf4&originHeight=709&originWidth=1528&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=264622&status=done&style=none&taskId=uf03d3173-ab35-4385-bf17-f51539a6f7c&title=&width=1222.4)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1686143778086-bc502b8a-f183-4504-9752-26a6f758ac3a.png#averageHue=%23f9f9f9&clientId=u74305d4e-dac9-4&from=paste&height=445&id=u43cb432e&originHeight=556&originWidth=886&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=73911&status=done&style=none&taskId=ufef4e51d-e664-41a9-942a-2349c6efbd9&title=&width=708.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1686143831989-201de438-f48a-4ff7-aa61-c4f84fe68a2d.png#averageHue=%23f0f5ef&clientId=u74305d4e-dac9-4&from=paste&height=382&id=u6d815d9e&originHeight=478&originWidth=1552&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=263764&status=done&style=none&taskId=u01c3672c-89fd-4e3e-a0bb-6d2d1aaf5ec&title=&width=1241.6)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1686145361749-f416dfb8-72a8-4642-a463-7ba5a83c1ed7.png#averageHue=%232e2d2c&clientId=u74305d4e-dac9-4&from=paste&height=306&id=uf5fd11dc&originHeight=382&originWidth=854&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=29378&status=done&style=none&taskId=ub5c85e27-dfb5-4eb2-b761-cb0b42abc5d&title=&width=683.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1686145349763-e6084500-d59d-44d9-8dd6-c5e89e7da77c.png#averageHue=%232d2c2b&clientId=u74305d4e-dac9-4&from=paste&height=494&id=u329417b1&originHeight=617&originWidth=1041&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=66977&status=done&style=none&taskId=u5896531b-922d-4add-b4d7-a184355a996&title=&width=832.8)
## 自定义线程池
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1686145303057-2051f0d5-a074-4e5b-ba9f-c40e59783ec4.png#averageHue=%23fbf9f9&clientId=u74305d4e-dac9-4&from=paste&height=641&id=u254f0eb6&originHeight=801&originWidth=1624&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=291710&status=done&style=none&taskId=u6c5ae8a4-9db7-4464-943d-7391d0d175a&title=&width=1299.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1686145398890-adaca1b9-5d23-4459-8cc0-5e3cb4129cb0.png#averageHue=%23f5f4f4&clientId=u74305d4e-dac9-4&from=paste&height=530&id=ud4858505&originHeight=663&originWidth=1616&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=392131&status=done&style=none&taskId=u06e4352c-7b42-44ec-b99f-fecb521f818&title=&width=1292.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1686145969832-361cd23c-3179-4ae6-819c-4b96c078fa8b.png#averageHue=%23f8f8f8&clientId=u74305d4e-dac9-4&from=paste&height=534&id=uf1e309ad&originHeight=668&originWidth=1425&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=231068&status=done&style=none&taskId=u8138465e-b436-45aa-8d6c-75e441f1b21&title=&width=1140)
## 线程池最大合适
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1686146637470-bcd2d984-9da1-4c93-8364-0631d3776f2c.png#averageHue=%23fcf3f2&clientId=u74305d4e-dac9-4&from=paste&height=637&id=u500b7b00&originHeight=796&originWidth=1534&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=267881&status=done&style=none&taskId=u0851790c-2848-4a82-bb57-bf70d97c420&title=&width=1227.2)

# 网络编程
## 入门
网络编程：在网络通信协议下，不同计算机上运行的程序，进行的数据传输![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689730019592-60f21cc5-3156-4c4d-bb84-397cac669b5b.png#averageHue=%23faf7f6&clientId=u0383b77f-0b6c-4&from=paste&height=807&id=u15a0d0e2&originHeight=1009&originWidth=2001&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=542605&status=done&style=none&taskId=u24034d34-8421-4b15-b733-cacd1521cbc&title=&width=1600.8)
BS架构优缺点：
1、不需要开发客户端，只需要页面+服务端
2、用户不需要下载，打开浏览器就能使用
3、如果应用过大、用户体验受到影响
CS架构的优缺点：
1、画面可以做的非常精美，用户体验好
2、需要开发客户端，也需要开发服务端
3、用户需要下载和更新麻烦
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689730253829-d71f06e9-7975-4b3d-9833-5a72bb55b2d1.png#averageHue=%23f7efee&clientId=u0383b77f-0b6c-4&from=paste&height=737&id=ub8554e46&originHeight=921&originWidth=1961&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=585290&status=done&style=none&taskId=ud271303b-d3d2-48f6-aed4-bcb464b2d06&title=&width=1568.8)
### 网络编程三要素
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689730339512-640a082a-f122-4547-a99d-712683a8cd8a.png#averageHue=%23faf8f8&clientId=u0383b77f-0b6c-4&from=paste&height=712&id=u395a457a&originHeight=890&originWidth=1828&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=228540&status=done&style=none&taskId=u495ba891-b897-4505-891c-48ecf101d7f&title=&width=1462.4)
### IP
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689730441099-e66490b2-79b6-4b7f-844e-7f03317912db.png#averageHue=%23faf9f9&clientId=u0383b77f-0b6c-4&from=paste&height=715&id=ubd62022c&originHeight=894&originWidth=1520&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=178748&status=done&style=none&taskId=ud85f2105-90f3-4181-8687-8f5e0deaba0&title=&width=1216)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689730531792-0dc933ed-23ab-4d07-8d3b-7c28ceb45711.png#averageHue=%23f8f7f7&clientId=u0383b77f-0b6c-4&from=paste&height=767&id=u0b25c6f2&originHeight=959&originWidth=1819&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=202658&status=done&style=none&taskId=ub4469cd8-fa84-4d0a-957c-9f4ba89f6a1&title=&width=1455.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689730566078-4040cc1d-36bc-41d0-8766-394ebd9f8b01.png#averageHue=%23f5f4f4&clientId=u0383b77f-0b6c-4&from=paste&height=767&id=ue2b1595d&originHeight=959&originWidth=1976&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=292999&status=done&style=none&taskId=udc81b327-f718-4306-8a82-40f5b19841f&title=&width=1580.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689730613098-f976394e-6072-44d7-82d5-d5a04d4f1e82.png#averageHue=%23f8f0ef&clientId=u0383b77f-0b6c-4&from=paste&height=741&id=u4167aad0&originHeight=926&originWidth=1755&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=430221&status=done&style=none&taskId=u5baeee45-79ab-45f7-a7f4-10c34b6034b&title=&width=1404)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689730682194-f51c4b29-60b8-4b60-8bb5-d8db1a3f8b2d.png#averageHue=%23f4f3f2&clientId=u0383b77f-0b6c-4&from=paste&height=240&id=u88ab10a7&originHeight=300&originWidth=2090&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=173270&status=done&style=none&taskId=ud80a3eb0-829b-43f2-9679-902af092963&title=&width=1672)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689730755388-c27d6ee2-4281-4913-8c22-b6c6df3194ea.png#averageHue=%23f2f0f0&clientId=u0383b77f-0b6c-4&from=paste&height=175&id=u81f7c4cf&originHeight=219&originWidth=1921&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=103225&status=done&style=none&taskId=u387e99e3-3d81-4015-b587-9f5ee9a6b3e&title=&width=1536.8)![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689730762505-b163aa7c-3fa1-4171-8042-8b48f03f89ec.png#averageHue=%23e7e2e1&clientId=u0383b77f-0b6c-4&from=paste&height=245&id=ue11876af&originHeight=306&originWidth=698&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=83205&status=done&style=none&taskId=u39cc593b-6524-4396-b993-9d11b90b069&title=&width=558.4)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689730895768-03c8ca94-774a-4924-affb-e7b3e6bc6445.png#averageHue=%23f5efef&clientId=u0383b77f-0b6c-4&from=paste&height=683&id=u3400b679&originHeight=854&originWidth=1433&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=321816&status=done&style=none&taskId=u8860fc1f-416d-4c90-9f2d-ce5c19ea488&title=&width=1146.4)
### 端口号
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689732027237-0727ce0a-3ca2-4f22-9748-0b89aaccbcbd.png#averageHue=%23f7f5f5&clientId=u0383b77f-0b6c-4&from=paste&height=596&id=ufb9c47f8&originHeight=745&originWidth=1401&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=219974&status=done&style=none&taskId=ub0fdf1d9-f301-4d54-88e0-d47a9a4da15&title=&width=1120.8)
### 协议
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689732226289-1551a3b3-0af5-4276-bd37-fe7f104e21c1.png#averageHue=%23e6dbd9&clientId=u0383b77f-0b6c-4&from=paste&height=827&id=u68c60595&originHeight=1034&originWidth=2028&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=679543&status=done&style=none&taskId=ue01d9cb9-04c8-445c-b4ab-a61d7ab142d&title=&width=1622.4)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689732574670-01e6f987-3f6c-4c37-9478-87e4a56b56b2.png#averageHue=%23f4f1f0&clientId=u0383b77f-0b6c-4&from=paste&height=801&id=ue121eddd&originHeight=1001&originWidth=2129&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=690372&status=done&style=none&taskId=ua63f42c7-3592-426b-877f-b3b30ec2604&title=&width=1703.2)
#### UDP发送数据
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689732638630-c352cbba-d726-49fa-90d4-0e9ad2de93d8.png#averageHue=%23fbf9f8&clientId=u0383b77f-0b6c-4&from=paste&height=618&id=udb69cc41&originHeight=773&originWidth=1425&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=256316&status=done&style=none&taskId=u43faf9d4-3d35-4bce-aa47-7e51c4fff45&title=&width=1140)
```java
package com.itheima.a02udpdemo;

import java.io.IOException;
import java.net.*;

public class SendMessageDemo {
    public static void main(String[] args) throws IOException {
        //发送数据

        //1、创建DatagramSocket对象
        //细节：
        //绑定端口，以后我们就是通过这个端口往外发送
        //空参：所有可用的端口中随机一个进行使用
        //有参：指定端口号绑定

        DatagramSocket ds = new DatagramSocket();
        //2、打包数据
        String str="你好呀";
        byte[] bytes = str.getBytes();
        InetAddress address = InetAddress.getByName("127.0.0.1");
        int port=10086;
        DatagramPacket dp = new DatagramPacket(bytes,bytes.length,address,port);
        //3、发送数据
        ds.send(dp);

        //4、释放资源
        ds.close();

    }
}

```
#### UDP接收数据
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689733224209-33b3b448-fe3c-4d9a-a1f2-861bbab3cc1f.png#averageHue=%23faf8f8&clientId=u0383b77f-0b6c-4&from=paste&height=542&id=u3e8d83b8&originHeight=678&originWidth=1263&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=191074&status=done&style=none&taskId=u353df7f2-1d5e-48f3-9173-4c64a8f7a99&title=&width=1010.4)
```java
package com.itheima.a02udpdemo;

import java.io.IOException;
import java.net.DatagramPacket;
import java.net.DatagramSocket;
import java.net.InetAddress;
import java.net.SocketException;

public class ReceiveMessageDemo {
    public static void main(String[] args) throws IOException {
        //接收数据

        //1、创建DatagramSocket对象(快递公司)
        //细节：
        //在接收的时候，一定要绑定端口
        //并且绑定的端口，一定要跟发送的端口保持一致
        DatagramSocket ds = new DatagramSocket(10086);

        //2、接收数据包
        byte[] bytes = new byte[1024];
        DatagramPacket dp = new DatagramPacket(bytes, bytes.length);

        //该方法是阻塞的
        //程序执行到这一步时候，会在这里死等
        //等发送端发送消息
        ds.receive(dp);

        //3、解析数据包
        byte[] data = dp.getData();
        int length = dp.getLength();
        int port = dp.getPort();
        InetAddress address = dp.getAddress();//从哪台电脑发来的

        System.out.println("接收到数据"+new String(data,0,length));
        System.out.println("该数据是从"+address+"这台电脑中的"+port+"这个端口发出来的");

        //4、释放资源
        ds.close();

    }
}

```
#### 单播、组播、广播
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689737321458-c25304cc-a870-46c1-85e4-80b85cd6609e.png#averageHue=%23fdfbfb&clientId=u0383b77f-0b6c-4&from=paste&height=850&id=udd7d12d8&originHeight=1063&originWidth=1780&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=285068&status=done&style=none&taskId=u98decce1-aa2b-49c1-b59d-521eb6891ae&title=&width=1424)
代码
## TPC通信协议
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689738334434-495a006b-8469-451d-9442-49108e8f8d25.png#averageHue=%23f6f2f1&clientId=u0383b77f-0b6c-4&from=paste&height=817&id=u534b069a&originHeight=1021&originWidth=1876&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=444799&status=done&style=none&taskId=uc0dd1d83-3a7b-4501-8fe5-3d96bbd22a2&title=&width=1500.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689738410640-9dba15ed-abfc-4578-a223-f04bb2ca5d40.png#averageHue=%23f6f4f3&clientId=u0383b77f-0b6c-4&from=paste&height=891&id=u522f5dab&originHeight=1114&originWidth=2138&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=764631&status=done&style=none&taskId=uae4b1bb9-97c3-414e-8f73-b99e324535a&title=&width=1710.4)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689750027473-904cb326-722a-42e9-a4e0-392028d1aa32.png#averageHue=%23fdfcfb&clientId=u0383b77f-0b6c-4&from=paste&height=714&id=ufa77d2af&originHeight=893&originWidth=1924&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=535204&status=done&style=none&taskId=u59b395ef-5ef4-4bb0-81b2-ff5c2b32043&title=&width=1539.2)
## 三次握手 四次挥手协议
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689750243456-acbafdd6-ee26-49ad-8d4d-89bde0910f37.png#averageHue=%23f4f2f2&clientId=u0383b77f-0b6c-4&from=paste&height=828&id=ue99c6ca9&originHeight=1035&originWidth=1633&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=358725&status=done&style=none&taskId=u61980e80-5e39-418c-84c1-30aa404f199&title=&width=1306.4)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689750229145-cac7f8e7-0300-4da4-a7e5-896462bea962.png#averageHue=%23f3f0f0&clientId=u0383b77f-0b6c-4&from=paste&height=894&id=u4f504d21&originHeight=1118&originWidth=2046&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=513071&status=done&style=none&taskId=udbe82ed7-ad86-45ad-847f-c2dad643e38&title=&width=1636.8)

# 反射
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689819254101-b3aa6ae6-bb4b-4fe7-8101-006a63661360.png#averageHue=%23fbf3f3&clientId=ue5560304-2ab6-4&from=paste&height=837&id=u0378f841&originHeight=1046&originWidth=2061&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=452494&status=done&style=none&taskId=u964f5cc6-353b-42c1-abd7-a469a005de5&title=&width=1648.8)
## 获取Class对象的三种方式
全类名：包名+类名
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689947363393-33eb519a-121e-4e32-a227-6c7892cd73d5.png#averageHue=%23fbf8f8&clientId=u4a989eb0-a033-4&from=paste&height=610&id=u3ab53cf7&originHeight=763&originWidth=1539&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=232860&status=done&style=none&taskId=u63f325c5-09f8-47aa-a532-fb243032b3d&title=&width=1231.2)
```java
package com.itheima.myreflect1;

public class MyReflectDemo1 {
    public static void main(String[] args) throws ClassNotFoundException {
        /*获取class对象的三种方式
        * */

        //1、第一种方式
        //全类名 ： 包名 + 类名
        //最为常用
        Class clazz1 = Class.forName("com.itheima.myreflect1.Student");

        //第二种方式
        //一般更多的是当作参数进行传递
        Class clazz2 = Student.class;

        //3、第三种方式
        //当我们有了这个类的对象时，才可以使用
        Student s = new Student();
        Class clazz3 = s.getClass();

        System.out.println(clazz1);//class com.itheima.myreflect1.Student
        System.out.println(clazz2);//class com.itheima.myreflect1.Student
        System.out.println(clazz3);//class com.itheima.myreflect1.Student

        System.out.println(clazz1 == clazz2);//true
        System.out.println(clazz2 == clazz3);//true、
        
    }
}

```
## 反射获取构造方法
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689986287325-281098a2-89ab-4858-94e9-e896b702a8d2.png#averageHue=%23f2f1f1&clientId=u9660ae6e-d8bd-4&from=paste&height=767&id=u7600f7d1&originHeight=959&originWidth=1812&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=565987&status=done&style=none&taskId=u23fc0004-a18e-4685-a3e4-e2f9910ffbd&title=&width=1449.6)
```java
package com.itheima.myreflect2;


import java.lang.reflect.Constructor;
import java.lang.reflect.InvocationTargetException;
import java.lang.reflect.Parameter;

public class MyReflectDemo1 {
    public static void main(String[] args) throws ClassNotFoundException, NoSuchMethodException, InvocationTargetException, InstantiationException, IllegalAccessException {
        /*反射获取构造方法
        * */

        //1、获取clazz字节码文件对象
        Class clazz = Class.forName("com.itheima.myreflect2.Student");

        //2、获取构造方法
//        Constructor[] cons1 = clazz.getConstructors();
//        for (Constructor constructor : cons1) {
//            System.out.println(constructor);
//        }
//        Constructor[] cons2 = clazz.getDeclaredConstructors();
//        for (Constructor constructor : cons2) {
//            System.out.println(constructor);
//        }

//        Constructor con1 = clazz.getDeclaredConstructor();
//        System.out.println(con1);
//
//        Constructor con2 = clazz.getDeclaredConstructor(String.class);//public com.itheima.myreflect2.Student(java.lang.String)
//        System.out.println(con2);
//
//        Constructor con3 = clazz.getDeclaredConstructor(int.class);//protected com.itheima.myreflect2.Student(int)
//        System.out.println(con3);
//
        Constructor con4 = clazz.getDeclaredConstructor(String.class, int.class);

        //3、获取到权限修饰符代表的常量字段值
//        int modifiers = con4.getModifiers();
//        System.out.println(modifiers);//2

        //4、获取到形参
//        Parameter[] parameters = con4.getParameters();
//        for (Parameter parameter : parameters) {
//            System.out.println(parameter);
//        }

        //5、创建对象
        //暴力反射：表示临时取消权限校验
        con4.setAccessible(true);
        Student s= (Student)con4.newInstance("张三", 23);
        System.out.println(s);
    }
}

```
## 获取成员变量
```java
package com.itheima.myreflect3;



import java.lang.reflect.Constructor;
import java.lang.reflect.Field;
import java.lang.reflect.InvocationTargetException;

public class MyReflectDemo1 {
    public static void main(String[] args) throws ClassNotFoundException, NoSuchMethodException, InvocationTargetException, InstantiationException, IllegalAccessException, NoSuchFieldException {
        /*反射获取成员变量
        * */
        //获取字节码文件的对象
        Class clazz = Class.forName("com.itheima.myreflect3.Student");

        //获取所有成员变量
        Field[] fields = clazz.getDeclaredFields();
        for (Field field : fields) {
            System.out.println(field);
        }
        //获取单个成员变量
        Field name = clazz.getDeclaredField("name");
        System.out.println(name);

        //获取权限修饰符
        int modifiers = name.getModifiers();
        System.out.println(modifiers);

        //获取成员变量名字
        String n = name.getName();
        System.out.println(n);

        //获取成员变量的数据类型
        Class<?> type = name.getType();
        System.out.println(type);

        //获取成员变量记录的值
        Student s = new Student("张三",23,"男");
        name.setAccessible(true);
        Object value = name.get(s);
        System.out.println(value);

        //修改对象里面记录的值
        name.set(s,"lisi");
        System.out.println(s);
    }
}

```
## 获取成员方法
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689988723676-9c104daa-cfef-4a53-8309-a63c818d84c1.png#averageHue=%23f2f1f1&clientId=u9660ae6e-d8bd-4&from=paste&height=866&id=ua7c5bc36&originHeight=1083&originWidth=1920&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=654022&status=done&style=none&taskId=u32ef5f3c-ae99-4a9b-8df8-c3208f07059&title=&width=1536)
```java
package com.itheima.myreflect4;

import java.lang.reflect.InvocationTargetException;
import java.lang.reflect.Method;
import java.lang.reflect.Parameter;

public class MyReflectDemo {
    public static void main(String[] args) throws ClassNotFoundException, NoSuchMethodException, InvocationTargetException, IllegalAccessException {
        Class clazz = Class.forName("com.itheima.myreflect4.Student");

        //获取里面所有的方法对象（包含父类中所有的公共方法）
//        Method[] methods = clazz.getMethods();
//        for (Method method : methods) {
//            System.out.println(method);
//        }

        //获取里面所有的方法对象（不能获取父类的，但是可以获取本类中私有的方法）
//        Method[] declaredMethods = clazz.getDeclaredMethods();
//        for (Method declaredMethod : declaredMethods) {
//            System.out.println(declaredMethod);
//        }

        //获取单一方法
        Method m = clazz.getDeclaredMethod("eat", String.class);
        System.out.println(m);

        //获取方法的修饰符
        int modifiers = m.getModifiers();
        System.out.println(modifiers);

        //获取方法的名字
        String name = m.getName();
        System.out.println(name);

        //获取方法的形参
        Parameter[] parameters = m.getParameters();
        for (Parameter parameter : parameters) {
            System.out.println(parameter);
        }

        //获取方法抛出的异常
        Class<?>[] exceptionTypes = m.getExceptionTypes();
        for (Class<?> exceptionType : exceptionTypes) {
            System.out.println(exceptionType);
        }

        //方法运行
        //Object invoke(Object obj,Object... args):运行方法
        //参数一：用obj对象调用该方法
        //参数二：调用方法传递的参数（如果没有就不去）
        //返回值：方法的返回值（如果没有就不写）

        Student s = new Student();
        m.setAccessible(true);
        m.invoke(s,"汉堡包");
        
    }
}

```
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689990127374-c1d823ac-9b7c-42fd-8c3a-e9d1f784f319.png#averageHue=%23f8f3f2&clientId=u9660ae6e-d8bd-4&from=paste&height=799&id=ua30c75e7&originHeight=999&originWidth=1283&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=429566&status=done&style=none&taskId=uc7c69932-f85e-4d41-8af4-1be66d6fd77&title=&width=1026.4)
# 特殊文件
## properties
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689835022407-36eaf1a9-6e0f-4345-8b40-af59d52989de.png#averageHue=%23eeebeb&clientId=ubb9954a6-8725-4&from=paste&height=815&id=u30ff2b3a&originHeight=1019&originWidth=1503&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=583503&status=done&style=none&taskId=u7ebd4067-a9c7-4088-88e3-480f63eab08&title=&width=1202.4)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689836842846-5e3f32dd-d71c-4a08-b5b5-b728f5178ce0.png#averageHue=%23f2f0ef&clientId=u497f1187-887a-4&from=paste&height=765&id=u3ce6cfa4&originHeight=956&originWidth=1701&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=550973&status=done&style=none&taskId=ub777e07d-892f-4b3a-b7b7-b723531a186&title=&width=1360.8)
如果出现乱码
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689837383254-5bdde6c6-36aa-47f0-a3b3-3dae947add80.png#averageHue=%23e8ecf0&clientId=u497f1187-887a-4&from=paste&height=58&id=u526b518d&originHeight=73&originWidth=1614&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=25945&status=done&style=none&taskId=u8e900727-2f9a-48ee-b40d-46b239b2f85&title=&width=1291.2)
```java
package com.itheima.d1_properties;

import java.io.*;
import java.util.Properties;
import java.util.Set;

public class PropertiesTest1 {
    public static void main(String[] args) throws IOException {
        //1、创建一个Properties的对象出来（键值对集合，空容器）
        Properties properties = new Properties();
        System.out.println(properties);
        //1、开始加载属性文件中的键值对数据到properties对象中去
        properties.load(new FileReader("D:\\程序代码\\Java\\basic.code\\SpecialFile\\src\\users.properties"));
        System.out.println(properties);
        //3、根据键取值
        System.out.println(properties.getProperty("lisi"));
        Set<String> keys = properties.stringPropertyNames();
        //4、遍历全部的键和值
        for (String key : keys) {
            String value = properties.getProperty(key);
            System.out.println(key + "--->value" + value);
        }
        properties.forEach((k, v)-> System.out.println(k + "--->" + v));
    }
}

```
```java
package com.itheima.d1_properties;

import java.io.FileOutputStream;
import java.io.IOException;
import java.io.OutputStreamWriter;
import java.util.Properties;

public class PropertiesTest2 {
    public static void main(String[] args) throws IOException {
        Properties properties = new Properties();
        properties.setProperty("张无忌","minmin");
        properties.setProperty("abc","123");
        properties.store(new OutputStreamWriter(new FileOutputStream("SpecialFile\\src\\users2.properties"),"UTF-8"),
                "i saved many users!");
    }
}

```
## XML
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689837506691-db797dd9-5751-43b3-9f29-65dd63708797.png#averageHue=%23f7f6f6&clientId=u497f1187-887a-4&from=paste&height=695&id=u9696cdbe&originHeight=869&originWidth=1826&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=474618&status=done&style=none&taskId=ud5a8b28e-816c-4f97-8eaf-e84a4dc07b5&title=&width=1460.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689837785825-f267caa2-2990-418a-ac2d-f4dacf60eba4.png#averageHue=%23f9f8f5&clientId=u497f1187-887a-4&from=paste&height=760&id=u66b34c0e&originHeight=950&originWidth=1695&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=409192&status=done&style=none&taskId=u675161df-f334-490c-9fb1-0477153547f&title=&width=1356)
### 解析XML
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689838415542-3ae834da-dbff-429e-8d0d-6689b5915344.png#averageHue=%23f9f8f8&clientId=u497f1187-887a-4&from=paste&height=802&id=u9e480fef&originHeight=1003&originWidth=1349&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=270792&status=done&style=none&taskId=u6b512716-b54f-424e-aff1-41646d77a41&title=&width=1079.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689838482325-131cd905-b9d5-49c7-b61d-6397d8ac0f1f.png#averageHue=%23fbf7ee&clientId=u497f1187-887a-4&from=paste&height=759&id=ua8fcbf5a&originHeight=949&originWidth=1821&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=476809&status=done&style=none&taskId=u489fd0fb-3f23-4699-9f5d-eb8dda75535&title=&width=1456.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689838493919-7dd18b45-aa68-4fcd-a215-97ee0cd58824.png#averageHue=%23cfcecb&clientId=u497f1187-887a-4&from=paste&height=697&id=uf3ce0ccf&originHeight=871&originWidth=1273&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=413592&status=done&style=none&taskId=u97d8a2b6-c850-45a1-8c6c-c4ef8ae384f&title=&width=1018.4)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689838604147-58834036-ad1f-4d4e-991c-d5965cc3d4f6.png#averageHue=%23ebebeb&clientId=u497f1187-887a-4&from=paste&height=753&id=u2a342099&originHeight=941&originWidth=1858&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=427985&status=done&style=none&taskId=u01ee9113-008f-40d7-89d2-98254f62068&title=&width=1486.4)
解析XML
```java
package com.itheima.d2.xml;

import org.dom4j.Attribute;
import org.dom4j.Document;
import org.dom4j.DocumentException;
import org.dom4j.Element;
import org.dom4j.io.SAXReader;

import java.util.List;

public class Demo4JTest1 {
    public static void main(String[] args) throws DocumentException {
//        1、创建一个Dom4J框架提供的解析器对象
        SAXReader saxReader = new SAXReader();
//        2、使用saxReader对象把需要解析的XML文件读成一个Document对象
//        路径必须是相对路径
        Document document = saxReader.read("SpecialFile\\src\\helloworld.xml");
//        3、从文档对象中解析XML文件的全部数据
        Element root = document.getRootElement();
        System.out.println(root.getName());

//        4、获取根元素下的全部一级子元素
        List<Element> elements = root.elements();
//        List<Element> elements = root.elements("user");
        for (Element element : elements) {
            System.out.println(element.getName());
        }
//        5、获取当前元素下的某个子元素
        Element people = root.element("people");
        System.out.println(people.getText());
//        如果下面有很多子元素user,默认获取第一个
        Element user = root.element("user");
        System.out.println(user.elementText("name"));

//        6、获取元素的属性信息
        System.out.println("---------------------------------------------------------");
        System.out.println(user.attributeValue("id"));
        Attribute id = user.attribute("id");
        System.out.println(id.getName());
        System.out.println(id.getValue());

        List<Attribute> attributes = user.attributes();
        for (Attribute attribute : attributes) {
            System.out.println(attribute.getName() + "=" + attribute.getValue());
        }

//        7、获取全部文本的内容：获取当前元素下的子元素的文本值
        System.out.println(user.elementText("name"));
        System.out.println(user.elementText("地址"));
        System.out.println(user.elementTextTrim("地址"));//去除文本去除前后空格
        System.out.println(user.elementText("password"));

        Element data = user.element("data");
        System.out.println(data.getText());
        System.out.println(data.getTextTrim());

    }
}

```
### 将数据写入XML
使用字符串拼接
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689840164712-4b0cc352-969c-41bd-9357-cc3e373866e5.png#averageHue=%23f9f9f8&clientId=u497f1187-887a-4&from=paste&height=829&id=u3173dc9c&originHeight=1036&originWidth=1300&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=554546&status=done&style=none&taskId=u9904c00e-50f4-4cf7-8887-da989f488a6&title=&width=1040)
### 约束
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689840448612-cf3e1377-7636-409a-bf0d-312e9751ae68.png#averageHue=%23f7f3f0&clientId=u497f1187-887a-4&from=paste&height=779&id=u897b5216&originHeight=974&originWidth=1848&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=564111&status=done&style=none&taskId=u7027e0f3-b1b1-42e8-af3e-639dcabce15&title=&width=1478.4)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689857931040-88189eb2-731e-42e2-8be6-208a8666148b.png#averageHue=%23f7f5f5&clientId=u1fb998c5-320c-4&from=paste&height=440&id=u3ffebf7a&originHeight=550&originWidth=854&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=180277&status=done&style=none&taskId=u21d3281e-0a0c-43b1-b532-77059542200&title=&width=683.2)
















 
# 动态代理
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689991356503-23bf559f-8e53-4bbc-818f-c1a90f20ec82.png#averageHue=%23f7f2f1&clientId=u97482a06-06b6-4&from=paste&height=685&id=u0d3c2781&originHeight=856&originWidth=1229&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=379464&status=done&style=none&taskId=ubd0bef17-d11c-400c-be8a-5e032ad0c36&title=&width=983.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/35848979/1689991444023-a80295fe-8dc8-46cf-936c-9d6f9cdd5b18.png#averageHue=%23f5f3e9&clientId=u97482a06-06b6-4&from=paste&height=532&id=uad3995a4&originHeight=665&originWidth=1813&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=380446&status=done&style=none&taskId=ubd4ffebd-660a-4851-b1f3-fc2b37cb53e&title=&width=1450.4)
