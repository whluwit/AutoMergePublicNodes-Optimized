# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-22 12:33:44 |
| 运行耗时 | 303.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 92264 |
| 去重后节点 | 23731 |
| TCP 可达 | 3000 |
| 真实可用 | 804 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23731 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.3 |
| tcp | 40.5 |
| probe | 59.9 |
| real_test | 156.3 |
| generate | 38.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52367 |
| trojan | 16126 |
| shadowsocks | 10808 |
| vmess | 10566 |
| hysteria2 | 1852 |
| shadowsocksr | 202 |
| http | 168 |
| socks | 116 |
| anytls | 32 |
| hysteria | 15 |
| tuic | 12 |

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
| 81.58 | shadowsocks | 233.5 | 609.5 | 22.37 | 0.0 | 10.0 | 13.76 | 19.7 | Au1rxx-base64 | 155.138.136.240 |
| 81.38 | shadowsocks | 253.1 | 618.8 | 21.92 | 0.0 | 10.0 | 13.76 | 19.7 | Au1rxx-base64 | 156.146.38.169 |
| 81.11 | shadowsocks | 255.2 | 638.4 | 21.87 | 0.0 | 10.0 | 13.76 | 19.7 | Au1rxx-base64 | 156.146.38.168 |
| 80.65 | shadowsocks | 253.2 | 623.5 | 21.92 | 0.0 | 10.0 | 13.76 | 19.7 | Au1rxx-base64 | 156.146.38.167 |
| 80.49 | trojan | 343.4 | 873.2 | 19.83 | 0.0 | 10.0 | 14.17 | 19.7 | Au1rxx-base64 | 64.74.163.118 |
| 80.41 | shadowsocks | 295.1 | 773.6 | 20.95 | 0.0 | 10.0 | 13.76 | 19.7 | Au1rxx-base64 | 37.19.198.236 |
| 77.71 | vless | 296.5 | 711.2 | 20.91 | 0.0 | 10.0 | 7.76 | 19.7 | Au1rxx-base64 | 137.184.218.169 |
| 77.45 | vless | 250.2 | 625.1 | 21.99 | 0.0 | 10.0 | 7.76 | 19.7 | Au1rxx-base64 | 198.251.78.29 |
| 76.89 | vless | 257.7 | 671.7 | 21.81 | 0.0 | 10.0 | 7.76 | 17.32 | Surfboard-tg-mixed | 216.152.147.28 |
| 76.54 | shadowsocks | 328.8 | 737.0 | 20.17 | 0.0 | 10.0 | 13.76 | 19.7 | Au1rxx-base64 | 108.181.57.93 |
| 76.49 | vless | 283.7 | 676.3 | 21.21 | 0.0 | 10.0 | 7.76 | 19.7 | Au1rxx-base64 | 169.40.42.90 |
| 76.04 | shadowsocks | 380.7 | 961.2 | 18.96 | 0.0 | 10.0 | 13.76 | 17.32 | Surfboard-tg-mixed | 156.146.38.170 |
| 75.93 | shadowsocks | 310.5 | 644.2 | 20.59 | 0.0 | 10.0 | 13.76 | 19.7 | Au1rxx-base64 | 154.12.240.141 |
| 75.72 | vless | 315.4 | 718.5 | 20.48 | 0.0 | 10.0 | 7.76 | 19.7 | Au1rxx-base64 | 169.40.42.89 |
| 75.65 | vless | 322.1 | 693.7 | 20.32 | 0.0 | 10.0 | 7.76 | 19.7 | Au1rxx-base64 | 169.40.42.229 |
| 75.65 | vless | 394.8 | 1008.2 | 18.64 | 0.0 | 10.0 | 7.76 | 19.7 | Au1rxx-base64 | 169.40.42.104 |
| 75.53 | vless | 311.2 | 709.4 | 20.57 | 0.0 | 10.0 | 7.76 | 19.7 | Au1rxx-base64 | 140.99.223.187 |
| 75.47 | vless | 315.7 | 709.9 | 20.47 | 0.0 | 10.0 | 7.76 | 19.7 | Au1rxx-base64 | 169.40.42.225 |
| 75.34 | vless | 324.1 | 770.1 | 20.28 | 0.0 | 10.0 | 7.76 | 19.7 | Au1rxx-base64 | 158.69.112.254 |
| 75.26 | vless | 321.9 | 738.4 | 20.33 | 0.0 | 10.0 | 7.76 | 19.7 | Au1rxx-base64 | 107.151.201.59 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.941 | 507 | 1674 | prefer |
| zhangkai | 0.997 | 1.0 | 112 | 144 | prefer |
| Surfboard-tg-mixed | 0.886 | 0.809 | 178 | 6287 | prefer |
| mheidari-all | 0.608 | 0.528 | 125 | 21719 | observe |
| nscl5-all | 0.335 | 1.0 | 1 | 3321 | observe |
| tg-oneclickvpnkeys | 0.317 | 1.0 | 2 | 146 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5096 | observe |
| Epodonios-all | 0.255 | None | 0 | 6868 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3989 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6876 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5093 | observe |
| barry-far-vless | 0.255 | None | 0 | 5403 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4074 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5974 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 30 |
| geo | TimeoutError | - | 22 |
| 204 | TimeoutError | - | 21 |
| cn-block | TimeoutError | - | 16 |
| speed | TimeoutError | - | 16 |
| speed | ClientOSError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |
| 204 | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
