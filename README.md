# stockanalysis
股票爱好者，对股票的一些统计与分析
分析策略需求设计：
1.判断新股的涨停终结日，终结日当天成交量暴涨。
2.判断四日，八日增幅，跌幅。

数据准备：
     万科历年数据


架构设计：

	* 数据累积
	* 
		* 即时数据抓取：
		* 
			* 抓取器：通过聚合API可以实现
			* 定时抓取：
			* 抓取数据解析器：Json
			* 导入数据库：
			* 抓取数据模型设计：根据API返回类型

		* 历史存量数据抓取
		* 
			* 通过爱搞搞的互联网is金矿获取数据
			* 数据模型：根据返回数据类型确定


	* 数据分析
	* 
		* 待定


