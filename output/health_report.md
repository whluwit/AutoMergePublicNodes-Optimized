# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-09 10:49:42 |
| 运行耗时 | 622.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 85031 |
| 去重后节点 | 22037 |
| TCP 可达 | 3000 |
| 真实可用 | 489 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22037 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.4 |
| tcp | 36.8 |
| probe | 227.9 |
| real_test | 270.2 |
| generate | 80.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52668 |
| vmess | 12038 |
| shadowsocks | 9860 |
| trojan | 7998 |
| hysteria2 | 1629 |
| http | 639 |
| shadowsocksr | 124 |
| socks | 56 |
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
| 81.77 | hysteria2 | 238.4 | 638.7 | 22.26 | 0.0 | 10.0 | 13.85 | 16.76 | Surfboard-tg-mixed | 159.223.157.129 |
| 78.16 | vless | 279.8 | 712.5 | 21.3 | 0.0 | 8.99 | 8.47 | 19.4 | Au1rxx-base64 | 169.40.42.182 |
| 78.0 | vless | 286.6 | 690.7 | 21.14 | 0.0 | 9.02 | 8.47 | 19.4 | Au1rxx-base64 | 169.40.42.229 |
| 77.91 | vless | 289.5 | 754.4 | 21.08 | 0.0 | 8.96 | 8.47 | 19.4 | Au1rxx-base64 | 169.40.42.75 |
| 77.73 | vless | 299.9 | 732.3 | 20.84 | 0.0 | 9.02 | 8.47 | 19.4 | Au1rxx-base64 | 66.70.179.198 |
| 77.47 | hysteria2 | 309.5 | 596.5 | 20.61 | 0.0 | 9.07 | 13.85 | 19.4 | Au1rxx-base64 | 66.94.121.46 |
| 76.73 | vless | 343.1 | 905.4 | 19.83 | 0.0 | 9.06 | 8.47 | 19.4 | Au1rxx-base64 | 169.40.42.231 |
| 76.53 | vless | 272.7 | 751.6 | 21.46 | 0.0 | 9.2 | 8.47 | 19.4 | Au1rxx-base64 | 47.253.226.114 |
| 76.36 | vless | 306.8 | 751.4 | 20.68 | 0.0 | 8.96 | 8.47 | 19.4 | Au1rxx-base64 | 169.40.42.184 |
| 76.29 | vless | 360.6 | 979.8 | 19.43 | 0.0 | 8.99 | 8.47 | 19.4 | Au1rxx-base64 | 185.95.231.156 |
| 76.24 | vless | 361.3 | 843.3 | 19.41 | 0.0 | 8.96 | 8.47 | 19.4 | Au1rxx-base64 | 169.40.42.212 |
| 76.02 | vless | 326.9 | 851.1 | 20.21 | 0.0 | 8.99 | 8.47 | 19.4 | Au1rxx-base64 | 169.40.42.95 |
| 75.94 | shadowsocks | 293.8 | 803.8 | 20.98 | 0.0 | 10.0 | 13.48 | 15.48 | mheidari-all | 37.19.198.244 |
| 75.63 | vless | 286.1 | 741.1 | 21.15 | 0.0 | 8.99 | 8.47 | 19.4 | Au1rxx-base64 | 169.40.42.15 |
| 75.58 | vless | 287.3 | 686.8 | 21.13 | 0.0 | 9.02 | 8.47 | 19.4 | Au1rxx-base64 | 169.40.42.35 |
| 75.57 | vless | 288.4 | 746.9 | 21.1 | 0.0 | 8.96 | 8.47 | 19.4 | Au1rxx-base64 | 169.40.42.232 |
| 75.47 | vless | 347.9 | 924.0 | 19.72 | 0.0 | 9.06 | 8.47 | 19.4 | Au1rxx-base64 | 169.40.42.202 |
| 75.3 | vless | 287.8 | 621.5 | 21.12 | 0.0 | 8.98 | 8.47 | 19.4 | Au1rxx-base64 | 169.40.42.89 |
| 75.01 | shadowsocks | 282.9 | 660.0 | 21.23 | 0.0 | 10.0 | 13.48 | 16.76 | Surfboard-tg-mixed | 156.146.38.167 |
| 74.91 | vless | 293.0 | 633.3 | 20.99 | 0.0 | 8.99 | 8.47 | 19.4 | Au1rxx-base64 | 169.40.42.16 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.978 | 0.911 | 248 | 1749 | prefer |
| mheidari-all | 0.856 | 0.781 | 114 | 16452 | prefer |
| Surfboard-tg-mixed | 0.852 | 0.776 | 165 | 7479 | prefer |
| DeltaKronecker-all | 0.66 | 0.688 | 16 | 5187 | observe |
| ermaozi-get_subscribe | 0.644 | 0.636 | 22 | 473 | observe |
| ermaozi | 0.635 | 0.625 | 32 | 442 | observe |
| tg-oneclickvpnkeys | 0.262 | 1.0 | 1 | 180 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4795 | observe |
| Epodonios-all | 0.255 | None | 0 | 7964 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9095 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6181 | observe |
| barry-far-vless | 0.255 | None | 0 | 6404 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4219 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 29 |
| geo | ClientOSError | - | 24 |
| 204 | TimeoutError | - | 23 |
| cn-block | TimeoutError | - | 12 |
| cn-block | ClientOSError | - | 4 |
| speed | ProxyError | - | 4 |
| speed | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 3 |
| geo | TimeoutError | - | 3 |
| speed | ClientOSError | - | 3 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:39336: bind: address already in use | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
