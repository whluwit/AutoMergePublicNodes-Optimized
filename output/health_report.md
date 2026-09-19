# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-19 15:24:06 |
| 运行耗时 | 592.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 88358 |
| 去重后节点 | 25224 |
| TCP 可达 | 3000 |
| 真实可用 | 449 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25224 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.4 |
| tcp | 41.9 |
| probe | 240.0 |
| real_test | 217.7 |
| generate | 85.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53237 |
| vmess | 14034 |
| shadowsocks | 10524 |
| trojan | 8562 |
| hysteria2 | 1217 |
| http | 575 |
| shadowsocksr | 128 |
| socks | 64 |
| hysteria | 9 |
| tuic | 4 |
| anytls | 4 |

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
| 80.93 | vless | 254.9 | 705.9 | 21.88 | 0.0 | 10.0 | 10.77 | 18.28 | Au1rxx-base64 | 79.141.172.154 |
| 79.79 | shadowsocks | 246.4 | 662.2 | 22.07 | 0.0 | 10.0 | 13.44 | 18.28 | Au1rxx-base64 | 37.19.198.243 |
| 79.71 | shadowsocks | 250.2 | 673.1 | 21.99 | 0.0 | 10.0 | 13.44 | 18.28 | Au1rxx-base64 | 37.19.198.160 |
| 79.66 | shadowsocks | 252.2 | 684.1 | 21.94 | 0.0 | 10.0 | 13.44 | 18.28 | Au1rxx-base64 | 37.19.198.236 |
| 79.62 | vless | 311.5 | 755.4 | 20.57 | 0.0 | 10.0 | 10.77 | 18.28 | Au1rxx-base64 | 169.40.42.35 |
| 78.82 | vless | 345.9 | 860.7 | 19.77 | 0.0 | 10.0 | 10.77 | 18.28 | Au1rxx-base64 | 169.40.42.133 |
| 78.76 | vless | 297.1 | 706.9 | 20.9 | 0.0 | 10.0 | 10.77 | 18.28 | Au1rxx-base64 | 216.152.147.28 |
| 78.54 | vless | 358.0 | 898.8 | 19.49 | 0.0 | 10.0 | 10.77 | 18.28 | Au1rxx-base64 | 169.40.42.212 |
| 78.52 | vless | 358.9 | 955.4 | 19.47 | 0.0 | 10.0 | 10.77 | 18.28 | Au1rxx-base64 | 169.40.42.168 |
| 78.4 | vless | 364.1 | 981.2 | 19.35 | 0.0 | 10.0 | 10.77 | 18.28 | Au1rxx-base64 | 185.95.231.156 |
| 78.35 | shadowsocks | 254.6 | 669.3 | 21.89 | 0.0 | 10.0 | 13.44 | 17.02 | mheidari-all | 37.19.198.244 |
| 78.16 | vless | 374.4 | 1018.8 | 19.11 | 0.0 | 10.0 | 10.77 | 18.28 | Au1rxx-base64 | 137.184.218.169 |
| 78.03 | vless | 380.2 | 797.8 | 18.98 | 0.0 | 10.0 | 10.77 | 18.28 | Au1rxx-base64 | 169.40.42.74 |
| 77.92 | vless | 380.2 | 1018.4 | 18.98 | 0.0 | 10.0 | 10.77 | 18.28 | Au1rxx-base64 | 169.40.42.225 |
| 77.74 | vless | 282.7 | 705.4 | 21.23 | 0.0 | 8.46 | 10.77 | 18.28 | Au1rxx-base64 | ww9.levikogjgfdd.ir |
| 77.47 | vless | 253.8 | 693.0 | 21.9 | 0.0 | 10.0 | 10.77 | 15.8 | Surfboard-tg-mixed | 47.253.226.114 |
| 77.29 | vless | 412.1 | 1060.0 | 18.24 | 0.0 | 10.0 | 10.77 | 18.28 | Au1rxx-base64 | 169.40.42.95 |
| 77.23 | vless | 414.8 | 871.0 | 18.18 | 0.0 | 10.0 | 10.77 | 18.28 | Au1rxx-base64 | 169.40.42.89 |
| 76.88 | vless | 310.6 | 729.2 | 20.59 | 0.0 | 10.0 | 10.77 | 18.28 | Au1rxx-base64 | 169.40.42.231 |
| 76.59 | vless | 436.8 | 1133.5 | 17.67 | 0.0 | 10.0 | 10.77 | 18.28 | Au1rxx-base64 | 169.40.42.163 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.939 | 0.879 | 314 | 1568 | prefer |
| mheidari-all | 0.698 | 0.62 | 121 | 19364 | observe |
| Surfboard-tg-mixed | 0.634 | 0.555 | 146 | 7296 | observe |
| ermaozi | 0.591 | 0.833 | 12 | 250 | observe |
| DeltaKronecker-all | 0.418 | 0.5 | 10 | 6421 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4251 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5174 | observe |
| Epodonios-all | 0.255 | None | 0 | 7933 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3995 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9336 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5900 | observe |
| barry-far-vless | 0.255 | None | 0 | 6222 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.238 | None | 0 | 1569 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 36 |
| cn-block | ClientOSError | - | 31 |
| geo | TimeoutError | - | 23 |
| speed | ClientOSError | - | 17 |
| 204 | ProxyError | - | 16 |
| cn-block | TimeoutError | - | 14 |
| 204 | TimeoutError | - | 11 |
| speed | TimeoutError | - | 9 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
