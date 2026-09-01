# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-01 16:03:30 |
| 运行耗时 | 323.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 84240 |
| 去重后节点 | 24694 |
| TCP 可达 | 3000 |
| 真实可用 | 609 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24694 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.4 |
| tcp | 41.0 |
| probe | 89.4 |
| real_test | 131.4 |
| generate | 54.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52683 |
| vmess | 11786 |
| shadowsocks | 10312 |
| trojan | 7676 |
| hysteria2 | 1399 |
| http | 145 |
| shadowsocksr | 130 |
| socks | 86 |
| hysteria | 9 |
| tuic | 9 |
| anytls | 5 |

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
| 81.51 | vless | 253.4 | 646.4 | 21.91 | 0.0 | 10.0 | 11.64 | 17.96 | Au1rxx-base64 | 137.184.218.169 |
| 81.48 | vless | 254.9 | 657.9 | 21.88 | 0.0 | 10.0 | 11.64 | 17.96 | Au1rxx-base64 | 204.48.20.223 |
| 81.41 | vless | 257.7 | 658.7 | 21.81 | 0.0 | 10.0 | 11.64 | 17.96 | Au1rxx-base64 | 167.17.69.171 |
| 80.85 | vless | 270.8 | 661.4 | 21.51 | 0.0 | 10.0 | 11.64 | 17.96 | Au1rxx-base64 | 172.105.104.54 |
| 79.98 | vless | 319.5 | 833.9 | 20.38 | 0.0 | 10.0 | 11.64 | 17.96 | Au1rxx-base64 | 169.40.42.212 |
| 79.95 | vless | 302.5 | 644.3 | 20.78 | 0.0 | 10.0 | 11.64 | 17.96 | Au1rxx-base64 | 169.40.42.173 |
| 79.68 | vless | 273.2 | 634.6 | 21.45 | 0.0 | 10.0 | 11.64 | 17.96 | Au1rxx-base64 | 195.211.99.45 |
| 79.09 | vless | 301.6 | 619.8 | 20.8 | 0.0 | 10.0 | 11.64 | 17.96 | Au1rxx-base64 | 195.211.99.49 |
| 79.06 | vless | 269.5 | 667.7 | 21.54 | 0.0 | 10.0 | 11.64 | 17.96 | Au1rxx-base64 | 169.40.42.179 |
| 79.0 | vless | 362.1 | 966.7 | 19.4 | 0.0 | 10.0 | 11.64 | 17.96 | Au1rxx-base64 | 169.40.42.182 |
| 78.84 | vless | 369.0 | 971.6 | 19.24 | 0.0 | 10.0 | 11.64 | 17.96 | Au1rxx-base64 | 169.40.42.52 |
| 78.74 | vless | 373.3 | 985.5 | 19.14 | 0.0 | 10.0 | 11.64 | 17.96 | Au1rxx-base64 | 185.95.231.156 |
| 77.84 | shadowsocks | 245.0 | 645.0 | 22.11 | 0.0 | 10.0 | 13.2 | 17.96 | Au1rxx-base64 | 37.19.198.244 |
| 77.55 | vless | 338.0 | 834.5 | 19.95 | 0.0 | 10.0 | 11.64 | 17.96 | Au1rxx-base64 | 66.70.179.198 |
| 77.5 | vless | 350.0 | 862.7 | 19.68 | 0.0 | 10.0 | 11.64 | 17.96 | Au1rxx-base64 | 169.40.42.163 |
| 77.12 | vless | 308.9 | 688.7 | 20.63 | 0.0 | 10.0 | 11.64 | 17.96 | Au1rxx-base64 | 169.40.42.16 |
| 76.81 | vless | 306.7 | 702.1 | 20.68 | 0.0 | 10.0 | 11.64 | 17.96 | Au1rxx-base64 | 169.40.42.89 |
| 76.64 | vless | 313.7 | 771.2 | 20.52 | 0.0 | 10.0 | 11.64 | 17.96 | Au1rxx-base64 | 169.40.42.232 |
| 76.64 | vless | 363.4 | 887.4 | 19.37 | 0.0 | 10.0 | 11.64 | 17.96 | Au1rxx-base64 | 216.152.147.28 |
| 76.39 | vless | 335.6 | 868.8 | 20.01 | 0.0 | 10.0 | 11.64 | 17.96 | Au1rxx-base64 | 169.40.42.202 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.982 | 0.914 | 383 | 1760 | prefer |
| zhangkai | 0.886 | 0.913 | 23 | 144 | prefer |
| mheidari-all | 0.853 | 0.777 | 148 | 17557 | prefer |
| Surfboard-tg-mixed | 0.798 | 0.72 | 168 | 6964 | prefer |
| DeltaKronecker-all | 0.287 | 0.5 | 2 | 7294 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4708 | observe |
| Epodonios-all | 0.255 | None | 0 | 7367 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8076 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5838 | observe |
| barry-far-vless | 0.255 | None | 0 | 6013 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4013 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1760 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 28 |
| cn-block | TimeoutError | - | 23 |
| cn-block | ClientOSError | - | 17 |
| geo | ClientOSError | - | 10 |
| speed | ClientOSError | - | 8 |
| 204 | ProxyError | - | 8 |
| 204 | ProxyConnectionError | - | 7 |
| speed | TimeoutError | - | 5 |
| geo | TimeoutError | - | 5 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
