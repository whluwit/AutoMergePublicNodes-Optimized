# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-08 02:51:44 |
| 运行耗时 | 393.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 91466 |
| 去重后节点 | 25342 |
| TCP 可达 | 3000 |
| 真实可用 | 715 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25342 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.7 |
| tcp | 41.4 |
| probe | 94.6 |
| real_test | 205.5 |
| generate | 43.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57452 |
| vmess | 12157 |
| shadowsocks | 10321 |
| trojan | 9043 |
| hysteria2 | 1775 |
| http | 503 |
| shadowsocksr | 118 |
| socks | 48 |
| anytls | 20 |
| hysteria | 16 |
| tuic | 13 |

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
| 84.21 | vless | 256.7 | 659.7 | 21.84 | 0.0 | 10.0 | 12.37 | 20.0 | Au1rxx-base64 | 169.40.42.179 |
| 83.65 | vless | 280.6 | 657.3 | 21.28 | 0.0 | 10.0 | 12.37 | 20.0 | Au1rxx-base64 | 169.40.42.225 |
| 83.61 | vless | 282.5 | 630.4 | 21.24 | 0.0 | 10.0 | 12.37 | 20.0 | Au1rxx-base64 | 169.40.42.133 |
| 83.58 | vless | 283.6 | 753.7 | 21.21 | 0.0 | 10.0 | 12.37 | 20.0 | Au1rxx-base64 | 169.40.42.163 |
| 83.57 | vless | 284.0 | 636.6 | 21.2 | 0.0 | 10.0 | 12.37 | 20.0 | Au1rxx-base64 | 169.40.42.235 |
| 83.43 | vless | 290.1 | 651.4 | 21.06 | 0.0 | 10.0 | 12.37 | 20.0 | Au1rxx-base64 | 169.40.42.15 |
| 83.39 | vless | 291.9 | 649.2 | 21.02 | 0.0 | 10.0 | 12.37 | 20.0 | Au1rxx-base64 | 169.40.42.224 |
| 83.31 | vless | 252.1 | 661.8 | 21.94 | 0.0 | 10.0 | 12.37 | 20.0 | Au1rxx-base64 | 195.123.235.177 |
| 83.28 | vless | 296.8 | 819.8 | 20.91 | 0.0 | 10.0 | 12.37 | 20.0 | Au1rxx-base64 | 137.184.218.169 |
| 82.84 | vless | 315.5 | 800.8 | 20.47 | 0.0 | 10.0 | 12.37 | 20.0 | Au1rxx-base64 | 66.70.179.198 |
| 82.57 | vless | 327.3 | 884.5 | 20.2 | 0.0 | 10.0 | 12.37 | 20.0 | Au1rxx-base64 | 167.17.69.171 |
| 82.49 | vless | 331.0 | 885.0 | 20.12 | 0.0 | 10.0 | 12.37 | 20.0 | Au1rxx-base64 | 169.40.42.231 |
| 82.48 | vless | 331.3 | 896.9 | 20.11 | 0.0 | 10.0 | 12.37 | 20.0 | Au1rxx-base64 | 169.40.42.182 |
| 82.38 | vless | 265.4 | 635.9 | 21.63 | 0.0 | 10.0 | 12.37 | 20.0 | Au1rxx-base64 | 169.40.42.35 |
| 82.37 | vless | 335.9 | 858.4 | 20.0 | 0.0 | 10.0 | 12.37 | 20.0 | Au1rxx-base64 | 169.40.42.232 |
| 82.32 | vless | 279.4 | 696.4 | 21.31 | 0.0 | 10.0 | 12.37 | 20.0 | Au1rxx-base64 | 169.40.42.184 |
| 82.24 | vless | 341.8 | 931.6 | 19.87 | 0.0 | 10.0 | 12.37 | 20.0 | Au1rxx-base64 | 169.40.42.212 |
| 82.19 | vless | 343.7 | 931.4 | 19.82 | 0.0 | 10.0 | 12.37 | 20.0 | Au1rxx-base64 | 169.40.42.168 |
| 82.16 | vless | 345.0 | 807.9 | 19.79 | 0.0 | 10.0 | 12.37 | 20.0 | Au1rxx-base64 | 169.40.42.223 |
| 82.01 | shadowsocks | 232.8 | 644.9 | 22.39 | 0.0 | 10.0 | 13.62 | 20.0 | Au1rxx-base64 | 37.19.198.236 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.995 | 1.0 | 41 | 450 | prefer |
| Au1rxx-base64 | 0.951 | 0.88 | 375 | 1834 | prefer |
| Surfboard-tg-mixed | 0.924 | 0.851 | 94 | 7423 | prefer |
| ermaozi-get_subscribe | 0.907 | 1.0 | 18 | 470 | prefer |
| DeltaKronecker-all | 0.495 | 0.412 | 80 | 6417 | observe |
| mheidari-all | 0.377 | 0.297 | 714 | 22287 | observe |
| tg-oneclickvpnkeys | 0.263 | 1.0 | 1 | 196 | observe |
| Epodonios-all | 0.255 | None | 0 | 7885 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8454 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6226 | observe |
| barry-far-vless | 0.255 | None | 0 | 6444 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4218 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1834 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 198 |
| speed | TimeoutError | - | 96 |
| speed | ClientOSError | - | 95 |
| geo | ClientOSError | - | 92 |
| cn-block | ClientOSError | - | 73 |
| cn-block | TimeoutError | - | 21 |
| 204 | TimeoutError | - | 12 |
| 204 | ProxyError | - | 12 |
| 204 | ClientOSError | - | 9 |
| cn-block | ProxyError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
