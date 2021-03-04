# 1.1.8

* 修复路径存在空格导致无法编译的问题[#588](https://github.com/coreybutler/nvm-windows/issues/588)
* 修复windows 10 64 位下无法编译的问题[#548](https://github.com/coreybutler/nvm-windows/issues/548)
* 默认构建为64位(GOARCH=amd64)
* 修复go 1.16 利用go module构建的问题, 并启用appveyor ci
