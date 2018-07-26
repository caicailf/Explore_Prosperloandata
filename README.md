# Explore_Prosperloandata

# 背景

互联网技术的发展,为金融创新提供了条件,并未不断涌现的金融创新在实践中的应用于推广奠定了坚实基础.其中,网络借贷就是资金借贷活动借助互联网平台而实现的一种去中介化的模式创新.作为网贷平台的主要形式,P2P平台通过直接撮合借贷双方,改变了传统商业银行作为资金融通中介的借贷模式,近年来发展迅速。Prosper是美国的一家P2P（个人对个人）在线借贷平台网站，世界排名2万左右。网站撮合了一些有闲钱的人和一些急于用钱的人。本项目选取了该公司自2006年至2014年总共11W的贷款数据,试图分析Prosper贷款人质量,贷款资金价格界定规则等问题.

# 文件

* prosperLoanData.csv  prosper数据集
* Explore_Prosperloandata.Rmd  
* Explore_Prosperloandata.html

# 简介
此数据集包含 113,937 项贷款，每项贷款有 81 个变量，包括贷款⾦额、借款利率（或利率）、当前贷款状态、借款⼈收⼊、借款⼈就业状态、借款⼈信⽤历史及最新⽀付信息。

# 探究问题

* 贷款利率会受到哪些因素的影响？
* 最常见的贷款用途是哪些？
* 获得的贷款金额和年收入是否相关？

# 安装包

<pre><code>install packages("ggplot2")
</code></pre>
<pre><code>install packages("dplyr")
</code></pre>
<pre><code>install.packages("gridExtra")
</code></pre>
