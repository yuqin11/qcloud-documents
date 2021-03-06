>? 目前弹性公网 IPv6 处于内测中，如有需要，请提交 [内测申请](https://cloud.tencent.com/apply/p/c28sebss8v)。

本教程将帮助您搭建一个具有 IPv6 CIDR 的私有网络（VPC），并为 VPC 内的云服务器或者弹性网卡开启 IPv6，实现 IPv6 的内外网通信。
## 操作场景
1. 云服务器启用 IPv6，和 VPC 内其他云服务器的 IPv6 内网互通。
2. 云服务器启用 IPv6，和 Internet 的 IPv6 用户进行双向通信。
![](https://main.qcloudimg.com/raw/245f8acb1bea7b002035193b089bf1b7.png)

## 操作须知
1. 在开始使用腾讯云产品前，您需要先 [注册腾讯云账号](https://cloud.tencent.com/register?s_url=https%3A%2F%2Fcloud.tencent.com%2F)。
2. 目前支持 IPv6 的地域为北京、上海、广州、上海金融云、深圳金融云，请在这些地域部署 IPv6 服务。
3. IPv6 地址为 GUA 地址，每个 VPC 分配1个`/56`的 IPv6 CIDR，每个子网分配1个`/64`的 IPv6 CIDR，每个弹性网卡分配1个 IPv6 地址。
4. 主网卡、辅助网卡均支持申请 IPv6 地址。想要了解更多云服务器和弹性网卡的关系，请参见 [弹性网卡](https://cloud.tencent.com/document/product/576) 产品文档。

## 操作步骤
[步骤1：VPC 配置 IPv6](https://cloud.tencent.com/document/product/1142/40133)
[步骤2：云服务器配置 IPv6](https://cloud.tencent.com/document/product/1142/40134)
