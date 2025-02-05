# PheWAS学习笔记

MPG Primer: PheWAS, UKBB (2024):https://www.youtube.com/watch?v=4evyahwyRNM&t=1s

![1](./PheWAS-UKBB/1.png)

![2](./PheWAS-UKBB/2.webp)

**biobank关联研究中的问题：样本间相关性高，常规线性模型不合适**

![3](./PheWAS-UKBB/3.webp)

**已有的一些线性模型**

![4](./PheWAS-UKBB/4.webp)

**如果用线性模型针对某一研究曼哈顿图如下:**

![5](./PheWAS-UKBB/5.png)

**换个混合模型**

![6](./PheWAS-UKBB/6.webp)

**但是又不适合大数据**

![7](./PheWAS-UKBB/7.webp)

**因此第二个挑战是大数据**

![8](./PheWAS-UKBB/8.png)

**第三个挑战是严重的case-control样本数量不均衡**

![9](./PheWAS-UKBB/9.webp)

![10](./PheWAS-UKBB/10.webp)

**解决办法：新算法**

![11](./PheWAS-UKBB/11.webp)

**示例结果如下，是不是已经不那么乱了**

![12](./PheWAS-UKBB/12.png)

**更多的例子**

![13](./PheWAS-UKBB/13.webp)

**来多个算法比较一下：SAIGE很优秀啊**

![14](./PheWAS-UKBB/14.png)

**好的模型算法越来越多**

![15](./PheWAS-UKBB/15.webp)

**其实队列研究的一个主要方向还有：rare variant**

![16](./PheWAS-UKBB/16.png)

**因此针对队列研究的总体需求汇总如下**

![17](./PheWAS-UKBB/17.webp)

**专门针对rare variant的关联研究工具**

![18](./PheWAS-UKBB/18.webp)

**然后汇总一下上面所说的，针对数量性状模型选择**

![19](./PheWAS-UKBB/19.webp)

**针对质量性状模型选择**

![20](./PheWAS-UKBB/20.webp)

**最后关于biobank联盟**

![21](./PheWAS-UKBB/21.webp)

![22](./PheWAS-UKBB/22.webp)

![23](./PheWAS-UKBB/23.png)

![24](./PheWAS-UKBB/24.webp)

![25](./PheWAS-UKBB/25.webp)

**还有一个，这个全称是看名字应该就知道啥意思：BRaVa:BiobankRareVariant Analysis**
![26](./PheWAS-UKBB/26.png)




single-variant association and Collapsing rare variants