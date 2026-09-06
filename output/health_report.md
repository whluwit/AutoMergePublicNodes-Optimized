# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-06 02:39:29 |
| 运行耗时 | 325.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 97301 |
| 去重后节点 | 25520 |
| TCP 可达 | 3000 |
| 真实可用 | 639 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25520 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.4 |
| tcp | 42.6 |
| probe | 78.3 |
| real_test | 158.4 |
| generate | 39.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 62264 |
| vmess | 12557 |
| shadowsocks | 10946 |
| trojan | 9178 |
| hysteria2 | 1944 |
| http | 145 |
| shadowsocksr | 131 |
| socks | 66 |
| anytls | 38 |
| hysteria | 18 |
| tuic | 14 |

## 评分权重

| 因子 | 权重 |
| --- | --- |
| latency | 25.0 |
| jitter | 15.0 |
| tcp | 10.0 |
| speed | 10.0 |
| fingerprint_resistance | 5.0 |
| protocol_history | 15.0 |
| source_history | 20.0 |

## Top 节点评分

| 评分 | 协议 | 延迟(ms) | 抖动(ms) | 延迟分 | 抖动分 | TCP分 | 协议历史分 | 来源历史分 | 来源 | 服务器 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 82.66 | hysteria2 | 225.0 | 535.5 | 22.57 | 0.0 | 10.0 | 13.33 | 17.76 | Au1rxx-base64 | 66.94.121.46 |
| 79.21 | shadowsocks | 236.0 | 605.8 | 22.31 | 0.0 | 9.37 | 13.77 | 17.76 | Au1rxx-base64 | 156.146.38.167 |
| 78.83 | shadowsocks | 241.3 | 615.8 | 22.19 | 0.0 | 10.0 | 13.77 | 17.76 | Au1rxx-base64 | 156.146.38.169 |
| 77.09 | http | 252.0 | 518.3 | 21.94 | 0.0 | 10.0 | 13.12 | 18.52 | zhangkai | 138.199.35.216 |
| 75.73 | vless | 265.4 | 562.0 | 21.63 | 0.0 | 10.0 | 9.3 | 17.76 | Au1rxx-base64 | 172.233.139.46 |
| 74.8 | vless | 351.9 | 855.7 | 19.63 | 0.0 | 10.0 | 9.3 | 17.76 | Au1rxx-base64 | 15.204.97.216 |
| 73.73 | trojan | 286.6 | 565.6 | 21.14 | 0.0 | 10.0 | 12.35 | 17.76 | Au1rxx-base64 | 107.150.105.84 |
| 73.58 | vless | 271.8 | 564.5 | 21.49 | 0.0 | 10.0 | 9.3 | 17.76 | Au1rxx-base64 | 172.235.38.85 |
| 73.48 | shadowsocks | 334.2 | 752.8 | 20.04 | 0.0 | 10.0 | 13.77 | 17.76 | Au1rxx-base64 | 37.19.198.160 |
| 73.24 | vless | 337.5 | 763.8 | 19.97 | 0.0 | 10.0 | 9.3 | 17.76 | Au1rxx-base64 | 23.94.227.94 |
| 73.22 | vless | 271.4 | 545.1 | 21.5 | 0.0 | 10.0 | 9.3 | 17.76 | Au1rxx-base64 | 38.209.125.45 |
| 72.82 | shadowsocks | 297.8 | 660.0 | 20.88 | 0.0 | 10.0 | 13.77 | 16.6 | Surfboard-tg-mixed | 198.98.53.130 |
| 72.82 | shadowsocks | 302.6 | 626.0 | 20.77 | 0.0 | 9.36 | 13.77 | 17.76 | Au1rxx-base64 | 108.181.0.177 |
| 72.8 | shadowsocks | 309.3 | 675.2 | 20.62 | 0.0 | 10.0 | 13.77 | 16.6 | Surfboard-tg-mixed | 37.19.198.243 |
| 72.55 | vless | 360.2 | 707.5 | 19.44 | 0.0 | 10.0 | 9.3 | 17.76 | Au1rxx-base64 | 38.180.242.205 |
| 72.46 | shadowsocks | 237.8 | 607.2 | 22.27 | 0.0 | 10.0 | 13.77 | 10.42 | mheidari-all | 156.146.38.168 |
| 72.3 | shadowsocks | 245.0 | 628.7 | 22.11 | 0.0 | 10.0 | 13.77 | 10.42 | mheidari-all | 156.146.38.170 |
| 72.27 | http | 244.7 | 539.0 | 22.11 | 0.0 | 10.0 | 13.12 | 18.52 | zhangkai | 138.199.35.198 |
| 72.13 | hysteria2 | 559.0 | 1442.8 | 14.84 | 0.0 | 10.0 | 13.33 | 17.76 | Au1rxx-base64 | 159.223.157.129 |
| 71.7 | trojan | 569.9 | 1514.3 | 14.59 | 0.0 | 10.0 | 12.35 | 17.76 | Au1rxx-base64 | 64.94.95.118 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.986 | 0.916 | 308 | 1827 | prefer |
| zhangkai | 0.962 | 1.0 | 21 | 144 | prefer |
| Surfboard-tg-mixed | 0.91 | 0.833 | 210 | 7416 | prefer |
| tg-oneclickvpnkeys | 0.482 | 1.0 | 6 | 132 | observe |
| mheidari-all | 0.357 | 0.277 | 546 | 22409 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6965 | observe |
| DeltaKronecker-all | 0.284 | 0.333 | 6 | 6212 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4887 | observe |
| Epodonios-all | 0.255 | None | 0 | 7876 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8354 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6183 | observe |
| barry-far-vless | 0.255 | None | 0 | 6398 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4087 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 176 |
| speed | TimeoutError | - | 65 |
| cn-block | ClientOSError | - | 64 |
| geo | ClientOSError | - | 63 |
| speed | ClientOSError | - | 39 |
| cn-block | TimeoutError | - | 20 |
| 204 | TimeoutError | - | 18 |
| 204 | ProxyError | - | 10 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:36528: bind: address already in use | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
