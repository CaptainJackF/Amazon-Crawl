# Amazon-Crawl
# 亚马逊特价书目爬取

使用R语言写爬虫(rvest)非常方便，但最终卡在 写入数据库中，数据库设置的是 'UTF-8'编码，Dataframe中的文本也是 'UTF-8'，但写入后部分数据会丢失(为NULL)。
