# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-26 19:45:48 |
| 运行耗时 | 233.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 75714 |
| 去重后节点 | 22771 |
| TCP 可达 | 3000 |
| 真实可用 | 296 |
| Verified 输出 | 296 |
| Global 输出 | 300 |
| All 输出 | 22771 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| geo | 1.3 |
| tcp | 30.8 |
| probe | 58.3 |
| real_test | 97.8 |
| generate | 41.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 42606 |
| trojan | 11601 |
| vmess | 11440 |
| shadowsocks | 9496 |
| hysteria2 | 254 |
| shadowsocksr | 164 |
| http | 80 |
| socks | 63 |
| hysteria | 8 |
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
| 76.73 | shadowsocks | 252.7 | 622.7 | 21.93 | 0.0 | 10.0 | 12.2 | 16.6 | Au1rxx-base64 | 156.146.38.167 |
| 76.71 | shadowsocks | 253.6 | 641.1 | 21.91 | 0.0 | 10.0 | 12.2 | 16.6 | Au1rxx-base64 | 156.146.38.170 |
| 75.98 | shadowsocks | 241.5 | 595.7 | 22.19 | 0.0 | 10.0 | 12.2 | 16.6 | Au1rxx-base64 | 156.146.38.168 |
| 74.13 | vless | 329.2 | 793.0 | 20.16 | 0.0 | 10.0 | 9.5 | 15.98 | mheidari-all | 47.253.226.114 |
| 73.58 | shadowsocks | 248.9 | 641.9 | 22.02 | 0.0 | 10.0 | 12.2 | 16.6 | Au1rxx-base64 | 156.146.38.169 |
| 73.51 | vless | 281.5 | 558.2 | 21.26 | 0.0 | 10.0 | 9.5 | 16.6 | Au1rxx-base64 | 144.34.235.155 |
| 73.3 | shadowsocks | 299.0 | 697.0 | 20.86 | 0.0 | 10.0 | 12.2 | 16.6 | Au1rxx-base64 | 37.19.198.244 |
| 71.6 | shadowsocks | 339.9 | 846.9 | 19.91 | 0.0 | 10.0 | 12.2 | 16.6 | Au1rxx-base64 | 37.19.198.160 |
| 71.26 | shadowsocks | 389.0 | 1011.0 | 18.77 | 0.0 | 10.0 | 12.2 | 16.6 | Au1rxx-base64 | 172.234.202.34 |
| 70.91 | shadowsocks | 287.2 | 557.2 | 21.13 | 0.0 | 10.0 | 12.2 | 16.6 | Au1rxx-base64 | 173.244.56.9 |
| 70.88 | shadowsocks | 311.8 | 628.3 | 20.56 | 0.0 | 10.0 | 12.2 | 16.6 | Au1rxx-base64 | 149.22.95.183 |
| 70.42 | shadowsocks | 296.5 | 696.1 | 20.92 | 0.0 | 10.0 | 12.2 | 16.6 | Au1rxx-base64 | 37.19.198.236 |
| 70.29 | shadowsocks | 323.7 | 727.8 | 20.28 | 0.0 | 10.0 | 12.2 | 15.98 | mheidari-all | 198.98.53.130 |
| 70.15 | shadowsocks | 328.7 | 697.1 | 20.17 | 0.0 | 10.0 | 12.2 | 16.6 | Au1rxx-base64 | 173.244.56.6 |
| 68.98 | shadowsocks | 406.3 | 963.6 | 18.37 | 0.0 | 10.0 | 12.2 | 15.98 | mheidari-all | 108.181.57.93 |
| 68.77 | vless | 428.2 | 922.2 | 17.86 | 0.0 | 10.0 | 9.5 | 16.6 | Au1rxx-base64 | 15.204.97.214 |
| 68.5 | vless | 424.9 | 931.3 | 17.94 | 0.0 | 10.0 | 9.5 | 16.6 | Au1rxx-base64 | 15.204.97.219 |
| 68.4 | vless | 420.7 | 973.0 | 18.04 | 0.0 | 10.0 | 9.5 | 15.6 | Surfboard-tg-mixed | 15.223.121.250 |
| 67.01 | shadowsocks | 293.5 | 687.6 | 20.98 | 0.0 | 10.0 | 12.2 | 16.6 | Au1rxx-base64 | 37.19.198.243 |
| 66.79 | vless | 484.7 | 1083.0 | 16.56 | 0.0 | 10.0 | 9.5 | 15.98 | mheidari-all | 34.213.172.16 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.89 | 1.0 | 18 | 39 | prefer |
| Au1rxx-base64 | 0.827 | 0.844 | 32 | 86 | prefer |
| mheidari-all | 0.666 | 0.587 | 143 | 16147 | observe |
| Surfboard-tg-mixed | 0.644 | 0.565 | 239 | 5075 | observe |
| DeltaKronecker-all | 0.396 | 0.312 | 93 | 6283 | observe |
| nscl5-all | 0.302 | 1.0 | 1 | 1175 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4567 | observe |
| Epodonios-all | 0.255 | None | 0 | 7688 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3985 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7108 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3761 | observe |
| barry-far-vless | 0.255 | None | 0 | 4543 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5248 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 82 |
| 204 | TimeoutError | - | 49 |
| cn-block | TimeoutError | - | 24 |
| 204 | ProxyError | - | 18 |
| 204 | ClientOSError | - | 18 |
| geo | TimeoutError | - | 14 |
| geo | ClientOSError | - | 9 |
| cn-block | ClientOSError | - | 7 |
| speed | TimeoutError | - | 6 |
| geo | ProxyError | - | 3 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 296 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
