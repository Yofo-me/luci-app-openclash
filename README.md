# luci-app-openclash
该项目来自于https://github.com/vernesong/OpenClash
之所以建立这个项目只是为了方便编译克隆
luci-app-openclash 适用于Openwrt 编译
## 同步源码
    cd lede/package
    git clone https://github.com/yuos-bit/luci-app-openclash.git 
    更新，安装软件包,输入
    ./scripts/feeds update luci
    ./scripts/feeds install -a
    然后再输入make menuconfig V=sc
    选择要编译的包 LuCI -> Applications -> luci-app-openclash
    
    您也可以直接拷贝 `luci-app-openclash` 文件夹至其他 `OpenWrt` 项目的 `Package` 目录下随固件编译
    make menuconfig
    选择要编译的包 LuCI -> Applications -> luci-app-openclash
