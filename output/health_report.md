# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-01 02:30:30 |
| 运行耗时 | 417.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 78568 |
| 去重后节点 | 22801 |
| TCP 可达 | 3000 |
| 真实可用 | 881 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22801 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.4 |
| tcp | 34.1 |
| probe | 79.1 |
| real_test | 260.6 |
| generate | 36.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46649 |
| vmess | 12020 |
| shadowsocks | 10223 |
| trojan | 8844 |
| hysteria2 | 569 |
| http | 87 |
| shadowsocksr | 73 |
| socks | 57 |
| anytls | 26 |
| hysteria | 14 |
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
| 77.89 | http | 365.2 | 852.1 | 19.32 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.7 |
| 77.5 | vless | 307.8 | 714.8 | 20.65 | 0.0 | 10.0 | 10.25 | 16.6 | Au1rxx-base64 | 216.152.147.28 |
| 76.47 | http | 385.9 | 895.2 | 18.85 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.8 |
| 76.43 | shadowsocks | 238.1 | 629.1 | 22.27 | 0.0 | 9.37 | 12.19 | 16.6 | Au1rxx-base64 | 156.146.38.170 |
| 76.4 | http | 403.0 | 939.9 | 18.45 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 156.146.59.5 |
| 75.59 | hysteria2 | 284.9 | 671.4 | 21.18 | 0.0 | 9.29 | 10.26 | 16.6 | Au1rxx-base64 | 159.223.157.129 |
| 75.34 | hysteria2 | 285.7 | 695.3 | 21.16 | 0.0 | 9.32 | 10.26 | 16.6 | Au1rxx-base64 | 138.124.68.188 |
| 75.01 | hysteria2 | 292.3 | 710.2 | 21.01 | 0.0 | 8.57 | 10.26 | 16.6 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 74.33 | shadowsocks | 241.9 | 604.1 | 22.18 | 0.0 | 9.36 | 12.19 | 16.6 | Au1rxx-base64 | 156.146.38.167 |
| 74.33 | vless | 266.3 | 610.1 | 21.61 | 0.0 | 10.0 | 10.25 | 16.6 | Au1rxx-base64 | 216.227.161.95 |
| 73.8 | vless | 291.2 | 579.6 | 21.04 | 0.0 | 10.0 | 10.25 | 16.6 | Au1rxx-base64 | 192.204.50.220 |
| 73.77 | http | 501.3 | 1223.6 | 16.17 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.196 |
| 73.72 | http | 497.4 | 1214.5 | 16.26 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.197 |
| 73.71 | http | 501.2 | 1225.3 | 16.18 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.207 |
| 73.68 | http | 501.6 | 1214.7 | 16.17 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.204 |
| 73.65 | http | 492.1 | 1196.5 | 16.39 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.199 |
| 73.62 | shadowsocks | 299.1 | 712.5 | 20.85 | 0.0 | 9.36 | 12.19 | 16.6 | Au1rxx-base64 | 37.19.198.160 |
| 73.62 | http | 495.0 | 1201.1 | 16.32 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.218 |
| 73.61 | http | 498.3 | 1211.4 | 16.24 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.205 |
| 73.44 | http | 504.3 | 1238.2 | 16.1 | 0.0 | 10.0 | 14.82 | 19.84 | zhangkai | 138.199.35.209 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | 1.0 | 80 | 110 | prefer |
| Au1rxx-base64 | 0.951 | 0.886 | 518 | 1661 | prefer |
| Surfboard-tg-mixed | 0.563 | 0.562 | 16 | 5432 | observe |
| DeltaKronecker-all | 0.415 | 0.335 | 980 | 5144 | observe |
| nscl5-all | 0.362 | 1.0 | 2 | 1258 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 52 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5507 | observe |
| Epodonios-all | 0.255 | None | 0 | 6122 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6608 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4234 | observe |
| barry-far-vless | 0.255 | None | 0 | 4596 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5081 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1661 | observe |
| mheidari-all | 0.239 | 0.167 | 12 | 16450 | downweight |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 271 |
| speed | ClientOSError | - | 159 |
| cn-block | TimeoutError | - | 113 |
| geo | ClientOSError | - | 82 |
| speed | TimeoutError | - | 67 |
| 204 | TimeoutError | - | 12 |
| cn-block | ClientOSError | - | 11 |
| 204 | ProxyError | - | 10 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
