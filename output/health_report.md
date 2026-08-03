# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-03 14:33:11 |
| 运行耗时 | 279.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 83611 |
| 去重后节点 | 24679 |
| TCP 可达 | 3000 |
| 真实可用 | 551 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 24679 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.4 |
| tcp | 37.6 |
| probe | 57.6 |
| real_test | 142.6 |
| generate | 33.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50831 |
| vmess | 12726 |
| shadowsocks | 10452 |
| trojan | 8614 |
| hysteria2 | 732 |
| http | 86 |
| shadowsocksr | 77 |
| socks | 71 |
| hysteria | 10 |
| anytls | 7 |
| tuic | 5 |

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
| 79.77 | http | 299.1 | 654.8 | 20.85 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.218 |
| 79.04 | http | 334.1 | 763.5 | 20.04 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.211 |
| 79.01 | http | 318.8 | 723.8 | 20.4 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.216 |
| 74.64 | vless | 301.0 | 736.0 | 20.81 | 0.0 | 10.0 | 8.55 | 15.92 | Au1rxx-base64 | 66.175.217.170 |
| 74.0 | vless | 250.2 | 536.2 | 21.99 | 0.0 | 10.0 | 8.55 | 15.92 | Au1rxx-base64 | 192.204.50.220 |
| 72.91 | shadowsocks | 262.5 | 555.3 | 21.7 | 0.0 | 10.0 | 12.72 | 15.92 | Au1rxx-base64 | 173.244.56.6 |
| 71.8 | vless | 233.3 | 440.0 | 22.38 | 0.0 | 10.0 | 8.55 | 15.92 | Au1rxx-base64 | 108.162.192.5 |
| 71.29 | shadowsocks | 280.1 | 338.8 | 21.29 | 2.29 | 10.0 | 12.72 | 15.92 | Au1rxx-base64 | 149.22.87.204 |
| 71.27 | shadowsocks | 285.3 | 335.6 | 21.17 | 2.42 | 10.0 | 12.72 | 15.92 | Au1rxx-base64 | 149.22.87.241 |
| 71.0 | vless | 305.9 | 666.7 | 20.7 | 0.0 | 10.0 | 8.55 | 15.92 | Au1rxx-base64 | 70.39.198.183 |
| 70.99 | vless | 263.3 | 442.2 | 21.68 | 0.0 | 10.0 | 8.55 | 15.92 | Au1rxx-base64 | 172.64.32.6 |
| 70.8 | shadowsocks | 306.1 | 653.9 | 20.69 | 0.0 | 10.0 | 12.72 | 15.92 | Au1rxx-base64 | 156.146.38.167 |
| 70.72 | shadowsocks | 325.3 | 683.7 | 20.25 | 0.0 | 10.0 | 12.72 | 15.92 | Au1rxx-base64 | 156.146.38.170 |
| 70.61 | vless | 502.9 | 1379.8 | 16.14 | 0.0 | 10.0 | 8.55 | 15.92 | Au1rxx-base64 | 52.43.158.158 |
| 70.37 | shadowsocks | 284.6 | 581.4 | 21.19 | 0.0 | 10.0 | 12.72 | 15.92 | Au1rxx-base64 | 173.244.56.9 |
| 70.24 | shadowsocks | 319.4 | 674.5 | 20.39 | 0.0 | 10.0 | 12.72 | 15.92 | Au1rxx-base64 | 156.146.38.169 |
| 70.17 | shadowsocks | 323.5 | 686.7 | 20.29 | 0.0 | 10.0 | 12.72 | 15.92 | Au1rxx-base64 | 156.146.38.168 |
| 69.93 | hysteria2 | 356.1 | 720.6 | 19.54 | 0.0 | 10.0 | 9.75 | 15.92 | Au1rxx-base64 | 159.223.157.129 |
| 69.65 | vless | 322.1 | 566.3 | 20.32 | 0.0 | 10.0 | 8.55 | 15.92 | Au1rxx-base64 | 70.39.198.93 |
| 69.48 | vless | 297.2 | 571.4 | 20.9 | 0.0 | 10.0 | 8.55 | 15.92 | Au1rxx-base64 | 70.39.197.13 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.99 | 1.0 | 69 | 92 | prefer |
| Au1rxx-base64 | 0.798 | 0.732 | 518 | 1692 | prefer |
| mheidari-all | 0.577 | 0.497 | 181 | 18776 | observe |
| Surfboard-tg-mixed | 0.515 | 0.5 | 16 | 5293 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 3833 | observe |
| DeltaKronecker-all | 0.27 | 0.176 | 17 | 6205 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 54 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5285 | observe |
| Epodonios-all | 0.255 | None | 0 | 5891 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6783 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4162 | observe |
| barry-far-vless | 0.255 | None | 0 | 4526 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5196 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 82 |
| 204 | ProxyError | - | 36 |
| speed | TimeoutError | - | 28 |
| geo | TimeoutError | - | 25 |
| cn-block | TimeoutError | - | 25 |
| speed | ClientOSError | - | 17 |
| 204 | TimeoutError | - | 15 |
| 204 | ClientOSError | - | 10 |
| cn-block | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 5 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
