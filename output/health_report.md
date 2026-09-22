# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-22 20:55:35 |
| 运行耗时 | 468.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 84310 |
| 去重后节点 | 23815 |
| TCP 可达 | 3000 |
| 真实可用 | 405 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23815 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| geo | 1.4 |
| tcp | 39.1 |
| probe | 200.8 |
| real_test | 145.3 |
| generate | 73.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51021 |
| vmess | 13754 |
| shadowsocks | 9654 |
| trojan | 8024 |
| hysteria2 | 1036 |
| http | 584 |
| shadowsocksr | 155 |
| socks | 64 |
| hysteria | 11 |
| tuic | 4 |
| anytls | 3 |

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
| 81.81 | hysteria2 | 252.8 | 676.0 | 21.93 | 0.0 | 10.0 | 12.6 | 18.38 | Au1rxx-base64 | 159.223.157.129 |
| 79.76 | shadowsocks | 255.0 | 706.8 | 21.87 | 0.0 | 10.0 | 13.51 | 18.38 | Au1rxx-base64 | 37.19.198.243 |
| 79.43 | shadowsocks | 269.4 | 721.3 | 21.54 | 0.0 | 10.0 | 13.51 | 18.38 | Au1rxx-base64 | 37.19.198.160 |
| 78.94 | shadowsocks | 290.6 | 798.3 | 21.05 | 0.0 | 10.0 | 13.51 | 18.38 | Au1rxx-base64 | 37.19.198.236 |
| 78.45 | shadowsocks | 311.7 | 865.1 | 20.56 | 0.0 | 10.0 | 13.51 | 18.38 | Au1rxx-base64 | 37.19.198.244 |
| 78.23 | vless | 289.4 | 769.1 | 21.08 | 0.0 | 10.0 | 8.77 | 18.38 | Au1rxx-base64 | 169.40.42.212 |
| 78.12 | vless | 294.0 | 662.3 | 20.97 | 0.0 | 10.0 | 8.77 | 18.38 | Au1rxx-base64 | 169.40.42.90 |
| 77.82 | shadowsocks | 317.2 | 829.5 | 20.43 | 0.0 | 10.0 | 13.51 | 18.38 | Au1rxx-base64 | 38.180.135.156 |
| 77.37 | vless | 326.3 | 836.2 | 20.22 | 0.0 | 10.0 | 8.77 | 18.38 | Au1rxx-base64 | 66.70.179.198 |
| 77.29 | vless | 279.5 | 676.2 | 21.31 | 0.0 | 10.0 | 8.77 | 18.38 | Au1rxx-base64 | 195.211.98.43 |
| 77.12 | shadowsocks | 369.2 | 994.9 | 19.23 | 0.0 | 10.0 | 13.51 | 18.38 | Au1rxx-base64 | 142.4.216.225 |
| 76.94 | shadowsocks | 355.3 | 981.6 | 19.55 | 0.0 | 10.0 | 13.51 | 18.38 | Au1rxx-base64 | 15.204.247.206 |
| 76.87 | vless | 337.3 | 790.2 | 19.97 | 0.0 | 10.0 | 8.77 | 18.38 | Au1rxx-base64 | 169.40.42.202 |
| 76.77 | vless | 352.3 | 976.5 | 19.62 | 0.0 | 10.0 | 8.77 | 18.38 | Au1rxx-base64 | 185.95.231.156 |
| 76.55 | vless | 362.1 | 935.7 | 19.4 | 0.0 | 10.0 | 8.77 | 18.38 | Au1rxx-base64 | 169.40.42.173 |
| 76.38 | vless | 326.3 | 896.8 | 20.23 | 0.0 | 10.0 | 8.77 | 18.38 | Au1rxx-base64 | 185.95.231.233 |
| 76.21 | vless | 376.8 | 895.7 | 19.06 | 0.0 | 10.0 | 8.77 | 18.38 | Au1rxx-base64 | 169.40.42.75 |
| 76.2 | vless | 377.2 | 915.3 | 19.05 | 0.0 | 10.0 | 8.77 | 18.38 | Au1rxx-base64 | 169.40.42.74 |
| 76.12 | vless | 380.5 | 1036.6 | 18.97 | 0.0 | 10.0 | 8.77 | 18.38 | Au1rxx-base64 | 169.40.42.16 |
| 75.98 | hysteria2 | 337.7 | 666.2 | 19.96 | 0.0 | 10.0 | 12.6 | 18.38 | Au1rxx-base64 | 66.94.121.46 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.928 | 0.871 | 31 | 6324 | prefer |
| Au1rxx-base64 | 0.909 | 0.842 | 292 | 1718 | prefer |
| mheidari-all | 0.818 | 0.744 | 78 | 15951 | prefer |
| Surfboard-tg-mixed | 0.598 | 0.519 | 108 | 7279 | observe |
| ermaozi | 0.594 | 0.586 | 29 | 325 | observe |
| Epodonios-all | 0.255 | None | 0 | 7749 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9217 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5930 | observe |
| barry-far-vless | 0.255 | None | 0 | 5928 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4252 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1718 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-ScrapeCategorize-Vless | 0.207 | 0.0 | 1 | 4915 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 37 |
| geo | ClientOSError | - | 24 |
| 204 | ProxyConnectionError | - | 14 |
| cn-block | ClientOSError | - | 13 |
| 204 | ProxyError | - | 12 |
| cn-block | TimeoutError | - | 12 |
| 204 | TimeoutError | - | 10 |
| geo | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| speed | TimeoutError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
