# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-27 14:27:55 |
| 运行耗时 | 355.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 85424 |
| 去重后节点 | 22965 |
| TCP 可达 | 3000 |
| 真实可用 | 873 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22965 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| geo | 1.3 |
| tcp | 31.8 |
| probe | 72.7 |
| real_test | 201.1 |
| generate | 41.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48176 |
| trojan | 15938 |
| vmess | 10374 |
| shadowsocks | 9953 |
| hysteria2 | 704 |
| shadowsocksr | 101 |
| socks | 69 |
| http | 64 |
| anytls | 22 |
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
| 79.07 | trojan | 376.8 | 1045.0 | 19.05 | 0.0 | 10.0 | 13.76 | 19.26 | Au1rxx-base64 | 148.72.168.35 |
| 79.01 | hysteria2 | 296.4 | 632.4 | 20.92 | 0.0 | 10.0 | 12.0 | 19.26 | Au1rxx-base64 | 159.223.157.129 |
| 78.8 | shadowsocks | 246.8 | 603.3 | 22.07 | 0.0 | 10.0 | 11.51 | 19.26 | Au1rxx-base64 | 156.146.38.167 |
| 78.76 | shadowsocks | 250.0 | 610.2 | 21.99 | 0.0 | 10.0 | 11.51 | 19.26 | Au1rxx-base64 | 156.146.38.170 |
| 78.55 | shadowsocks | 249.9 | 611.3 | 21.99 | 0.0 | 10.0 | 11.51 | 19.26 | Au1rxx-base64 | 156.146.38.168 |
| 77.85 | shadowsocks | 264.4 | 654.2 | 21.66 | 0.0 | 10.0 | 11.51 | 19.26 | Au1rxx-base64 | 37.19.198.244 |
| 77.75 | shadowsocks | 281.7 | 707.2 | 21.26 | 0.0 | 10.0 | 11.51 | 19.26 | Au1rxx-base64 | 37.19.198.236 |
| 77.54 | shadowsocks | 302.8 | 772.8 | 20.77 | 0.0 | 10.0 | 11.51 | 19.26 | Au1rxx-base64 | 37.19.198.160 |
| 76.18 | shadowsocks | 340.1 | 897.8 | 19.91 | 0.0 | 10.0 | 11.51 | 19.26 | Au1rxx-base64 | 185.196.61.82 |
| 76.02 | vless | 200.3 | 568.8 | 23.14 | 0.0 | 10.0 | 4.76 | 18.12 | mheidari-all | 154.193.55.183 |
| 75.2 | shadowsocks | 248.9 | 606.5 | 22.02 | 0.0 | 10.0 | 11.51 | 19.26 | Au1rxx-base64 | 156.146.38.169 |
| 74.56 | trojan | 496.2 | 1315.7 | 16.29 | 0.0 | 10.0 | 13.76 | 19.26 | Au1rxx-base64 | 153.75.250.171 |
| 74.41 | trojan | 481.2 | 1239.1 | 16.64 | 0.0 | 10.0 | 13.76 | 19.26 | Au1rxx-base64 | 163.245.196.68 |
| 73.63 | shadowsocks | 281.3 | 546.5 | 21.27 | 0.0 | 10.0 | 11.51 | 19.26 | Au1rxx-base64 | 149.22.95.183 |
| 72.89 | hysteria2 | 382.1 | 708.7 | 18.93 | 0.0 | 9.9 | 12.0 | 19.26 | Au1rxx-base64 | 62.210.124.146 |
| 72.78 | shadowsocks | 293.0 | 581.5 | 21.0 | 0.0 | 10.0 | 11.51 | 19.26 | Au1rxx-base64 | 173.244.56.9 |
| 72.21 | shadowsocks | 304.1 | 601.4 | 20.74 | 0.0 | 10.0 | 11.51 | 19.26 | Au1rxx-base64 | 108.181.118.10 |
| 72.19 | shadowsocks | 325.2 | 727.1 | 20.25 | 0.0 | 10.0 | 11.51 | 19.26 | Au1rxx-base64 | 108.181.57.93 |
| 71.69 | shadowsocks | 338.2 | 644.9 | 19.95 | 0.0 | 10.0 | 11.51 | 19.26 | Au1rxx-base64 | 108.181.0.177 |
| 71.43 | shadowsocks | 305.9 | 574.1 | 20.7 | 0.0 | 10.0 | 11.51 | 19.26 | Au1rxx-base64 | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.991 | 0.935 | 399 | 1456 | prefer |
| zhangkai | 0.987 | 1.0 | 59 | 74 | prefer |
| Surfboard-tg-mixed | 0.822 | 0.75 | 64 | 5641 | prefer |
| DeltaKronecker-all | 0.808 | 0.733 | 101 | 5643 | prefer |
| mheidari-all | 0.689 | 0.61 | 515 | 19227 | observe |
| tg-oneclickvpnkeys | 0.405 | 1.0 | 4 | 131 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 3959 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4831 | observe |
| Epodonios-all | 0.255 | None | 0 | 6520 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3968 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6628 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4484 | observe |
| barry-far-vless | 0.255 | None | 0 | 4866 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5017 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 123 |
| speed | ClientOSError | - | 59 |
| geo | ClientOSError | - | 24 |
| cn-block | TimeoutError | - | 15 |
| 204 | TimeoutError | - | 15 |
| 204 | ProxyError | - | 12 |
| speed | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 8 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
