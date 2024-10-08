# C

## Mdr's C tutorial

```c
#define INTRODUCTION 52
// 向着星辰与深渊，欢迎来到 mdr 的 C 语言教程！

#define INFORMATION 'C'
// B 站账号 Minsecrus
// GitHub 账号 Minsecrus
// QQ 交流群 885719573

#include <stdio.h>
int main(int argc, char* argv[]){
    printf("%d %c", INTRODUCTION, INFORMATION);
    return 0;
}
```

这里是 **Mdr's C Tutorial**，欢迎来这里共同学习  
本教程的目标：在 **准确** 的基础上力争 **简洁** 和 **生动**  
此教程并非一时兴起而作，实则怀“为往圣继绝学，为万世开太平”之愿，深思熟虑打造而成  
得天独厚者，替天行善

[**总纲**](/教程/总纲.md)

[**关于本教程**](/About.md)

## 文档规范

1. 标题由 **一级标题** 开始，依次递减
2. **强调** 用 `** **` 标识，*次强调* 用 `* *` 标识，`代码块` 用 `` ` ` `` 标识
3. `*** ***` `** **` `* *` `` ` ` `` 前后 **各空一个空格**；在中文标点前后的空格可省略
4. 引文和注释用 `>` 标识
5. 在中文上下文中用全角小括号（）
6. 在一个 **术语 (Terminology)** 首次出现的时候在 **半角小括号** 内给出 **对应的外来语**，同时给出 **首字母缩略语 (Acronym)**。这些外来语通常对应 **概念 (Concept)** 的原文 ，希望有助于读者明确分辨词语的含义。
   1. 为减少读者的记忆负担，下文分情况使用 **术语的汉语表述** 和 **首字母缩略语**：初始章节以前者为主，进阶章节以后者为主
   2. 外来语和缩略语可能视情况在不同章节多次出现
   3. 括号左侧右侧各空一个空格
   4. 大部分外来语单词摘自 [维基百科](https://zh.wikipedia.org) 和 [C++ 参考手册](https://en.cppreference.com/)
7. **专有名词** 需 **大写**
8. 图片统一放在 `/images/` 目录下，并采用 **绝对路径** 引入  
   截图统一采用 **PNG** 格式，命名为三位数字，如：`001.png`；  
   拍照统一采用 **JPEG** 格式，命名为两位数字，如：`01.jpg`；

## 代码规范

1. 源文件后缀名为 `.c`，头文件后缀名为 `.h`
2. 标识符采用惯例命名，不允许使用拼音
3. `if` `else` `for` `while` 必须跟随一条 **复合语句**，即用 **大括号** 包裹

## 鸣谢名单（按时间顺序）

### 个人（贡献者）

+ **mdr** （[GitHub - Minsecrus](https://github.com/Minsecrus)）
+ **@幻** （[GitHub - huan201](https://github.com/huan201)）
+ **JuaJuanchi** （[GitHub - JuaJuanchi](https://github.com/Jua-Juanchi)）
+ **Enoch.驊** （[GitHub - gngtwhh](https://github.com/gngtwhh)）
+ **No** （[CNBlogs - Kroner](https://www.cnblogs.com/Kroner)）（[GitHub - Kroner](https://github.com/Kroner)）
+ **xly** （[GitHub - LY-Xiang](https://github.com/LY-Xiang)）（[GitHub - hfsz2313](https://github.com/hfsz2313)）
+ **革匊习习中** （[GitHub - Juvwxyz](https://github.com/Juvwxyz)）
+ **0x7E7**
+ **FHU-yezi** （[GitHub - FHU-yezi](https://github.com/FHU-yezi)）
+ **菲露露** （[GitHub - LovelyLavender4](https://github.com/lovelylavender4)）
+ **XIAOYI12** （[GitHub - xiaoyi1212](https://github.com/xiaoyi1212)）

### 组织

+ **艾猫工作室** （[aymao.com](https://www.aymao.com/)）

### 特别鸣谢

+ **FrankHB** （[GitHub - FrankHB](https://github.com/FrankHB)）
+ **jajuju**
+ **Fresky** （[GitHub - FreskyZ](https://github.com/FreskyZ)）
+ **兔兔**

## 许可证

[**CC-BY-SA 4.0**](/LICENSE)

## 参考资料

+ [***ISO C standard***](https://open-std.org/JTC1/SC22/WG14/)
+ [***C++ 参考手册***](https://zh.cppreference.com/w/c/language)
+ ***C Primer Plus*** （ISBN 978-0-321-92842-9）
+ ***算法导论*** （ISBN 978-7-111-40701-0）
+ [***Let's Build a Simple Database***](https://cstack.github.io/db_tutorial/)
