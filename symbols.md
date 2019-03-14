# 符号对照表

## 基础

B教授所有的写法都是 [Lisp](https://zh.wikipedia.org/zh-hant/LISP) 风格：
```
(方法 (对象A) (对象B)) => 对象A 方法 对象B
```

很多时候只是层数比较多看起来比较麻烦，最简单的区分就是数括号


|符号|写法|例子|效果|
|-|-|-|-|
|¬|not|(not A)|¬A|
|∧|and|(and A B)|A ∧ B|
|∨|or|(or A B)|A ∨ B|
|=|=|(= A B)|A = B|
|∃|exists|(exists (x) ([expression]))|(∃x [expression])|
|⇒|implies|(implies A B)|A ⇒ B|
|∀|forall|(forall A B)|∀ A B|

特别的，有一种（例如[MiracleOn34thStreet](/MiracleOn34thStreet.slt)） :
```
SpeaksDutch(kris)
```
会让你自己设定一种方法，这种的写法也很简单：
```
(SpeaksDutch kris)
```

## 数学符号

|符号|表达式|
|-|-|
|φ|\phi|
|ψ|\psi|


## 小提示

- 注意大小写：每一点细微的差别都可能导致不通过，大小写是最容易出问题的地方
- 如果你那不准你的`Assume`是不是对的，直接把`Goal`推导改成`PC Oracle`，如果是绿的说明你目前的假设是可以得出（或者是可以自证的）
