# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-23 13:51:04 |
| 运行耗时 | 292.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 83423 |
| 去重后节点 | 22782 |
| TCP 可达 | 3000 |
| 真实可用 | 624 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22782 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 14.5 |
| geo | 1.6 |
| tcp | 32.8 |
| probe | 61.8 |
| real_test | 155.0 |
| generate | 27.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 48263 |
| trojan | 14071 |
| shadowsocks | 10360 |
| vmess | 10084 |
| hysteria2 | 426 |
| shadowsocksr | 79 |
| socks | 56 |
| http | 50 |
| tuic | 17 |
| hysteria | 14 |
| anytls | 3 |

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
| 75.1 | vless | 236.6 | 587.7 | 22.3 | 0.0 | 10.0 | 4.22 | 18.58 | mheidari-all | 154.193.55.183 |
| 74.79 | trojan | 466.5 | 1199.2 | 16.98 | 0.0 | 10.0 | 13.99 | 18.58 | mheidari-all | 163.245.196.68 |
| 71.91 | trojan | 333.5 | 619.7 | 20.06 | 0.0 | 10.0 | 13.99 | 18.58 | mheidari-all | 54.70.42.11 |
| 71.47 | trojan | 432.3 | 741.3 | 17.77 | 0.0 | 9.75 | 13.99 | 18.58 | mheidari-all | 91.107.145.13 |
| 70.04 | trojan | 333.5 | 624.9 | 20.06 | 0.0 | 10.0 | 13.99 | 18.58 | mheidari-all | 35.89.240.174 |
| 69.76 | trojan | 329.5 | 626.1 | 20.15 | 0.0 | 10.0 | 13.99 | 18.58 | mheidari-all | 54.245.13.147 |
| 69.58 | vless | 279.4 | 531.5 | 21.31 | 0.0 | 10.0 | 4.22 | 18.58 | mheidari-all | 104.16.9.20 |
| 69.4 | trojan | 347.8 | 660.4 | 19.73 | 0.0 | 10.0 | 13.99 | 18.58 | mheidari-all | 44.255.92.71 |
| 69.17 | trojan | 336.9 | 641.0 | 19.98 | 0.0 | 10.0 | 13.99 | 18.58 | mheidari-all | 35.163.152.150 |
| 69.12 | trojan | 491.0 | 814.5 | 16.41 | 0.0 | 9.95 | 13.99 | 18.58 | mheidari-all | 108.131.197.101 |
| 68.85 | trojan | 494.4 | 851.8 | 16.33 | 0.0 | 9.95 | 13.99 | 18.58 | mheidari-all | 3.255.155.50 |
| 68.77 | vless | 324.2 | 685.9 | 20.27 | 0.0 | 10.0 | 4.22 | 18.58 | mheidari-all | 45.206.5.122 |
| 68.75 | trojan | 500.3 | 847.4 | 16.2 | 0.0 | 9.95 | 13.99 | 18.58 | mheidari-all | 3.255.100.31 |
| 68.69 | trojan | 503.3 | 858.4 | 16.13 | 0.0 | 9.97 | 13.99 | 18.58 | mheidari-all | 108.131.117.154 |
| 68.6 | trojan | 503.9 | 851.4 | 16.11 | 0.0 | 9.95 | 13.99 | 18.58 | mheidari-all | 18.202.244.191 |
| 68.36 | trojan | 506.3 | 814.0 | 16.06 | 0.0 | 9.88 | 13.99 | 18.58 | mheidari-all | 52.208.138.36 |
| 68.21 | trojan | 504.1 | 807.8 | 16.11 | 0.0 | 9.8 | 13.99 | 18.58 | mheidari-all | 79.133.126.190 |
| 68.16 | trojan | 519.1 | 864.0 | 15.76 | 0.0 | 9.83 | 13.99 | 18.58 | mheidari-all | 193.169.239.214 |
| 68.08 | trojan | 520.0 | 853.6 | 15.74 | 0.0 | 9.88 | 13.99 | 18.58 | mheidari-all | 79.133.126.137 |
| 67.97 | trojan | 579.0 | 851.1 | 14.37 | 0.0 | 10.0 | 13.99 | 18.58 | mheidari-all | 104.18.152.208 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| DeltaKronecker-all | 0.895 | 0.819 | 149 | 5572 | prefer |
| Surfboard-tg-mixed | 0.813 | 0.739 | 88 | 5390 | prefer |
| mheidari-all | 0.717 | 0.638 | 613 | 19424 | prefer |
| Au1rxx-base64 | 0.566 | 1.0 | 8 | 432 | observe |
| xiaoji235-airport-v2ray-all | 0.391 | 1.0 | 2 | 4399 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4757 | observe |
| Epodonios-all | 0.255 | None | 0 | 6487 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3975 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7288 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4196 | observe |
| barry-far-vless | 0.255 | None | 0 | 4775 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4954 | observe |
| nscl5-all | 0.255 | None | 0 | 2435 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 103 |
| speed | ClientOSError | - | 67 |
| 204 | TimeoutError | - | 32 |
| cn-block | TimeoutError | - | 32 |
| geo | ClientOSError | - | 13 |
| 204 | ProxyError | - | 12 |
| speed | TimeoutError | - | 9 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
