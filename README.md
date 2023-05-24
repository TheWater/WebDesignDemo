# 记录一些问题



## 使用git
> github 上传错误
【Git/GitHub】解决Git上传时OpenSSL SSL_read: Connection was reset, errno 10054的错误

git_bash 执行 git config http.sslVerify "false" 命令
git_bash 执行 git config --global --unset http.proxy 命令或git config --global --unset https.proxy
再按照正常操作提交代码，操作成功。
