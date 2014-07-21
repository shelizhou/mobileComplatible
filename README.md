# 移动端的一些兼容

## android下 的input textarea背景边框无法改变，而且输入时会出现默认的输入框
解决办法如下，但是会引起一些另外的bug
```
  -webkit-user-modify: read-write-plaintext-only;
```
联系我：513915539@qq.com
