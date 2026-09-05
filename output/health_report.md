# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-05 09:56:49 |
| 运行耗时 | 274.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 83214 |
| 去重后节点 | 22116 |
| TCP 可达 | 3000 |
| 真实可用 | 546 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22116 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.4 |
| tcp | 37.2 |
| probe | 75.8 |
| real_test | 121.4 |
| generate | 34.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 52788 |
| vmess | 11213 |
| shadowsocks | 9728 |
| trojan | 7839 |
| hysteria2 | 1296 |
| http | 146 |
| shadowsocksr | 131 |
| socks | 53 |
| hysteria | 10 |
| tuic | 10 |

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
| 84.04 | http | 193.6 | 494.6 | 23.3 | 0.0 | 10.0 | 14.5 | 19.24 | zhangkai | 138.199.35.198 |
| 84.01 | http | 194.9 | 495.6 | 23.27 | 0.0 | 10.0 | 14.5 | 19.24 | zhangkai | 138.199.35.216 |
| 83.58 | vless | 203.2 | 531.2 | 23.07 | 0.0 | 10.0 | 10.51 | 20.0 | Au1rxx-base64 | 172.233.139.46 |
| 83.57 | vless | 203.9 | 492.8 | 23.06 | 0.0 | 10.0 | 10.51 | 20.0 | Au1rxx-base64 | 172.235.43.210 |
| 83.1 | hysteria2 | 323.9 | 787.6 | 20.28 | 0.0 | 10.0 | 13.93 | 20.0 | Au1rxx-base64 | 66.94.121.46 |
| 82.89 | shadowsocks | 200.8 | 480.8 | 23.13 | 0.0 | 10.0 | 14.26 | 20.0 | Au1rxx-base64 | 108.181.118.10 |
| 82.62 | shadowsocks | 233.9 | 509.7 | 22.36 | 0.0 | 10.0 | 14.26 | 20.0 | Au1rxx-base64 | 173.244.56.6 |
| 82.06 | shadowsocks | 258.3 | 634.6 | 21.8 | 0.0 | 10.0 | 14.26 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 82.06 | shadowsocks | 258.3 | 633.6 | 21.8 | 0.0 | 10.0 | 14.26 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 80.58 | shadowsocks | 194.4 | 479.7 | 23.28 | 0.0 | 10.0 | 14.26 | 17.54 | Surfboard-tg-mixed | 108.181.0.177 |
| 80.4 | vless | 211.0 | 536.2 | 22.89 | 0.0 | 10.0 | 10.51 | 20.0 | Au1rxx-base64 | 23.94.227.94 |
| 79.62 | shadowsocks | 234.2 | 514.8 | 22.36 | 0.0 | 10.0 | 14.26 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 79.19 | vless | 198.7 | 527.9 | 23.18 | 0.0 | 10.0 | 10.51 | 20.0 | Au1rxx-base64 | 204.44.127.222 |
| 79.14 | shadowsocks | 285.7 | 633.0 | 21.16 | 0.0 | 10.0 | 14.26 | 20.0 | Au1rxx-base64 | 23.150.248.20 |
| 78.53 | vless | 227.2 | 520.4 | 22.52 | 0.0 | 10.0 | 10.51 | 20.0 | Au1rxx-base64 | 162.159.38.127 |
| 78.52 | vless | 212.2 | 509.8 | 22.87 | 0.0 | 10.0 | 10.51 | 20.0 | Au1rxx-base64 | 172.235.38.85 |
| 77.8 | shadowsocks | 289.9 | 618.4 | 21.07 | 0.0 | 10.0 | 14.26 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 77.54 | vless | 217.1 | 501.2 | 22.75 | 0.0 | 10.0 | 10.51 | 20.0 | Au1rxx-base64 | 172.64.42.85 |
| 77.28 | vless | 204.3 | 508.6 | 23.05 | 0.0 | 10.0 | 10.51 | 13.72 | mheidari-all | 216.167.21.32 |
| 76.09 | vless | 342.7 | 706.8 | 19.84 | 0.0 | 10.0 | 10.51 | 20.0 | Au1rxx-base64 | 138.124.60.146 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Au1rxx-base64 | 0.934 | 0.864 | 309 | 1813 | prefer |
| Surfboard-tg-mixed | 0.852 | 0.775 | 182 | 7332 | prefer |
| mheidari-all | 0.836 | 0.76 | 125 | 15508 | prefer |
| DeltaKronecker-all | 0.781 | 0.778 | 18 | 6212 | prefer |
| tg-oneclickvpnkeys | 0.444 | 1.0 | 5 | 118 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 7753 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8562 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6108 | observe |
| barry-far-vless | 0.255 | None | 0 | 6302 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4095 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1813 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 43 |
| geo | ClientOSError | - | 20 |
| cn-block | TimeoutError | - | 17 |
| 204 | ProxyError | - | 11 |
| speed | TimeoutError | - | 7 |
| geo | TimeoutError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| speed | ClientOSError | - | 3 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
