# 开发前必读
1. 在调用其它接口前，需要使用登录接口获取token。并在调用其它接口时在请求头（header）中添加调用登录接口后获得的`token`参数。
2. 新版本教务系统对响应内容进行了变更，添加了`success`和`result`字段，并在`success`为`false`时有`msg`字段。本文档编写时以旧版本作为基准，因此部分页面可能还没有更新新版，欢迎提交PR帮助完善文档。