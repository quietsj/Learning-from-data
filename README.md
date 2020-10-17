
<head>
    <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
    <script type="text/x-mathjax-config">
        MathJax.Hub.Config({
            tex2jax: {
            skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
            inlineMath: [['$','$']]
            }
        });
    </script>
</head>

# Learning from data

今年2月的时候开始学习台大林轩田老师的机器学习课程，感觉讲的非常好，课程的参考教材是**learning from data**，网上查阅资料的时候发现关于这本书的笔记几乎没有，所以想自己做一个学习笔记，记录教材中的习题的解法，一来可以加深自己的理解，而来也可以给后来学习的小伙伴一些参考。这份笔记主要以**learning from data**的习题解析为主，笔记形式为Markdown以及Jupyter Notebook结合的形式，因为笔者水平有限，难免有些错误，欢迎指出。 



<br/>

参考资料:  
https://blog.csdn.net/a1015553840/article/details/51085129  
http://www.vynguyen.net/category/study/machine-learning/page/6/  
http://book.caltech.edu/bookforum/index.php



书籍介绍：

https://book.douban.com/subject/11026330/



<br/>

校阅：[Wang](https://github.com/Splendid-sun)



<br/>

补充说明：仓库中有四类文件，分别是Jupyter Notebook，py，pdf，md，代码部分保存在Jupyter Notebook和py文件中。  



<br/>

### 更新日志：

2018/6/1

- 上传Chapter1

2018/6/15

- 上传Chapter2
- 2018/10/8日更新：根据网友RingoTC提醒([链接](https://github.com/Doraemonzzz/Learning-from-data/issues/1))，修改problem 2.2并对一些排版做了一些调整。

2018/7/1

- 上传Chapter3

2018/7/15

- 上传Chapter4,Chapter5

2018/7/31

- 上传Chapter8

2018/9/5

- 上传Chapter7

2018/11/29

- 感谢[黄博](https://github.com/fengdu78)的推广，最近star的小伙伴逐渐增多，我后续会抽空对资料进行一些优化，如果大家发现什么问题可以直接发issue，希望能借助大家的力量把这份资料做的更好，谢谢！另外最后两个章节已经完成了一部分，争取年底左右完成。

2018/12/4

- 上传Chapter6，Chapter9的草稿，其中Chaper6大部分已经完成，Chapter9只完成了一部分，后续部分会尽快给出解答。

2018/12/12

- 完成Chapter9绝大多数内容，剩余少部分等有空再解答。

2018/12/14

- 完成Chapter6绝大多数内容，剩余少部分等有空再解答。

2018/12/18

- 今天挺多朋友关注到这份资料，还是挺高兴的，我后续还会对资料进行优化，不过由于期末考，这个工作应该会等到一个月之后开始。

2019/2/11

- 从今天开始优化笔记内容，今天对第一章Exercise部分进行改正以及代码优化。

2019/2/12

- 完成Chapter 1的优化，补充了Hoeffding不等式的初等证明。

2019/2/20

- 完成Chapter 2的优化。

2019/3/6

- 完成Chapter 3的优化。

2019/3/13

- 完成Chapter 4的优化。

2019/3/15

- 完成Chapter 5的优化。

2019/3/24

- 完成Chapter 8的优化。

2019/4/4

- 完成Chapter 7的优化。

2019/5/1

- 完成Chapter 8的优化。

2019/5/4

- 完成Chapter 9的优化。



<br/>

### 总结：

​	前后历时半年多，总算把LFD的习题整理完了，除了第六章，第八章和第九章少部分习题以外，其他所有习题均已完成。教材的上半部分（第一章到第五章）是精髓，补充部分（第六章到第九章）有部分章节稍显仓促，而且有一些小错误，第九章部分实际应用可能较少，但是总的来说，本书绝对是一本不可多得的好书。

​	这本书是台大林轩田老师的机器学习课程配套教材，内容通俗易懂，非常精彩，不是单纯罗列公式，是一本非常适合入门的机器学习书籍。但是尽管该书是一本入门书籍，要吃透这本书还是需要相当多的时间，尤其是课后习题部分，有的难度非常大，所以我在学习的过程中将习题都整理了一遍，方便自己以后查阅和他人参考。

​	后续的计划是明年初将课本再复习一遍，并对自己整理的资料再优化一下，完成剩余没有完成的题目，有时间的话会写一些学习笔记，将课本中的算法自己都实施一遍。如果各位读者发现哪里有问题或者有更好的解法，可以发issue或者给我发邮件，我会及时更新我的习题解答，谢谢。

  

<br/>

### 习题完成情况：

| 章节      | 总共习题 | 完成习题 | 剩余部分                        | 优化情况   |
| --------- | -------- | -------- | ------------------------------- | ---------- |
| Chapter 1 | 25       | 25       | 无                              | 已完成优化 |
| Chapter 2 | 32       | 32       | 无                              | 已完成优化 |
| Chapter 3 | 35       | 35       | 无                              | 已完成优化 |
| Chapter 4 | 38       | 38       | 无                              | 已完成优化 |
| Chapter 5 | 11       | 11       | 无                              | 已完成优化 |
| Chapter 6 | 43       | 40       | Problem 16,17,25                | 已完成优化 |
| Chapter 7 | 35       | 35       | 无                              | 已完成优化 |
| Chapter 8 | 35       | 35       | 无                              | 已完成优化 |
| Chapter 9 | 46       | 41       | Exercise 18,Problem 17,26,27,28 | 已完成优化 |
| 总计      | 300      | 292      |                                 |            |

(a) 因为$y(t)\ne \text {sign}(w^T(t)x(t))$，所以当$\text {sign}(w^T(t)x(t))>0 $时，$y(t)=-1$， 当$\text {sign}(w^T(t)x(t))<0 $时，$y(t)=1$，所以$y(t)w^T(t)x(t) < 0$

(b) $$ y(t)w^T(t+1)x(t)=y(t)(w(t) + y(t)x(t))x(t)=y(t)w^T(t)x(t)+y^2(t)x^T(t)x(t) $$ 注意$x(t)$的第一个分量为$1$(参考课本)，所以$y^2(t)x^T(t)x(t)>0$，因此 $$ y(t)w^T(t+1)x(t)>y(t)w^T(t)x(t) $$
