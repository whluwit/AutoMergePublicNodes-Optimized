# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.9.1 |
| 更新时间 | 2026-06-18 04:43:59 |
| 运行耗时 | 216.1s |
| 订阅源总数 | 44 |
| 健康订阅源 | 44 |
| 原始节点 | 67675 |
| 去重后节点 | 22191 |
| TCP 可达 | 807 |
| 真实可用 | 614 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22191 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 2.0 |
| geo | 1.2 |
| tcp | 57.1 |
| probe | 103.2 |
| real_test | 35.9 |
| generate | 16.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 36790 |
| shadowsocks | 10235 |
| vmess | 10116 |
| trojan | 10057 |
| hysteria2 | 179 |
| shadowsocksr | 160 |
| http | 95 |
| socks | 35 |
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
| 77.48 | shadowsocks | 225.1 | 603.6 | 22.57 | 0.0 | 10.0 | 13.67 | 16.74 | mheidari-all | 198.98.53.130 |
| 77.02 | shadowsocks | 227.4 | 620.7 | 22.51 | 0.0 | 10.0 | 13.67 | 16.34 | Au1rxx-base64 | 37.19.198.160 |
| 76.91 | shadowsocks | 232.5 | 633.2 | 22.4 | 0.0 | 10.0 | 13.67 | 16.34 | Au1rxx-base64 | 37.19.198.243 |
| 76.77 | shadowsocks | 238.3 | 643.9 | 22.26 | 0.0 | 10.0 | 13.67 | 16.34 | Au1rxx-base64 | 37.19.198.244 |
| 75.84 | shadowsocks | 278.5 | 770.7 | 21.33 | 0.0 | 10.0 | 13.67 | 16.34 | Au1rxx-base64 | 37.19.198.236 |
| 75.74 | trojan | 256.1 | 650.7 | 21.85 | 0.0 | 10.0 | 12.07 | 18.82 | Surfboard-tg-mixed | 207.126.167.150 |
| 73.77 | shadowsocks | 281.3 | 645.7 | 21.27 | 0.0 | 10.0 | 13.67 | 16.34 | Au1rxx-base64 | 156.146.38.167 |
| 72.63 | trojan | 334.8 | 885.8 | 20.03 | 0.0 | 10.0 | 12.07 | 18.82 | Surfboard-tg-mixed | 45.61.52.243 |
| 72.48 | shadowsocks | 353.2 | 833.0 | 19.6 | 0.0 | 10.0 | 13.67 | 16.34 | Au1rxx-base64 | 107.172.250.161 |
| 72.4 | shadowsocks | 318.3 | 767.4 | 20.41 | 0.0 | 10.0 | 13.67 | 16.34 | Au1rxx-base64 | 156.146.38.170 |
| 72.27 | shadowsocks | 318.8 | 765.1 | 20.4 | 0.0 | 10.0 | 13.67 | 16.34 | Au1rxx-base64 | 149.28.255.6 |
| 72.14 | shadowsocks | 278.3 | 644.0 | 21.34 | 0.0 | 10.0 | 13.67 | 16.34 | Au1rxx-base64 | 156.146.38.169 |
| 71.8 | vless | 302.9 | 843.6 | 20.77 | 0.0 | 10.0 | 10.71 | 18.82 | Surfboard-tg-mixed | 137.184.218.169 |
| 71.77 | shadowsocks | 249.5 | 653.2 | 22.0 | 0.0 | 10.0 | 13.67 | 11.6 | DeltaKronecker-all | 108.181.57.93 |
| 70.45 | vless | 361.1 | 919.2 | 19.42 | 0.0 | 10.0 | 10.71 | 18.82 | Surfboard-tg-mixed | 37.1.212.241 |
| 70.44 | shadowsocks | 316.6 | 756.5 | 20.45 | 0.0 | 10.0 | 13.67 | 16.34 | Au1rxx-base64 | 156.146.38.168 |
| 69.77 | vless | 347.0 | 896.3 | 19.75 | 0.0 | 10.0 | 10.71 | 16.74 | mheidari-all | 185.156.47.96 |
| 69.56 | shadowsocks | 231.3 | 630.1 | 22.42 | 0.0 | 9.99 | 13.67 | 16.34 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |
| 69.5 | vless | 294.9 | 815.8 | 20.95 | 0.0 | 10.0 | 10.71 | 16.34 | Au1rxx-base64 | 159.89.87.21 |
| 69.23 | trojan | 382.8 | 899.2 | 18.92 | 0.0 | 10.0 | 12.07 | 16.74 | mheidari-all | 207.126.167.241 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.966 | 1.0 | 25 | 73 | prefer |
| Surfboard-tg-mixed | 0.926 | 0.848 | 356 | 4586 | prefer |
| Au1rxx-base64 | 0.868 | 0.872 | 78 | 126 | prefer |
| mheidari-all | 0.845 | 0.767 | 215 | 13927 | prefer |
| DeltaKronecker-all | 0.493 | 0.411 | 124 | 7763 | observe |
| Epodonios-all | 0.335 | 1.0 | 1 | 6401 | observe |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4274 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3977 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 5959 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3590 | observe |
| barry-far-vless | 0.255 | None | 0 | 4240 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4541 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| nscl5-all | 0.217 | None | 0 | 1044 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| general | unknown | - | 179 |
| speed | ClientOSError | - | 3 |
| 204 | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | TimeoutError | - | 2 |
| speed | TimeoutError | - | 2 |
| 204 | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
