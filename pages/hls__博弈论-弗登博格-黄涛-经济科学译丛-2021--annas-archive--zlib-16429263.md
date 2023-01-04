file-path:: /Users/zzyang/Documents/Books/O1 数学/O29 应用数学-博弈论/博弈论-弗登博格-黄涛-经济科学译丛-2021--annas-archive--zlib-16429263.pdf

-
- # 完全信息的静态博弈
	- ## 第一章 策略式博弈和纳什均衡
		- ### 1.1 策略式博弈和重复严格优势的介绍
			- #### 1.1.1 策略式博弈
				- [[博弈]]
				- [[标准式博弈]]
					- 参与人集合 $i \in \mathscr{I}=\{1,2, \cdots, I\}$
					- 对每个参与人 $i$ 有纯策略空间 $S_i$
					- 对每个参与人 $i$ 有收益函数 $u_i$
						- 输入：策略组合 $s=\left(s_1, \cdots, s_I\right)$
						- 输出：冯诺伊曼-摩根斯坦效用 $u_i(s)$
					- 最大化参与人自身的收益函数，并因此合作或对抗
				- [[冯诺伊曼-摩根斯坦效用]]
				- [[策略式]]：
				- [[共同知识]]：所有人知道策略式的结构，也知道对手知道，也知道对手知道知道。。。
				- [[双人零和博弈]]：$\sum_{i=1}^2 u_i(s)=0$ 的博弈
				- [[零和博弈]]：$\sum_{i=1}^I u_i(s)=0$ 的博弈
				  background-color:: purple
				- [[有限博弈]]：策略空间 $S=x_i S_i$ 有限的博弈
					- 一般提到博弈自带有限性假设
					- $x_i$ 表示的是每一次博弈中的选择
					  background-color:: purple
				- [[纯策略]]
					- 在策略空间这个向量空间中，决策只能取基向量，一定正交
					  background-color:: purple
					- 纯策略博弈下从参与人到收益函数
					  background-color:: green
						- 参与人集合 $i \in \mathscr{I}=\{1,2, \cdots, I\}$
						  background-color:: green
						- 参与人的选择就是策略，多个选择组成向量，由于是纯策略，这个向量一定是 zero-one 的基向量
						  background-color:: green
						- 这些基向量构成纯策略空间 $S_i$
						  background-color:: green
						- 每个人的每个选择是一个基向量，这些基向量的组合 $s=\left(s_1, \cdots, s_I\right)$ 对应着策略式中的每一个格子
						  background-color:: green
						- 冯诺伊曼-摩根斯坦效用就是格子中的值，角标 $i$ 取了向量函数的一个 entry，对应着 $i$ 参与人的期望
						  background-color:: green
				- [[混合策略]]：$\sigma_i\left(s_i\right)$ 是赋予纯策略 $s_i$ 的概率分布
					- 相对于纯策略而言
					- 参与人的随机化彼此独立
					- $\sigma_i$ 在混合策略空间 $\sum_i$
					- 混合策略组合的空间是 $\sum=x_i \sum_i$
					- 收益是相应纯策略收益的数学期望
						- 组合 $\sigma$ 下参与人 $i$ 的收益 $\sum_{s \in S}\left(\prod_{j=1}^I \sigma_j\left(s_j\right)\right) u_i(s)$
						- 概率x纯策略 的线性组合
						  background-color:: purple
					- 混合策略博弈下从参与人到收益函数
					  background-color:: green
						- 参与人集合 $i \in \mathscr{I}=\{1,2, \cdots, I\}$
						  background-color:: green
						- 已有纯策略 $s_i$，$\sigma_i\left(s_i\right)$ 是概率加权
						  background-color:: green
						- 这些策略向量构成纯策略空间 $\sum_i$
						  background-color:: green
						- 给出组合 $\sigma$ 的时候就决定了策略的概率分布
						  background-color:: green
						- $\prod_{j=1}^I \sigma_j\left(s_j\right)$ 对一个由一系列参与人决策决定的格子，它发生的概率是多少
						  background-color:: green
				- 博弈的结构是共同知识 #博弈-共同知识
				- 社会科学中的博弈大多是非零和的 #社会科学-博弈
				- [[EXAMPLE/上中下，左中右双人博弈]]
					- 这是一个有限双人博弈
					- 这是一个纯策略博弈
					- [:span]
					  ls-type:: annotation
					  hl-page:: 27
					  hl-color:: yellow
					  id:: 63b3d740-7599-4c8c-a162-42a53988a200
					  hl-type:: area
					  hl-stamp:: 1672730431067
			- #### 1.1.2 劣势策略
				- [[重复优势]]
				- [[严格劣势策略]]
					- 如果存在 $\sigma_i^{\prime} \in \sum_i$ 使得 $u_i\left(\sigma_i^{\prime}, s_{-i}\right)>u_i\left(s_i, s_{-i}\right),  s_{-i} \in S_{-i}$，那么纯策略 $s_i$ 对于参与人 $i$ 是严格劣势的
						- $\left(s_i^{\prime}, s_{-i}\right)=\left(s_1, \cdots, s_{i-1}, s_i^{\prime}, s_{i+1}, \cdots, s_I\right)$ 表示只有该参与人改变策略
							- $s_{-i}$ 表示参与人 $i$ 的对手
			- #### 1.1.3 剔除劣势策略的应用
				- [[EXAMPLE/囚徒困境]]
				- [[EXAMPLE/二级价格拍卖]]
		- ### 1.2 纳什均衡
			- #### 1.2.1 纳什均衡的定义
			- #### 1.2.2 纯策略均衡的例子
			- #### 1.2.3 纯策略均衡不存在