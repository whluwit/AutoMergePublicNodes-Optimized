# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.9.1 |
| 更新时间 | 2026-06-18 04:53:04 |
| 运行耗时 | 204.4s |
| 订阅源总数 | 64 |
| 健康订阅源 | 64 |
| 原始节点 | 69566 |
| 去重后节点 | 22438 |
| TCP 可达 | 806 |
| 真实可用 | 622 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22438 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.7 |
| geo | 1.3 |
| tcp | 63.9 |
| probe | 94.9 |
| real_test | 23.1 |
| generate | 17.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 38116 |
| shadowsocks | 10434 |
| trojan | 10273 |
| vmess | 10208 |
| hysteria2 | 226 |
| shadowsocksr | 160 |
| http | 96 |
| socks | 45 |
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
| 78.3 | shadowsocks | 227.4 | 620.7 | 22.51 | 0.0 | 10.0 | 13.93 | 17.36 | Au1rxx-base64 | 37.19.198.160 |
| 78.19 | shadowsocks | 232.5 | 633.2 | 22.4 | 0.0 | 10.0 | 13.93 | 17.36 | Au1rxx-base64 | 37.19.198.243 |
| 78.05 | shadowsocks | 238.3 | 643.9 | 22.26 | 0.0 | 10.0 | 13.93 | 17.36 | Au1rxx-base64 | 37.19.198.244 |
| 77.9 | shadowsocks | 225.1 | 603.6 | 22.57 | 0.0 | 10.0 | 13.93 | 16.9 | mheidari-all | 198.98.53.130 |
| 77.12 | shadowsocks | 278.5 | 770.7 | 21.33 | 0.0 | 10.0 | 13.93 | 17.36 | Au1rxx-base64 | 37.19.198.236 |
| 76.64 | trojan | 256.1 | 650.7 | 21.85 | 0.0 | 10.0 | 12.77 | 18.52 | Surfboard-tg-mixed | 207.126.167.150 |
| 75.05 | shadowsocks | 281.3 | 645.7 | 21.27 | 0.0 | 10.0 | 13.93 | 17.36 | Au1rxx-base64 | 156.146.38.167 |
| 74.26 | shadowsocks | 353.2 | 833.0 | 19.6 | 0.0 | 10.0 | 13.93 | 17.36 | Au1rxx-base64 | 107.172.250.161 |
| 73.68 | shadowsocks | 318.3 | 767.4 | 20.41 | 0.0 | 10.0 | 13.93 | 17.36 | Au1rxx-base64 | 156.146.38.170 |
| 73.55 | shadowsocks | 318.8 | 765.1 | 20.4 | 0.0 | 10.0 | 13.93 | 17.36 | Au1rxx-base64 | 149.28.255.6 |
| 73.53 | trojan | 334.8 | 885.8 | 20.03 | 0.0 | 10.0 | 12.77 | 18.52 | Surfboard-tg-mixed | 45.61.52.243 |
| 73.42 | shadowsocks | 278.3 | 644.0 | 21.34 | 0.0 | 10.0 | 13.93 | 17.36 | Au1rxx-base64 | 156.146.38.169 |
| 72.22 | shadowsocks | 316.6 | 756.5 | 20.45 | 0.0 | 10.0 | 13.93 | 17.36 | Au1rxx-base64 | 156.146.38.168 |
| 71.56 | vless | 302.9 | 843.6 | 20.77 | 0.0 | 10.0 | 10.27 | 18.52 | Surfboard-tg-mixed | 137.184.218.169 |
| 70.8 | shadowsocks | 231.3 | 630.1 | 22.42 | 0.0 | 9.95 | 13.93 | 17.36 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |
| 70.59 | trojan | 382.8 | 899.2 | 18.92 | 0.0 | 10.0 | 12.77 | 16.9 | mheidari-all | 207.126.167.241 |
| 70.58 | vless | 294.9 | 815.8 | 20.95 | 0.0 | 10.0 | 10.27 | 17.36 | Au1rxx-base64 | 159.89.87.21 |
| 70.49 | shadowsocks | 330.3 | 595.9 | 20.13 | 0.0 | 10.0 | 13.93 | 17.36 | Au1rxx-base64 | 108.181.0.177 |
| 70.46 | shadowsocks | 318.1 | 634.1 | 20.41 | 0.0 | 10.0 | 13.93 | 17.36 | Au1rxx-base64 | 173.244.56.9 |
| 70.29 | shadowsocks | 249.5 | 653.2 | 22.0 | 0.0 | 10.0 | 13.93 | 9.86 | DeltaKronecker-all | 108.181.57.93 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.966 | 1.0 | 25 | 73 | prefer |
| Surfboard-tg-mixed | 0.95 | 0.872 | 345 | 4586 | prefer |
| mheidari-all | 0.86 | 0.783 | 212 | 13927 | prefer |
| Au1rxx-base64 | 0.855 | 0.859 | 78 | 126 | prefer |
| DeltaKronecker-all | 0.52 | 0.439 | 139 | 7763 | observe |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4274 | observe |
| Epodonios-all | 0.255 | None | 0 | 6401 | observe |
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
| general | unknown | - | 176 |
| geo | ClientOSError | - | 2 |
| 204 | TimeoutError | - | 2 |
| geo | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
