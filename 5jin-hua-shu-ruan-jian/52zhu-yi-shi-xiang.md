>###特别注意

1. 如果对核酸序列进行分析， 并且是CDS 编码区的核酸序列，一般需要将核酸序列分别先翻译成氨基酸序列， 进行比对， 然后再对应到核酸序列上。这一流程可以通过MEGA 3.0 以后的版本实现。MEGA3 现在允许两条核苷酸，先翻成蛋白序列比对之后再倒回去，做后续计算。

2. 无论是核酸序列还是蛋白序列，一般应当先做成FASTA 格式。FASTA 格式的序列，第一行由符号“ >”开头，后面跟着序列的名称，可以自定义，例如user1， protein1 等等。将所有的FASTA 格式的序列存放在同一个文件中。文件的编辑可用Windows 自带的记事本工具，或者EditPlus （google 搜索可得）来操作。

3. 构建NJ 或者MP 树需要先将序列做多序列比对的处理。作者推荐使用ClustalX 进行多序列比对的分析。多序列比对的结果有时需要后续处理并应用于文章中， 这里作者推荐使用GeneDoc 工具。而构建ML 树则不需要预先的多序列比对。因此，作者推荐的软件组合为： MEGA + ClustalX + GeneDoc + BioEdit 。
