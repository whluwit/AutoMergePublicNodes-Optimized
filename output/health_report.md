# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-24 18:39:25 |
| 运行耗时 | 339.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 84182 |
| 去重后节点 | 23793 |
| TCP 可达 | 3000 |
| 真实可用 | 569 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23793 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 70.8 |
| geo | 1.4 |
| tcp | 36.8 |
| probe | 58.6 |
| real_test | 129.7 |
| generate | 42.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53072 |
| shadowsocks | 10742 |
| vmess | 10393 |
| trojan | 8106 |
| hysteria2 | 1483 |
| http | 164 |
| shadowsocksr | 127 |
| socks | 75 |
| hysteria | 13 |
| tuic | 5 |
| anytls | 2 |

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
| 84.01 | vless | 212.8 | 498.5 | 22.85 | 0.0 | 10.0 | 11.54 | 19.62 | Au1rxx-base64 | 23.172.40.60 |
| 83.8 | vless | 222.1 | 548.5 | 22.64 | 0.0 | 10.0 | 11.54 | 19.62 | Au1rxx-base64 | 15.204.97.209 |
| 83.66 | vless | 227.8 | 567.3 | 22.5 | 0.0 | 10.0 | 11.54 | 19.62 | Au1rxx-base64 | 15.204.97.197 |
| 82.79 | trojan | 232.3 | 529.9 | 22.4 | 0.0 | 10.0 | 13.33 | 19.62 | Au1rxx-base64 | 35.91.251.124 |
| 82.38 | shadowsocks | 218.2 | 532.3 | 22.73 | 0.0 | 10.0 | 14.03 | 19.62 | Au1rxx-base64 | 94.72.127.58 |
| 82.36 | shadowsocks | 219.1 | 538.7 | 22.71 | 0.0 | 10.0 | 14.03 | 19.62 | Au1rxx-base64 | 94.72.127.55 |
| 82.13 | shadowsocks | 219.2 | 544.2 | 22.7 | 0.0 | 10.0 | 14.03 | 19.62 | Au1rxx-base64 | 154.12.240.141 |
| 81.86 | vless | 305.8 | 803.8 | 20.7 | 0.0 | 10.0 | 11.54 | 19.62 | Au1rxx-base64 | 15.204.97.216 |
| 81.46 | vless | 323.2 | 849.3 | 20.3 | 0.0 | 10.0 | 11.54 | 19.62 | Au1rxx-base64 | 15.204.97.214 |
| 81.44 | trojan | 231.3 | 525.2 | 22.42 | 0.0 | 8.57 | 13.33 | 19.62 | Au1rxx-base64 | sincere-gelding.rooster465.autos |
| 81.42 | trojan | 229.4 | 546.2 | 22.47 | 0.0 | 10.0 | 13.33 | 19.62 | Au1rxx-base64 | 107.150.105.84 |
| 80.93 | trojan | 293.7 | 718.3 | 20.98 | 0.0 | 10.0 | 13.33 | 19.62 | Au1rxx-base64 | 14.1.28.76 |
| 80.88 | shadowsocks | 230.8 | 553.8 | 22.44 | 0.0 | 9.02 | 14.03 | 19.62 | Au1rxx-base64 | 154.53.60.212 |
| 79.57 | http | 383.2 | 1056.8 | 18.91 | 0.0 | 10.0 | 14.38 | 19.28 | zhangkai | 138.199.35.198 |
| 79.5 | vless | 397.0 | 948.1 | 18.59 | 0.0 | 10.0 | 11.54 | 19.62 | Au1rxx-base64 | 150.241.82.19 |
| 79.48 | http | 386.9 | 1072.2 | 18.82 | 0.0 | 10.0 | 14.38 | 19.28 | zhangkai | 138.199.35.216 |
| 78.94 | shadowsocks | 226.8 | 522.6 | 22.53 | 0.0 | 10.0 | 14.03 | 16.38 | mheidari-all | 62.146.171.57 |
| 78.29 | vless | 310.8 | 647.9 | 20.58 | 0.0 | 9.81 | 11.54 | 19.62 | Au1rxx-base64 | us.windconnect.pro |
| 78.13 | vless | 251.0 | 674.4 | 21.97 | 0.0 | 10.0 | 11.54 | 19.62 | Au1rxx-base64 | 23.94.239.108 |
| 77.93 | shadowsocks | 248.5 | 643.6 | 22.02 | 0.0 | 10.0 | 14.03 | 16.38 | mheidari-all | 108.181.118.10 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Au1rxx-base64 | 0.939 | 0.87 | 362 | 1779 | prefer |
| Surfboard-tg-mixed | 0.929 | 0.855 | 117 | 6472 | prefer |
| mheidari-all | 0.895 | 0.823 | 79 | 19577 | prefer |
| DeltaKronecker-all | 0.625 | 0.545 | 121 | 5914 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4899 | observe |
| Epodonios-all | 0.255 | None | 0 | 6977 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3989 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7298 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5396 | observe |
| barry-far-vless | 0.255 | None | 0 | 5685 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4132 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.246 | None | 0 | 1780 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 36 |
| cn-block | TimeoutError | - | 35 |
| 204 | TimeoutError | - | 26 |
| 204 | ProxyError | - | 10 |
| speed | TimeoutError | - | 9 |
| geo | ClientOSError | - | 8 |
| speed | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
