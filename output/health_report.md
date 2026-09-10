# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-10 20:31:51 |
| 运行耗时 | 642.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 83485 |
| 去重后节点 | 22832 |
| TCP 可达 | 3000 |
| 真实可用 | 393 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22832 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| geo | 1.4 |
| tcp | 39.2 |
| probe | 282.2 |
| real_test | 239.0 |
| generate | 75.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50628 |
| vmess | 12527 |
| shadowsocks | 9803 |
| trojan | 8061 |
| hysteria2 | 1698 |
| http | 567 |
| shadowsocksr | 124 |
| socks | 55 |
| tuic | 10 |
| hysteria | 8 |
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
| 77.7 | hysteria2 | 274.5 | 606.8 | 21.42 | 0.0 | 10.0 | 11.43 | 17.46 | Au1rxx-base64 | 66.94.121.46 |
| 76.92 | vless | 256.4 | 640.6 | 21.84 | 0.0 | 10.0 | 9.13 | 17.46 | Au1rxx-base64 | 38.180.242.205 |
| 75.27 | vless | 313.2 | 744.4 | 20.53 | 0.0 | 10.0 | 9.13 | 17.46 | Au1rxx-base64 | 47.253.226.114 |
| 74.74 | shadowsocks | 310.2 | 728.3 | 20.6 | 0.0 | 10.0 | 13.73 | 16.1 | Surfboard-tg-mixed | 37.19.198.244 |
| 74.53 | shadowsocks | 245.7 | 605.2 | 22.09 | 0.0 | 10.0 | 13.73 | 16.1 | Surfboard-tg-mixed | 156.146.38.167 |
| 74.53 | vless | 308.1 | 738.7 | 20.65 | 0.0 | 10.0 | 9.13 | 17.46 | Au1rxx-base64 | 79.141.172.154 |
| 73.64 | vless | 309.2 | 675.1 | 20.62 | 0.0 | 10.0 | 9.13 | 17.46 | Au1rxx-base64 | 195.123.235.177 |
| 73.37 | vless | 352.5 | 729.1 | 19.62 | 0.0 | 10.0 | 9.13 | 17.46 | Au1rxx-base64 | 169.40.42.224 |
| 73.26 | shadowsocks | 311.9 | 734.4 | 20.56 | 0.0 | 10.0 | 13.73 | 16.1 | Surfboard-tg-mixed | 37.19.198.236 |
| 73.07 | vless | 294.1 | 565.9 | 20.97 | 0.0 | 10.0 | 9.13 | 17.46 | Au1rxx-base64 | 172.235.43.210 |
| 73.01 | vless | 368.6 | 751.3 | 19.25 | 0.0 | 10.0 | 9.13 | 17.46 | Au1rxx-base64 | 169.40.42.35 |
| 72.75 | vless | 325.5 | 664.3 | 20.24 | 0.0 | 10.0 | 9.13 | 17.46 | Au1rxx-base64 | 38.209.125.45 |
| 72.29 | vless | 323.2 | 631.4 | 20.3 | 0.0 | 10.0 | 9.13 | 17.46 | Au1rxx-base64 | 172.235.38.85 |
| 72.06 | shadowsocks | 263.8 | 695.2 | 21.67 | 0.0 | 10.0 | 13.73 | 10.66 | mheidari-all | 156.146.38.169 |
| 71.92 | shadowsocks | 414.4 | 1066.0 | 18.19 | 0.0 | 10.0 | 13.73 | 17.46 | Au1rxx-base64 | 15.204.247.206 |
| 71.91 | vless | 280.2 | 678.7 | 21.29 | 0.0 | 10.0 | 9.13 | 17.46 | Au1rxx-base64 | 188.137.243.243 |
| 71.85 | shadowsocks | 272.9 | 683.6 | 21.46 | 0.0 | 10.0 | 13.73 | 10.66 | mheidari-all | 156.146.38.168 |
| 71.77 | shadowsocks | 329.4 | 732.1 | 20.15 | 0.0 | 10.0 | 13.73 | 16.1 | Surfboard-tg-mixed | 108.181.57.93 |
| 71.71 | shadowsocks | 304.9 | 588.3 | 20.72 | 0.0 | 10.0 | 13.73 | 16.1 | Surfboard-tg-mixed | 173.244.56.9 |
| 71.69 | shadowsocks | 295.4 | 568.7 | 20.94 | 0.0 | 10.0 | 13.73 | 16.1 | Surfboard-tg-mixed | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.934 | 0.872 | 257 | 1642 | prefer |
| ermaozi | 0.856 | 0.87 | 23 | 405 | prefer |
| DeltaKronecker-all | 0.853 | 0.938 | 16 | 5853 | prefer |
| Surfboard-tg-mixed | 0.758 | 0.681 | 144 | 7221 | prefer |
| mheidari-all | 0.715 | 0.64 | 50 | 15823 | prefer |
| tg-oneclickvpnkeys | 0.319 | 1.0 | 2 | 194 | observe |
| roosterkid-openproxylist-v2ray | 0.275 | 0.667 | 3 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4995 | observe |
| Epodonios-all | 0.255 | None | 0 | 7677 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8881 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5840 | observe |
| barry-far-vless | 0.255 | None | 0 | 6058 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4255 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 21 |
| 204 | TimeoutError | - | 21 |
| cn-block | TimeoutError | - | 16 |
| 204 | ProxyError | - | 13 |
| cn-block | ClientOSError | - | 13 |
| geo | TimeoutError | - | 10 |
| 204 | ClientOSError | - | 6 |
| speed | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
