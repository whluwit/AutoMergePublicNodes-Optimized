# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-18 10:37:54 |
| 运行耗时 | 663.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83517 |
| 去重后节点 | 22969 |
| TCP 可达 | 3000 |
| 真实可用 | 398 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22969 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.6 |
| tcp | 37.8 |
| probe | 277.7 |
| real_test | 260.8 |
| generate | 79.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49726 |
| vmess | 13257 |
| shadowsocks | 10073 |
| trojan | 8225 |
| hysteria2 | 1377 |
| http | 649 |
| shadowsocksr | 127 |
| socks | 69 |
| hysteria | 8 |
| anytls | 4 |
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
| 82.78 | hysteria2 | 245.9 | 550.5 | 22.09 | 0.0 | 10.0 | 14.29 | 19.42 | Au1rxx-base64 | 66.94.121.46 |
| 82.19 | shadowsocks | 203.6 | 481.3 | 23.06 | 0.0 | 10.0 | 14.21 | 19.42 | Au1rxx-base64 | 108.181.118.10 |
| 80.31 | shadowsocks | 263.3 | 644.9 | 21.68 | 0.0 | 10.0 | 14.21 | 19.42 | Au1rxx-base64 | 156.146.38.167 |
| 78.94 | shadowsocks | 262.7 | 639.4 | 21.7 | 0.0 | 10.0 | 14.21 | 19.42 | Au1rxx-base64 | 156.146.38.169 |
| 78.03 | vless | 198.0 | 476.4 | 23.2 | 0.0 | 10.0 | 6.41 | 19.42 | Au1rxx-base64 | 45.149.172.80 |
| 77.69 | vless | 255.8 | 642.4 | 21.86 | 0.0 | 10.0 | 6.41 | 19.42 | Au1rxx-base64 | 198.200.42.129 |
| 75.58 | shadowsocks | 460.0 | 226.7 | 17.13 | 6.5 | 9.82 | 14.21 | 19.42 | Au1rxx-base64 | 84.247.155.196 |
| 73.78 | shadowsocks | 242.5 | 577.6 | 22.17 | 0.0 | 10.0 | 14.21 | 11.9 | Surfboard-tg-mixed | 108.181.0.177 |
| 73.46 | vless | 303.6 | 673.8 | 20.75 | 0.0 | 10.0 | 6.41 | 19.42 | Au1rxx-base64 | 38.180.242.205 |
| 73.3 | vless | 330.0 | 746.4 | 20.14 | 0.0 | 10.0 | 6.41 | 19.42 | Au1rxx-base64 | 79.141.172.154 |
| 73.08 | vless | 217.0 | 463.3 | 22.75 | 0.0 | 10.0 | 6.41 | 19.42 | Au1rxx-base64 | 104.18.39.218 |
| 72.78 | http | 400.2 | 1119.8 | 18.51 | 0.0 | 10.0 | 11.25 | 16.02 | ermaozi | 138.199.35.207 |
| 72.66 | http | 405.6 | 1131.4 | 18.39 | 0.0 | 10.0 | 11.25 | 16.02 | ermaozi | 138.199.35.210 |
| 72.64 | http | 406.3 | 1128.3 | 18.37 | 0.0 | 10.0 | 11.25 | 16.02 | ermaozi | 138.199.35.215 |
| 72.35 | shadowsocks | 258.2 | 650.7 | 21.8 | 0.0 | 10.0 | 14.21 | 10.34 | mheidari-all | 173.244.56.6 |
| 72.33 | shadowsocks | 259.1 | 635.4 | 21.78 | 0.0 | 10.0 | 14.21 | 10.34 | mheidari-all | 156.146.38.168 |
| 72.26 | shadowsocks | 262.3 | 642.2 | 21.71 | 0.0 | 10.0 | 14.21 | 10.34 | mheidari-all | 156.146.38.170 |
| 72.17 | http | 426.6 | 1102.0 | 17.9 | 0.0 | 10.0 | 11.25 | 16.02 | ermaozi | 138.199.35.218 |
| 72.15 | http | 427.4 | 1101.7 | 17.88 | 0.0 | 10.0 | 11.25 | 16.02 | ermaozi | 138.199.35.216 |
| 72.13 | http | 428.5 | 1103.3 | 17.86 | 0.0 | 10.0 | 11.25 | 16.02 | ermaozi | 138.199.35.201 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.885 | 0.823 | 260 | 1622 | prefer |
| ermaozi | 0.729 | 0.723 | 47 | 378 | prefer |
| mheidari-all | 0.716 | 0.641 | 64 | 15778 | prefer |
| Surfboard-tg-mixed | 0.658 | 0.579 | 152 | 7294 | observe |
| DeltaKronecker-all | 0.44 | 0.354 | 48 | 6040 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4241 | observe |
| ermaozi-get_subscribe | 0.327 | 1.0 | 2 | 402 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 7751 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8957 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5763 | observe |
| barry-far-vless | 0.255 | None | 0 | 5979 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1622 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 40 |
| geo | TimeoutError | - | 27 |
| 204 | ProxyError | - | 25 |
| geo | ClientOSError | - | 25 |
| cn-block | TimeoutError | - | 19 |
| speed | TimeoutError | - | 18 |
| speed | ClientOSError | - | 10 |
| cn-block | ClientOSError | - | 8 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
