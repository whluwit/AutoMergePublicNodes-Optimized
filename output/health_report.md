# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-27 02:47:19 |
| 运行耗时 | 228.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 76051 |
| 去重后节点 | 22904 |
| TCP 可达 | 3000 |
| 真实可用 | 506 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22904 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| geo | 1.4 |
| tcp | 30.6 |
| probe | 51.9 |
| real_test | 98.5 |
| generate | 41.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 42848 |
| trojan | 11909 |
| vmess | 11191 |
| shadowsocks | 9512 |
| hysteria2 | 253 |
| shadowsocksr | 161 |
| socks | 86 |
| http | 80 |
| hysteria | 8 |
| tuic | 2 |
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
| 75.37 | shadowsocks | 234.3 | 638.7 | 22.35 | 0.0 | 10.0 | 10.48 | 16.54 | Au1rxx-base64 | 37.19.198.160 |
| 74.25 | shadowsocks | 282.8 | 793.6 | 21.23 | 0.0 | 10.0 | 10.48 | 16.54 | Au1rxx-base64 | 37.19.198.244 |
| 74.2 | vless | 297.4 | 811.7 | 20.89 | 0.0 | 10.0 | 7.77 | 16.54 | Au1rxx-base64 | 159.89.87.21 |
| 72.42 | shadowsocks | 232.3 | 636.3 | 22.4 | 0.0 | 10.0 | 10.48 | 16.54 | Au1rxx-base64 | 37.19.198.243 |
| 72.39 | shadowsocks | 276.6 | 774.1 | 21.37 | 0.0 | 10.0 | 10.48 | 16.54 | Au1rxx-base64 | 37.19.198.236 |
| 72.35 | vless | 281.6 | 804.9 | 21.26 | 0.0 | 10.0 | 7.77 | 13.32 | mheidari-all | 47.253.226.114 |
| 72.11 | shadowsocks | 284.8 | 661.3 | 21.19 | 0.0 | 10.0 | 10.48 | 16.54 | Au1rxx-base64 | 156.146.38.167 |
| 72.09 | shadowsocks | 354.7 | 966.3 | 19.57 | 0.0 | 10.0 | 10.48 | 16.54 | Au1rxx-base64 | 172.234.202.34 |
| 71.23 | shadowsocks | 284.8 | 651.0 | 21.19 | 0.0 | 10.0 | 10.48 | 16.54 | Au1rxx-base64 | 156.146.38.170 |
| 71.14 | shadowsocks | 278.2 | 767.3 | 21.34 | 0.0 | 10.0 | 10.48 | 13.32 | mheidari-all | 198.98.53.130 |
| 71.01 | shadowsocks | 287.6 | 670.3 | 21.12 | 0.0 | 10.0 | 10.48 | 16.54 | Au1rxx-base64 | 156.146.38.168 |
| 70.71 | shadowsocks | 287.6 | 641.4 | 21.12 | 0.0 | 10.0 | 10.48 | 16.54 | Au1rxx-base64 | 156.146.38.169 |
| 69.7 | vless | 247.4 | 659.6 | 22.05 | 0.0 | 10.0 | 7.77 | 12.88 | Surfboard-tg-mixed | 137.184.218.169 |
| 69.0 | shadowsocks | 249.8 | 664.1 | 21.99 | 0.0 | 10.0 | 10.48 | 13.32 | mheidari-all | 108.181.57.93 |
| 66.82 | shadowsocks | 335.1 | 579.2 | 20.02 | 0.0 | 10.0 | 10.48 | 16.54 | Au1rxx-base64 | 149.22.95.183 |
| 66.73 | vless | 379.3 | 931.4 | 19.0 | 0.0 | 10.0 | 7.77 | 12.88 | Surfboard-tg-mixed | 15.223.121.250 |
| 66.33 | vless | 265.2 | 652.4 | 21.64 | 0.0 | 10.0 | 7.77 | 7.92 | DeltaKronecker-all | 104.19.142.226 |
| 66.11 | vless | 274.5 | 681.3 | 21.42 | 0.0 | 10.0 | 7.77 | 7.92 | DeltaKronecker-all | 198.41.209.87 |
| 65.25 | shadowsocks | 426.9 | 848.0 | 17.9 | 0.0 | 10.0 | 10.48 | 16.54 | Au1rxx-base64 | 108.181.118.10 |
| 65.18 | vless | 271.8 | 670.8 | 21.49 | 0.0 | 10.0 | 7.77 | 7.92 | DeltaKronecker-all | 104.25.161.29 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.909 | 0.831 | 325 | 5149 | prefer |
| snakem982 | 0.89 | 1.0 | 18 | 39 | prefer |
| mheidari-all | 0.739 | 0.66 | 206 | 16221 | prefer |
| Au1rxx-base64 | 0.64 | 0.643 | 42 | 100 | observe |
| nscl5-all | 0.359 | 1.0 | 2 | 1186 | observe |
| DeltaKronecker-all | 0.342 | 0.26 | 200 | 6283 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 7720 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3973 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7255 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3785 | observe |
| barry-far-vless | 0.255 | None | 0 | 4565 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5248 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 133 |
| geo | TimeoutError | - | 78 |
| geo | ClientOSError | - | 35 |
| cn-block | TimeoutError | - | 13 |
| 204 | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 8 |
| speed | TimeoutError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| 204 | ProxyError | - | 4 |
| cn-block | ProxyError | - | 1 |
| geo | status | 403 | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 296 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
