假设客户地某一次点击的商品和他之前和之后点击的商品存在着一定的联系，因此可以将skipgram这种模型应用到这种场景中。

文章里面训练了两个模型

用户的短期兴趣（listing embedding): 新用户或临时决定去哪一个地方去旅游

<img src="https://pic4.zhimg.com/80/v2-58e9d379adc1781569742b00411884bf_720w.jpg">

用户的长期兴趣（user-type embedding和listing-type embedding): 根据顾客以往的订房时候的喜欢和消费习惯（离市中心距离，价格，房子类型等等）。


