# 关于机器人的实践方法

16生物萃英班 资淑梅 320160927360

---

前言：Blockly是一个用于Web、Android、IOS的可视化代码编辑器库。Blockly使用了相互关联的积木来表示表达代码中变量、逻辑表达式、循环等。它让用户能够了解编程，而不用面对命令行上让人恐惧和枯燥的代码和语法。在我们学习过程中，不难感受到Blockly对编程新人的友好，从以下三方面体现出来：第一，Blockly里面的编程语言并不是全字母形式的，相对起C语言或者是Python等编程工具来说，Blockly的语言比较通俗易懂，只要是学过高中数学选修课本的人基本都能做一个简单的程序出来；第二，在进行编程的时候，因为Blockly的程序是以积木的形式体现的，所以，若是初学者选择了与上一个方块不相符的方块进行下一步编程的话，方块是没法连在一起的，因此语言也没办法进行下去；第三，利用Blockly进行编程之后，我们还可以选择python等其他语言来体现之前在Blockly中完成的程序，从而与Blockly中的方块对应来简单学习其他语言。本文主要是对两个简单的编程进行相应的说明。

关键词：Blockly；编程；初学；

一、引言

对于人脑来说，精准地判断正确与否是建立在人脑已掌握该知识的基础之上，但是如果要用计算机来判断正确与否的话则只需要编写相关的程序就能进行判断。本文的第一个小程序的就对“1+1=2”的正确性进行判断，用Blockly来对这个数学题目进行判断是比较简单的，因为在用Blockly进行编程的过程中，它会把一些比较复杂的语句简单化，因此只需要拼接几个小方块的可以了。但是，XML中显示的却是一长串的代码。第二的小程序是关于对将来某一天所进行的行为进行判断，“三天打渔两天晒网”就是该程序的前提，以第一天在“打渔”为起点，开始的1、2、3三天在打渔，而后的4、5两天在晒网，求第N天是在进行“打渔”还是在“晒网”。对于这种数学题，编程理所当然是以数学为基础再进行修饰，从而得到一套完整的程序。我们不难看出在本题当中“5”是解题的关键————某数对5取余数，若余数为1、2、3则在“打渔”，若余数为0或4则在“晒网”。将这个条件变成语句输入进去，就能得到第N天是在“打渔”还是在“晒网”。对于人类来说，计算一个数学题题目，只要写出相关的公式就可以得出它的答案，但是计算机不同，计算机需要经过严格的运行过程，其中的代码稍有差错，导致的结果就千差万别，所以，计算机的计算之所以精准，就是因为计算机的运行过程本身就精密无比，容不得沙子。在接下来的内容当中，笔者将会详细讲述一套代码的诞生过程。

二、编程内容

2.1 对“1+1=2”的正确与否进行判断

  首先我们知道，“1+1=2”是事实，但是在笔者一开始写的时候，以为Blockly不认为“1+1=2”是事实，因此就在判断之前加上了条件（如图1），但是后来发现判断句对整个判断并没有起到什么决定性作用，于是就把它删掉了，简化成图二的样子，简化之后的语句照样能够正常运行，且在更改图中黄色框部分的数字之后，计算机能够准确地给出相应的答案（图3）。

![](/assets/TE4LE3HV1MY7CSFZ_YP8@VW.png)![](/assets/CY$N%U%%28CHAP%28_J_~%295K%28@D.png)

![](/assets/CG7O6RFCKYRLKE}EJI}GW2R.png)

```
    虽然在Blockly的板块上，我们所看到的过程比较简单，但是在XML中，表达出来的却是一长串的代码，这样使笔者不得不认为Blockly之所以比较容易上手，不仅仅是因为它以积木的形式来表述编程，更是因为它简化了许多复杂的步骤，由简化之后的板块所得到的XML代码如下。
```

![](/assets/V80Q24FT{L[VRPVQ68NV8[U.png)

