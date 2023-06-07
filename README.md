# leetcode_exp
记录我的刷题过程以及心得笔记， 跟随[代码随想录](https://github.com/youngyangyang04/leetcode-master)的刷题脚步

## 数组  2023.06.06完成

就撒地方

1. [数组：704.二分查找](https://github.com/WaNg-2-29/leetcode_exp/blob/main/records/704.%20%E4%BA%8C%E5%88%86%E6%9F%A5%E6%89%BE.md)
2. [数组：27.移除元素](https://github.com/WaNg-2-29/leetcode_exp/blob/main/records/27.%20%E7%A7%BB%E9%99%A4%E5%85%83%E7%B4%A0.md)
3. [数组：977.有序数组的平方](https://github.com/WaNg-2-29/leetcode_exp/blob/main/records/977.%20%E6%9C%89%E5%BA%8F%E6%95%B0%E7%BB%84%E7%9A%84%E5%B9%B3%E6%96%B9.md)
4. [数组：209.长度最小的子数组](https://github.com/WaNg-2-29/leetcode_exp/blob/main/records/209.%20%E9%95%BF%E5%BA%A6%E6%9C%80%E5%B0%8F%E7%9A%84%E5%AD%90%E6%95%B0%E7%BB%84.md)
5. [数组：59.螺旋矩阵II](https://github.com/WaNg-2-29/leetcode_exp/blob/main/records/59.%20%E8%9E%BA%E6%97%8B%E7%9F%A9%E9%98%B5%20II.md)

![image text](https://camo.githubusercontent.com/97d746e877876898e216a451d20a4abd607a8ab20f31886a4ab7379fb7cd2214/68747470733a2f2f636f64652d7468696e6b696e672d313235333835353039332e66696c652e6d7971636c6f75642e636f6d2f706963732f2545362539352542302545372542422538342545362538302542422545372542422539332e706e67)





## 链表  2023.6.7完成

+ 链表是一种通过指针串联在一起的线性结构，每一个节点由两部分组成，一个是数据域一个是指针域（存放指向下一个节点的指针），最后一个节点的指针域指向null（空指针的意思）。

+ 链表分类：单链表，双链表，循环链表
+ 存储方式：在内存中并不是连续分布的，通过指针域的各个指针将所有节点连接起来。
+ 链表的定义

```c++
struct ListNode{
  int val;	//节点的值
  ListNode *next;	//指向下一节点的指针
  ListNode(int x): val(x), next(NULL){}	//节点的构造函数
};
```

节点的构造函数用于初始化节点的值和指针。如果不定义构造函数，那么默认会有一个无参的默认构造函数，但是这个默认构造函数只会将节点的值和指针初始化为默认值，而不能自定义赋值。

使用默认构造函数时，可以在定义节点后再给节点的值和指针赋值，但是无法在定义节点时就给变量赋值。而使用自定义的构造函数，则可以在定义节点时直接给节点的值和指针赋初值，从而避免了在后续代码中再次赋值的步骤。



