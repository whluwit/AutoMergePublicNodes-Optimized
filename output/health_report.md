# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-27 21:42:16 |
| 运行耗时 | 225.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 87070 |
| 去重后节点 | 23515 |
| TCP 可达 | 3000 |
| 真实可用 | 440 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23515 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.0 |
| geo | 1.4 |
| tcp | 39.2 |
| probe | 43.8 |
| real_test | 96.6 |
| generate | 40.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 53668 |
| shadowsocks | 11840 |
| vmess | 11575 |
| trojan | 7616 |
| hysteria2 | 1950 |
| http | 164 |
| shadowsocksr | 141 |
| socks | 75 |
| anytls | 20 |
| hysteria | 16 |
| tuic | 5 |

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
| 83.25 | vless | 210.6 | 545.2 | 22.9 | 0.0 | 10.0 | 10.47 | 19.88 | Au1rxx-base64 | 15.204.97.216 |
| 82.55 | shadowsocks | 209.5 | 556.8 | 22.93 | 0.0 | 10.0 | 13.74 | 19.88 | Au1rxx-base64 | 149.22.95.183 |
| 81.15 | vless | 301.7 | 826.1 | 20.8 | 0.0 | 10.0 | 10.47 | 19.88 | Au1rxx-base64 | 15.204.97.197 |
| 81.11 | vless | 303.3 | 806.3 | 20.76 | 0.0 | 10.0 | 10.47 | 19.88 | Au1rxx-base64 | 15.204.97.209 |
| 80.72 | shadowsocks | 258.6 | 583.9 | 21.79 | 0.0 | 10.0 | 13.74 | 19.88 | Au1rxx-base64 | 94.72.127.58 |
| 80.02 | vless | 350.4 | 969.5 | 19.67 | 0.0 | 10.0 | 10.47 | 19.88 | Au1rxx-base64 | 15.204.97.214 |
| 78.95 | vless | 265.5 | 572.3 | 21.63 | 0.0 | 10.0 | 10.47 | 19.88 | Au1rxx-base64 | 166.88.186.151 |
| 78.73 | vless | 274.9 | 613.2 | 21.41 | 0.0 | 10.0 | 10.47 | 19.88 | Au1rxx-base64 | 108.186.202.51 |
| 77.32 | shadowsocks | 271.3 | 565.3 | 21.5 | 0.0 | 10.0 | 13.74 | 19.88 | Au1rxx-base64 | 108.181.0.177 |
| 77.12 | hysteria2 | 360.7 | 732.4 | 19.43 | 0.0 | 10.0 | 13.12 | 19.88 | Au1rxx-base64 | 159.223.157.129 |
| 76.99 | vless | 362.4 | 283.0 | 19.39 | 4.39 | 10.0 | 10.47 | 19.88 | Au1rxx-base64 | 46.250.250.149 |
| 76.38 | vless | 450.4 | 1160.1 | 17.35 | 0.0 | 10.0 | 10.47 | 19.88 | Au1rxx-base64 | 51.81.203.63 |
| 76.26 | shadowsocks | 259.5 | 278.8 | 21.77 | 4.54 | 9.97 | 13.74 | 17.24 | Surfboard-tg-mixed | 149.22.87.240 |
| 76.15 | trojan | 265.1 | 564.6 | 21.64 | 0.0 | 10.0 | 11.81 | 19.88 | Au1rxx-base64 | 14.1.28.76 |
| 76.03 | shadowsocks | 304.6 | 579.6 | 20.73 | 0.0 | 10.0 | 13.74 | 19.88 | Au1rxx-base64 | 173.244.56.6 |
| 75.91 | hysteria2 | 315.7 | 284.0 | 20.47 | 4.35 | 9.29 | 13.12 | 19.88 | Au1rxx-base64 | 134.185.87.191 |
| 75.22 | shadowsocks | 318.8 | 339.5 | 20.4 | 2.27 | 10.0 | 13.74 | 19.88 | Au1rxx-base64 | 84.247.155.196 |
| 75.12 | shadowsocks | 336.5 | 675.3 | 19.99 | 0.0 | 10.0 | 13.74 | 19.88 | Au1rxx-base64 | 173.244.56.9 |
| 75.1 | vless | 348.0 | 703.1 | 19.72 | 0.0 | 10.0 | 10.47 | 19.88 | Au1rxx-base64 | 195.211.99.49 |
| 74.94 | vless | 349.4 | 700.8 | 19.69 | 0.0 | 10.0 | 10.47 | 19.88 | Au1rxx-base64 | 195.211.99.45 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.985 | 0.923 | 300 | 1622 | prefer |
| zhangkai | 0.964 | 1.0 | 22 | 144 | prefer |
| Surfboard-tg-mixed | 0.807 | 0.731 | 130 | 6577 | prefer |
| mheidari-all | 0.617 | 0.538 | 78 | 19755 | observe |
| DeltaKronecker-all | 0.48 | 1.0 | 4 | 4318 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4783 | observe |
| Epodonios-all | 0.255 | None | 0 | 6955 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3991 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7129 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5393 | observe |
| barry-far-vless | 0.255 | None | 0 | 5568 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4019 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5418 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.24 | None | 0 | 1622 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 31 |
| 204 | TimeoutError | - | 20 |
| cn-block | TimeoutError | - | 14 |
| speed | ClientOSError | - | 8 |
| speed | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 5 |
| 204 | ProxyError | - | 4 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
