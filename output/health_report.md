# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-22 18:26:44 |
| 运行耗时 | 302.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 86107 |
| 去重后节点 | 23819 |
| TCP 可达 | 3000 |
| 真实可用 | 730 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23819 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.2 |
| geo | 1.5 |
| tcp | 40.4 |
| probe | 61.9 |
| real_test | 153.3 |
| generate | 35.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50398 |
| trojan | 12939 |
| shadowsocks | 10467 |
| vmess | 10304 |
| hysteria2 | 1511 |
| shadowsocksr | 168 |
| http | 168 |
| socks | 117 |
| anytls | 16 |
| hysteria | 11 |
| tuic | 8 |

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
| 82.04 | vless | 259.8 | 641.4 | 21.76 | 0.0 | 10.0 | 11.28 | 20.0 | Au1rxx-base64 | 198.251.78.29 |
| 81.65 | shadowsocks | 259.7 | 637.8 | 21.77 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 81.18 | shadowsocks | 256.7 | 628.3 | 21.83 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 80.65 | vless | 264.6 | 689.5 | 21.65 | 0.0 | 10.0 | 11.28 | 17.72 | Surfboard-tg-mixed | 216.152.147.28 |
| 80.3 | vless | 321.2 | 762.6 | 20.34 | 0.0 | 10.0 | 11.28 | 20.0 | Au1rxx-base64 | 158.69.112.254 |
| 79.64 | shadowsocks | 270.6 | 616.4 | 21.51 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 23.150.248.20 |
| 79.29 | vless | 400.8 | 1047.9 | 18.5 | 0.0 | 10.0 | 11.28 | 20.0 | Au1rxx-base64 | 137.184.218.169 |
| 79.28 | vless | 374.9 | 1000.0 | 19.1 | 0.0 | 10.0 | 11.28 | 20.0 | Au1rxx-base64 | 45.138.100.226 |
| 79.06 | vless | 429.4 | 1117.7 | 17.84 | 0.0 | 10.0 | 11.28 | 20.0 | Au1rxx-base64 | 167.17.69.171 |
| 78.35 | shadowsocks | 303.6 | 780.0 | 20.75 | 0.0 | 10.0 | 13.88 | 17.72 | Surfboard-tg-mixed | 156.146.38.167 |
| 78.06 | vless | 470.8 | 1226.8 | 16.88 | 0.0 | 10.0 | 11.28 | 20.0 | Au1rxx-base64 | 130.107.73.148 |
| 77.19 | shadowsocks | 236.4 | 625.1 | 22.31 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 155.138.136.240 |
| 76.75 | hysteria2 | 263.2 | 659.3 | 21.69 | 0.0 | 10.0 | 14.0 | 12.16 | mheidari-all | 159.223.157.129 |
| 76.56 | trojan | 439.5 | 1149.9 | 17.6 | 0.0 | 10.0 | 14.47 | 20.0 | Au1rxx-base64 | 64.74.163.118 |
| 76.28 | shadowsocks | 304.6 | 632.3 | 20.73 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 149.22.95.183 |
| 76.08 | shadowsocks | 284.1 | 732.2 | 21.2 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 75.96 | vless | 366.9 | 873.0 | 19.29 | 0.0 | 10.0 | 11.28 | 20.0 | Au1rxx-base64 | 169.40.42.15 |
| 75.88 | shadowsocks | 294.4 | 595.3 | 20.96 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 94.72.127.58 |
| 75.71 | shadowsocks | 301.7 | 630.6 | 20.79 | 0.0 | 10.0 | 13.88 | 20.0 | Au1rxx-base64 | 94.72.127.55 |
| 75.58 | vless | 380.6 | 858.5 | 18.97 | 0.0 | 10.0 | 11.28 | 20.0 | Au1rxx-base64 | 38.180.242.205 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.997 | 1.0 | 113 | 144 | prefer |
| Au1rxx-base64 | 0.99 | 0.918 | 499 | 1853 | prefer |
| mheidari-all | 0.865 | 0.792 | 77 | 14443 | prefer |
| Surfboard-tg-mixed | 0.751 | 0.674 | 138 | 6394 | prefer |
| tg-oneclickvpnkeys | 0.318 | 1.0 | 2 | 176 | observe |
| DeltaKronecker-all | 0.291 | 0.25 | 12 | 5015 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5096 | observe |
| Epodonios-all | 0.255 | None | 0 | 6973 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3990 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7145 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5216 | observe |
| barry-far-vless | 0.255 | None | 0 | 5527 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4074 | observe |
| nscl5-all | 0.255 | None | 0 | 3321 | observe |
| Au1rxx-clash | 0.249 | None | 0 | 1853 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 28 |
| cn-block | TimeoutError | - | 28 |
| geo | TimeoutError | - | 18 |
| geo | ClientOSError | - | 11 |
| 204 | ProxyError | - | 8 |
| speed | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 6 |
| speed | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:48638: bind: address already in use | - | 1 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
