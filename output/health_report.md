# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-14 21:25:33 |
| 运行耗时 | 657.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 98749 |
| 去重后节点 | 27376 |
| TCP 可达 | 3000 |
| 真实可用 | 331 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27376 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 52.5 |
| geo | 1.5 |
| tcp | 48.0 |
| probe | 234.7 |
| real_test | 228.4 |
| generate | 92.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58832 |
| vmess | 16342 |
| shadowsocks | 11639 |
| trojan | 9977 |
| hysteria2 | 1282 |
| http | 398 |
| shadowsocksr | 171 |
| socks | 59 |
| anytls | 25 |
| hysteria | 18 |
| tuic | 6 |

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
| 79.28 | hysteria2 | 291.0 | 703.0 | 21.04 | 0.0 | 10.0 | 12.69 | 17.24 | Au1rxx-base64 | 129.213.91.185 |
| 78.19 | vless | 272.4 | 669.6 | 21.47 | 0.0 | 10.0 | 10.43 | 17.24 | Au1rxx-base64 | 147.45.60.160 |
| 78.06 | shadowsocks | 240.4 | 600.4 | 22.21 | 0.0 | 10.0 | 12.61 | 17.24 | Au1rxx-base64 | 156.146.38.170 |
| 77.89 | shadowsocks | 247.7 | 615.1 | 22.04 | 0.0 | 10.0 | 12.61 | 17.24 | Au1rxx-base64 | 156.146.38.169 |
| 77.84 | shadowsocks | 250.0 | 621.9 | 21.99 | 0.0 | 10.0 | 12.61 | 17.24 | Au1rxx-base64 | 156.146.38.167 |
| 76.63 | shadowsocks | 302.1 | 732.1 | 20.78 | 0.0 | 10.0 | 12.61 | 17.24 | Au1rxx-base64 | 37.19.198.160 |
| 75.85 | shadowsocks | 304.6 | 741.3 | 20.73 | 0.0 | 10.0 | 12.61 | 17.24 | Au1rxx-base64 | 37.19.198.236 |
| 75.11 | shadowsocks | 302.5 | 736.0 | 20.78 | 0.0 | 10.0 | 12.61 | 17.24 | Au1rxx-base64 | 37.19.198.243 |
| 74.65 | vless | 285.8 | 562.7 | 21.16 | 0.0 | 10.0 | 10.43 | 17.24 | Au1rxx-base64 | 47.251.108.158 |
| 73.7 | vless | 301.4 | 588.7 | 20.8 | 0.0 | 10.0 | 10.43 | 17.24 | Au1rxx-base64 | 45.32.69.110 |
| 73.42 | http | 303.1 | 576.1 | 20.76 | 0.0 | 10.0 | 10.91 | 19.32 | zhangkai | 138.199.35.198 |
| 73.21 | http | 323.6 | 561.6 | 20.29 | 0.0 | 10.0 | 10.91 | 19.32 | zhangkai | 138.199.35.216 |
| 73.12 | vless | 383.0 | 909.9 | 18.91 | 0.0 | 9.96 | 10.43 | 17.24 | Au1rxx-base64 | ww9.levikogjgfdd.ir |
| 72.5 | vless | 335.7 | 639.3 | 20.01 | 0.0 | 10.0 | 10.43 | 17.24 | Au1rxx-base64 | 44.248.233.99 |
| 71.96 | vless | 342.7 | 647.3 | 19.84 | 0.0 | 9.67 | 10.43 | 17.24 | Au1rxx-base64 | tk1.high-speed-test-56424.me |
| 71.7 | shadowsocks | 305.3 | 631.6 | 20.71 | 0.0 | 10.0 | 12.61 | 17.24 | Au1rxx-base64 | 173.244.56.9 |
| 71.52 | vless | 344.7 | 844.9 | 19.8 | 0.0 | 10.0 | 10.43 | 17.24 | Au1rxx-base64 | uspanel.unixzone.us |
| 71.37 | shadowsocks | 306.1 | 637.1 | 20.69 | 0.0 | 10.0 | 12.61 | 15.98 | mheidari-all | 149.22.95.183 |
| 71.2 | shadowsocks | 398.0 | 981.2 | 18.56 | 0.0 | 10.0 | 12.61 | 17.24 | Au1rxx-base64 | 15.204.246.132 |
| 71.09 | vless | 379.7 | 791.2 | 18.99 | 0.0 | 10.0 | 10.43 | 17.24 | Au1rxx-base64 | 169.40.42.90 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.971 | 0.909 | 44 | 23828 | prefer |
| Au1rxx-base64 | 0.912 | 0.844 | 275 | 1761 | prefer |
| Surfboard-tg-mixed | 0.897 | 0.828 | 58 | 7197 | prefer |
| zhangkai | 0.441 | 0.429 | 21 | 144 | observe |
| DeltaKronecker-all | 0.259 | 0.333 | 3 | 4803 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5125 | observe |
| Epodonios-all | 0.255 | None | 0 | 7716 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10189 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5754 | observe |
| barry-far-vless | 0.255 | None | 0 | 5978 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4271 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1761 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyConnectionError | - | 22 |
| cn-block | TimeoutError | - | 18 |
| geo | TimeoutError | - | 9 |
| 204 | TimeoutError | - | 7 |
| speed | ClientOSError | - | 5 |
| 204 | ProxyError | - | 4 |
| speed | TimeoutError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| 204 | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
