# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-09 19:40:57 |
| 运行耗时 | 179.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 78769 |
| 去重后节点 | 23876 |
| TCP 可达 | 3000 |
| 真实可用 | 224 |
| Verified 输出 | 224 |
| Global 输出 | 234 |
| All 输出 | 23876 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| geo | 1.4 |
| tcp | 31.9 |
| probe | 47.0 |
| real_test | 67.4 |
| generate | 27.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45000 |
| trojan | 12568 |
| vmess | 10589 |
| shadowsocks | 9358 |
| hysteria2 | 841 |
| shadowsocksr | 148 |
| http | 135 |
| socks | 113 |
| hysteria | 10 |
| anytls | 5 |
| tuic | 2 |

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
| 80.83 | shadowsocks | 232.3 | 630.2 | 22.4 | 0.0 | 10.0 | 13.73 | 18.7 | Au1rxx-base64 | 37.19.198.160 |
| 80.66 | shadowsocks | 239.7 | 649.2 | 22.23 | 0.0 | 10.0 | 13.73 | 18.7 | Au1rxx-base64 | 37.19.198.243 |
| 80.61 | shadowsocks | 241.6 | 659.9 | 22.18 | 0.0 | 10.0 | 13.73 | 18.7 | Au1rxx-base64 | 37.19.198.236 |
| 80.54 | shadowsocks | 231.6 | 620.7 | 22.42 | 0.0 | 10.0 | 13.73 | 18.7 | Au1rxx-base64 | 147.90.234.133 |
| 79.88 | shadowsocks | 251.9 | 649.9 | 21.95 | 0.0 | 10.0 | 13.73 | 18.7 | Au1rxx-base64 | 108.181.57.93 |
| 79.82 | shadowsocks | 276.0 | 762.2 | 21.39 | 0.0 | 10.0 | 13.73 | 18.7 | Au1rxx-base64 | 198.98.53.130 |
| 79.37 | shadowsocks | 295.4 | 831.3 | 20.94 | 0.0 | 10.0 | 13.73 | 18.7 | Au1rxx-base64 | 37.19.198.244 |
| 79.35 | shadowsocks | 296.3 | 820.9 | 20.92 | 0.0 | 10.0 | 13.73 | 18.7 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |
| 76.88 | shadowsocks | 280.6 | 638.7 | 21.28 | 0.0 | 10.0 | 13.73 | 18.7 | Au1rxx-base64 | 156.146.38.167 |
| 76.75 | shadowsocks | 282.1 | 655.1 | 21.25 | 0.0 | 10.0 | 13.73 | 18.7 | Au1rxx-base64 | 156.146.38.168 |
| 76.4 | shadowsocks | 324.0 | 767.6 | 20.28 | 0.0 | 10.0 | 13.73 | 18.7 | Au1rxx-base64 | 156.146.38.169 |
| 73.68 | shadowsocks | 354.3 | 889.8 | 19.58 | 0.0 | 10.0 | 13.73 | 18.7 | Au1rxx-base64 | 185.196.61.82 |
| 73.66 | shadowsocks | 317.7 | 559.9 | 20.42 | 0.0 | 10.0 | 13.73 | 18.7 | Au1rxx-base64 | 173.244.56.6 |
| 73.55 | trojan | 338.2 | 778.1 | 19.95 | 0.0 | 10.0 | 10.22 | 18.7 | Au1rxx-base64 | 45.32.195.168 |
| 73.46 | shadowsocks | 325.7 | 555.1 | 20.24 | 0.0 | 10.0 | 13.73 | 18.7 | Au1rxx-base64 | 173.244.56.9 |
| 73.0 | shadowsocks | 316.2 | 559.1 | 20.46 | 0.0 | 10.0 | 13.73 | 18.7 | Au1rxx-base64 | 108.181.0.177 |
| 72.57 | shadowsocks | 320.9 | 562.5 | 20.35 | 0.0 | 10.0 | 13.73 | 18.7 | Au1rxx-base64 | 108.181.118.10 |
| 72.43 | trojan | 347.9 | 771.0 | 19.73 | 0.0 | 10.0 | 10.22 | 18.7 | Au1rxx-base64 | 149.28.241.235 |
| 71.92 | shadowsocks | 286.5 | 649.8 | 21.15 | 0.0 | 10.0 | 13.73 | 18.7 | Au1rxx-base64 | 156.146.38.170 |
| 71.65 | shadowsocks | 345.7 | 646.6 | 19.78 | 0.0 | 10.0 | 13.73 | 18.7 | Au1rxx-base64 | 149.22.95.183 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.899 | 0.926 | 27 | 66 | prefer |
| Surfboard-tg-mixed | 0.629 | 0.55 | 222 | 5585 | observe |
| DeltaKronecker-all | 0.594 | 0.515 | 68 | 7533 | observe |
| xiaoji235-airport-v2ray-all | 0.438 | 1.0 | 3 | 2703 | observe |
| nscl5-all | 0.364 | 1.0 | 2 | 1319 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4306 | observe |
| Epodonios-all | 0.255 | None | 0 | 6500 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3974 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6851 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4106 | observe |
| barry-far-vless | 0.255 | None | 0 | 4741 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5403 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 68 |
| 204 | TimeoutError | - | 24 |
| geo | TimeoutError | - | 12 |
| geo | ClientOSError | - | 10 |
| 204 | ProxyError | - | 8 |
| 204 | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 6 |
| cn-block | TimeoutError | - | 5 |
| speed | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| geo | ProxyError | - | 2 |
| speed | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 224 | - |
| global | False | 300 | 234 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
