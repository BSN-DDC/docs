### 一、门户 OpenAPI 说明
BSN-DDC 基础网络门户 OpenAPI 是 BSN 联盟面向平台方开放的一套官方 DDC 管理服务接口，不包含官方门户（ddc.bsnbase.com)内的 “业务开通”、“资金账户充值/提现” 操作。

BSN 联盟建议平台方按照《BSN-DDC基础网络门户OpenAPI说明手册.pdf》进行接口对接，将官方 DDC 的管理侧功能和查询类功能集成到自己的业务门户内。调用接口过程中，都需在请求头填写 apitoken，服务侧会对apitoken 的值进行有效性验证，同时根据此值将请求报文关联到对应的平台方。

服务地址和 apitoken 的值，请登录 ddc.bsnbase.com 在【业务开通信息】内查看。


