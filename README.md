# pveopenwrtx86_64ssrp

OpenWrt 18.06.9 r8077-7cbbab7246

luci-app-ssr-plus all ipk
```
opkg update
```
```
opkg remove dnsmasq && opkg install dnsmasq-full
```
```
opkg install luci-i18n-base-zh-cn luci-i18n-firewall-zh-cn openssh-sftp-server
```
```
opkg install dns2socks_2.1-1_x86_64.ipk pdnsd-alt_1.2.9b-par-a8e46ccba7b0fa2230d6c42ab6dcd92926f6c21d_x86_64.ipk trojan_1.16.0-1_x86_64.ipk \
ipt2socks_1.1.3-2_x86_64.ipk redsocks2_0.67-4_x86_64.ipk uci_2019-05-17-f199b961-2_x86_64.ipk \
kcptun-client_20210103-1_x86_64.ipk shadowsocks-rust-sslocal_1.10.9-1_x86_64.ipk v2ray-core_4.39.1-1_x86_64.ipk \
libnss_3.61-3_x86_64.ipk shadowsocks-rust-ssserver_1.10.9-1_x86_64.ipk v2ray-ctl_4.39.1-1_x86_64.ipk \
luci-app-ssr-plus_184-3_all.ipk shadowsocksr-libev-ssr-check_2.5.6-8_x86_64.ipk v2ray-extra_4.39.1-1_all.ipk \
luci-i18n-ssr-plus-zh-cn_184-3_all.ipk shadowsocksr-libev-ssr-local_2.5.6-8_x86_64.ipk v2ray-geodata_4.39.1-1_all.ipk \
microsocks_1.0.2-1_x86_64.ipk shadowsocksr-libev-ssr-redir_2.5.6-8_x86_64.ipk v2ray-plugin_4.38.3-1_x86_64.ipk \
naiveproxy_90.0.4430.85-6-1_x86_64.ipk shadowsocksr-libev-ssr-server_2.5.6-8_x86_64.ipk xray-core_1.4.2-2_x86_64.ipk \
nspr_4.29-1_x86_64.ipk simple-obfs_0.0.5-5_x86_64.ipk xray-geodata_1.4.2-2_x86_64.ipk \
nss-utils_3.61-3_x86_64.ipk tcping_0.3-1_x86_64.ipk xray-plugin_1.4.2-1_x86_64.ipk
```
