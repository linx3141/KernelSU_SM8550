sh getclang.sh以获取clang
source source-clang.sh以应用clang环境
sh build.sh以构建内核(目前鲁棒性较差 建议自己拿出来命令执行
编译好的kernel image在 sm8550/out/arch/arm64/boot/Image
可以使用magiskboot拆包替换内核再打包刷入
也可以替换可用的ak3包内的image以卡刷

ksu toolkit:
https://github.com/backslashxx/ksu_toolkit

Inferno's build(ksu ksunext sukisu)
https://github.com/inferno0230/kernel_oneplus_sm8550-CI
