# FutuAPI

下载富途API:
```
pip install futu
```
下载富途FutuOpenD客户端：https://www.futunn.com/download/openAPI

安装完成FutuOpenD客户端后打开:

![alt text](https://github.com/NathanHuang2020/FutuAPI/blob/master/FutuScreenShot.png?raw=true)

在客户端输入用户名密码(第一次登陆会要求认证)。



返回Python,获取数据：

```
from futu import *
quote_ctx = OpenQuoteContext(host='127.0.0.1', port=11111)
print(quote_ctx.get_market_snapshot('HK.00700'))
quote_ctx.close() 
```
