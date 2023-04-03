## Paper:1




1. Title: Learning to Split and Transfer for Bilingual Vocabulary Expansion
（学习切分和迁移用于双语词汇扩充）

2. Authors: Jingjing Wang, Masao Utiyama, Lemao Liu, Andrew Finch, Eiichiro Sumita

3. Affiliation: Jingjing Wang为中国科学院计算技术研究所，其他作者为日本研究机构。

4. Keywords: Bilingual terminology, vocabulary expansion, unsupervised learning, transfer learning

5. Urls: Paper=https://www.aclweb.org/anthology/P19-1235.pdf, Github: None

6. Summary: 

- (1):该论文致力于使用无监督的方法，通过词汇切分和迁移来扩充双语术语词汇。
- (2):过去的方法可能对低频词汇或偏特殊领域的词汇表现不佳，而本文提出的方法通过深度自编码器学习了两种语言之间的变换，并使用无监督的方法将双语语料库拆分成不同级别的主题，从而扩充了词汇量。
- (3):该论文提出一种基于无监督学习和迁移学习的新方法，通过学习两种语言上的词汇转换，然后使用从迁移词汇表构建的树来转移更具创新性的词汇。本文使用双语语料库，利用Grocery数据集训练并评估了该方法。
- (4):本文使用Grocery数据集进行评估，结果表明，该方法在词汇扩充方面比其他基准方法表现更好。





8. Conclusion: 

- (1): 本文的研究意义在于使用无监督的方式，通过词汇切分和迁移方法扩充了双语术语词汇。在双语信息处理领域，这种方法可以更好地解决资源匮乏和领域专业性较强等问题。

- (2): 创新点方面，本文主要采用了深度自编码器进行迁移学习和语料库拆分，利用无监督的方法来扩充词汇量。在性能方面，本文使用Grocery数据集进行了评估，结果表明，该方法在词汇扩充方面比其他基准方法表现更好。但是，在工作量方面，尽管无监督学习方法可以减少标注数据的需求，但该方法的计算消耗较高，并需要进行参数调整。因此，实际使用时需要对计算资源进行更多的投入和排序。




