# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-27 11:25:36 |
| 运行耗时 | 600.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 95694 |
| 去重后节点 | 26581 |
| TCP 可达 | 3000 |
| 真实可用 | 438 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26581 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| geo | 1.4 |
| tcp | 43.8 |
| probe | 276.1 |
| real_test | 193.4 |
| generate | 81.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58150 |
| vmess | 14704 |
| shadowsocks | 11312 |
| trojan | 9137 |
| hysteria2 | 1454 |
| http | 641 |
| shadowsocksr | 168 |
| socks | 79 |
| anytls | 26 |
| hysteria | 15 |
| tuic | 8 |

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
| 80.06 | hysteria2 | 255.1 | 598.8 | 21.87 | 0.0 | 8.75 | 13.57 | 18.32 | Au1rxx-base64 | 66.94.121.46 |
| 79.76 | hysteria2 | 232.4 | 241.1 | 22.4 | 5.96 | 6.61 | 13.57 | 18.32 | Au1rxx-base64 | open.w2m.ink |
| 78.58 | shadowsocks | 254.9 | 619.5 | 21.88 | 0.0 | 8.62 | 13.76 | 18.32 | Au1rxx-base64 | 156.146.38.168 |
| 78.5 | shadowsocks | 259.1 | 630.6 | 21.78 | 0.0 | 8.64 | 13.76 | 18.32 | Au1rxx-base64 | 156.146.38.169 |
| 78.42 | shadowsocks | 262.0 | 646.7 | 21.71 | 0.0 | 8.63 | 13.76 | 18.32 | Au1rxx-base64 | 156.146.38.167 |
| 78.01 | shadowsocks | 259.5 | 639.6 | 21.77 | 0.0 | 10.0 | 13.76 | 16.48 | Surfboard-tg-mixed | 156.146.38.170 |
| 77.68 | vless | 200.9 | 531.4 | 23.13 | 0.0 | 8.65 | 7.58 | 18.32 | Au1rxx-base64 | 172.233.139.46 |
| 77.51 | vless | 207.2 | 533.9 | 22.98 | 0.0 | 8.63 | 7.58 | 18.32 | Au1rxx-base64 | 172.235.43.210 |
| 77.44 | http | 195.1 | 508.7 | 23.26 | 0.0 | 10.0 | 11.62 | 15.56 | ermaozi | 138.199.35.210 |
| 77.44 | vless | 212.0 | 524.3 | 22.87 | 0.0 | 8.67 | 7.58 | 18.32 | Au1rxx-base64 | 195.123.240.65 |
| 77.41 | http | 196.4 | 511.3 | 23.23 | 0.0 | 10.0 | 11.62 | 15.56 | ermaozi | 138.199.35.199 |
| 77.4 | http | 196.8 | 512.0 | 23.22 | 0.0 | 10.0 | 11.62 | 15.56 | ermaozi | 138.199.35.217 |
| 77.39 | http | 197.5 | 509.7 | 23.21 | 0.0 | 10.0 | 11.62 | 15.56 | ermaozi | 138.199.35.211 |
| 77.36 | http | 198.4 | 516.8 | 23.18 | 0.0 | 10.0 | 11.62 | 15.56 | ermaozi | 138.199.35.219 |
| 77.36 | http | 198.4 | 512.6 | 23.18 | 0.0 | 10.0 | 11.62 | 15.56 | ermaozi | 138.199.35.213 |
| 77.34 | http | 199.4 | 515.3 | 23.16 | 0.0 | 10.0 | 11.62 | 15.56 | ermaozi | 138.199.35.200 |
| 77.32 | http | 200.2 | 522.9 | 23.14 | 0.0 | 10.0 | 11.62 | 15.56 | ermaozi | 138.199.35.206 |
| 77.28 | http | 201.9 | 523.1 | 23.1 | 0.0 | 10.0 | 11.62 | 15.56 | ermaozi | 138.199.35.197 |
| 77.25 | http | 203.2 | 528.3 | 23.07 | 0.0 | 10.0 | 11.62 | 15.56 | ermaozi | 138.199.35.209 |
| 77.22 | http | 204.5 | 535.3 | 23.04 | 0.0 | 10.0 | 11.62 | 15.56 | ermaozi | 138.199.35.216 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.913 | 0.852 | 290 | 1589 | prefer |
| mheidari-all | 0.788 | 0.714 | 70 | 22397 | prefer |
| Surfboard-tg-mixed | 0.758 | 0.681 | 116 | 7025 | prefer |
| DeltaKronecker-all | 0.716 | 0.65 | 20 | 5466 | prefer |
| ermaozi | 0.697 | 0.69 | 58 | 338 | observe |
| ermaozi-get_subscribe | 0.401 | 0.438 | 16 | 361 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 149 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7510 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3995 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8971 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5637 | observe |
| barry-far-vless | 0.255 | None | 0 | 5862 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4277 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 31 |
| 204 | TimeoutError | - | 24 |
| cn-block | TimeoutError | - | 21 |
| geo | TimeoutError | - | 20 |
| speed | TimeoutError | - | 12 |
| speed | ClientOSError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| geo | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 5 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:33760: bind: address already in use | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
