# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-25 21:10:11 |
| 运行耗时 | 518.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97260 |
| 去重后节点 | 26455 |
| TCP 可达 | 3000 |
| 真实可用 | 361 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26455 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| geo | 1.5 |
| tcp | 43.5 |
| probe | 217.8 |
| real_test | 169.4 |
| generate | 78.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59661 |
| vmess | 15069 |
| shadowsocks | 11209 |
| trojan | 8876 |
| hysteria2 | 1551 |
| http | 576 |
| shadowsocksr | 169 |
| socks | 96 |
| anytls | 27 |
| hysteria | 15 |
| tuic | 11 |

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
| 82.46 | vless | 205.8 | 543.0 | 23.01 | 0.0 | 9.08 | 10.93 | 19.44 | Au1rxx-base64 | 172.235.43.210 |
| 81.76 | vless | 237.7 | 637.5 | 22.28 | 0.0 | 9.11 | 10.93 | 19.44 | Au1rxx-base64 | 192.3.247.109 |
| 81.66 | vless | 241.4 | 563.1 | 22.19 | 0.0 | 9.1 | 10.93 | 19.44 | Au1rxx-base64 | 15.204.97.216 |
| 81.14 | vless | 268.4 | 688.8 | 21.56 | 0.0 | 9.21 | 10.93 | 19.44 | Au1rxx-base64 | 5.78.159.214 |
| 79.11 | vless | 267.6 | 718.6 | 21.58 | 0.0 | 10.0 | 10.93 | 16.6 | Surfboard-tg-mixed | 172.235.38.85 |
| 77.99 | vless | 214.3 | 536.0 | 22.82 | 0.0 | 9.1 | 10.93 | 19.44 | Au1rxx-base64 | 195.123.240.65 |
| 77.81 | shadowsocks | 208.8 | 530.8 | 22.94 | 0.0 | 10.0 | 12.77 | 16.6 | Surfboard-tg-mixed | 5.78.51.123 |
| 77.6 | vless | 336.8 | 831.7 | 19.98 | 0.0 | 9.07 | 10.93 | 19.44 | Au1rxx-base64 | 136.117.218.86 |
| 77.17 | shadowsocks | 242.5 | 544.4 | 22.16 | 0.0 | 10.0 | 12.77 | 16.6 | Surfboard-tg-mixed | 173.244.56.6 |
| 76.98 | shadowsocks | 244.8 | 615.8 | 22.11 | 0.0 | 10.0 | 12.77 | 16.6 | Surfboard-tg-mixed | 108.181.0.177 |
| 76.66 | vless | 280.4 | 718.3 | 21.29 | 0.0 | 10.0 | 10.93 | 19.44 | Au1rxx-base64 | 15.204.97.214 |
| 76.34 | vless | 253.1 | 625.0 | 21.92 | 0.0 | 9.05 | 10.93 | 19.44 | Au1rxx-base64 | 38.244.20.25 |
| 75.55 | vless | 216.8 | 495.2 | 22.76 | 0.0 | 9.25 | 10.93 | 19.44 | Au1rxx-base64 | 172.64.32.108 |
| 75.39 | vless | 172.0 | 476.4 | 23.8 | 0.0 | 9.22 | 10.93 | 19.44 | Au1rxx-base64 | 173.249.207.28 |
| 74.96 | shadowsocks | 275.6 | 686.6 | 21.4 | 0.0 | 10.0 | 12.77 | 16.6 | Surfboard-tg-mixed | 173.244.56.9 |
| 74.7 | vless | 365.0 | 929.6 | 19.33 | 0.0 | 10.0 | 10.93 | 19.44 | Au1rxx-base64 | 15.204.97.197 |
| 74.52 | vless | 310.2 | 855.9 | 20.6 | 0.0 | 8.55 | 10.93 | 19.44 | Au1rxx-base64 | c10s3.portablesubmarines.com |
| 74.24 | shadowsocks | 195.4 | 520.4 | 23.25 | 0.0 | 10.0 | 12.77 | 12.72 | mheidari-all | 192.3.247.109 |
| 74.06 | vless | 343.5 | 706.5 | 19.83 | 0.0 | 9.07 | 10.93 | 19.44 | Au1rxx-base64 | 195.211.98.43 |
| 74.03 | shadowsocks | 348.0 | 822.3 | 19.72 | 0.0 | 9.24 | 12.77 | 19.44 | Au1rxx-base64 | 156.146.38.168 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.956 | 0.891 | 238 | 1701 | prefer |
| mheidari-all | 0.712 | 0.635 | 104 | 22345 | prefer |
| Surfboard-tg-mixed | 0.651 | 0.573 | 110 | 7370 | observe |
| ermaozi | 0.555 | 0.545 | 33 | 304 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5293 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 5452 | observe |
| Epodonios-all | 0.255 | None | 0 | 7740 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9249 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5959 | observe |
| barry-far-vless | 0.255 | None | 0 | 6190 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4304 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1701 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 41 |
| cn-block | TimeoutError | - | 24 |
| cn-block | ClientOSError | - | 19 |
| 204 | ProxyConnectionError | - | 17 |
| 204 | ProxyError | - | 9 |
| geo | TimeoutError | - | 8 |
| speed | ClientOSError | - | 5 |
| speed | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
