# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-15 03:05:00 |
| 运行耗时 | 670.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 98773 |
| 去重后节点 | 27498 |
| TCP 可达 | 3000 |
| 真实可用 | 377 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27498 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| geo | 1.5 |
| tcp | 46.9 |
| probe | 240.5 |
| real_test | 298.8 |
| generate | 75.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58407 |
| vmess | 16297 |
| shadowsocks | 11795 |
| trojan | 10179 |
| hysteria2 | 1151 |
| http | 657 |
| shadowsocksr | 164 |
| socks | 68 |
| anytls | 32 |
| hysteria | 17 |
| tuic | 6 |

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
| 82.24 | hysteria2 | 255.5 | 697.4 | 21.86 | 0.0 | 10.0 | 13.64 | 18.24 | Au1rxx-base64 | 129.213.91.185 |
| 81.7 | vless | 259.4 | 701.0 | 21.77 | 0.0 | 10.0 | 11.69 | 18.24 | Au1rxx-base64 | 159.89.87.21 |
| 81.08 | vless | 286.5 | 688.1 | 21.15 | 0.0 | 10.0 | 11.69 | 18.24 | Au1rxx-base64 | 169.40.42.35 |
| 80.27 | vless | 321.2 | 806.1 | 20.34 | 0.0 | 10.0 | 11.69 | 18.24 | Au1rxx-base64 | 169.40.42.212 |
| 80.12 | shadowsocks | 250.9 | 697.9 | 21.97 | 0.0 | 10.0 | 13.91 | 18.24 | Au1rxx-base64 | 37.19.198.236 |
| 80.11 | shadowsocks | 251.3 | 698.7 | 21.96 | 0.0 | 10.0 | 13.91 | 18.24 | Au1rxx-base64 | 37.19.198.244 |
| 80.03 | shadowsocks | 254.7 | 707.3 | 21.88 | 0.0 | 10.0 | 13.91 | 18.24 | Au1rxx-base64 | 37.19.198.160 |
| 79.98 | shadowsocks | 257.0 | 718.7 | 21.83 | 0.0 | 10.0 | 13.91 | 18.24 | Au1rxx-base64 | 37.19.198.243 |
| 79.97 | vless | 291.1 | 696.8 | 21.04 | 0.0 | 10.0 | 11.69 | 18.24 | Au1rxx-base64 | 193.233.202.250 |
| 79.86 | vless | 339.0 | 944.6 | 19.93 | 0.0 | 10.0 | 11.69 | 18.24 | Au1rxx-base64 | 185.95.231.156 |
| 79.85 | vless | 296.3 | 668.5 | 20.92 | 0.0 | 10.0 | 11.69 | 18.24 | Au1rxx-base64 | 169.40.42.229 |
| 79.79 | shadowsocks | 243.4 | 665.3 | 22.14 | 0.0 | 10.0 | 13.91 | 18.24 | Au1rxx-base64 | 140.82.63.79 |
| 79.57 | vless | 351.4 | 844.0 | 19.64 | 0.0 | 10.0 | 11.69 | 18.24 | Au1rxx-base64 | 169.40.42.184 |
| 79.52 | vless | 353.8 | 956.7 | 19.59 | 0.0 | 10.0 | 11.69 | 18.24 | Au1rxx-base64 | 169.40.42.173 |
| 79.47 | vless | 355.9 | 852.8 | 19.54 | 0.0 | 10.0 | 11.69 | 18.24 | Au1rxx-base64 | 169.40.42.168 |
| 79.43 | vless | 357.8 | 925.6 | 19.5 | 0.0 | 10.0 | 11.69 | 18.24 | Au1rxx-base64 | 169.40.42.90 |
| 79.16 | vless | 267.7 | 648.9 | 21.58 | 0.0 | 10.0 | 11.69 | 18.24 | Au1rxx-base64 | 169.40.42.74 |
| 78.74 | vless | 257.7 | 685.5 | 21.81 | 0.0 | 10.0 | 11.69 | 18.24 | Au1rxx-base64 | 195.123.235.183 |
| 78.21 | vless | 262.5 | 639.5 | 21.7 | 0.0 | 10.0 | 11.69 | 18.24 | Au1rxx-base64 | 169.40.42.235 |
| 78.03 | vless | 341.1 | 726.1 | 19.88 | 0.0 | 10.0 | 11.69 | 18.24 | Au1rxx-base64 | 5.34.178.120 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.944 | 0.884 | 344 | 1564 | prefer |
| DeltaKronecker-all | 0.446 | 0.625 | 8 | 4803 | observe |
| ermaozi | 0.438 | 0.407 | 59 | 703 | observe |
| mheidari-all | 0.316 | 0.233 | 180 | 23886 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5125 | observe |
| Epodonios-all | 0.255 | None | 0 | 7681 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9909 | observe |
| Surfboard-tg-mixed | 0.255 | 0.222 | 9 | 7169 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5728 | observe |
| barry-far-vless | 0.255 | None | 0 | 5978 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4271 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.238 | None | 0 | 1564 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 101 |
| speed | ClientOSError | - | 29 |
| 204 | ProxyError | - | 27 |
| geo | ClientOSError | - | 25 |
| 204 | ProxyConnectionError | - | 11 |
| speed | TimeoutError | - | 10 |
| 204 | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| cn-block | TimeoutError | - | 2 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
