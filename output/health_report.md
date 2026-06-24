# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-24 19:45:06 |
| 运行耗时 | 266.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 76859 |
| 去重后节点 | 22597 |
| TCP 可达 | 3000 |
| 真实可用 | 401 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22597 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.4 |
| tcp | 29.5 |
| probe | 58.5 |
| real_test | 126.3 |
| generate | 46.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45377 |
| trojan | 10855 |
| vmess | 10201 |
| shadowsocks | 9826 |
| hysteria2 | 234 |
| shadowsocksr | 163 |
| http | 129 |
| socks | 66 |
| hysteria | 6 |
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
| 77.5 | shadowsocks | 226.8 | 627.8 | 22.53 | 0.0 | 10.0 | 13.57 | 15.4 | Au1rxx-base64 | 37.19.198.244 |
| 77.4 | shadowsocks | 230.8 | 640.3 | 22.43 | 0.0 | 10.0 | 13.57 | 15.4 | Au1rxx-base64 | 37.19.198.236 |
| 77.38 | shadowsocks | 232.0 | 642.9 | 22.41 | 0.0 | 10.0 | 13.57 | 15.4 | Au1rxx-base64 | 37.19.198.160 |
| 74.82 | shadowsocks | 321.1 | 885.2 | 20.35 | 0.0 | 10.0 | 13.57 | 15.4 | Au1rxx-base64 | 108.181.57.93 |
| 73.85 | shadowsocks | 277.7 | 635.2 | 21.35 | 0.0 | 10.0 | 13.57 | 15.4 | Au1rxx-base64 | 156.146.38.168 |
| 73.76 | vless | 259.6 | 687.7 | 21.77 | 0.0 | 10.0 | 9.87 | 17.12 | Surfboard-tg-mixed | 137.184.218.169 |
| 73.2 | vless | 269.9 | 658.0 | 21.53 | 0.0 | 10.0 | 9.87 | 17.12 | Surfboard-tg-mixed | 104.16.9.20 |
| 72.84 | shadowsocks | 280.6 | 642.0 | 21.28 | 0.0 | 10.0 | 13.57 | 15.4 | Au1rxx-base64 | 156.146.38.167 |
| 71.81 | vless | 436.8 | 1099.6 | 17.67 | 0.0 | 10.0 | 9.87 | 17.12 | Surfboard-tg-mixed | 15.223.121.250 |
| 69.78 | shadowsocks | 309.1 | 561.1 | 20.62 | 0.0 | 10.0 | 13.57 | 15.4 | Au1rxx-base64 | 173.244.56.9 |
| 69.45 | shadowsocks | 322.6 | 667.3 | 20.31 | 0.0 | 10.0 | 13.57 | 15.4 | Au1rxx-base64 | 108.181.0.177 |
| 69.32 | shadowsocks | 327.5 | 686.3 | 20.2 | 0.0 | 10.0 | 13.57 | 15.4 | Au1rxx-base64 | 108.181.118.10 |
| 69.17 | shadowsocks | 362.7 | 729.3 | 19.38 | 0.0 | 10.0 | 13.57 | 15.4 | Au1rxx-base64 | 173.244.56.6 |
| 69.07 | shadowsocks | 334.7 | 643.7 | 20.03 | 0.0 | 10.0 | 13.57 | 15.4 | Au1rxx-base64 | 149.22.95.183 |
| 67.93 | shadowsocks | 271.4 | 752.5 | 21.49 | 0.0 | 10.0 | 13.57 | 15.4 | Au1rxx-base64 | 198.98.53.130 |
| 67.79 | shadowsocks | 291.0 | 803.1 | 21.04 | 0.0 | 10.0 | 13.57 | 15.4 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |
| 67.55 | shadowsocks | 418.0 | 747.1 | 18.1 | 0.0 | 10.0 | 13.57 | 17.12 | Surfboard-tg-mixed | 82.38.31.2 |
| 67.27 | shadowsocks | 421.3 | 758.9 | 18.02 | 0.0 | 10.0 | 13.57 | 17.12 | Surfboard-tg-mixed | 193.29.139.151 |
| 67.17 | shadowsocks | 428.3 | 758.2 | 17.86 | 0.0 | 10.0 | 13.57 | 17.12 | Surfboard-tg-mixed | 193.29.139.233 |
| 67.14 | shadowsocks | 429.2 | 772.2 | 17.84 | 0.0 | 10.0 | 13.57 | 17.12 | Surfboard-tg-mixed | 82.38.31.218 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.977 | 1.0 | 36 | 82 | prefer |
| Surfboard-tg-mixed | 0.804 | 0.726 | 226 | 5375 | prefer |
| Au1rxx-base64 | 0.746 | 0.75 | 60 | 114 | prefer |
| mheidari-all | 0.71 | 0.632 | 190 | 15681 | prefer |
| DeltaKronecker-all | 0.61 | 0.531 | 64 | 6644 | observe |
| nscl5-all | 0.301 | 1.0 | 1 | 1140 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4745 | observe |
| Epodonios-all | 0.255 | None | 0 | 8092 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3980 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7510 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4084 | observe |
| barry-far-vless | 0.255 | None | 0 | 4852 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4710 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 72 |
| 204 | TimeoutError | - | 28 |
| cn-block | TimeoutError | - | 24 |
| 204 | ProxyError | - | 15 |
| cn-block | ClientOSError | - | 8 |
| speed | TimeoutError | - | 7 |
| 204 | ClientOSError | - | 5 |
| geo | TimeoutError | - | 5 |
| cn-block | ProxyError | - | 4 |
| geo | ClientOSError | - | 4 |
| speed | ProxyError | - | 4 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
