# 中国商密算法SM2,SM3,SM4

- 本源码基于 [国家商用密码检测中心](http://www.scctc.org.cn/) 提供的SM234源码
- SM2算法需要使用miracl lib库，本工程包含lib库为`64位`版本
- SM2暂时只调试了加解密和签名验签操作，`密钥交换`有空再说
- 本源码仅供学习研究使用，请勿用于商用目的

# 开发环境

- 操作系统: WIN7 64位
- 集成开发环境: VS2017社区版

# 联系我

- [My Git](https://github.com/khaosi)

- khaosi@sina.com

# 重要节点

## 节点1

2019-09-05 完成以下接口调试：

- SM2(加解密，签名验签)
- SM3
- SM4(ECB CBC)

2019-10-03
- 补充SM2旧版密文结构(C1C2C3)解密调试。备注：新版密文结构(C1C3C2)
