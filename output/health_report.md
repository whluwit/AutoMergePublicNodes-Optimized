# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-16 19:06:51 |
| 运行耗时 | 228.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 79647 |
| 去重后节点 | 24641 |
| TCP 可达 | 3000 |
| 真实可用 | 382 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24641 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| geo | 1.5 |
| tcp | 33.2 |
| probe | 48.8 |
| real_test | 103.4 |
| generate | 37.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46404 |
| trojan | 12192 |
| vmess | 10850 |
| shadowsocks | 9645 |
| hysteria2 | 275 |
| shadowsocksr | 130 |
| http | 97 |
| socks | 40 |
| hysteria | 10 |
| tuic | 4 |

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
| 79.33 | shadowsocks | 270.5 | 668.5 | 21.52 | 0.0 | 10.0 | 13.57 | 18.24 | Au1rxx-base64 | 37.19.198.244 |
| 78.97 | shadowsocks | 265.0 | 651.7 | 21.64 | 0.0 | 10.0 | 13.57 | 18.24 | Au1rxx-base64 | 156.146.38.169 |
| 78.7 | shadowsocks | 259.2 | 636.2 | 21.78 | 0.0 | 10.0 | 13.57 | 18.24 | Au1rxx-base64 | 156.146.38.167 |
| 78.26 | shadowsocks | 270.9 | 671.7 | 21.51 | 0.0 | 10.0 | 13.57 | 18.24 | Au1rxx-base64 | 156.146.38.170 |
| 77.66 | shadowsocks | 277.5 | 672.4 | 21.35 | 0.0 | 10.0 | 13.57 | 18.24 | Au1rxx-base64 | 108.181.57.93 |
| 77.39 | shadowsocks | 267.9 | 664.0 | 21.58 | 0.0 | 10.0 | 13.57 | 18.24 | Au1rxx-base64 | 37.19.198.236 |
| 77.05 | shadowsocks | 275.1 | 693.5 | 21.41 | 0.0 | 10.0 | 13.57 | 18.24 | Au1rxx-base64 | 37.19.198.160 |
| 76.95 | shadowsocks | 308.4 | 835.0 | 20.64 | 0.0 | 10.0 | 13.57 | 18.24 | Au1rxx-base64 | 50.114.177.235 |
| 76.62 | shadowsocks | 271.8 | 656.8 | 21.49 | 0.0 | 10.0 | 13.57 | 18.24 | Au1rxx-base64 | 156.146.38.168 |
| 76.18 | shadowsocks | 385.0 | 820.8 | 18.87 | 0.0 | 10.0 | 13.57 | 18.24 | Au1rxx-base64 | 185.196.61.82 |
| 75.47 | shadowsocks | 300.4 | 759.0 | 20.82 | 0.0 | 10.0 | 13.57 | 18.24 | Au1rxx-base64 | 37.19.198.243 |
| 73.98 | shadowsocks | 302.5 | 561.1 | 20.78 | 0.0 | 10.0 | 13.57 | 18.24 | Au1rxx-base64 | 173.244.56.6 |
| 73.4 | shadowsocks | 304.0 | 570.9 | 20.74 | 0.0 | 10.0 | 13.57 | 18.24 | Au1rxx-base64 | 173.244.56.9 |
| 72.71 | shadowsocks | 311.8 | 546.6 | 20.56 | 0.0 | 10.0 | 13.57 | 18.24 | Au1rxx-base64 | 108.181.118.10 |
| 72.61 | shadowsocks | 350.5 | 713.6 | 19.66 | 0.0 | 10.0 | 13.57 | 18.24 | Au1rxx-base64 | 108.181.0.177 |
| 69.99 | vless | 283.6 | 693.2 | 21.21 | 0.0 | 10.0 | 2.54 | 18.24 | Au1rxx-base64 | 47.89.186.170 |
| 69.96 | shadowsocks | 289.1 | 698.9 | 21.09 | 0.0 | 10.0 | 13.57 | 18.24 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |
| 69.63 | shadowsocks | 289.2 | 561.4 | 21.08 | 0.0 | 10.0 | 13.57 | 18.24 | Au1rxx-base64 | 149.22.95.183 |
| 68.25 | shadowsocks | 551.8 | 1139.4 | 15.01 | 0.0 | 10.0 | 13.57 | 18.24 | Au1rxx-base64 | 68.168.222.210 |
| 67.95 | shadowsocks | 392.9 | 418.2 | 18.68 | 0.0 | 9.48 | 13.57 | 18.24 | Au1rxx-base64 | 149.22.87.241 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.915 | 0.917 | 108 | 149 | prefer |
| DeltaKronecker-all | 0.799 | 0.721 | 226 | 8462 | prefer |
| Surfboard-tg-mixed | 0.58 | 0.5 | 156 | 5554 | observe |
| xiaoji235-airport-v2ray-all | 0.325 | 1.0 | 1 | 1757 | observe |
| mheidari-all | 0.324 | 0.375 | 8 | 16694 | observe |
| nscl5-all | 0.316 | 1.0 | 1 | 1519 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4470 | observe |
| Epodonios-all | 0.255 | None | 0 | 6586 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3971 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6877 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4319 | observe |
| barry-far-vless | 0.255 | None | 0 | 4954 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5260 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 61 |
| speed | ClientOSError | - | 50 |
| 204 | TimeoutError | - | 19 |
| cn-block | TimeoutError | - | 10 |
| 204 | ProxyError | - | 4 |
| speed | TimeoutError | - | 4 |
| geo | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| cn-block | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
