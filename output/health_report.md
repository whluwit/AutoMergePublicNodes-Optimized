# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-25 18:36:53 |
| 运行耗时 | 245.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 77879 |
| 去重后节点 | 22524 |
| TCP 可达 | 3000 |
| 真实可用 | 568 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22524 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 1.4 |
| tcp | 36.3 |
| probe | 52.6 |
| real_test | 111.3 |
| generate | 38.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48684 |
| shadowsocks | 10560 |
| vmess | 10478 |
| trojan | 6438 |
| hysteria2 | 1345 |
| http | 164 |
| shadowsocksr | 131 |
| socks | 69 |
| hysteria | 7 |
| tuic | 3 |

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
| 85.44 | hysteria2 | 247.9 | 659.1 | 22.04 | 0.0 | 10.0 | 14.5 | 20.0 | mheidari-all | 159.223.157.129 |
| 81.78 | shadowsocks | 264.4 | 713.1 | 21.66 | 0.0 | 10.0 | 14.12 | 20.0 | mheidari-all | 37.19.198.160 |
| 81.69 | shadowsocks | 268.3 | 724.6 | 21.57 | 0.0 | 10.0 | 14.12 | 20.0 | mheidari-all | 37.19.198.243 |
| 80.89 | shadowsocks | 302.8 | 827.6 | 20.77 | 0.0 | 10.0 | 14.12 | 20.0 | mheidari-all | 37.19.198.244 |
| 80.31 | shadowsocks | 245.6 | 661.3 | 22.09 | 0.0 | 10.0 | 14.12 | 18.1 | Au1rxx-base64 | 37.19.198.236 |
| 80.2 | vless | 276.8 | 645.1 | 21.37 | 0.0 | 10.0 | 11.07 | 18.1 | Au1rxx-base64 | 169.40.42.225 |
| 80.13 | shadowsocks | 243.7 | 620.4 | 22.14 | 0.0 | 10.0 | 14.12 | 18.1 | Au1rxx-base64 | 155.138.136.240 |
| 79.52 | vless | 320.8 | 856.7 | 20.35 | 0.0 | 10.0 | 11.07 | 18.1 | Au1rxx-base64 | 137.184.218.169 |
| 79.27 | vless | 331.5 | 894.1 | 20.1 | 0.0 | 10.0 | 11.07 | 18.1 | Au1rxx-base64 | 79.127.243.217 |
| 79.14 | vless | 337.2 | 934.2 | 19.97 | 0.0 | 10.0 | 11.07 | 18.1 | Au1rxx-base64 | 47.89.186.170 |
| 78.39 | vless | 369.5 | 982.0 | 19.22 | 0.0 | 10.0 | 11.07 | 18.1 | Au1rxx-base64 | 185.95.231.156 |
| 78.3 | vless | 373.4 | 790.8 | 19.13 | 0.0 | 10.0 | 11.07 | 18.1 | Au1rxx-base64 | 169.40.42.16 |
| 78.24 | vless | 300.9 | 708.5 | 20.81 | 0.0 | 10.0 | 11.07 | 18.1 | Au1rxx-base64 | 66.70.179.198 |
| 78.13 | shadowsocks | 318.3 | 870.8 | 20.41 | 0.0 | 10.0 | 14.12 | 18.1 | Au1rxx-base64 | 38.180.135.156 |
| 77.74 | vless | 350.5 | 951.9 | 19.67 | 0.0 | 10.0 | 11.07 | 18.1 | Au1rxx-base64 | 45.138.100.226 |
| 77.7 | vless | 399.5 | 888.3 | 18.53 | 0.0 | 10.0 | 11.07 | 18.1 | Au1rxx-base64 | 169.40.42.229 |
| 77.55 | shadowsocks | 312.8 | 730.8 | 20.54 | 0.0 | 10.0 | 14.12 | 20.0 | mheidari-all | 156.146.38.170 |
| 77.42 | shadowsocks | 361.0 | 756.3 | 19.42 | 0.0 | 10.0 | 14.12 | 17.88 | Surfboard-tg-mixed | 142.4.216.225 |
| 77.28 | vless | 369.9 | 914.8 | 19.22 | 0.0 | 10.0 | 11.07 | 18.1 | Au1rxx-base64 | 169.40.42.202 |
| 77.21 | vless | 304.7 | 653.5 | 20.73 | 0.0 | 10.0 | 11.07 | 18.1 | Au1rxx-base64 | 198.251.78.29 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.964 | 1.0 | 22 | 144 | prefer |
| Au1rxx-base64 | 0.903 | 0.845 | 432 | 1502 | prefer |
| mheidari-all | 0.851 | 0.779 | 68 | 14446 | prefer |
| DeltaKronecker-all | 0.846 | 0.778 | 45 | 6340 | prefer |
| Surfboard-tg-mixed | 0.779 | 0.702 | 131 | 6434 | prefer |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4912 | observe |
| Epodonios-all | 0.255 | None | 0 | 6936 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7007 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5291 | observe |
| barry-far-vless | 0.255 | None | 0 | 5564 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4119 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.235 | None | 0 | 1505 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | TimeoutError | - | 47 |
| geo | TimeoutError | - | 19 |
| 204 | TimeoutError | - | 17 |
| cn-block | TimeoutError | - | 16 |
| geo | ClientOSError | - | 11 |
| 204 | ProxyError | - | 8 |
| speed | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
