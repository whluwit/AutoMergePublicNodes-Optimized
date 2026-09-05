# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-05 02:43:17 |
| 运行耗时 | 324.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 84220 |
| 去重后节点 | 23645 |
| TCP 可达 | 3000 |
| 真实可用 | 728 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23645 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.5 |
| tcp | 39.0 |
| probe | 87.0 |
| real_test | 154.7 |
| generate | 35.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53098 |
| vmess | 11451 |
| shadowsocks | 9879 |
| trojan | 8055 |
| hysteria2 | 1390 |
| http | 146 |
| shadowsocksr | 124 |
| socks | 51 |
| tuic | 15 |
| hysteria | 10 |
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
| 84.02 | vless | 199.9 | 510.3 | 23.15 | 0.0 | 10.0 | 11.83 | 19.04 | Au1rxx-base64 | 172.233.139.46 |
| 83.74 | vless | 212.2 | 523.9 | 22.87 | 0.0 | 10.0 | 11.83 | 19.04 | Au1rxx-base64 | 38.127.121.44 |
| 83.57 | vless | 219.3 | 527.6 | 22.7 | 0.0 | 10.0 | 11.83 | 19.04 | Au1rxx-base64 | 172.235.38.85 |
| 81.19 | shadowsocks | 193.5 | 469.9 | 23.3 | 0.0 | 10.0 | 13.35 | 19.04 | Au1rxx-base64 | 108.181.0.177 |
| 80.79 | shadowsocks | 210.8 | 506.4 | 22.9 | 0.0 | 10.0 | 13.35 | 19.04 | Au1rxx-base64 | 108.181.118.10 |
| 80.16 | vless | 234.6 | 534.3 | 22.35 | 0.0 | 10.0 | 11.83 | 17.98 | mheidari-all | 104.18.81.92 |
| 80.09 | shadowsocks | 251.6 | 615.8 | 21.95 | 0.0 | 10.0 | 13.35 | 19.04 | Au1rxx-base64 | 156.146.38.167 |
| 79.95 | shadowsocks | 268.6 | 657.3 | 21.56 | 0.0 | 10.0 | 13.35 | 19.04 | Au1rxx-base64 | 173.244.56.6 |
| 79.52 | vless | 199.9 | 517.7 | 23.15 | 0.0 | 10.0 | 11.83 | 19.04 | Au1rxx-base64 | 204.44.127.222 |
| 78.87 | vless | 206.3 | 523.5 | 23.0 | 0.0 | 10.0 | 11.83 | 19.04 | Au1rxx-base64 | 23.94.227.94 |
| 78.87 | vless | 358.1 | 895.4 | 19.49 | 0.0 | 10.0 | 11.83 | 19.04 | Au1rxx-base64 | 31.58.50.200 |
| 78.85 | http | 416.8 | 1167.8 | 18.13 | 0.0 | 10.0 | 14.48 | 19.24 | zhangkai | 138.199.35.198 |
| 78.83 | http | 417.8 | 1159.9 | 18.11 | 0.0 | 10.0 | 14.48 | 19.24 | zhangkai | 138.199.35.216 |
| 78.71 | vless | 213.5 | 536.6 | 22.84 | 0.0 | 10.0 | 11.83 | 19.04 | Au1rxx-base64 | 38.150.33.232 |
| 78.69 | vless | 214.0 | 512.1 | 22.82 | 0.0 | 10.0 | 11.83 | 19.04 | Au1rxx-base64 | 38.246.229.58 |
| 78.51 | shadowsocks | 307.6 | 775.4 | 20.66 | 0.0 | 10.0 | 13.35 | 19.04 | Au1rxx-base64 | 156.146.38.170 |
| 78.43 | shadowsocks | 263.7 | 649.2 | 21.67 | 0.0 | 10.0 | 13.35 | 17.98 | mheidari-all | 156.146.38.168 |
| 77.98 | vless | 266.4 | 611.8 | 21.61 | 0.0 | 10.0 | 11.83 | 19.04 | Au1rxx-base64 | 172.64.154.8 |
| 77.24 | vless | 245.8 | 283.3 | 22.09 | 4.38 | 9.92 | 11.83 | 16.14 | Surfboard-tg-mixed | 31.76.91.72 |
| 76.64 | vless | 324.3 | 460.5 | 20.27 | 0.0 | 10.0 | 11.83 | 19.04 | Au1rxx-base64 | 162.159.0.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.929 | 393 | 1887 | prefer |
| zhangkai | 0.962 | 1.0 | 21 | 144 | prefer |
| Surfboard-tg-mixed | 0.877 | 0.8 | 210 | 7265 | prefer |
| mheidari-all | 0.686 | 0.607 | 229 | 16194 | observe |
| tg-oneclickvpnkeys | 0.554 | 1.0 | 8 | 118 | observe |
| DeltaKronecker-all | 0.35 | 0.265 | 98 | 7089 | observe |
| Epodonios-all | 0.255 | None | 0 | 7727 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8088 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6067 | observe |
| barry-far-vless | 0.255 | None | 0 | 6282 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4095 | observe |
| Au1rxx-clash | 0.25 | None | 0 | 1887 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| 10ium-ScrapeCategorize-Vless | 0.24 | 0.25 | 4 | 4810 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 87 |
| speed | TimeoutError | - | 44 |
| geo | ClientOSError | - | 38 |
| speed | ClientOSError | - | 22 |
| cn-block | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 9 |
| 204 | ProxyError | - | 4 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |
| 204 | ServerDisconnectedError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
