### 斐讯N1 / 贝壳云 一键制作OpenWrt镜像脚本
#### Usage
1. 编译, 不会的可以去 [Lean's OpenWrt Source](https://github.com/coolsnowwolf/lede "Lean's OpenWrt Source")  
   target选 "QEMU ARM Virtual Machine" > "ARMv8 multiplatform"
2. 将编译好的固件放入到"openwrt"目录  
   注意: 固件格式只支持 " *rootfs.tar.gz "、" *ext4-factory.img\[.gz] "、" *root.ext4\[.gz] "
3. 执行bash mk.sh, 默认输出路径"out/xxx.img"
4. 写入U盘 / 线刷 启动OpenWrt
