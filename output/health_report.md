# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-23 01:06:25 |
| 运行耗时 | 309.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 83287 |
| 去重后节点 | 23720 |
| TCP 可达 | 3000 |
| 真实可用 | 866 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23720 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.4 |
| tcp | 39.9 |
| probe | 58.5 |
| real_test | 166.9 |
| generate | 36.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50100 |
| trojan | 10582 |
| shadowsocks | 10338 |
| vmess | 10304 |
| hysteria2 | 1480 |
| shadowsocksr | 171 |
| http | 167 |
| socks | 115 |
| anytls | 16 |
| hysteria | 11 |
| tuic | 3 |

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
| 83.36 | vless | 249.8 | 644.7 | 22.0 | 0.0 | 10.0 | 11.56 | 19.8 | Au1rxx-base64 | 169.40.42.225 |
| 83.0 | vless | 265.2 | 697.6 | 21.64 | 0.0 | 10.0 | 11.56 | 19.8 | Au1rxx-base64 | 169.40.42.89 |
| 82.81 | vless | 273.5 | 667.5 | 21.45 | 0.0 | 10.0 | 11.56 | 19.8 | Au1rxx-base64 | 169.40.42.16 |
| 82.13 | vless | 302.7 | 833.1 | 20.77 | 0.0 | 10.0 | 11.56 | 19.8 | Au1rxx-base64 | 137.184.218.169 |
| 81.86 | vless | 314.5 | 708.1 | 20.5 | 0.0 | 10.0 | 11.56 | 19.8 | Au1rxx-base64 | 169.40.42.104 |
| 81.79 | vless | 317.4 | 875.3 | 20.43 | 0.0 | 10.0 | 11.56 | 19.8 | Au1rxx-base64 | 79.127.243.217 |
| 81.65 | vless | 323.4 | 810.0 | 20.29 | 0.0 | 10.0 | 11.56 | 19.8 | Au1rxx-base64 | 169.40.42.90 |
| 81.45 | vless | 291.0 | 658.0 | 21.04 | 0.0 | 10.0 | 11.56 | 19.8 | Au1rxx-base64 | 198.251.78.29 |
| 81.37 | vless | 266.7 | 644.5 | 21.6 | 0.0 | 10.0 | 11.56 | 19.8 | Au1rxx-base64 | 169.40.42.232 |
| 80.98 | vless | 266.0 | 696.0 | 21.62 | 0.0 | 10.0 | 11.56 | 19.8 | Au1rxx-base64 | 169.40.42.74 |
| 80.89 | vless | 356.5 | 846.8 | 19.53 | 0.0 | 10.0 | 11.56 | 19.8 | Au1rxx-base64 | 169.40.42.202 |
| 80.68 | vless | 280.7 | 736.6 | 21.28 | 0.0 | 10.0 | 11.56 | 19.8 | Au1rxx-base64 | 169.40.42.173 |
| 80.56 | hysteria2 | 307.3 | 865.8 | 20.66 | 0.0 | 10.0 | 13.7 | 17.3 | mheidari-all | 159.223.157.129 |
| 80.39 | vless | 277.5 | 651.6 | 21.35 | 0.0 | 10.0 | 11.56 | 19.8 | Au1rxx-base64 | 154.40.137.160 |
| 80.25 | vless | 383.9 | 994.1 | 18.89 | 0.0 | 10.0 | 11.56 | 19.8 | Au1rxx-base64 | 158.69.112.254 |
| 79.91 | shadowsocks | 296.2 | 797.6 | 20.92 | 0.0 | 10.0 | 13.19 | 19.8 | Au1rxx-base64 | 142.4.216.225 |
| 79.91 | vless | 368.4 | 945.2 | 19.25 | 0.0 | 10.0 | 11.56 | 19.8 | Au1rxx-base64 | 209.200.246.86 |
| 79.69 | vless | 334.4 | 911.3 | 20.04 | 0.0 | 10.0 | 11.56 | 19.8 | Au1rxx-base64 | 169.40.42.223 |
| 78.89 | vless | 395.0 | 1114.0 | 18.63 | 0.0 | 10.0 | 11.56 | 19.8 | Au1rxx-base64 | 45.138.100.226 |
| 78.68 | shadowsocks | 241.5 | 669.3 | 22.19 | 0.0 | 10.0 | 13.19 | 17.3 | mheidari-all | 37.19.198.236 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.943 | 513 | 1723 | prefer |
| zhangkai | 0.988 | 0.991 | 113 | 144 | prefer |
| Surfboard-tg-mixed | 0.893 | 0.816 | 207 | 6333 | prefer |
| mheidari-all | 0.548 | 0.468 | 154 | 14498 | observe |
| nscl5-all | 0.355 | 1.0 | 2 | 1082 | observe |
| DeltaKronecker-all | 0.347 | 0.261 | 88 | 5015 | observe |
| tg-oneclickvpnkeys | 0.317 | 1.0 | 2 | 146 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5096 | observe |
| Epodonios-all | 0.255 | None | 0 | 6920 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3986 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6994 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5187 | observe |
| barry-far-vless | 0.255 | None | 0 | 5496 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4074 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 84 |
| speed | TimeoutError | - | 47 |
| geo | ClientOSError | - | 32 |
| cn-block | TimeoutError | - | 22 |
| speed | ClientOSError | - | 13 |
| 204 | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 4 |
| 204 | ProxyError | - | 4 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
