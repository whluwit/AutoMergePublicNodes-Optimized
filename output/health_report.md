# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-04 15:44:10 |
| 运行耗时 | 305.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 84293 |
| 去重后节点 | 23430 |
| TCP 可达 | 3000 |
| 真实可用 | 579 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23430 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.5 |
| tcp | 38.8 |
| probe | 91.2 |
| real_test | 126.7 |
| generate | 40.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53572 |
| vmess | 11410 |
| shadowsocks | 9603 |
| trojan | 7954 |
| hysteria2 | 1390 |
| http | 144 |
| shadowsocksr | 131 |
| socks | 63 |
| tuic | 15 |
| hysteria | 10 |
| anytls | 1 |

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
| 81.04 | shadowsocks | 256.2 | 658.7 | 21.85 | 0.0 | 10.0 | 13.91 | 19.28 | Au1rxx-base64 | 156.146.38.168 |
| 79.48 | vless | 277.0 | 586.0 | 21.37 | 0.0 | 10.0 | 11.96 | 19.28 | Au1rxx-base64 | 172.235.38.85 |
| 79.43 | shadowsocks | 239.4 | 613.4 | 22.24 | 0.0 | 10.0 | 13.91 | 19.28 | Au1rxx-base64 | 156.146.38.169 |
| 79.11 | vless | 342.5 | 821.1 | 19.85 | 0.0 | 10.0 | 11.96 | 19.28 | Au1rxx-base64 | 15.204.97.216 |
| 78.9 | vless | 361.3 | 863.7 | 19.41 | 0.0 | 10.0 | 11.96 | 19.28 | Au1rxx-base64 | 15.204.97.197 |
| 78.58 | vless | 320.2 | 668.5 | 20.36 | 0.0 | 10.0 | 11.96 | 19.28 | Au1rxx-base64 | 38.127.121.44 |
| 78.42 | shadowsocks | 244.8 | 628.1 | 22.11 | 0.0 | 10.0 | 13.91 | 16.4 | Surfboard-tg-mixed | 156.146.38.167 |
| 78.3 | shadowsocks | 352.8 | 635.0 | 19.61 | 0.0 | 10.0 | 13.91 | 19.28 | Au1rxx-base64 | 23.150.248.20 |
| 78.25 | vless | 289.8 | 632.0 | 21.07 | 0.0 | 10.0 | 11.96 | 19.28 | Au1rxx-base64 | 172.233.139.46 |
| 76.68 | vless | 325.3 | 557.2 | 20.25 | 0.0 | 10.0 | 11.96 | 19.28 | Au1rxx-base64 | 31.58.50.200 |
| 76.24 | vless | 372.0 | 752.9 | 19.17 | 0.0 | 10.0 | 11.96 | 19.28 | Au1rxx-base64 | 23.237.192.18 |
| 75.98 | vless | 248.8 | 549.8 | 22.02 | 0.0 | 10.0 | 11.96 | 19.28 | Au1rxx-base64 | 204.44.127.222 |
| 75.77 | shadowsocks | 299.8 | 651.6 | 20.84 | 0.0 | 10.0 | 13.91 | 19.28 | Au1rxx-base64 | 108.181.0.177 |
| 75.74 | vless | 429.3 | 1058.8 | 17.84 | 0.0 | 10.0 | 11.96 | 19.28 | Au1rxx-base64 | 45.138.100.226 |
| 75.38 | vless | 466.6 | 1182.0 | 16.98 | 0.0 | 10.0 | 11.96 | 19.28 | Au1rxx-base64 | 51.81.203.63 |
| 74.94 | vless | 377.5 | 762.5 | 19.04 | 0.0 | 10.0 | 11.96 | 19.28 | Au1rxx-base64 | 204.48.20.223 |
| 74.63 | vless | 307.7 | 743.3 | 20.66 | 0.0 | 10.0 | 11.96 | 19.28 | Au1rxx-base64 | 5.78.48.21 |
| 74.36 | vless | 392.7 | 813.2 | 18.69 | 0.0 | 10.0 | 11.96 | 19.28 | Au1rxx-base64 | 169.40.42.232 |
| 74.13 | vless | 348.7 | 836.4 | 19.71 | 0.0 | 10.0 | 11.96 | 19.28 | Au1rxx-base64 | 15.204.97.219 |
| 73.92 | vless | 369.9 | 745.3 | 19.22 | 0.0 | 10.0 | 11.96 | 19.28 | Au1rxx-base64 | 169.40.42.89 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.965 | 0.897 | 351 | 1751 | prefer |
| zhangkai | 0.964 | 1.0 | 22 | 144 | prefer |
| Surfboard-tg-mixed | 0.872 | 0.796 | 147 | 7209 | prefer |
| mheidari-all | 0.802 | 0.725 | 142 | 15927 | prefer |
| DeltaKronecker-all | 0.734 | 0.667 | 24 | 7089 | prefer |
| tg-oneclickvpnkeys | 0.481 | 1.0 | 6 | 104 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4810 | observe |
| Epodonios-all | 0.255 | None | 0 | 7667 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8718 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6091 | observe |
| barry-far-vless | 0.255 | None | 0 | 6339 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4123 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 29 |
| 204 | TimeoutError | - | 25 |
| geo | ClientOSError | - | 14 |
| cn-block | ClientOSError | - | 11 |
| geo | TimeoutError | - | 10 |
| speed | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 5 |
| 204 | ProxyError | - | 5 |
| speed | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
