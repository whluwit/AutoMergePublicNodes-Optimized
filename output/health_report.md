# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-22 03:10:45 |
| 运行耗时 | 651.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 91687 |
| 去重后节点 | 25155 |
| TCP 可达 | 3000 |
| 真实可用 | 546 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25155 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 16.5 |
| geo | 1.4 |
| tcp | 43.0 |
| probe | 235.9 |
| real_test | 278.2 |
| generate | 76.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 54139 |
| vmess | 14741 |
| shadowsocks | 11160 |
| trojan | 9263 |
| hysteria2 | 1477 |
| http | 649 |
| shadowsocksr | 131 |
| socks | 81 |
| anytls | 21 |
| hysteria | 17 |
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
| 80.4 | shadowsocks | 252.1 | 624.8 | 21.94 | 0.0 | 9.68 | 13.68 | 19.24 | Au1rxx-base64 | 156.146.38.168 |
| 79.35 | vless | 268.2 | 663.7 | 21.57 | 0.0 | 9.77 | 8.77 | 19.24 | Au1rxx-base64 | 195.211.98.43 |
| 79.08 | hysteria2 | 343.0 | 784.8 | 19.84 | 0.0 | 9.9 | 12.75 | 19.24 | Au1rxx-base64 | 66.94.121.46 |
| 75.83 | vless | 320.6 | 764.4 | 20.36 | 0.0 | 9.88 | 8.77 | 19.24 | Au1rxx-base64 | 47.253.226.114 |
| 74.93 | shadowsocks | 250.7 | 597.3 | 21.97 | 0.0 | 10.0 | 13.68 | 13.28 | Surfboard-tg-mixed | 156.146.38.167 |
| 74.89 | shadowsocks | 252.5 | 619.5 | 21.93 | 0.0 | 10.0 | 13.68 | 13.28 | Surfboard-tg-mixed | 156.146.38.169 |
| 74.68 | vless | 326.6 | 721.5 | 20.22 | 0.0 | 10.0 | 8.77 | 19.24 | Au1rxx-base64 | 138.124.60.146 |
| 74.64 | hysteria2 | 285.5 | 691.6 | 21.17 | 0.0 | 10.0 | 12.75 | 11.82 | mheidari-all | 159.223.157.129 |
| 74.59 | vless | 356.2 | 853.6 | 19.53 | 0.0 | 9.72 | 8.77 | 19.24 | Au1rxx-base64 | 169.40.42.16 |
| 73.63 | vless | 333.6 | 779.9 | 20.06 | 0.0 | 9.13 | 8.77 | 19.24 | Au1rxx-base64 | ww9.levikogjgfdd.ir |
| 73.5 | shadowsocks | 249.6 | 595.1 | 22.0 | 0.0 | 10.0 | 13.68 | 11.82 | mheidari-all | 156.146.38.170 |
| 73.3 | vless | 368.7 | 775.0 | 19.24 | 0.0 | 9.67 | 8.77 | 19.24 | Au1rxx-base64 | 169.40.42.35 |
| 73.22 | vless | 382.5 | 782.3 | 18.92 | 0.0 | 9.67 | 8.77 | 19.24 | Au1rxx-base64 | 169.40.42.89 |
| 73.06 | vless | 342.3 | 777.2 | 19.85 | 0.0 | 9.68 | 8.77 | 19.24 | Au1rxx-base64 | 169.40.42.212 |
| 72.79 | vless | 294.0 | 675.5 | 20.97 | 0.0 | 9.7 | 8.77 | 19.24 | Au1rxx-base64 | 198.251.78.29 |
| 72.71 | vless | 361.7 | 686.4 | 19.4 | 0.0 | 9.68 | 8.77 | 19.24 | Au1rxx-base64 | 169.40.42.133 |
| 72.64 | vless | 393.7 | 823.2 | 18.67 | 0.0 | 9.7 | 8.77 | 19.24 | Au1rxx-base64 | 169.40.42.173 |
| 72.56 | vless | 330.7 | 614.4 | 20.12 | 0.0 | 9.69 | 8.77 | 19.24 | Au1rxx-base64 | 195.123.240.65 |
| 72.23 | vless | 335.4 | 647.6 | 20.01 | 0.0 | 9.86 | 8.77 | 19.24 | Au1rxx-base64 | 15.204.97.216 |
| 72.15 | vless | 422.6 | 906.1 | 17.99 | 0.0 | 9.71 | 8.77 | 19.24 | Au1rxx-base64 | 169.40.42.231 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.913 | 0.849 | 312 | 1657 | prefer |
| Surfboard-tg-mixed | 0.666 | 0.587 | 254 | 7121 | observe |
| ermaozi | 0.642 | 0.633 | 49 | 369 | observe |
| mheidari-all | 0.524 | 0.443 | 212 | 19852 | observe |
| 10ium-ScrapeCategorize-Vless | 0.259 | 0.333 | 3 | 5290 | observe |
| Epodonios-all | 0.255 | None | 0 | 7572 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8711 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5672 | observe |
| barry-far-vless | 0.255 | None | 0 | 5888 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4344 | observe |
| Au1rxx-clash | 0.241 | None | 0 | 1658 | observe |
| ermaozi-get_subscribe | 0.235 | 0.4 | 5 | 393 | downweight |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| tg-oneclickvpnkeys | 0.213 | 0.5 | 2 | 138 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 76 |
| geo | TimeoutError | - | 60 |
| speed | TimeoutError | - | 48 |
| cn-block | ClientOSError | - | 41 |
| speed | ClientOSError | - | 40 |
| cn-block | TimeoutError | - | 22 |
| 204 | ProxyError | - | 21 |
| 204 | TimeoutError | - | 14 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
