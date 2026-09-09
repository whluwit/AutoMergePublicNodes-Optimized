# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-09 15:59:18 |
| 运行耗时 | 645.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 84834 |
| 去重后节点 | 22009 |
| TCP 可达 | 3000 |
| 真实可用 | 484 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22009 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| geo | 1.3 |
| tcp | 36.9 |
| probe | 257.2 |
| real_test | 265.3 |
| generate | 80.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52145 |
| vmess | 12300 |
| shadowsocks | 9917 |
| trojan | 7947 |
| hysteria2 | 1761 |
| http | 560 |
| shadowsocksr | 133 |
| socks | 52 |
| hysteria | 9 |
| tuic | 8 |
| anytls | 2 |

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
| 82.42 | vless | 285.0 | 725.0 | 21.18 | 0.0 | 10.0 | 11.68 | 19.56 | Au1rxx-base64 | 66.70.179.198 |
| 82.24 | vless | 292.8 | 725.4 | 21.0 | 0.0 | 10.0 | 11.68 | 19.56 | Au1rxx-base64 | 169.40.42.225 |
| 82.18 | vless | 252.1 | 712.4 | 21.94 | 0.0 | 10.0 | 11.68 | 19.56 | Au1rxx-base64 | 47.253.226.114 |
| 82.18 | vless | 295.2 | 730.5 | 20.94 | 0.0 | 10.0 | 11.68 | 19.56 | Au1rxx-base64 | 169.40.42.52 |
| 82.17 | vless | 296.0 | 809.0 | 20.93 | 0.0 | 10.0 | 11.68 | 19.56 | Au1rxx-base64 | 137.184.218.169 |
| 81.97 | vless | 304.6 | 701.3 | 20.73 | 0.0 | 10.0 | 11.68 | 19.56 | Au1rxx-base64 | 169.40.42.179 |
| 81.78 | vless | 312.5 | 713.7 | 20.54 | 0.0 | 10.0 | 11.68 | 19.56 | Au1rxx-base64 | 169.40.42.212 |
| 81.73 | hysteria2 | 233.5 | 638.6 | 22.37 | 0.0 | 10.0 | 13.42 | 17.04 | Surfboard-tg-mixed | 159.223.157.129 |
| 80.83 | vless | 284.8 | 642.5 | 21.19 | 0.0 | 10.0 | 11.68 | 19.56 | Au1rxx-base64 | 169.40.42.16 |
| 80.79 | vless | 355.3 | 912.8 | 19.55 | 0.0 | 10.0 | 11.68 | 19.56 | Au1rxx-base64 | 169.40.42.74 |
| 80.69 | vless | 359.8 | 975.9 | 19.45 | 0.0 | 10.0 | 11.68 | 19.56 | Au1rxx-base64 | 169.40.42.229 |
| 80.48 | vless | 369.0 | 1033.9 | 19.24 | 0.0 | 10.0 | 11.68 | 19.56 | Au1rxx-base64 | 185.95.231.156 |
| 79.96 | shadowsocks | 307.0 | 804.3 | 20.67 | 0.0 | 10.0 | 14.23 | 19.56 | Au1rxx-base64 | 38.180.135.156 |
| 79.92 | vless | 335.3 | 780.2 | 20.02 | 0.0 | 10.0 | 11.68 | 19.56 | Au1rxx-base64 | 169.40.42.90 |
| 79.92 | vless | 393.2 | 1027.5 | 18.68 | 0.0 | 10.0 | 11.68 | 19.56 | Au1rxx-base64 | 169.40.42.95 |
| 79.75 | vless | 400.3 | 979.0 | 18.51 | 0.0 | 10.0 | 11.68 | 19.56 | Au1rxx-base64 | 169.40.42.202 |
| 79.52 | vless | 318.8 | 852.3 | 20.4 | 0.0 | 10.0 | 11.68 | 19.56 | Au1rxx-base64 | 169.40.42.75 |
| 79.49 | shadowsocks | 243.7 | 674.9 | 22.14 | 0.0 | 10.0 | 14.23 | 17.12 | mheidari-all | 37.19.198.244 |
| 79.31 | shadowsocks | 335.3 | 936.8 | 20.02 | 0.0 | 10.0 | 14.23 | 19.56 | Au1rxx-base64 | 15.204.246.132 |
| 79.27 | vless | 361.2 | 991.5 | 19.42 | 0.0 | 10.0 | 11.68 | 19.56 | Au1rxx-base64 | 169.40.42.184 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.984 | 0.919 | 284 | 1709 | prefer |
| Surfboard-tg-mixed | 0.857 | 0.781 | 155 | 7428 | prefer |
| ermaozi | 0.824 | 0.833 | 24 | 410 | prefer |
| DeltaKronecker-all | 0.689 | 0.619 | 21 | 5187 | observe |
| mheidari-all | 0.682 | 0.604 | 111 | 16618 | observe |
| tg-oneclickvpnkeys | 0.319 | 1.0 | 2 | 205 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4795 | observe |
| Epodonios-all | 0.255 | None | 0 | 7926 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9119 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6118 | observe |
| barry-far-vless | 0.255 | None | 0 | 6336 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4219 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1709 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 40 |
| cn-block | TimeoutError | - | 17 |
| 204 | ProxyError | - | 16 |
| cn-block | ClientOSError | - | 16 |
| 204 | TimeoutError | - | 14 |
| speed | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 4 |
| geo | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |
| speed | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
