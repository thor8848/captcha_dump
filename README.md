# 序言
> 有的时候训练一些特殊验证码， 需要训练集，我们手动识别太累了，所以写了一个简单版的 下载验证码器，并打码返回结果

# 单线程下载
在下载过程中发现多线程下载的验证码很多是相同的**（短时间内下载的验证码相同）**所以老老实实用的单线程 `request`

# 识别结果
```bash
识别结果_图片md5值.jpg
```