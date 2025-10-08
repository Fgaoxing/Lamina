## 修改内容

${{ needs.generate-changelog.outputs.changelog }}

## 预编译版本

| 系统类型 | 目标三元组 | 工具链 |
|---------|-----------|--------|
| **Windows** | | |
| Windows | x86_64-pc-windows-msvc | msvc |
| Windows | aarch64-pc-windows-msvc | msvc |
| **macOS** | | |
| macOS | x86_64-apple-darwin | darwin |
| macOS | aarch64-apple-darwin | darwin |
| **Linux** | | |
| Linux | i386-unknown-linux-gnu | gnu |
| Linux | i686-unknown-linux-gnu | gnu |
| Linux | x86_64-unknown-linux-gnu | gnu |
| Linux | x32-unknown-linux-gnux32 | gnux32 |
| Linux | arm-unknown-linux-gnueabi | gnueabi |
| Linux | armv7-unknown-linux-gnueabihf | gnueabihf |
| Linux | aarch64-unknown-linux-gnu | gnu |
| Linux | mips-unknown-linux-gnu | gnu |
| Linux | mipsel-unknown-linux-gnu | gnu |
| Linux | mips64-unknown-linux-gnuabi64 | gnuabi64 |
| Linux | mips64el-unknown-linux-gnuabi64 | gnuabi64 |
| Linux | mipsr6-unknown-linux-gnu | gnu |
| Linux | mipsr6el-unknown-linux-gnu | gnu |
| Linux | powerpc-unknown-linux-gnu | gnu |
| Linux | ppc64-unknown-linux-gnu | gnu |
| Linux | ppc64le-unknown-linux-gnu | gnu |
| Linux | alpha-unknown-linux-gnu | gnu |
| Linux | arc-unknown-linux-gnu | gnu |
| Linux | loongarch64-unknown-linux-gnu | gnu |
| Linux | m68k-unknown-linux-gnu | gnu |
| Linux | riscv64-unknown-linux-gnu | gnu |
| Linux | s390x-unknown-linux-gnu | gnu |
| Linux | sh4-unknown-linux-gnu | gnu |
| Linux | sparc64-unknown-linux-gnu | gnu |

共计29个预编译版本

请使用sha256校验

## 安装

> 请想尝试使用包管理器来安装

1. 下载对应平台的二进制文件
2. 在命令行中执行：`chmod +x xxx`
3. 运行：`./xxx`