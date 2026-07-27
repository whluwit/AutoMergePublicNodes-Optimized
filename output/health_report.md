# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-27 09:47:19 |
| 运行耗时 | 357.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 84233 |
| 去重后节点 | 22882 |
| TCP 可达 | 3000 |
| 真实可用 | 882 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22882 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.5 |
| tcp | 31.2 |
| probe | 63.8 |
| real_test | 209.5 |
| generate | 45.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 46867 |
| trojan | 15547 |
| shadowsocks | 10533 |
| vmess | 10337 |
| hysteria2 | 622 |
| shadowsocksr | 103 |
| socks | 93 |
| http | 84 |
| anytls | 22 |
| hysteria | 13 |
| tuic | 12 |

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
| 83.58 | trojan | 249.2 | 681.3 | 22.01 | 0.0 | 10.0 | 14.57 | 20.0 | Au1rxx-base64 | 153.75.250.171 |
| 82.26 | shadowsocks | 215.8 | 586.0 | 22.78 | 0.0 | 10.0 | 13.48 | 20.0 | Au1rxx-base64 | 198.98.53.130 |
| 82.18 | hysteria2 | 231.4 | 640.6 | 22.42 | 0.0 | 10.0 | 12.86 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 82.04 | shadowsocks | 225.2 | 619.0 | 22.56 | 0.0 | 10.0 | 13.48 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 81.76 | shadowsocks | 237.5 | 662.4 | 22.28 | 0.0 | 10.0 | 13.48 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 81.66 | shadowsocks | 241.6 | 673.6 | 22.18 | 0.0 | 10.0 | 13.48 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 80.26 | shadowsocks | 302.5 | 851.6 | 20.78 | 0.0 | 10.0 | 13.48 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 79.26 | shadowsocks | 272.9 | 629.6 | 21.46 | 0.0 | 10.0 | 13.48 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 78.64 | trojan | 304.3 | 658.3 | 20.73 | 0.0 | 10.0 | 14.57 | 20.0 | Au1rxx-base64 | 163.245.196.68 |
| 78.55 | shadowsocks | 281.4 | 647.5 | 21.26 | 0.0 | 10.0 | 13.48 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 78.4 | shadowsocks | 272.1 | 624.2 | 21.48 | 0.0 | 10.0 | 13.48 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 78.22 | shadowsocks | 355.8 | 899.5 | 19.54 | 0.0 | 10.0 | 13.48 | 20.0 | Au1rxx-base64 | 185.196.61.82 |
| 76.81 | trojan | 345.9 | 864.2 | 19.77 | 0.0 | 10.0 | 14.57 | 16.3 | DeltaKronecker-all | 64.74.163.118 |
| 76.18 | shadowsocks | 323.3 | 730.7 | 20.29 | 0.0 | 10.0 | 13.48 | 20.0 | Au1rxx-base64 | 108.181.57.93 |
| 75.21 | hysteria2 | 360.2 | 702.3 | 19.44 | 0.0 | 10.0 | 12.86 | 20.0 | Au1rxx-base64 | 62.210.124.146 |
| 74.43 | hysteria2 | 426.8 | 875.4 | 17.9 | 0.0 | 10.0 | 12.86 | 20.0 | Au1rxx-base64 | 5.255.102.165 |
| 74.35 | shadowsocks | 281.0 | 652.0 | 21.27 | 0.0 | 10.0 | 13.48 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 74.3 | shadowsocks | 318.5 | 581.7 | 20.4 | 0.0 | 10.0 | 13.48 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 73.83 | shadowsocks | 333.7 | 613.4 | 20.05 | 0.0 | 10.0 | 13.48 | 20.0 | Au1rxx-base64 | 108.181.0.177 |
| 73.76 | trojan | 333.8 | 756.6 | 20.05 | 0.0 | 10.0 | 14.57 | 20.0 | Au1rxx-base64 | 64.94.95.118 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.991 | 1.0 | 76 | 86 | prefer |
| Au1rxx-base64 | 0.963 | 0.909 | 429 | 1407 | prefer |
| mheidari-all | 0.906 | 0.829 | 240 | 19339 | prefer |
| Surfboard-tg-mixed | 0.549 | 0.469 | 192 | 5483 | observe |
| tg-oneclickvpnkeys | 0.482 | 1.0 | 6 | 132 | observe |
| DeltaKronecker-all | 0.478 | 0.397 | 302 | 5643 | observe |
| xiaoji235-airport-v2ray-all | 0.287 | 0.5 | 2 | 3959 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4831 | observe |
| Epodonios-all | 0.255 | None | 0 | 6410 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3971 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6188 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4173 | observe |
| barry-far-vless | 0.255 | None | 0 | 4692 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5017 | observe |
| Au1rxx-clash | 0.231 | None | 0 | 1407 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 149 |
| speed | ClientOSError | - | 67 |
| geo | ClientOSError | - | 40 |
| 204 | ProxyError | - | 23 |
| 204 | TimeoutError | - | 22 |
| cn-block | TimeoutError | - | 20 |
| speed | TimeoutError | - | 19 |
| cn-block | ClientOSError | - | 9 |
| cn-block | ProxyError | - | 7 |
| 204 | ClientOSError | - | 7 |
| speed | ProxyError | - | 4 |
| geo | ProxyError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
