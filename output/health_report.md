# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-20 21:19:15 |
| 运行耗时 | 572.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 94585 |
| 去重后节点 | 26418 |
| TCP 可达 | 3000 |
| 真实可用 | 370 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26418 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 1.5 |
| tcp | 44.4 |
| probe | 223.7 |
| real_test | 219.8 |
| generate | 78.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56382 |
| vmess | 16876 |
| shadowsocks | 11690 |
| trojan | 8108 |
| hysteria2 | 1140 |
| shadowsocksr | 163 |
| http | 97 |
| socks | 70 |
| anytls | 36 |
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
| 78.67 | vless | 219.3 | 489.6 | 22.7 | 0.0 | 10.0 | 10.09 | 15.88 | mheidari-all | 47.251.108.158 |
| 78.52 | vless | 204.0 | 504.4 | 23.06 | 0.0 | 9.25 | 10.09 | 16.12 | Au1rxx-base64 | 154.29.145.196 |
| 77.91 | hysteria2 | 259.5 | 622.3 | 21.77 | 0.0 | 9.23 | 11.79 | 16.12 | Au1rxx-base64 | 66.94.121.46 |
| 77.91 | vless | 262.7 | 665.1 | 21.7 | 0.0 | 10.0 | 10.09 | 16.12 | Au1rxx-base64 | 154.12.38.159 |
| 77.59 | vless | 246.3 | 622.9 | 22.08 | 0.0 | 9.3 | 10.09 | 16.12 | Au1rxx-base64 | 45.63.53.81 |
| 77.01 | hysteria2 | 195.0 | 518.2 | 23.26 | 0.0 | 10.0 | 11.79 | 15.7 | Surfboard-tg-mixed | 179.255.104.98 |
| 76.65 | vless | 250.2 | 556.5 | 21.99 | 0.0 | 9.28 | 10.09 | 16.12 | Au1rxx-base64 | 23.95.222.127 |
| 76.15 | shadowsocks | 261.4 | 630.9 | 21.73 | 0.0 | 10.0 | 12.86 | 15.88 | mheidari-all | 156.146.38.170 |
| 76.14 | shadowsocks | 255.9 | 621.9 | 21.85 | 0.0 | 10.0 | 12.86 | 15.7 | Surfboard-tg-mixed | 156.146.38.169 |
| 75.9 | shadowsocks | 262.6 | 635.3 | 21.7 | 0.0 | 9.22 | 12.86 | 16.12 | Au1rxx-base64 | 156.146.38.167 |
| 74.81 | shadowsocks | 262.8 | 629.7 | 21.69 | 0.0 | 9.19 | 12.86 | 16.12 | Au1rxx-base64 | 156.146.38.168 |
| 72.85 | shadowsocks | 287.2 | 636.3 | 21.13 | 0.0 | 10.0 | 12.86 | 16.12 | Au1rxx-base64 | 149.22.95.183 |
| 72.56 | hysteria2 | 324.2 | 752.7 | 20.27 | 0.0 | 9.18 | 11.79 | 16.12 | Au1rxx-base64 | 129.213.91.185 |
| 71.94 | shadowsocks | 195.1 | 516.6 | 23.26 | 0.0 | 9.2 | 12.86 | 16.12 | Au1rxx-base64 | 95.215.201.18 |
| 71.89 | vless | 324.7 | 705.5 | 20.26 | 0.0 | 8.82 | 10.09 | 16.12 | Au1rxx-base64 | tk1.high-speed-test-56424.me |
| 71.64 | vless | 206.8 | 501.9 | 22.99 | 0.0 | 9.18 | 10.09 | 16.12 | Au1rxx-base64 | 154.40.55.185 |
| 71.31 | vless | 437.6 | 1087.9 | 17.65 | 0.0 | 9.23 | 10.09 | 16.12 | Au1rxx-base64 | 51.81.203.63 |
| 71.16 | vless | 386.3 | 284.3 | 18.84 | 4.34 | 9.2 | 10.09 | 16.12 | Au1rxx-base64 | 142.91.108.25 |
| 70.89 | vless | 347.0 | 763.3 | 19.75 | 0.0 | 10.0 | 10.09 | 16.12 | Au1rxx-base64 | 162.35.126.130 |
| 70.63 | shadowsocks | 278.4 | 283.6 | 21.33 | 4.36 | 9.18 | 12.86 | 16.12 | Au1rxx-base64 | 149.22.87.240 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.908 | 0.835 | 97 | 23621 | prefer |
| Au1rxx-base64 | 0.878 | 0.823 | 260 | 1438 | prefer |
| Surfboard-tg-mixed | 0.864 | 0.792 | 72 | 6945 | prefer |
| zhangkai | 0.561 | 0.565 | 23 | 31 | observe |
| DeltaKronecker-all | 0.373 | 0.6 | 5 | 3519 | observe |
| SoliSpirit-all | 0.335 | 1.0 | 1 | 9871 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 74 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4967 | observe |
| Epodonios-all | 0.255 | None | 0 | 7425 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5487 | observe |
| barry-far-vless | 0.255 | None | 0 | 5701 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4127 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 24 |
| 204 | TimeoutError | - | 13 |
| 204 | ProxyError | - | 12 |
| speed | ClientOSError | - | 12 |
| speed | TimeoutError | - | 10 |
| 204 | ProxyConnectionError | - | 6 |
| cn-block | ClientOSError | - | 6 |
| geo | ClientOSError | - | 4 |
| geo | TimeoutError | - | 2 |
| geo | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
