# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-01 19:06:25 |
| 运行耗时 | 289.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 78657 |
| 去重后节点 | 23488 |
| TCP 可达 | 3000 |
| 真实可用 | 592 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23488 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 1.4 |
| tcp | 35.0 |
| probe | 59.0 |
| real_test | 146.1 |
| generate | 41.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47047 |
| vmess | 12270 |
| shadowsocks | 10199 |
| trojan | 8168 |
| hysteria2 | 632 |
| http | 157 |
| shadowsocksr | 71 |
| socks | 65 |
| anytls | 26 |
| hysteria | 14 |
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
| 83.81 | http | 253.9 | 639.4 | 21.9 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 156.146.59.50 |
| 83.67 | http | 260.0 | 651.1 | 21.76 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 156.146.59.33 |
| 83.6 | http | 263.0 | 657.0 | 21.69 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 156.146.59.25 |
| 83.36 | http | 273.3 | 708.9 | 21.45 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 156.146.59.21 |
| 83.31 | http | 275.5 | 714.3 | 21.4 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 156.146.59.8 |
| 83.25 | http | 278.3 | 703.7 | 21.34 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 156.146.59.16 |
| 83.22 | http | 279.2 | 712.9 | 21.31 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 156.146.59.7 |
| 81.79 | http | 255.0 | 654.3 | 21.88 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 156.146.59.49 |
| 81.53 | http | 266.1 | 690.3 | 21.62 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 156.146.59.43 |
| 80.49 | http | 267.7 | 690.3 | 21.58 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 156.146.59.41 |
| 79.05 | hysteria2 | 241.2 | 651.0 | 22.19 | 0.0 | 8.8 | 12.5 | 16.66 | Au1rxx-base64 | 159.223.157.129 |
| 78.87 | hysteria2 | 253.6 | 687.0 | 21.91 | 0.0 | 8.8 | 12.5 | 16.66 | Au1rxx-base64 | 138.124.68.188 |
| 78.32 | shadowsocks | 238.9 | 640.0 | 22.25 | 0.0 | 10.0 | 13.41 | 16.66 | Au1rxx-base64 | 37.19.198.236 |
| 78.24 | shadowsocks | 242.4 | 648.8 | 22.17 | 0.0 | 10.0 | 13.41 | 16.66 | Au1rxx-base64 | 37.19.198.160 |
| 78.0 | vless | 251.8 | 651.7 | 21.95 | 0.0 | 10.0 | 9.39 | 16.66 | Au1rxx-base64 | 167.99.48.117 |
| 77.84 | shadowsocks | 259.7 | 692.3 | 21.77 | 0.0 | 10.0 | 13.41 | 16.66 | Au1rxx-base64 | 37.19.198.243 |
| 77.82 | vless | 259.3 | 656.6 | 21.77 | 0.0 | 10.0 | 9.39 | 16.66 | Au1rxx-base64 | 167.17.69.171 |
| 77.32 | vless | 281.3 | 709.9 | 21.27 | 0.0 | 10.0 | 9.39 | 16.66 | Au1rxx-base64 | 78.111.89.171 |
| 76.53 | hysteria2 | 256.5 | 691.7 | 21.84 | 0.0 | 6.53 | 12.5 | 16.66 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 75.87 | http | 339.4 | 608.6 | 19.92 | 0.0 | 10.0 | 14.91 | 20.0 | zhangkai | 138.199.35.215 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.994 | 0.993 | 148 | 194 | prefer |
| Au1rxx-base64 | 0.786 | 0.719 | 463 | 1692 | prefer |
| DeltaKronecker-all | 0.62 | 0.54 | 124 | 5502 | observe |
| Surfboard-tg-mixed | 0.617 | 0.538 | 78 | 5294 | observe |
| 10ium-ScrapeCategorize-Vless | 0.335 | 1.0 | 1 | 5391 | observe |
| mheidari-all | 0.335 | 1.0 | 1 | 16619 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 55 | observe |
| Epodonios-all | 0.255 | None | 0 | 5908 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3970 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6646 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4168 | observe |
| barry-far-vless | 0.255 | None | 0 | 4547 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5071 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1692 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 95 |
| speed | TimeoutError | - | 26 |
| 204 | TimeoutError | - | 25 |
| cn-block | TimeoutError | - | 23 |
| geo | ClientOSError | - | 19 |
| speed | ClientOSError | - | 12 |
| 204 | ProxyError | - | 11 |
| 204 | ClientOSError | - | 9 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
