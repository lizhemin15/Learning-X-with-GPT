The reference book is "High Dimensional Data Analysis with Low Dimensional Models: Principles, Computation, and Applications" by Yi Ma, University of California, Berkeley, John Wright, Columbia University, and Emmanuel Candes, Stanford University. The book is available at https://people.eecs.berkeley.edu/~yima/Publication.html

In the first version, I will write the notes by Chinese. In the future, I will translate it into English.


## 0. 引言
    最初知道马老师这本书是在马老师的书刚出预印版的时候就知道了，那个时候刚组织学完国外的一本书HDP，说实话，形式大于内容。一直以来，充斥着博士毕业的压力，项目琐事的压力，一直就没有让自己沉下心读过一本书。换句话说，读博期间，我似乎都没有完整的啃过一本书。AI时代，也是一个快销时代，让很多事情从自己生产水泥然后盖房子，一下子快进到了搭积木建房子。虽然在这段时间也发了一些文章，但是我觉得离认知AI本身、离认知世界本身这件事情，渐行渐远了。搞科研的目的本身就是为了认知世界，而不是为了发文章。

    而马老师的文章和书，在这个时代给我一种眼前一亮，如沐春风的感觉。从压缩感知时代，一直到AI时代，马老师都是领域的引领者。我之前对科研的认知是，大家为了解决某个问题，找到了一些共性规律，发明了某个工具。但到马老师这里，我有了很不一样的感觉，虽然论Titlle，可能不如很多人，但是其一以贯之的研究思路应该是融合了他对世界的认知。而这个认知是迷人的，在没有翻开书籍，没有听马老师讲课的时候，还无法感受到这种魅力。而在读了马老师这本书第一节以后，就深深的被马老师所构建的世界观所吸引了。原来，在看似复杂的背后，有如此简单的逻辑！

    废话不多说，所有的笔记都将以ipynb的格式来存储，jupyter这种称为文学式编程，是我非常看好的一个范式，实际上也有了大量的从业人员使用ipynb来写代码或者写书。此次我也将一边阅读一边实现，读万卷书行万里路，代码实现就是我们走的路。
