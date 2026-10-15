# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-15 10:59:06 |
| 运行耗时 | 820.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99768 |
| 去重后节点 | 27804 |
| TCP 可达 | 3000 |
| 真实可用 | 419 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27804 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| geo | 1.5 |
| tcp | 47.7 |
| probe | 297.9 |
| real_test | 320.5 |
| generate | 144.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58945 |
| vmess | 16426 |
| shadowsocks | 12051 |
| trojan | 10183 |
| hysteria2 | 1166 |
| http | 706 |
| shadowsocksr | 170 |
| socks | 66 |
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
| 81.77 | hysteria2 | 276.0 | 707.1 | 21.39 | 0.0 | 10.0 | 13.0 | 18.88 | Au1rxx-base64 | 129.213.91.185 |
| 80.27 | shadowsocks | 282.8 | 730.7 | 21.23 | 0.0 | 10.0 | 14.16 | 18.88 | Au1rxx-base64 | 37.19.198.236 |
| 80.23 | shadowsocks | 284.8 | 737.9 | 21.19 | 0.0 | 10.0 | 14.16 | 18.88 | Au1rxx-base64 | 37.19.198.160 |
| 79.62 | shadowsocks | 311.1 | 817.0 | 20.58 | 0.0 | 10.0 | 14.16 | 18.88 | Au1rxx-base64 | 37.19.198.244 |
| 79.25 | shadowsocks | 305.4 | 772.1 | 20.71 | 0.0 | 10.0 | 14.16 | 18.88 | Au1rxx-base64 | 51.222.136.236 |
| 78.93 | shadowsocks | 340.6 | 902.0 | 19.89 | 0.0 | 10.0 | 14.16 | 18.88 | Au1rxx-base64 | 37.19.198.243 |
| 76.6 | vless | 270.6 | 635.0 | 21.51 | 0.0 | 10.0 | 6.75 | 18.88 | Au1rxx-base64 | 195.211.98.43 |
| 75.22 | vless | 261.2 | 634.6 | 21.73 | 0.0 | 10.0 | 6.75 | 18.88 | Au1rxx-base64 | 195.123.235.183 |
| 74.54 | shadowsocks | 326.5 | 685.9 | 20.22 | 0.0 | 10.0 | 14.16 | 18.88 | Au1rxx-base64 | 156.146.38.170 |
| 74.49 | shadowsocks | 324.5 | 682.0 | 20.27 | 0.0 | 10.0 | 14.16 | 18.88 | Au1rxx-base64 | 156.146.38.168 |
| 74.43 | shadowsocks | 326.4 | 688.5 | 20.22 | 0.0 | 10.0 | 14.16 | 18.88 | Au1rxx-base64 | 156.146.38.167 |
| 74.31 | vless | 392.8 | 1031.4 | 18.68 | 0.0 | 10.0 | 6.75 | 18.88 | Au1rxx-base64 | 185.95.231.156 |
| 74.15 | vless | 306.3 | 745.4 | 20.69 | 0.0 | 10.0 | 6.75 | 18.88 | Au1rxx-base64 | 159.89.87.21 |
| 73.85 | vless | 381.0 | 897.9 | 18.96 | 0.0 | 10.0 | 6.75 | 18.88 | Au1rxx-base64 | 169.40.42.90 |
| 73.8 | shadowsocks | 358.7 | 785.8 | 19.47 | 0.0 | 10.0 | 14.16 | 18.88 | Au1rxx-base64 | 156.146.38.169 |
| 72.01 | shadowsocks | 362.5 | 646.6 | 19.39 | 0.0 | 10.0 | 14.16 | 18.88 | Au1rxx-base64 | 173.244.56.6 |
| 71.78 | trojan | 446.9 | 1196.7 | 17.43 | 0.0 | 10.0 | 13.47 | 18.88 | Au1rxx-base64 | 69.164.240.85 |
| 71.76 | vless | 287.3 | 719.4 | 21.13 | 0.0 | 10.0 | 6.75 | 18.88 | Au1rxx-base64 | 66.70.179.198 |
| 71.63 | shadowsocks | 369.5 | 643.5 | 19.23 | 0.0 | 10.0 | 14.16 | 18.88 | Au1rxx-base64 | 173.244.56.9 |
| 70.57 | vless | 367.4 | 786.9 | 19.27 | 0.0 | 10.0 | 6.75 | 18.88 | Au1rxx-base64 | 51.79.31.36 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.866 | 0.796 | 447 | 1769 | prefer |
| ermaozi | 0.487 | 0.458 | 59 | 703 | observe |
| DeltaKronecker-all | 0.438 | 0.354 | 79 | 5147 | observe |
| mheidari-all | 0.421 | 0.667 | 6 | 24005 | observe |
| Surfboard-tg-mixed | 0.373 | 0.6 | 5 | 7139 | observe |
| ermaozi-get_subscribe | 0.279 | 1.0 | 1 | 595 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5089 | observe |
| Epodonios-all | 0.255 | None | 0 | 7685 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10092 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5693 | observe |
| barry-far-vless | 0.255 | None | 0 | 5924 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4338 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 40 |
| 204 | ProxyError | - | 39 |
| cn-block | TimeoutError | - | 19 |
| geo | ClientOSError | - | 18 |
| speed | ClientOSError | - | 17 |
| speed | TimeoutError | - | 17 |
| geo | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 9 |
| 204 | ProxyConnectionError | - | 4 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
