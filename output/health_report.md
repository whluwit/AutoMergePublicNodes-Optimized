# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-19 10:21:25 |
| 运行耗时 | 579.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 87126 |
| 去重后节点 | 25045 |
| TCP 可达 | 3000 |
| 真实可用 | 494 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25045 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.4 |
| tcp | 41.3 |
| probe | 229.8 |
| real_test | 218.8 |
| generate | 81.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51973 |
| vmess | 13799 |
| shadowsocks | 10532 |
| trojan | 8694 |
| hysteria2 | 1264 |
| http | 656 |
| shadowsocksr | 127 |
| socks | 64 |
| hysteria | 9 |
| tuic | 4 |
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
| 85.23 | hysteria2 | 199.5 | 525.0 | 23.16 | 0.0 | 10.0 | 14.21 | 18.86 | Au1rxx-base64 | 66.94.121.46 |
| 81.15 | shadowsocks | 240.9 | 626.1 | 22.2 | 0.0 | 10.0 | 14.09 | 18.86 | Au1rxx-base64 | 149.22.95.183 |
| 78.6 | vless | 292.5 | 796.5 | 21.01 | 0.0 | 10.0 | 8.73 | 18.86 | Au1rxx-base64 | 15.204.97.216 |
| 78.44 | vless | 299.5 | 800.7 | 20.85 | 0.0 | 10.0 | 8.73 | 18.86 | Au1rxx-base64 | 51.81.203.63 |
| 77.36 | vless | 261.7 | 583.9 | 21.72 | 0.0 | 10.0 | 8.73 | 18.86 | Au1rxx-base64 | 31.58.50.200 |
| 77.28 | vless | 259.7 | 558.6 | 21.77 | 0.0 | 10.0 | 8.73 | 18.86 | Au1rxx-base64 | 198.200.42.129 |
| 76.2 | shadowsocks | 295.2 | 582.9 | 20.94 | 0.0 | 10.0 | 14.09 | 18.86 | Au1rxx-base64 | 173.244.56.6 |
| 75.5 | vless | 296.7 | 808.1 | 20.91 | 0.0 | 10.0 | 8.73 | 18.86 | Au1rxx-base64 | 15.204.97.214 |
| 75.48 | vless | 211.1 | 550.2 | 22.89 | 0.0 | 10.0 | 8.73 | 18.86 | Au1rxx-base64 | 103.175.79.4 |
| 75.31 | trojan | 255.1 | 567.3 | 21.87 | 0.0 | 10.0 | 10.31 | 18.86 | Au1rxx-base64 | 100.42.228.109 |
| 75.16 | shadowsocks | 321.1 | 701.8 | 20.34 | 0.0 | 10.0 | 14.09 | 18.86 | Au1rxx-base64 | 156.146.38.168 |
| 74.85 | vless | 238.4 | 622.6 | 22.26 | 0.0 | 10.0 | 8.73 | 18.86 | Au1rxx-base64 | 140.235.168.5 |
| 74.69 | vless | 202.1 | 483.8 | 23.1 | 0.0 | 10.0 | 8.73 | 18.86 | Au1rxx-base64 | 195.26.229.222 |
| 74.55 | shadowsocks | 324.9 | 655.9 | 20.26 | 0.0 | 10.0 | 14.09 | 18.86 | Au1rxx-base64 | 23.150.248.20 |
| 74.48 | shadowsocks | 324.1 | 691.4 | 20.28 | 0.0 | 10.0 | 14.09 | 18.86 | Au1rxx-base64 | 156.146.38.169 |
| 74.44 | shadowsocks | 320.8 | 662.6 | 20.35 | 0.0 | 10.0 | 14.09 | 18.86 | Au1rxx-base64 | 156.146.38.170 |
| 74.02 | vless | 308.9 | 392.0 | 20.63 | 0.3 | 10.0 | 8.73 | 18.86 | Au1rxx-base64 | 104.18.46.234 |
| 73.53 | trojan | 246.1 | 544.2 | 22.08 | 0.0 | 10.0 | 10.31 | 18.86 | Au1rxx-base64 | 43.173.90.202 |
| 73.43 | shadowsocks | 304.1 | 739.4 | 20.74 | 0.0 | 10.0 | 14.09 | 18.86 | Au1rxx-base64 | 107.174.88.128 |
| 73.38 | vless | 281.3 | 412.4 | 21.27 | 0.0 | 10.0 | 8.73 | 15.38 | Surfboard-tg-mixed | 195.26.229.156 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.914 | 0.854 | 308 | 1569 | prefer |
| mheidari-all | 0.851 | 0.783 | 46 | 19088 | prefer |
| Surfboard-tg-mixed | 0.79 | 0.713 | 167 | 7238 | prefer |
| DeltaKronecker-all | 0.695 | 0.619 | 63 | 6421 | observe |
| ermaozi | 0.687 | 0.68 | 50 | 358 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4251 | observe |
| ermaozi-get_subscribe | 0.27 | 1.0 | 1 | 387 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5174 | observe |
| Epodonios-all | 0.255 | None | 0 | 7699 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8837 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5783 | observe |
| barry-far-vless | 0.255 | None | 0 | 5996 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 22 |
| 204 | TimeoutError | - | 20 |
| geo | TimeoutError | - | 20 |
| speed | ClientOSError | - | 19 |
| 204 | ProxyError | - | 17 |
| geo | ClientOSError | - | 16 |
| speed | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 11 |
| 204 | ProxyConnectionError | - | 5 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
