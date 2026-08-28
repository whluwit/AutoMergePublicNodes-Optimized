# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-28 21:44:32 |
| 运行耗时 | 246.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 77037 |
| 去重后节点 | 20866 |
| TCP 可达 | 3000 |
| 真实可用 | 517 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 20866 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.4 |
| tcp | 34.5 |
| probe | 53.4 |
| real_test | 110.8 |
| generate | 40.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47115 |
| vmess | 10731 |
| shadowsocks | 10517 |
| trojan | 6588 |
| hysteria2 | 1722 |
| http | 176 |
| shadowsocksr | 124 |
| socks | 54 |
| hysteria | 7 |
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
| 81.99 | trojan | 211.1 | 547.0 | 22.89 | 0.0 | 10.0 | 13.06 | 19.04 | Au1rxx-base64 | 14.1.28.76 |
| 80.46 | shadowsocks | 220.2 | 528.4 | 22.68 | 0.0 | 10.0 | 12.74 | 19.04 | Au1rxx-base64 | 149.22.95.183 |
| 80.09 | vless | 200.5 | 495.5 | 23.14 | 0.0 | 10.0 | 9.91 | 19.04 | Au1rxx-base64 | 192.220.9.89 |
| 80.01 | shadowsocks | 191.5 | 468.2 | 23.34 | 0.0 | 9.39 | 12.74 | 19.04 | Au1rxx-base64 | 108.181.0.177 |
| 79.85 | vless | 186.1 | 494.1 | 23.47 | 0.0 | 9.43 | 9.91 | 19.04 | Au1rxx-base64 | 31.58.50.200 |
| 79.62 | shadowsocks | 236.0 | 524.4 | 22.31 | 0.0 | 9.53 | 12.74 | 19.04 | Au1rxx-base64 | 173.244.56.6 |
| 79.55 | http | 388.3 | 1074.1 | 18.79 | 0.0 | 10.0 | 14.42 | 19.34 | zhangkai | 138.199.35.198 |
| 79.53 | vless | 311.0 | 815.1 | 20.58 | 0.0 | 10.0 | 9.91 | 19.04 | Au1rxx-base64 | 15.204.97.216 |
| 79.42 | vless | 223.6 | 229.4 | 22.6 | 6.4 | 9.94 | 9.91 | 16.52 | Surfboard-tg-mixed | 31.76.91.72 |
| 79.39 | http | 395.1 | 1103.5 | 18.63 | 0.0 | 10.0 | 14.42 | 19.34 | zhangkai | 138.199.35.216 |
| 79.16 | shadowsocks | 231.4 | 580.8 | 22.42 | 0.0 | 9.46 | 12.74 | 19.04 | Au1rxx-base64 | 108.181.118.10 |
| 78.99 | vless | 180.0 | 503.9 | 23.61 | 0.0 | 9.43 | 9.91 | 19.04 | Au1rxx-base64 | 64.23.229.123 |
| 77.7 | vless | 173.9 | 481.0 | 23.75 | 0.0 | 10.0 | 9.91 | 19.04 | Au1rxx-base64 | 45.33.62.226 |
| 77.44 | vless | 314.8 | 831.5 | 20.49 | 0.0 | 10.0 | 9.91 | 19.04 | Au1rxx-base64 | 15.204.97.195 |
| 77.14 | vless | 173.8 | 486.6 | 23.76 | 0.0 | 9.43 | 9.91 | 19.04 | Au1rxx-base64 | 173.230.155.55 |
| 77.12 | vless | 199.3 | 506.1 | 23.17 | 0.0 | 10.0 | 9.91 | 19.04 | Au1rxx-base64 | 172.233.156.123 |
| 77.06 | vless | 177.1 | 499.1 | 23.68 | 0.0 | 9.43 | 9.91 | 19.04 | Au1rxx-base64 | 45.33.62.166 |
| 77.04 | trojan | 195.4 | 506.7 | 23.25 | 0.0 | 9.53 | 13.06 | 19.04 | Au1rxx-base64 | 107.150.105.84 |
| 77.02 | vless | 178.6 | 485.1 | 23.64 | 0.0 | 9.43 | 9.91 | 19.04 | Au1rxx-base64 | 74.207.245.124 |
| 77.0 | vless | 204.3 | 487.1 | 23.05 | 0.0 | 10.0 | 9.91 | 19.04 | Au1rxx-base64 | 172.235.38.85 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.967 | 1.0 | 24 | 144 | prefer |
| Au1rxx-base64 | 0.961 | 0.892 | 342 | 1776 | prefer |
| mheidari-all | 0.905 | 0.833 | 78 | 14493 | prefer |
| Surfboard-tg-mixed | 0.737 | 0.659 | 167 | 6713 | prefer |
| DeltaKronecker-all | 0.586 | 0.8 | 10 | 4065 | observe |
| tg-oneclickvpnkeys | 0.445 | 1.0 | 5 | 140 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4725 | observe |
| Epodonios-all | 0.255 | None | 0 | 6861 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3988 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7878 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5540 | observe |
| barry-far-vless | 0.255 | None | 0 | 5468 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4081 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1776 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 23 |
| cn-block | TimeoutError | - | 19 |
| 204 | ProxyError | - | 18 |
| geo | ClientOSError | - | 17 |
| cn-block | ClientOSError | - | 10 |
| 204 | ClientOSError | - | 6 |
| speed | ClientOSError | - | 5 |
| geo | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |
| speed | TimeoutError | - | 2 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
