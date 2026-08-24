# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-24 06:51:25 |
| 运行耗时 | 309.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 78516 |
| 去重后节点 | 21926 |
| TCP 可达 | 3000 |
| 真实可用 | 715 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21926 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.4 |
| tcp | 34.8 |
| probe | 58.7 |
| real_test | 173.2 |
| generate | 36.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48733 |
| shadowsocks | 10331 |
| vmess | 10044 |
| trojan | 7816 |
| hysteria2 | 1194 |
| http | 164 |
| shadowsocksr | 124 |
| socks | 101 |
| hysteria | 7 |
| tuic | 2 |

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
| 82.4 | shadowsocks | 241.3 | 618.0 | 22.19 | 0.0 | 10.0 | 14.21 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 81.36 | shadowsocks | 264.6 | 630.7 | 21.65 | 0.0 | 10.0 | 14.21 | 20.0 | Au1rxx-base64 | 23.150.248.20 |
| 81.04 | shadowsocks | 251.3 | 584.3 | 21.96 | 0.0 | 10.0 | 14.21 | 20.0 | Au1rxx-base64 | 94.72.127.58 |
| 80.91 | shadowsocks | 252.0 | 594.6 | 21.94 | 0.0 | 10.0 | 14.21 | 20.0 | Au1rxx-base64 | 94.72.127.55 |
| 79.95 | shadowsocks | 266.8 | 597.1 | 21.6 | 0.0 | 9.74 | 14.21 | 20.0 | Au1rxx-base64 | 154.53.60.212 |
| 79.79 | shadowsocks | 236.5 | 610.5 | 22.3 | 0.0 | 10.0 | 14.21 | 17.28 | Surfboard-tg-mixed | 156.146.38.169 |
| 79.74 | hysteria2 | 387.6 | 925.8 | 18.81 | 0.0 | 10.0 | 14.38 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 79.58 | shadowsocks | 265.1 | 569.4 | 21.64 | 0.0 | 10.0 | 14.21 | 20.0 | Au1rxx-base64 | 154.12.242.150 |
| 79.49 | shadowsocks | 249.5 | 601.5 | 22.0 | 0.0 | 10.0 | 14.21 | 17.28 | Surfboard-tg-mixed | 156.146.38.168 |
| 79.43 | trojan | 261.7 | 651.9 | 21.72 | 0.0 | 10.0 | 10.71 | 20.0 | Au1rxx-base64 | 64.94.95.114 |
| 79.14 | vless | 265.9 | 594.6 | 21.62 | 0.0 | 10.0 | 10.05 | 20.0 | Au1rxx-base64 | 15.204.97.197 |
| 77.99 | shadowsocks | 253.5 | 572.6 | 21.91 | 0.0 | 10.0 | 14.21 | 20.0 | Au1rxx-base64 | 154.12.240.141 |
| 77.81 | vless | 326.3 | 758.6 | 20.22 | 0.0 | 10.0 | 10.05 | 20.0 | Au1rxx-base64 | 15.204.97.214 |
| 77.71 | shadowsocks | 304.6 | 692.5 | 20.73 | 0.0 | 9.76 | 14.21 | 20.0 | Au1rxx-base64 | 155.138.136.240 |
| 77.61 | shadowsocks | 210.8 | 501.3 | 22.9 | 0.0 | 10.0 | 14.21 | 20.0 | Au1rxx-base64 | 152.67.250.45 |
| 76.95 | vless | 329.9 | 709.7 | 20.14 | 0.0 | 10.0 | 10.05 | 20.0 | Au1rxx-base64 | 198.251.78.29 |
| 76.91 | trojan | 327.3 | 769.8 | 20.2 | 0.0 | 10.0 | 10.71 | 20.0 | Au1rxx-base64 | 34.94.125.227 |
| 76.86 | trojan | 286.1 | 678.6 | 21.15 | 0.0 | 10.0 | 10.71 | 20.0 | Au1rxx-base64 | 64.94.95.118 |
| 76.51 | trojan | 344.5 | 899.1 | 19.8 | 0.0 | 10.0 | 10.71 | 20.0 | Au1rxx-base64 | 64.94.95.115 |
| 76.48 | http | 472.3 | 1235.3 | 16.84 | 0.0 | 10.0 | 14.87 | 19.94 | zhangkai | 138.199.35.198 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.997 | 1.0 | 112 | 144 | prefer |
| Au1rxx-base64 | 0.966 | 0.9 | 379 | 1718 | prefer |
| Surfboard-tg-mixed | 0.868 | 0.792 | 144 | 6363 | prefer |
| mheidari-all | 0.84 | 0.882 | 17 | 14629 | prefer |
| DeltaKronecker-all | 0.393 | 0.312 | 416 | 5914 | observe |
| nscl5-all | 0.309 | 0.667 | 3 | 1008 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 177 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4899 | observe |
| Epodonios-all | 0.255 | None | 0 | 6867 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3988 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7231 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5242 | observe |
| barry-far-vless | 0.255 | None | 0 | 5530 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4097 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1728 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 154 |
| geo | ClientOSError | - | 64 |
| speed | ClientOSError | - | 62 |
| speed | TimeoutError | - | 28 |
| cn-block | TimeoutError | - | 19 |
| 204 | TimeoutError | - | 10 |
| 204 | ProxyError | - | 10 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
