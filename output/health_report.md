# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-02 02:53:29 |
| 运行耗时 | 267.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 76269 |
| 去重后节点 | 23383 |
| TCP 可达 | 3000 |
| 真实可用 | 592 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23383 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.3 |
| tcp | 30.8 |
| probe | 58.1 |
| real_test | 144.3 |
| generate | 28.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43082 |
| trojan | 12923 |
| vmess | 10333 |
| shadowsocks | 9182 |
| hysteria2 | 234 |
| socks | 216 |
| shadowsocksr | 157 |
| http | 135 |
| hysteria | 6 |
| tuic | 1 |

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
| 74.8 | shadowsocks | 256.9 | 632.3 | 21.83 | 0.0 | 10.0 | 11.43 | 15.54 | Au1rxx-base64 | 156.146.38.168 |
| 74.5 | shadowsocks | 269.8 | 668.1 | 21.53 | 0.0 | 10.0 | 11.43 | 15.54 | Au1rxx-base64 | 37.19.198.244 |
| 74.09 | shadowsocks | 252.2 | 622.0 | 21.94 | 0.0 | 10.0 | 11.43 | 15.54 | Au1rxx-base64 | 156.146.38.169 |
| 74.01 | shadowsocks | 291.1 | 742.7 | 21.04 | 0.0 | 10.0 | 11.43 | 15.54 | Au1rxx-base64 | 156.146.38.167 |
| 73.66 | shadowsocks | 267.1 | 659.3 | 21.59 | 0.0 | 10.0 | 11.43 | 15.54 | Au1rxx-base64 | 37.19.198.160 |
| 73.5 | vless | 287.7 | 680.9 | 21.12 | 0.0 | 10.0 | 9.48 | 15.88 | Surfboard-tg-mixed | 104.25.161.29 |
| 73.31 | vless | 306.2 | 769.1 | 20.69 | 0.0 | 10.0 | 9.48 | 13.3 | mheidari-all | 47.253.226.114 |
| 73.24 | shadowsocks | 272.6 | 666.4 | 21.47 | 0.0 | 10.0 | 11.43 | 15.54 | Au1rxx-base64 | 37.19.198.236 |
| 73.18 | vless | 287.3 | 677.0 | 21.13 | 0.0 | 10.0 | 9.48 | 15.88 | Surfboard-tg-mixed | 137.184.218.169 |
| 72.76 | shadowsocks | 248.4 | 609.7 | 22.03 | 0.0 | 10.0 | 11.43 | 13.3 | mheidari-all | 198.98.53.130 |
| 72.69 | vless | 334.9 | 537.4 | 20.03 | 0.0 | 10.0 | 9.48 | 15.88 | Surfboard-tg-mixed | 173.245.59.35 |
| 71.52 | vless | 435.1 | 1114.8 | 17.7 | 0.0 | 10.0 | 9.48 | 15.88 | Surfboard-tg-mixed | 130.107.73.148 |
| 71.17 | shadowsocks | 283.9 | 678.0 | 21.21 | 0.0 | 10.0 | 11.43 | 13.3 | mheidari-all | 108.181.57.93 |
| 70.01 | shadowsocks | 290.9 | 603.3 | 21.04 | 0.0 | 10.0 | 11.43 | 15.54 | Au1rxx-base64 | 149.22.95.183 |
| 69.74 | shadowsocks | 259.6 | 639.9 | 21.77 | 0.0 | 10.0 | 11.43 | 15.54 | Au1rxx-base64 | 37.19.198.243 |
| 69.48 | shadowsocks | 249.2 | 617.4 | 22.01 | 0.0 | 10.0 | 11.43 | 15.54 | Au1rxx-base64 | 156.146.38.170 |
| 69.13 | shadowsocks | 295.9 | 552.5 | 20.93 | 0.0 | 10.0 | 11.43 | 15.54 | Au1rxx-base64 | 173.244.56.9 |
| 68.99 | vless | 298.1 | 713.9 | 20.88 | 0.0 | 10.0 | 9.48 | 10.48 | DeltaKronecker-all | 198.41.209.87 |
| 68.76 | vless | 347.6 | 874.4 | 19.73 | 0.0 | 10.0 | 9.48 | 15.54 | Au1rxx-base64 | 159.89.87.21 |
| 68.13 | shadowsocks | 301.3 | 545.3 | 20.8 | 0.0 | 10.0 | 11.43 | 15.54 | Au1rxx-base64 | 108.181.118.10 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Surfboard-tg-mixed | 0.826 | 0.747 | 344 | 5714 | prefer |
| Au1rxx-base64 | 0.765 | 0.768 | 69 | 103 | prefer |
| mheidari-all | 0.561 | 0.481 | 316 | 16042 | observe |
| DeltaKronecker-all | 0.35 | 0.268 | 343 | 7631 | observe |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4308 | observe |
| Epodonios-all | 0.255 | None | 0 | 6523 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6496 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4236 | observe |
| barry-far-vless | 0.255 | None | 0 | 4744 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5331 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| nscl5-all | 0.221 | None | 0 | 1162 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 232 |
| geo | TimeoutError | - | 154 |
| geo | ClientOSError | - | 53 |
| speed | TimeoutError | - | 39 |
| 204 | ProxyError | - | 14 |
| cn-block | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 8 |
| 204 | TimeoutError | - | 7 |
| 204 | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 2 |
| speed | ClientPayloadError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
