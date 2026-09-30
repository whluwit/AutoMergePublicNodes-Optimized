# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-30 21:55:22 |
| 运行耗时 | 457.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97984 |
| 去重后节点 | 27231 |
| TCP 可达 | 3000 |
| 真实可用 | 439 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27231 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 1.4 |
| tcp | 45.5 |
| probe | 190.3 |
| real_test | 143.5 |
| generate | 71.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 60183 |
| vmess | 15243 |
| shadowsocks | 11364 |
| trojan | 9112 |
| hysteria2 | 1348 |
| http | 440 |
| shadowsocksr | 171 |
| socks | 68 |
| anytls | 32 |
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
| 81.02 | vless | 235.1 | 608.1 | 22.33 | 0.0 | 10.0 | 10.91 | 17.78 | Au1rxx-base64 | 195.123.235.177 |
| 80.9 | hysteria2 | 311.6 | 860.1 | 20.56 | 0.0 | 10.0 | 14.06 | 17.38 | mheidari-all | 159.223.157.129 |
| 80.36 | vless | 263.8 | 694.7 | 21.67 | 0.0 | 10.0 | 10.91 | 17.78 | Au1rxx-base64 | 169.40.42.133 |
| 79.51 | vless | 300.6 | 742.8 | 20.82 | 0.0 | 10.0 | 10.91 | 17.78 | Au1rxx-base64 | 169.40.42.231 |
| 79.42 | vless | 304.3 | 690.3 | 20.73 | 0.0 | 10.0 | 10.91 | 17.78 | Au1rxx-base64 | 169.40.42.90 |
| 79.22 | vless | 313.0 | 715.5 | 20.53 | 0.0 | 10.0 | 10.91 | 17.78 | Au1rxx-base64 | 169.40.42.224 |
| 79.17 | vless | 296.0 | 715.7 | 20.92 | 0.0 | 10.0 | 10.91 | 17.78 | Au1rxx-base64 | 167.17.69.171 |
| 78.85 | shadowsocks | 257.5 | 710.4 | 21.82 | 0.0 | 10.0 | 13.25 | 17.78 | Au1rxx-base64 | 37.19.198.236 |
| 78.64 | shadowsocks | 244.7 | 678.7 | 22.11 | 0.0 | 10.0 | 13.25 | 17.78 | Au1rxx-base64 | 140.82.63.79 |
| 78.59 | vless | 340.2 | 923.0 | 19.9 | 0.0 | 10.0 | 10.91 | 17.78 | Au1rxx-base64 | 169.40.42.35 |
| 78.59 | vless | 340.2 | 890.5 | 19.9 | 0.0 | 10.0 | 10.91 | 17.78 | Au1rxx-base64 | 66.70.179.198 |
| 78.57 | vless | 341.1 | 889.4 | 19.88 | 0.0 | 10.0 | 10.91 | 17.78 | Au1rxx-base64 | 169.40.42.74 |
| 78.54 | vless | 342.4 | 880.6 | 19.85 | 0.0 | 10.0 | 10.91 | 17.78 | Au1rxx-base64 | 169.40.42.89 |
| 78.48 | shadowsocks | 256.0 | 710.5 | 21.85 | 0.0 | 10.0 | 13.25 | 17.38 | mheidari-all | 37.19.198.244 |
| 78.24 | vless | 266.3 | 629.5 | 21.61 | 0.0 | 10.0 | 10.91 | 17.38 | mheidari-all | 216.227.161.95 |
| 78.15 | vless | 283.7 | 629.7 | 21.21 | 0.0 | 10.0 | 10.91 | 17.78 | Au1rxx-base64 | 169.40.42.163 |
| 77.99 | vless | 366.2 | 883.4 | 19.3 | 0.0 | 10.0 | 10.91 | 17.78 | Au1rxx-base64 | 169.40.42.168 |
| 77.77 | shadowsocks | 260.6 | 716.5 | 21.74 | 0.0 | 10.0 | 13.25 | 17.78 | Au1rxx-base64 | 37.19.198.243 |
| 77.73 | hysteria2 | 294.3 | 585.0 | 20.97 | 0.0 | 10.0 | 14.06 | 17.78 | Au1rxx-base64 | 192.255.128.123 |
| 77.63 | vless | 382.0 | 923.9 | 18.94 | 0.0 | 10.0 | 10.91 | 17.78 | Au1rxx-base64 | 169.40.42.104 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.911 | 0.841 | 334 | 1803 | prefer |
| Surfboard-tg-mixed | 0.911 | 0.841 | 63 | 7200 | prefer |
| mheidari-all | 0.909 | 0.835 | 103 | 22901 | prefer |
| zhangkai | 0.76 | 1.0 | 14 | 144 | prefer |
| DeltaKronecker-all | 0.287 | 0.5 | 2 | 5434 | observe |
| tg-oneclickvpnkeys | 0.257 | 1.0 | 1 | 50 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7696 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9724 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5833 | observe |
| barry-far-vless | 0.255 | None | 0 | 6072 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4183 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ermaozi-get_subscribe | 0.248 | 0.333 | 9 | 362 | downweight |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 43 |
| cn-block | TimeoutError | - | 12 |
| 204 | ProxyError | - | 11 |
| 204 | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 5 |
| speed | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
