# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-15 12:23:41 |
| 运行耗时 | 310.5s |
| 订阅源总数 | 44 |
| 健康订阅源 | 44 |
| 原始节点 | 40895 |
| 去重后节点 | 15968 |
| TCP 可达 | 1500 |
| 真实可用 | 274 |
| Verified 输出 | 274 |
| Global 输出 | 299 |
| All 输出 | 15968 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.0 |
| geo | 1.3 |
| tcp | 39.2 |
| real_test | 225.0 |
| generate | 42.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 21173 |
| shadowsocks | 8081 |
| trojan | 5929 |
| vmess | 5336 |
| hysteria2 | 141 |
| shadowsocksr | 93 |
| http | 86 |
| socks | 49 |
| hysteria | 6 |
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

| 评分 | 协议 | 延迟(ms) | 抖动(ms) | 延迟分 | 抖动分 | TCP分 | 协议历史分 | 来源历史分 | 来源 | 服务器 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 59.01 | shadowsocks | 194.6 | 474.6 | 32.58 | 0.0 | 10.0 | 5.33 | 11.1 | Au1rxx-base64 | 108.181.0.177 |
| 58.59 | shadowsocks | 207.7 | 515.3 | 32.16 | 0.0 | 10.0 | 5.33 | 11.1 | Au1rxx-base64 | 173.244.56.9 |
| 57.76 | shadowsocks | 233.3 | 552.6 | 31.33 | 0.0 | 10.0 | 5.33 | 11.1 | Au1rxx-base64 | 216.105.168.18 |
| 57.64 | shadowsocks | 339.7 | 308.6 | 27.88 | 3.43 | 9.9 | 5.33 | 11.1 | Au1rxx-base64 | 149.22.87.204 |
| 57.54 | http | 850.9 | 1052.6 | 11.31 | 0.0 | 9.15 | 18.7 | 18.38 | snakem982 | 84.239.49.207 |
| 57.53 | http | 848.7 | 1047.3 | 11.38 | 0.0 | 9.07 | 18.7 | 18.38 | snakem982 | 84.239.49.234 |
| 57.53 | http | 850.7 | 1017.0 | 11.32 | 0.0 | 9.13 | 18.7 | 18.38 | snakem982 | 84.239.14.146 |
| 57.42 | shadowsocks | 243.6 | 620.6 | 30.99 | 0.0 | 10.0 | 5.33 | 11.1 | Au1rxx-base64 | 173.244.56.6 |
| 57.37 | http | 856.9 | 1051.4 | 11.12 | 0.0 | 9.17 | 18.7 | 18.38 | snakem982 | 84.239.49.249 |
| 57.34 | http | 854.6 | 1062.3 | 11.19 | 0.0 | 9.07 | 18.7 | 18.38 | snakem982 | 84.239.49.214 |
| 57.32 | shadowsocks | 246.7 | 625.9 | 30.89 | 0.0 | 10.0 | 5.33 | 11.1 | Au1rxx-base64 | 108.181.118.10 |
| 57.3 | http | 856.1 | 1064.1 | 11.14 | 0.0 | 9.08 | 18.7 | 18.38 | snakem982 | 84.239.49.254 |
| 57.29 | shadowsocks | 341.8 | 316.3 | 27.81 | 3.14 | 9.91 | 5.33 | 11.1 | Au1rxx-base64 | 149.22.87.240 |
| 57.24 | http | 860.5 | 1084.1 | 11.0 | 0.0 | 9.16 | 18.7 | 18.38 | snakem982 | 84.239.49.239 |
| 57.18 | http | 862.8 | 1008.4 | 10.93 | 0.0 | 9.17 | 18.7 | 18.38 | snakem982 | 84.239.49.183 |
| 57.16 | http | 860.1 | 1054.4 | 11.01 | 0.0 | 9.07 | 18.7 | 18.38 | snakem982 | 84.239.14.158 |
| 57.15 | http | 859.9 | 1067.1 | 11.02 | 0.0 | 9.05 | 18.7 | 18.38 | snakem982 | 84.239.49.164 |
| 57.11 | http | 866.8 | 1042.5 | 10.8 | 0.0 | 9.23 | 18.7 | 18.38 | snakem982 | 84.239.49.201 |
| 57.06 | shadowsocks | 254.8 | 600.6 | 30.63 | 0.0 | 10.0 | 5.33 | 11.1 | Au1rxx-base64 | 156.146.38.170 |
| 57.06 | http | 866.1 | 1092.2 | 10.82 | 0.0 | 9.16 | 18.7 | 18.38 | snakem982 | 84.239.49.242 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.919 | 0.935 | 46 | 52 | prefer |
| roosterkid-openproxylist-v2ray | 0.592 | 0.593 | 27 | 150 | observe |
| Au1rxx-base64 | 0.575 | 0.574 | 68 | 99 | observe |
| Epodonios-all | 0.265 | 0.175 | 63 | 3000 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3000 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3447 | observe |
| barry-far-vless | 0.255 | None | 0 | 2000 | observe |
| mheidari-all | 0.24 | 0.153 | 98 | 2000 | downweight |
| Surfboard-tg-mixed | 0.233 | 0.152 | 794 | 4474 | downweight |
| barry-far-Sub2 | 0.195 | None | 0 | 489 | observe |
| barry-far-Sub1 | 0.194 | None | 0 | 481 | observe |
| MatinGhanbari-super-sub | 0.183 | None | 0 | 200 | observe |
| DeltaKronecker-all | 0.182 | 0.099 | 282 | 5458 | downweight |
| barabama-yudou66 | 0.182 | None | 0 | 163 | observe |
| Au1rxx-clash | 0.179 | None | 0 | 99 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ClientOSError | - | 479 |
| 204 | ProxyError | - | 358 |
| 204 | TimeoutError | - | 120 |
| geo | status | 429 | 66 |
| geo | status | 403 | 51 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | - | 42 |
| cn-block | TimeoutError | - | 35 |
| speed | ClientOSError | - | 16 |
| cn-block | ClientOSError | - | 11 |
| speed | TimeoutError | - | 9 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | - | 8 |
| geo | TimeoutError | - | 8 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: chacha20-poly1305 | - | 5 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �N|smy���{�4�Ϛ�M�o��}ֻ{� | - | 3 |
| geo | ClientOSError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 274 | - |
| global | False | 300 | 299 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
