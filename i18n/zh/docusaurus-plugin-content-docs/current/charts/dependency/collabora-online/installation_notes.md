# 安装笔记

如果您没有启用 `反向代理` on `Collabora` (It 不推荐，因为它不安全)， 为了使它能够工作，您必须：

* 从 `额外参数` 中删除 `-o:ssl.termination=true -o:ssl.enable=false`
* 设置 `服务器名称` 至 `主机IP:端口` (您为 `节点端口` 设置的端口号)
* 将 `服务类型` 设置为 `节点端口`
* 将 `端口类型` 设置为 `HTTPS`
* 在您将要使用的应用中禁用证书验证。 例如，下一个云端在 Collabora 的 URL 下有一个复选框来禁用 Cert 验证)