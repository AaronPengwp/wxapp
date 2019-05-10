微信小程序社区CrawlSpider案例
###CrawlSpider: 
 需要使用｀LinkExtractor｀和｀Rule｀。这两个东西决定爬虫的具体走向。

1、allow设置规则的方法：要能够限制在我们想要的url上面。不要跟其它url产生相同的正则表达式即可。
2、什么情况下使用follow：如果在爬取页面的时候，需要进满足当前条件的url再进行跟进，那么就设置为True。否则设置为Fash。
3、什么情况下该指定callback：如果这个url对应的页面，只是为了获取更多的url,并不需要里面的数据，那么可以不指定callback。如果想要获取url对应页面中的数据，那么就需要指定一个callback。
