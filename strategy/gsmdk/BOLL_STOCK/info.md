##简单的基于ta-lib的布林指标策略示例


策略逻辑： 

boll指标的买卖时机：

一，当布林线的上、中、下轨线同时向上运行时，且当前价格高于中轨的价格，则买入

二，当布林线的上、中、下轨线同时向下运行时，或者当前价格低于中轨的价格，则卖出