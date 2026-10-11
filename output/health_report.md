# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-11 03:55:26 |
| 运行耗时 | 1201.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97432 |
| 去重后节点 | 27464 |
| TCP 可达 | 3000 |
| 真实可用 | 533 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27464 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| geo | 1.5 |
| tcp | 46.1 |
| probe | 420.6 |
| real_test | 642.3 |
| generate | 82.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56955 |
| vmess | 15806 |
| shadowsocks | 11871 |
| trojan | 10394 |
| hysteria2 | 1558 |
| http | 550 |
| shadowsocksr | 163 |
| socks | 75 |
| anytls | 37 |
| hysteria | 16 |
| tuic | 7 |

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
| 82.91 | hysteria2 | 237.7 | 681.4 | 22.28 | 0.0 | 10.0 | 12.69 | 19.44 | Au1rxx-base64 | 129.213.91.185 |
| 82.64 | vless | 268.9 | 725.0 | 21.55 | 0.0 | 10.0 | 11.65 | 19.44 | Au1rxx-base64 | 159.89.87.21 |
| 82.58 | vless | 271.8 | 662.8 | 21.49 | 0.0 | 10.0 | 11.65 | 19.44 | Au1rxx-base64 | 169.40.42.229 |
| 82.41 | vless | 279.2 | 709.6 | 21.32 | 0.0 | 10.0 | 11.65 | 19.44 | Au1rxx-base64 | 66.70.179.198 |
| 82.32 | vless | 282.7 | 752.9 | 21.23 | 0.0 | 10.0 | 11.65 | 19.44 | Au1rxx-base64 | 169.40.42.184 |
| 81.94 | vless | 255.9 | 670.1 | 21.85 | 0.0 | 10.0 | 11.65 | 19.44 | Au1rxx-base64 | 169.40.42.231 |
| 81.64 | vless | 312.4 | 724.3 | 20.55 | 0.0 | 10.0 | 11.65 | 19.44 | Au1rxx-base64 | 169.40.42.235 |
| 81.33 | shadowsocks | 251.8 | 703.2 | 21.95 | 0.0 | 10.0 | 13.94 | 19.44 | Au1rxx-base64 | 37.19.198.244 |
| 81.3 | vless | 327.0 | 912.0 | 20.21 | 0.0 | 10.0 | 11.65 | 19.44 | Au1rxx-base64 | 185.95.231.156 |
| 81.21 | vless | 330.9 | 824.8 | 20.12 | 0.0 | 10.0 | 11.65 | 19.44 | Au1rxx-base64 | 169.40.42.16 |
| 80.97 | vless | 279.4 | 746.7 | 21.31 | 0.0 | 10.0 | 11.65 | 19.44 | Au1rxx-base64 | 169.40.42.179 |
| 80.7 | vless | 310.5 | 863.7 | 20.59 | 0.0 | 10.0 | 11.65 | 19.44 | Au1rxx-base64 | 137.184.218.169 |
| 80.68 | shadowsocks | 258.2 | 653.9 | 21.8 | 0.0 | 10.0 | 13.94 | 19.44 | Au1rxx-base64 | 140.82.63.79 |
| 80.61 | shadowsocks | 282.7 | 798.5 | 21.23 | 0.0 | 10.0 | 13.94 | 19.44 | Au1rxx-base64 | 37.19.198.160 |
| 80.6 | vless | 293.8 | 682.7 | 20.98 | 0.0 | 10.0 | 11.65 | 19.44 | Au1rxx-base64 | 169.40.42.74 |
| 80.33 | shadowsocks | 251.6 | 702.6 | 21.95 | 0.0 | 10.0 | 13.94 | 19.44 | Au1rxx-base64 | 37.19.198.236 |
| 80.33 | vless | 368.7 | 893.0 | 19.24 | 0.0 | 10.0 | 11.65 | 19.44 | Au1rxx-base64 | 169.40.42.212 |
| 80.28 | vless | 327.6 | 892.3 | 20.19 | 0.0 | 10.0 | 11.65 | 19.44 | Au1rxx-base64 | 169.40.42.173 |
| 80.04 | shadowsocks | 285.7 | 821.0 | 21.16 | 0.0 | 10.0 | 13.94 | 19.44 | Au1rxx-base64 | 15.204.247.206 |
| 79.63 | vless | 337.8 | 852.4 | 19.96 | 0.0 | 10.0 | 11.65 | 19.44 | Au1rxx-base64 | 169.40.42.182 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.987 | 0.917 | 386 | 1801 | prefer |
| zhangkai | 0.96 | 1.0 | 20 | 144 | prefer |
| Surfboard-tg-mixed | 0.58 | 0.5 | 20 | 7087 | observe |
| ermaozi-get_subscribe | 0.462 | 0.433 | 30 | 610 | observe |
| mheidari-all | 0.382 | 0.301 | 435 | 23592 | observe |
| DeltaKronecker-all | 0.352 | 0.364 | 11 | 5009 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4347 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4999 | observe |
| Epodonios-all | 0.255 | None | 0 | 7576 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9365 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5545 | observe |
| barry-far-vless | 0.255 | None | 0 | 5790 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1801 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 180 |
| speed | TimeoutError | - | 67 |
| geo | ClientOSError | - | 39 |
| speed | ClientOSError | - | 35 |
| 204 | ProxyError | - | 15 |
| cn-block | TimeoutError | - | 15 |
| 204 | ClientOSError | - | 10 |
| cn-block | ClientOSError | - | 6 |
| 204 | TimeoutError | - | 3 |
| 204 | ProxyConnectionError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
