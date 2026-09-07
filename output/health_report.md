# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-07 17:11:48 |
| 运行耗时 | 323.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 89384 |
| 去重后节点 | 25034 |
| TCP 可达 | 3000 |
| 真实可用 | 579 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25034 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.4 |
| tcp | 42.9 |
| probe | 89.9 |
| real_test | 143.0 |
| generate | 39.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55702 |
| vmess | 12357 |
| shadowsocks | 10546 |
| trojan | 8657 |
| hysteria2 | 1761 |
| http | 139 |
| shadowsocksr | 132 |
| socks | 47 |
| hysteria | 16 |
| anytls | 16 |
| tuic | 11 |

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
| 81.87 | vless | 311.2 | 752.1 | 20.57 | 0.0 | 10.0 | 11.4 | 19.9 | Au1rxx-base64 | 169.40.42.231 |
| 81.57 | vless | 291.3 | 686.5 | 21.03 | 0.0 | 10.0 | 11.4 | 19.9 | Au1rxx-base64 | 216.152.147.28 |
| 81.35 | shadowsocks | 243.4 | 653.2 | 22.14 | 0.0 | 10.0 | 13.31 | 19.9 | Au1rxx-base64 | 37.19.198.160 |
| 81.18 | vless | 341.0 | 822.5 | 19.88 | 0.0 | 10.0 | 11.4 | 19.9 | Au1rxx-base64 | 169.40.42.235 |
| 81.08 | shadowsocks | 255.1 | 690.1 | 21.87 | 0.0 | 10.0 | 13.31 | 19.9 | Au1rxx-base64 | 37.19.198.236 |
| 80.99 | hysteria2 | 302.9 | 838.5 | 20.77 | 0.0 | 10.0 | 14.42 | 19.9 | Au1rxx-base64 | 159.223.157.129 |
| 80.98 | shadowsocks | 259.7 | 692.8 | 21.77 | 0.0 | 10.0 | 13.31 | 19.9 | Au1rxx-base64 | 37.19.198.244 |
| 80.95 | vless | 331.4 | 738.3 | 20.11 | 0.0 | 10.0 | 11.4 | 19.9 | Au1rxx-base64 | 169.40.42.224 |
| 80.75 | vless | 360.0 | 822.3 | 19.45 | 0.0 | 10.0 | 11.4 | 19.9 | Au1rxx-base64 | 169.40.42.223 |
| 80.33 | vless | 377.8 | 1022.5 | 19.03 | 0.0 | 10.0 | 11.4 | 19.9 | Au1rxx-base64 | 185.95.231.156 |
| 80.29 | vless | 362.9 | 829.2 | 19.38 | 0.0 | 10.0 | 11.4 | 19.9 | Au1rxx-base64 | 169.40.42.89 |
| 80.19 | vless | 322.7 | 838.3 | 20.31 | 0.0 | 10.0 | 11.4 | 19.9 | Au1rxx-base64 | 169.40.42.212 |
| 80.05 | vless | 386.6 | 1002.1 | 18.83 | 0.0 | 10.0 | 11.4 | 19.9 | Au1rxx-base64 | 66.70.179.198 |
| 79.99 | vless | 392.5 | 652.0 | 18.69 | 0.0 | 10.0 | 11.4 | 19.9 | Au1rxx-base64 | 169.40.42.179 |
| 79.96 | vless | 264.1 | 661.8 | 21.66 | 0.0 | 10.0 | 11.4 | 19.9 | Au1rxx-base64 | 195.123.235.177 |
| 79.95 | hysteria2 | 298.2 | 584.0 | 20.88 | 0.0 | 10.0 | 14.42 | 19.9 | Au1rxx-base64 | 66.94.121.46 |
| 79.59 | vless | 280.1 | 708.5 | 21.29 | 0.0 | 10.0 | 11.4 | 19.9 | Au1rxx-base64 | 169.40.42.202 |
| 79.42 | vless | 417.3 | 1121.9 | 18.12 | 0.0 | 10.0 | 11.4 | 19.9 | Au1rxx-base64 | 167.17.69.171 |
| 79.16 | vless | 358.4 | 890.9 | 19.48 | 0.0 | 10.0 | 11.4 | 19.9 | Au1rxx-base64 | 169.40.42.163 |
| 78.99 | vless | 391.0 | 1048.4 | 18.73 | 0.0 | 10.0 | 11.4 | 19.9 | Au1rxx-base64 | 169.40.42.75 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.953 | 316 | 1785 | prefer |
| zhangkai | 0.964 | 1.0 | 22 | 144 | prefer |
| Surfboard-tg-mixed | 0.826 | 0.749 | 175 | 7406 | prefer |
| mheidari-all | 0.602 | 0.522 | 224 | 21150 | observe |
| tg-oneclickvpnkeys | 0.484 | 1.0 | 6 | 181 | observe |
| DeltaKronecker-all | 0.391 | 1.0 | 2 | 6417 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4650 | observe |
| Epodonios-all | 0.255 | None | 0 | 7870 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8891 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6099 | observe |
| barry-far-vless | 0.255 | None | 0 | 6314 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4138 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1785 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 67 |
| geo | ClientOSError | - | 35 |
| cn-block | ClientOSError | - | 19 |
| cn-block | TimeoutError | - | 18 |
| speed | ClientOSError | - | 5 |
| 204 | ProxyError | - | 5 |
| geo | TimeoutError | - | 5 |
| cn-block | ProxyError | - | 4 |
| speed | TimeoutError | - | 4 |
| speed | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| 204 | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
