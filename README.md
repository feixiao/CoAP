# CoAP快速入门

#### 入门资料
+ [《CoAP简介》](./source/CoAP%E7%AE%80%E4%BB%8B.md)
+ [《CoAP基础指南》](./source/CoAP%E5%9F%BA%E7%A1%80%E6%8C%87%E5%8D%97.md)
+ [《CoAP进阶指南》](./source/CoAP%E8%BF%9B%E9%98%B6%E6%8C%87%E5%8D%97.md)
+ [《受限节点网络的术语》](./source/RFC7228%20-%E3%80%8A%E5%8F%97%E9%99%90%E8%8A%82%E7%82%B9%E7%BD%91%E7%BB%9C%E7%9A%84%E6%9C%AF%E8%AF%AD%E3%80%8B%E4%B8%AD%E6%96%87%E7%89%88.md)
+ [《所限应用协议》](./source/RFC7252-%E3%80%8A%E5%8F%97%E9%99%90%E5%BA%94%E7%94%A8%E5%8D%8F%E8%AE%AE%E3%80%8B%E4%B8%AD%E6%96%87%E7%89%88.md)

#### 协议和数据包
+ [分布式通信COAP协议](https://blog.csdn.net/xgw1010/article/details/109374930)
  + 注：wireshark可能将CoAP识别为DTLS，处理方式为：
    ```text
    选择包右键：
        ——> Protocol Preferences
            ——> Frame
                ——> Open Frame Preferences 
            选择CoAP将端口改为5684即可
    ```


#### 开源项目
+ [libcoap](https://github.com/obgm/libcoap) OpenHarmony使用的CoAP库。
+ [《libcoap 接口分析与 CoAP 协议开发》](https://blog.csdn.net/song_lee/article/details/105653196)


#### 测试工具
```shell
npm install coap-cli -g
```


#### 参考资料
+ 《IoT开发实战: Coap卷》

