# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-05 14:30:55 |
| 运行耗时 | 254.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 83776 |
| 去重后节点 | 22573 |
| TCP 可达 | 3000 |
| 真实可用 | 554 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22573 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.3 |
| tcp | 37.9 |
| probe | 67.5 |
| real_test | 113.9 |
| generate | 29.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53118 |
| vmess | 11398 |
| shadowsocks | 9675 |
| trojan | 8013 |
| hysteria2 | 1222 |
| http | 146 |
| shadowsocksr | 130 |
| socks | 54 |
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
| 82.46 | vless | 227.8 | 603.7 | 22.5 | 0.0 | 10.0 | 11.28 | 18.68 | Au1rxx-base64 | 172.233.139.46 |
| 81.6 | vless | 265.3 | 654.3 | 21.64 | 0.0 | 10.0 | 11.28 | 18.68 | Au1rxx-base64 | 172.235.43.210 |
| 81.06 | shadowsocks | 199.1 | 474.9 | 23.17 | 0.0 | 10.0 | 13.71 | 18.68 | Au1rxx-base64 | 108.181.0.177 |
| 80.9 | shadowsocks | 205.8 | 474.0 | 23.01 | 0.0 | 10.0 | 13.71 | 18.68 | Au1rxx-base64 | 108.181.118.10 |
| 80.81 | shadowsocks | 231.5 | 537.9 | 22.42 | 0.0 | 10.0 | 13.71 | 18.68 | Au1rxx-base64 | 173.244.56.6 |
| 80.24 | vless | 237.5 | 618.3 | 22.28 | 0.0 | 10.0 | 11.28 | 18.68 | Au1rxx-base64 | 23.94.227.94 |
| 79.98 | trojan | 209.7 | 533.5 | 22.92 | 0.0 | 10.0 | 13.38 | 18.68 | Au1rxx-base64 | 107.150.105.84 |
| 79.36 | shadowsocks | 254.8 | 621.1 | 21.88 | 0.0 | 10.0 | 13.71 | 18.68 | Au1rxx-base64 | 156.146.38.170 |
| 79.14 | vless | 241.8 | 611.5 | 22.18 | 0.0 | 10.0 | 11.28 | 18.68 | Au1rxx-base64 | 38.246.229.58 |
| 78.37 | vless | 210.2 | 515.1 | 22.91 | 0.0 | 10.0 | 11.28 | 18.68 | Au1rxx-base64 | 204.44.127.222 |
| 78.37 | hysteria2 | 431.9 | 1047.1 | 17.78 | 0.0 | 10.0 | 14.06 | 18.68 | Au1rxx-base64 | 66.94.121.46 |
| 77.65 | vless | 357.7 | 872.5 | 19.5 | 0.0 | 10.0 | 11.28 | 18.68 | Au1rxx-base64 | 15.204.97.216 |
| 77.57 | trojan | 304.9 | 681.2 | 20.72 | 0.0 | 10.0 | 13.38 | 18.68 | Au1rxx-base64 | 64.94.95.115 |
| 77.5 | http | 479.3 | 1357.2 | 16.68 | 0.0 | 10.0 | 14.5 | 19.32 | zhangkai | 138.199.35.198 |
| 77.43 | shadowsocks | 264.0 | 645.2 | 21.67 | 0.0 | 10.0 | 13.71 | 16.72 | mheidari-all | 156.146.38.168 |
| 77.37 | shadowsocks | 285.8 | 631.5 | 21.16 | 0.0 | 10.0 | 13.71 | 18.68 | Au1rxx-base64 | 23.150.248.20 |
| 77.25 | vless | 237.2 | 619.4 | 22.29 | 0.0 | 10.0 | 11.28 | 18.68 | Au1rxx-base64 | 38.209.125.45 |
| 77.2 | http | 478.9 | 1349.2 | 16.69 | 0.0 | 10.0 | 14.5 | 19.32 | zhangkai | 138.199.35.216 |
| 77.02 | vless | 246.9 | 652.0 | 22.06 | 0.0 | 10.0 | 11.28 | 18.68 | Au1rxx-base64 | 198.44.36.41 |
| 76.88 | shadowsocks | 230.2 | 544.6 | 22.45 | 0.0 | 10.0 | 13.71 | 16.72 | mheidari-all | 173.244.56.9 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.993 | 0.928 | 401 | 1685 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Surfboard-tg-mixed | 0.823 | 0.746 | 138 | 7313 | prefer |
| mheidari-all | 0.82 | 0.75 | 48 | 16245 | prefer |
| DeltaKronecker-all | 0.801 | 1.0 | 13 | 6212 | prefer |
| tg-oneclickvpnkeys | 0.482 | 1.0 | 6 | 118 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 52 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4887 | observe |
| Epodonios-all | 0.255 | None | 0 | 7776 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8453 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6193 | observe |
| barry-far-vless | 0.255 | None | 0 | 6414 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4095 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 19 |
| 204 | TimeoutError | - | 13 |
| cn-block | TimeoutError | - | 13 |
| cn-block | ClientOSError | - | 9 |
| speed | TimeoutError | - | 7 |
| 204 | ClientOSError | - | 3 |
| 204 | ProxyError | - | 3 |
| speed | ClientOSError | - | 3 |
| geo | TimeoutError | - | 3 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:46280: bind: address already in use | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
