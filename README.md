# ubuntu-in-termux

[![DISCORD](https://img.shields.io/badge/Chat-On%20Discord-738BD7.svg?style=for-the-badge)](https://discord.gg/Xaqkdeh)

## 这是什么?

这是一个脚本，它可以让你在不需要 root 权限的情况下在 Termux 应用中安装 Ubuntu

## 版本

**• 目前使用的是:22.04,原先为24.10因为无非使用所以降低为22.04**

## 重要提示

**• 如果你必须在 x86/i*86 架构的 Termux 中使用 Ubuntu，或者更喜欢 Ubuntu 19.10，你可以使用原作者的这个分支 -> https://github.com/MFDGaming/ubuntu-in-termux/tree/ubuntu19.10**

**• 如果你收到一条错误信息显示“Fatal Kernel too old”，你必须取消注释“startubuntu.sh”文件中写着“command = -k 4.14.81”的那一行（删除该行前面的 # 号）**

### 安装步骤

1. Update termux: `apt-get update && apt-get upgrade -y`
2. Install wget: `apt-get install wget -y`
3. Install proot: `apt-get install proot -y`
4. Install git: `apt-get install git -y`
5. Go to HOME folder: `cd ~`
6. Download script: `git clone https://github.com/mmxd12/ubuntu-in-termux`
7. Go to script folder: `cd ubuntu-in-termux`
8. Give execution permission: `chmod +x ubuntu.sh`
9. Run the script: `./ubuntu.sh -y`
10. Now just start ubuntu: `./startubuntu.sh`
