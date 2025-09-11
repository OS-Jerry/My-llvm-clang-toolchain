# README


这是一个自动化构建OS的系统工具流，利用Github Action进行工作。


## 一、LLVM

```bash

# 首先clone本仓库
# 然后使用git tag 触发构建特定版本的llvm
git tag -f llvmorg-21.1.0 # 这会拉取llvm仓库的llvmorg-21.1.0版本的源码，并触发action编译，约4小时，完成后发布到release页面
git push origin llvmorg-21.1.0 -f

```


## 二、OS (Aarch64 and Riscv64)


## 三、QEMU


## 四、HAOC (Custom OS)

## 五、
