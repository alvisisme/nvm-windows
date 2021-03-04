# nvm-windows

个人定制版, 修复官方一些已知的问题

## 编译测试环境

1. go 1.16 windows/amd64

## 更新记录

* 修复路径存在空格导致无法编译的问题[#588](https://github.com/coreybutler/nvm-windows/issues/588)
* 修复windows 10 64 位下无法编译的问题[#548](https://github.com/coreybutler/nvm-windows/issues/548)
* 默认构建为64位

## 注意事项

* 编译时设置go代理方便下载以来[代理设置](https://goproxy.io/zh/docs/getting-started.html)
* 必须使用管理员权限运行本工具
