# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-17 10:16:34 |
| 运行耗时 | 817.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99237 |
| 去重后节点 | 27753 |
| TCP 可达 | 3000 |
| 真实可用 | 440 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27753 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.3 |
| geo | 1.5 |
| tcp | 48.9 |
| probe | 318.1 |
| real_test | 340.6 |
| generate | 100.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58041 |
| vmess | 16613 |
| shadowsocks | 12038 |
| trojan | 10221 |
| hysteria2 | 1329 |
| http | 717 |
| shadowsocksr | 168 |
| socks | 61 |
| anytls | 26 |
| hysteria | 17 |
| tuic | 6 |

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
| 80.88 | shadowsocks | 210.9 | 567.2 | 22.9 | 0.0 | 8.68 | 14.0 | 19.3 | Au1rxx-base64 | 149.22.95.183 |
| 78.72 | hysteria2 | 340.0 | 751.8 | 19.91 | 0.0 | 10.0 | 14.29 | 19.3 | Au1rxx-base64 | 129.213.91.185 |
| 76.77 | vless | 319.0 | 822.9 | 20.39 | 0.0 | 8.3 | 8.78 | 19.3 | Au1rxx-base64 | tk1.high-speed-test-56424.me |
| 75.48 | vless | 285.3 | 541.8 | 21.17 | 0.0 | 9.1 | 8.78 | 19.3 | Au1rxx-base64 | 195.123.240.65 |
| 75.36 | shadowsocks | 275.3 | 320.1 | 21.41 | 3.0 | 8.65 | 14.0 | 19.3 | Au1rxx-base64 | 149.22.87.240 |
| 75.25 | shadowsocks | 275.2 | 325.2 | 21.41 | 2.81 | 8.66 | 14.0 | 19.3 | Au1rxx-base64 | 149.22.87.241 |
| 75.24 | vless | 300.1 | 532.3 | 20.83 | 0.0 | 8.84 | 8.78 | 19.3 | Au1rxx-base64 | 95.111.212.241 |
| 75.1 | shadowsocks | 276.6 | 329.2 | 21.38 | 2.65 | 8.65 | 14.0 | 19.3 | Au1rxx-base64 | 149.22.87.204 |
| 75.01 | trojan | 317.9 | 305.2 | 20.42 | 3.56 | 8.79 | 12.6 | 19.3 | Au1rxx-base64 | 108.61.186.37 |
| 74.64 | vless | 262.8 | 581.3 | 21.69 | 0.0 | 8.87 | 8.78 | 19.3 | Au1rxx-base64 | 154.29.159.211 |
| 74.32 | shadowsocks | 314.3 | 675.1 | 20.5 | 0.0 | 8.68 | 14.0 | 19.3 | Au1rxx-base64 | 156.146.38.170 |
| 73.8 | shadowsocks | 314.9 | 676.7 | 20.49 | 0.0 | 8.72 | 14.0 | 19.3 | Au1rxx-base64 | 156.146.38.169 |
| 73.55 | vless | 479.5 | 1339.2 | 16.68 | 0.0 | 8.79 | 8.78 | 19.3 | Au1rxx-base64 | 51.81.203.63 |
| 73.52 | vless | 324.5 | 717.2 | 20.27 | 0.0 | 8.76 | 8.78 | 19.3 | Au1rxx-base64 | 147.45.60.160 |
| 73.45 | shadowsocks | 323.7 | 700.0 | 20.28 | 0.0 | 8.68 | 14.0 | 19.3 | Au1rxx-base64 | 156.146.38.168 |
| 72.4 | shadowsocks | 330.5 | 623.7 | 20.13 | 0.0 | 8.67 | 14.0 | 19.3 | Au1rxx-base64 | 173.244.56.6 |
| 72.37 | vless | 320.0 | 336.1 | 20.37 | 2.4 | 8.74 | 8.78 | 19.3 | Au1rxx-base64 | 43.167.232.174 |
| 72.22 | vless | 247.5 | 534.1 | 22.05 | 0.0 | 8.9 | 8.78 | 19.3 | Au1rxx-base64 | 176.122.183.26 |
| 71.98 | vless | 384.1 | 905.3 | 18.89 | 0.0 | 9.11 | 8.78 | 19.3 | Au1rxx-base64 | 154.9.241.170 |
| 71.78 | shadowsocks | 376.9 | 805.1 | 19.05 | 0.0 | 8.68 | 14.0 | 19.3 | Au1rxx-base64 | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.91 | 0.832 | 440 | 1993 | prefer |
| mheidari-all | 0.595 | 0.692 | 13 | 23828 | observe |
| Surfboard-tg-mixed | 0.512 | 0.429 | 35 | 7109 | observe |
| ermaozi | 0.479 | 0.45 | 100 | 702 | observe |
| DeltaKronecker-all | 0.361 | 0.278 | 18 | 4999 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4986 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1993 | observe |
| Epodonios-all | 0.255 | None | 0 | 7611 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9902 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5597 | observe |
| barry-far-vless | 0.255 | None | 0 | 5842 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4255 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 44 |
| 204 | TimeoutError | - | 38 |
| speed | TimeoutError | - | 17 |
| speed | ClientOSError | - | 17 |
| 204 | ProxyConnectionError | - | 13 |
| geo | ClientOSError | - | 13 |
| cn-block | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 7 |
| geo | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| cn-block | status | 530 | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
