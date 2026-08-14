# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-14 12:59:36 |
| 运行耗时 | 273.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 81470 |
| 去重后节点 | 23179 |
| TCP 可达 | 3000 |
| 真实可用 | 852 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23179 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| geo | 0.8 |
| tcp | 34.9 |
| probe | 55.4 |
| real_test | 148.6 |
| generate | 29.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 44752 |
| vmess | 13690 |
| trojan | 11918 |
| shadowsocks | 9755 |
| hysteria2 | 1036 |
| http | 156 |
| socks | 77 |
| shadowsocksr | 67 |
| tuic | 10 |
| hysteria | 7 |
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
| 83.73 | trojan | 231.7 | 527.9 | 22.41 | 0.0 | 10.0 | 14.28 | 19.78 | Au1rxx-base64 | 44.244.3.114 |
| 83.68 | trojan | 244.3 | 568.7 | 22.12 | 0.0 | 10.0 | 14.28 | 19.78 | Au1rxx-base64 | 35.86.90.51 |
| 83.04 | trojan | 240.8 | 551.8 | 22.2 | 0.0 | 9.28 | 14.28 | 19.78 | Au1rxx-base64 | natural-collie.rooster465.autos |
| 82.97 | trojan | 229.2 | 519.8 | 22.47 | 0.0 | 10.0 | 14.28 | 19.78 | Au1rxx-base64 | 44.243.85.47 |
| 82.85 | trojan | 234.9 | 546.9 | 22.34 | 0.0 | 10.0 | 14.28 | 19.78 | Au1rxx-base64 | 44.242.235.129 |
| 82.63 | shadowsocks | 188.3 | 467.8 | 23.42 | 0.0 | 10.0 | 13.93 | 19.78 | Au1rxx-base64 | 108.181.0.177 |
| 82.37 | shadowsocks | 221.2 | 517.0 | 22.66 | 0.0 | 10.0 | 13.93 | 19.78 | Au1rxx-base64 | 173.244.56.9 |
| 82.08 | shadowsocks | 212.2 | 522.1 | 22.87 | 0.0 | 10.0 | 13.93 | 19.78 | Au1rxx-base64 | 108.181.118.10 |
| 81.97 | trojan | 226.7 | 516.2 | 22.53 | 0.0 | 7.88 | 14.28 | 19.78 | Au1rxx-base64 | devoted-tapir.rooster465.autos |
| 81.69 | trojan | 243.8 | 567.7 | 22.13 | 0.0 | 10.0 | 14.28 | 19.78 | Au1rxx-base64 | 35.88.210.26 |
| 81.53 | trojan | 287.7 | 698.3 | 21.12 | 0.0 | 10.0 | 14.28 | 19.78 | Au1rxx-base64 | 44.246.163.102 |
| 81.52 | trojan | 240.6 | 554.8 | 22.21 | 0.0 | 10.0 | 14.28 | 19.78 | Au1rxx-base64 | 54.245.126.186 |
| 81.49 | shadowsocks | 258.9 | 599.8 | 21.78 | 0.0 | 10.0 | 13.93 | 19.78 | Au1rxx-base64 | 173.244.56.6 |
| 80.78 | trojan | 240.3 | 556.8 | 22.22 | 0.0 | 10.0 | 14.28 | 19.78 | Au1rxx-base64 | 34.221.30.108 |
| 80.62 | trojan | 238.1 | 550.2 | 22.27 | 0.0 | 10.0 | 14.28 | 19.78 | Au1rxx-base64 | 35.88.120.18 |
| 80.28 | vless | 182.1 | 467.9 | 23.56 | 0.0 | 10.0 | 6.94 | 19.78 | Au1rxx-base64 | 70.39.197.13 |
| 80.26 | http | 405.1 | 1135.0 | 18.4 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.210 |
| 80.23 | http | 406.5 | 1141.9 | 18.37 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.199 |
| 80.07 | trojan | 307.8 | 756.5 | 20.65 | 0.0 | 10.0 | 14.28 | 19.78 | Au1rxx-base64 | 54.188.176.255 |
| 80.02 | http | 415.6 | 1162.3 | 18.16 | 0.0 | 10.0 | 14.88 | 19.98 | zhangkai | 138.199.35.197 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.95 | 642 | 1959 | prefer |
| zhangkai | 0.999 | 1.0 | 127 | 159 | prefer |
| Surfboard-tg-mixed | 0.811 | 0.736 | 106 | 5845 | prefer |
| DeltaKronecker-all | 0.72 | 0.646 | 48 | 5969 | prefer |
| mheidari-all | 0.519 | 1.0 | 5 | 17030 | observe |
| nscl5-all | 0.278 | 0.5 | 2 | 1768 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5157 | observe |
| Epodonios-all | 0.255 | None | 0 | 6515 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7472 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4594 | observe |
| barry-far-vless | 0.255 | None | 0 | 4931 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5332 | observe |
| Au1rxx-clash | 0.253 | None | 0 | 1959 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 13 |
| geo | TimeoutError | - | 13 |
| 204 | TimeoutError | - | 12 |
| cn-block | TimeoutError | - | 12 |
| 204 | ProxyError | - | 8 |
| speed | ClientOSError | - | 5 |
| speed | TimeoutError | - | 5 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
