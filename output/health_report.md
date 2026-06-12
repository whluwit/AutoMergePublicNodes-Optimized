# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.2.0 |
| 更新时间 | 2026-06-12 00:03:03 |
| 运行耗时 | 217.2s |
| 订阅源总数 | 44 |
| 健康订阅源 | 44 |
| 原始节点 | 39955 |
| 去重后节点 | 15027 |
| TCP 可达 | 1500 |
| 真实可用 | 389 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 15027 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 2.8 |
| geo | 1.2 |
| tcp | 37.4 |
| real_test | 156.0 |
| generate | 19.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 20391 |
| shadowsocks | 7985 |
| trojan | 6037 |
| vmess | 5130 |
| hysteria2 | 184 |
| shadowsocksr | 90 |
| http | 86 |
| socks | 41 |
| hysteria | 6 |
| anytls | 4 |
| tuic | 1 |

## 评分权重

| 因子 | 权重 |
| --- | --- |
| latency | 35.0 |
| jitter | 15.0 |
| tcp | 10.0 |
| protocol_history | 20.0 |
| source_history | 20.0 |

## Top 节点评分

| 评分 | 协议 | 延迟(ms) | 抖动(ms) | 来源 | 服务器 |
| --- | --- | --- | --- | --- | --- |
| 55.91 | shadowsocks | 274.6 | 597.1 | Au1rxx-base64 | 37.19.198.244 |
| 55.82 | shadowsocks | 277.3 | 625.0 | Au1rxx-base64 | 37.19.198.160 |
| 55.82 | shadowsocks | 277.4 | 601.8 | Au1rxx-base64 | 37.19.198.243 |
| 55.8 | shadowsocks | 278.1 | 629.0 | Au1rxx-base64 | 37.19.198.236 |
| 55.6 | socks | 403.8 | 681.0 | Surfboard-tg-mixed | 134.122.1.61 |
| 54.33 | shadowsocks | 323.4 | 600.7 | Au1rxx-base64 | 156.146.38.167 |
| 54.28 | shadowsocks | 324.7 | 600.7 | Au1rxx-base64 | 156.146.38.168 |
| 54.25 | shadowsocks | 325.7 | 602.0 | Au1rxx-base64 | 156.146.38.169 |
| 54.14 | shadowsocks | 329.3 | 616.1 | Au1rxx-base64 | 156.146.38.170 |
| 53.57 | shadowsocks | 347.0 | 700.4 | Au1rxx-base64 | 149.28.255.6 |
| 52.99 | shadowsocks | 332.9 | 787.5 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |
| 52.58 | http | 1043.8 | 645.0 | snakem982 | 84.239.49.249 |
| 52.56 | http | 1043.8 | 610.4 | snakem982 | 84.239.49.55 |
| 52.41 | http | 1048.8 | 641.7 | snakem982 | 84.239.49.245 |
| 52.4 | http | 1048.8 | 611.0 | snakem982 | 84.239.49.242 |
| 52.28 | http | 1052.4 | 644.1 | snakem982 | 84.239.49.40 |
| 52.22 | shadowsocks | 388.5 | 516.6 | Au1rxx-base64 | 173.244.56.9 |
| 52.11 | shadowsocks | 392.0 | 492.1 | Au1rxx-base64 | 216.105.168.18 |
| 52.1 | http | 1058.5 | 624.9 | snakem982 | 84.239.49.42 |
| 52.09 | http | 1058.2 | 650.5 | snakem982 | 84.239.49.37 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.958 | 0.977 | 43 | 52 | prefer |
| Au1rxx-base64 | 0.62 | 0.62 | 71 | 88 | observe |
| Surfboard-tg-mixed | 0.395 | 0.315 | 731 | 4225 | observe |
| mheidari-all | 0.335 | 0.25 | 92 | 2000 | observe |
| Epodonios-all | 0.287 | 0.5 | 2 | 3000 | observe |
| roosterkid-openproxylist-v2ray | 0.273 | 0.25 | 28 | 150 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3000 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3224 | observe |
| barry-far-vless | 0.255 | None | 0 | 2000 | observe |
| DeltaKronecker-all | 0.198 | 0.115 | 321 | 4660 | downweight |
| barry-far-Sub2 | 0.195 | None | 0 | 501 | observe |
| barry-far-Sub1 | 0.194 | None | 0 | 473 | observe |
| MatinGhanbari-super-sub | 0.183 | None | 0 | 199 | observe |
| barabama-yudou66 | 0.182 | None | 0 | 163 | observe |
| Au1rxx-clash | 0.179 | None | 0 | 88 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ClientOSError | - | 392 |
| 204 | ProxyError | - | 360 |
| 204 | TimeoutError | - | 88 |
| speed | ClientOSError | - | 63 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | - | 55 |
| speed | TimeoutError | - | 49 |
| geo | status | 403 | 36 |
| cn-block | TimeoutError | - | 14 |
| cn-block | ClientOSError | - | 12 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �N|smy���{�4�Ϛ�M�o��}ֻ{� | - | 5 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | - | 5 |
| geo | status | 429 | 3 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: unsupported flow: xtls-rprx-vision-udp443 | - | 3 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �� | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: i�s���G�k� | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 280 | 300 | - |
| global | False | 284 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
