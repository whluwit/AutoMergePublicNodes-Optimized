# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-10 02:59:19 |
| 运行耗时 | 749.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 83752 |
| 去重后节点 | 21985 |
| TCP 可达 | 3000 |
| 真实可用 | 597 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21985 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.4 |
| tcp | 37.4 |
| probe | 286.8 |
| real_test | 336.8 |
| generate | 80.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51277 |
| vmess | 12130 |
| shadowsocks | 9930 |
| trojan | 8077 |
| hysteria2 | 1499 |
| http | 641 |
| shadowsocksr | 126 |
| socks | 52 |
| hysteria | 8 |
| tuic | 8 |
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
| 82.94 | vless | 257.3 | 635.0 | 21.82 | 0.0 | 9.46 | 12.14 | 19.52 | Au1rxx-base64 | 172.233.139.46 |
| 81.27 | shadowsocks | 212.6 | 519.5 | 22.86 | 0.0 | 9.48 | 13.41 | 19.52 | Au1rxx-base64 | 173.244.56.6 |
| 80.01 | shadowsocks | 267.7 | 681.7 | 21.58 | 0.0 | 10.0 | 13.41 | 19.52 | Au1rxx-base64 | 108.181.118.10 |
| 79.97 | shadowsocks | 268.7 | 649.5 | 21.56 | 0.0 | 9.48 | 13.41 | 19.52 | Au1rxx-base64 | 173.244.56.9 |
| 79.83 | shadowsocks | 227.3 | 476.8 | 22.52 | 0.0 | 10.0 | 13.41 | 18.4 | mheidari-all | 108.181.0.177 |
| 79.66 | shadowsocks | 255.9 | 622.6 | 21.85 | 0.0 | 10.0 | 13.41 | 18.4 | mheidari-all | 156.146.38.168 |
| 79.25 | vless | 206.8 | 526.4 | 22.99 | 0.0 | 9.6 | 12.14 | 19.52 | Au1rxx-base64 | 107.173.237.146 |
| 78.98 | vless | 349.7 | 828.5 | 19.68 | 0.0 | 9.64 | 12.14 | 19.52 | Au1rxx-base64 | 51.81.203.63 |
| 78.95 | vless | 354.3 | 860.0 | 19.58 | 0.0 | 9.6 | 12.14 | 19.52 | Au1rxx-base64 | 15.204.97.216 |
| 78.86 | vless | 241.2 | 565.9 | 22.2 | 0.0 | 10.0 | 12.14 | 19.52 | Au1rxx-base64 | 38.244.21.139 |
| 78.21 | shadowsocks | 318.1 | 803.1 | 20.41 | 0.0 | 9.48 | 13.41 | 19.52 | Au1rxx-base64 | 156.146.38.170 |
| 77.12 | trojan | 207.8 | 531.1 | 22.97 | 0.0 | 9.63 | 8.0 | 19.52 | Au1rxx-base64 | 107.150.105.84 |
| 76.8 | shadowsocks | 304.5 | 759.8 | 20.73 | 0.0 | 9.66 | 13.41 | 19.52 | Au1rxx-base64 | 156.146.38.167 |
| 76.78 | shadowsocks | 255.4 | 620.5 | 21.86 | 0.0 | 10.0 | 13.41 | 15.64 | Surfboard-tg-mixed | 156.146.38.169 |
| 76.73 | vless | 254.6 | 562.1 | 21.88 | 0.0 | 9.5 | 12.14 | 19.52 | Au1rxx-base64 | 38.246.229.58 |
| 76.61 | vless | 242.8 | 556.5 | 22.16 | 0.0 | 9.5 | 12.14 | 19.52 | Au1rxx-base64 | 31.58.50.200 |
| 76.6 | shadowsocks | 291.4 | 619.1 | 21.03 | 0.0 | 9.62 | 13.41 | 19.52 | Au1rxx-base64 | 149.22.95.183 |
| 76.13 | shadowsocks | 324.4 | 738.6 | 20.27 | 0.0 | 9.66 | 13.41 | 19.52 | Au1rxx-base64 | 23.150.248.20 |
| 75.55 | trojan | 238.2 | 547.7 | 22.26 | 0.0 | 10.0 | 8.0 | 18.4 | mheidari-all | 100.42.228.109 |
| 75.51 | vless | 356.6 | 695.1 | 19.52 | 0.0 | 10.0 | 12.14 | 19.52 | Au1rxx-base64 | 195.123.235.177 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.956 | 293 | 1545 | prefer |
| Surfboard-tg-mixed | 0.867 | 0.79 | 176 | 7448 | prefer |
| ermaozi | 0.709 | 0.698 | 53 | 449 | prefer |
| mheidari-all | 0.653 | 0.574 | 162 | 16259 | observe |
| ermaozi-get_subscribe | 0.502 | 0.562 | 16 | 469 | observe |
| DeltaKronecker-all | 0.399 | 0.315 | 111 | 5187 | observe |
| tg-oneclickvpnkeys | 0.317 | 1.0 | 2 | 147 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 53 | observe |
| Epodonios-all | 0.255 | None | 0 | 7910 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8678 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6108 | observe |
| barry-far-vless | 0.255 | None | 0 | 6333 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4247 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | TimeoutError | - | 45 |
| geo | ClientOSError | - | 44 |
| geo | TimeoutError | - | 39 |
| 204 | ProxyError | - | 29 |
| speed | ClientOSError | - | 24 |
| cn-block | ClientOSError | - | 11 |
| 204 | TimeoutError | - | 9 |
| cn-block | TimeoutError | - | 9 |
| 204 | ProxyConnectionError | - | 4 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
