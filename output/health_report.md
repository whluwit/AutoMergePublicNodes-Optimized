# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-01 08:17:31 |
| 运行耗时 | 292.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 78781 |
| 去重后节点 | 23173 |
| TCP 可达 | 3000 |
| 真实可用 | 654 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23173 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.4 |
| tcp | 34.2 |
| probe | 62.4 |
| real_test | 162.7 |
| generate | 25.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47168 |
| vmess | 12308 |
| shadowsocks | 10167 |
| trojan | 8176 |
| hysteria2 | 603 |
| http | 173 |
| shadowsocksr | 76 |
| socks | 62 |
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
| 82.88 | http | 283.2 | 675.2 | 21.22 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.7 |
| 82.77 | http | 287.8 | 698.4 | 21.11 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.5 |
| 82.05 | hysteria2 | 278.9 | 721.1 | 21.32 | 0.0 | 9.21 | 13.5 | 19.02 | Au1rxx-base64 | 138.124.68.188 |
| 81.89 | http | 294.9 | 711.8 | 20.95 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.8 |
| 81.52 | http | 279.1 | 678.5 | 21.32 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.50 |
| 81.28 | http | 286.6 | 695.1 | 21.14 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.20 |
| 81.2 | hysteria2 | 311.0 | 817.9 | 20.58 | 0.0 | 9.2 | 13.5 | 19.02 | Au1rxx-base64 | 159.223.157.129 |
| 80.81 | http | 277.5 | 668.2 | 21.35 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.25 |
| 80.79 | http | 286.7 | 694.8 | 21.14 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.23 |
| 80.6 | http | 296.7 | 723.2 | 20.91 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.21 |
| 80.59 | shadowsocks | 257.0 | 651.5 | 21.83 | 0.0 | 10.0 | 13.74 | 19.02 | Au1rxx-base64 | 37.19.198.236 |
| 80.51 | shadowsocks | 260.2 | 662.8 | 21.75 | 0.0 | 10.0 | 13.74 | 19.02 | Au1rxx-base64 | 37.19.198.160 |
| 80.4 | shadowsocks | 265.3 | 677.2 | 21.64 | 0.0 | 10.0 | 13.74 | 19.02 | Au1rxx-base64 | 37.19.198.243 |
| 80.32 | hysteria2 | 275.5 | 703.3 | 21.4 | 0.0 | 7.4 | 13.5 | 19.02 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 79.94 | http | 296.4 | 726.5 | 20.92 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.16 |
| 79.91 | shadowsocks | 254.9 | 624.9 | 21.88 | 0.0 | 9.27 | 13.74 | 19.02 | Au1rxx-base64 | 156.146.38.170 |
| 79.58 | shadowsocks | 278.9 | 705.4 | 21.32 | 0.0 | 10.0 | 13.74 | 19.02 | Au1rxx-base64 | 68.168.222.210 |
| 79.19 | http | 297.5 | 714.1 | 20.89 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.33 |
| 78.4 | shadowsocks | 329.9 | 846.8 | 20.14 | 0.0 | 10.0 | 13.74 | 19.02 | Au1rxx-base64 | 185.196.61.82 |
| 77.81 | shadowsocks | 302.1 | 768.0 | 20.78 | 0.0 | 9.27 | 13.74 | 19.02 | Au1rxx-base64 | 156.146.38.167 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | 1.0 | 159 | 228 | prefer |
| Au1rxx-base64 | 0.849 | 0.784 | 472 | 1656 | prefer |
| Surfboard-tg-mixed | 0.58 | 0.5 | 86 | 5316 | observe |
| DeltaKronecker-all | 0.425 | 0.344 | 224 | 5502 | observe |
| mheidari-all | 0.324 | 0.375 | 8 | 16723 | observe |
| xiaoji235-airport-v2ray-all | 0.282 | 0.5 | 2 | 1861 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 52 | observe |
| Epodonios-all | 0.255 | None | 0 | 5937 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6670 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4168 | observe |
| barry-far-vless | 0.255 | None | 0 | 4552 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5039 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1656 | observe |
| nscl5-all | 0.225 | None | 0 | 1258 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 101 |
| speed | TimeoutError | - | 48 |
| geo | ClientOSError | - | 44 |
| speed | ClientOSError | - | 35 |
| 204 | TimeoutError | - | 25 |
| 204 | ProxyError | - | 14 |
| cn-block | TimeoutError | - | 12 |
| 204 | ClientOSError | - | 12 |
| cn-block | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 3 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
