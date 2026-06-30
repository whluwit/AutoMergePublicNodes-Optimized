# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-30 09:30:11 |
| 运行耗时 | 237.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 104 |
| 原始节点 | 75285 |
| 去重后节点 | 23005 |
| TCP 可达 | 3000 |
| 真实可用 | 454 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23005 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.4 |
| tcp | 29.9 |
| probe | 55.3 |
| real_test | 108.4 |
| generate | 37.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 41903 |
| trojan | 13027 |
| vmess | 10353 |
| shadowsocks | 9376 |
| hysteria2 | 263 |
| shadowsocksr | 155 |
| http | 135 |
| socks | 66 |
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
| 78.97 | trojan | 285.4 | 646.5 | 21.17 | 0.0 | 10.0 | 12.62 | 16.96 | Surfboard-tg-mixed | 94.140.0.100 |
| 77.94 | shadowsocks | 242.7 | 650.7 | 22.16 | 0.0 | 10.0 | 13.8 | 16.48 | mheidari-all | 108.181.57.93 |
| 76.58 | vless | 259.0 | 732.9 | 21.78 | 0.0 | 10.0 | 8.32 | 16.48 | mheidari-all | 47.253.226.114 |
| 76.44 | shadowsocks | 227.3 | 632.4 | 22.52 | 0.0 | 10.0 | 13.8 | 14.12 | Au1rxx-base64 | 37.19.198.160 |
| 76.42 | shadowsocks | 228.2 | 633.1 | 22.5 | 0.0 | 10.0 | 13.8 | 14.12 | Au1rxx-base64 | 37.19.198.244 |
| 76.41 | shadowsocks | 228.3 | 634.4 | 22.49 | 0.0 | 10.0 | 13.8 | 14.12 | Au1rxx-base64 | 37.19.198.243 |
| 76.37 | shadowsocks | 230.1 | 640.5 | 22.45 | 0.0 | 10.0 | 13.8 | 14.12 | Au1rxx-base64 | 37.19.198.236 |
| 73.62 | shadowsocks | 243.3 | 660.2 | 22.15 | 0.0 | 10.0 | 13.8 | 14.12 | Au1rxx-base64 | tinkered-pennies-puppies.freesocks.work |
| 73.43 | shadowsocks | 277.6 | 640.7 | 21.35 | 0.0 | 10.0 | 13.8 | 14.12 | Au1rxx-base64 | 156.146.38.168 |
| 73.32 | shadowsocks | 279.3 | 643.7 | 21.31 | 0.0 | 10.0 | 13.8 | 14.12 | Au1rxx-base64 | 156.146.38.167 |
| 73.2 | vless | 361.8 | 602.2 | 19.4 | 0.0 | 10.0 | 8.32 | 16.48 | mheidari-all | 162.159.18.241 |
| 73.0 | shadowsocks | 277.8 | 643.3 | 21.35 | 0.0 | 10.0 | 13.8 | 14.12 | Au1rxx-base64 | 156.146.38.169 |
| 70.67 | trojan | 366.0 | 864.5 | 19.31 | 0.0 | 10.0 | 12.62 | 16.48 | mheidari-all | 64.94.95.118 |
| 70.0 | vless | 348.3 | 1011.0 | 19.72 | 0.0 | 10.0 | 8.32 | 16.96 | Surfboard-tg-mixed | 174.129.45.76 |
| 69.49 | shadowsocks | 296.7 | 560.3 | 20.91 | 0.0 | 10.0 | 13.8 | 14.12 | Au1rxx-base64 | 173.244.56.9 |
| 69.34 | shadowsocks | 246.3 | 594.5 | 22.08 | 0.0 | 10.0 | 13.8 | 16.48 | mheidari-all | 198.98.53.130 |
| 69.09 | trojan | 404.5 | 546.8 | 18.41 | 0.0 | 10.0 | 12.62 | 16.96 | Surfboard-tg-mixed | 91.193.58.201 |
| 68.97 | trojan | 444.5 | 754.2 | 17.49 | 0.0 | 10.0 | 12.62 | 16.96 | Surfboard-tg-mixed | 104.18.152.246 |
| 68.88 | shadowsocks | 340.9 | 710.2 | 19.89 | 0.0 | 10.0 | 13.8 | 14.12 | Au1rxx-base64 | 173.244.56.6 |
| 68.71 | trojan | 443.0 | 785.6 | 17.52 | 0.0 | 10.0 | 12.62 | 16.48 | mheidari-all | 104.16.174.117 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.794 | 0.805 | 41 | 95 | prefer |
| Surfboard-tg-mixed | 0.712 | 0.632 | 321 | 5386 | prefer |
| mheidari-all | 0.648 | 0.568 | 227 | 15701 | observe |
| DeltaKronecker-all | 0.585 | 0.505 | 97 | 7352 | observe |
| xiaoji235-airport-v2ray-all | 0.303 | 1.0 | 1 | 1204 | observe |
| nscl5-all | 0.3 | 1.0 | 1 | 1136 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4139 | observe |
| Epodonios-all | 0.255 | None | 0 | 6386 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3981 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6946 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3959 | observe |
| barry-far-vless | 0.255 | None | 0 | 4573 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5353 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 139 |
| geo | TimeoutError | - | 32 |
| 204 | TimeoutError | - | 23 |
| 204 | ClientOSError | - | 19 |
| geo | ClientOSError | - | 17 |
| cn-block | TimeoutError | - | 11 |
| 204 | ProxyError | - | 10 |
| speed | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 4 |
| speed | ProxyError | - | 4 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
