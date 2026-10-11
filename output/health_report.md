# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-11 17:49:39 |
| 运行耗时 | 774.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 99914 |
| 去重后节点 | 27587 |
| TCP 可达 | 3000 |
| 真实可用 | 426 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27587 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| geo | 1.5 |
| tcp | 47.2 |
| probe | 295.3 |
| real_test | 346.0 |
| generate | 78.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58819 |
| vmess | 15824 |
| shadowsocks | 11856 |
| trojan | 10967 |
| hysteria2 | 1517 |
| http | 634 |
| shadowsocksr | 166 |
| socks | 75 |
| anytls | 30 |
| hysteria | 16 |
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
| 84.15 | vless | 177.4 | 481.4 | 23.67 | 0.0 | 10.0 | 10.96 | 19.52 | Au1rxx-base64 | 47.251.108.158 |
| 84.11 | vless | 179.1 | 486.3 | 23.63 | 0.0 | 10.0 | 10.96 | 19.52 | Au1rxx-base64 | 137.175.82.40 |
| 83.72 | hysteria2 | 233.4 | 235.8 | 22.37 | 6.16 | 9.92 | 12.63 | 19.52 | Au1rxx-base64 | 158.101.148.79 |
| 83.69 | vless | 197.4 | 509.0 | 23.21 | 0.0 | 10.0 | 10.96 | 19.52 | Au1rxx-base64 | 107.173.237.146 |
| 82.87 | vless | 232.9 | 556.9 | 22.39 | 0.0 | 10.0 | 10.96 | 19.52 | Au1rxx-base64 | 15.204.97.216 |
| 82.84 | vless | 234.1 | 576.7 | 22.36 | 0.0 | 10.0 | 10.96 | 19.52 | Au1rxx-base64 | 15.204.97.197 |
| 82.79 | vless | 236.1 | 595.3 | 22.31 | 0.0 | 10.0 | 10.96 | 19.52 | Au1rxx-base64 | 154.12.38.159 |
| 82.71 | hysteria2 | 230.2 | 233.3 | 22.45 | 6.25 | 8.79 | 12.63 | 19.52 | Au1rxx-base64 | open.2ml.bid |
| 81.64 | trojan | 248.0 | 583.3 | 22.04 | 0.0 | 8.6 | 13.98 | 19.52 | Au1rxx-base64 | alert-titmouse.rooster465.autos |
| 80.96 | vless | 199.2 | 506.4 | 23.17 | 0.0 | 10.0 | 10.96 | 19.52 | Au1rxx-base64 | 144.202.126.147 |
| 80.74 | vless | 223.2 | 545.2 | 22.61 | 0.0 | 10.0 | 10.96 | 19.52 | Au1rxx-base64 | 154.12.38.202 |
| 80.46 | vless | 336.8 | 650.1 | 19.98 | 0.0 | 10.0 | 10.96 | 19.52 | Au1rxx-base64 | 23.95.222.127 |
| 79.94 | shadowsocks | 240.6 | 581.4 | 22.21 | 0.0 | 10.0 | 12.47 | 19.52 | Au1rxx-base64 | 149.22.95.183 |
| 79.81 | vless | 333.5 | 809.1 | 20.06 | 0.0 | 10.0 | 10.96 | 19.52 | Au1rxx-base64 | 136.67.16.72 |
| 79.55 | vless | 376.3 | 990.3 | 19.07 | 0.0 | 10.0 | 10.96 | 19.52 | Au1rxx-base64 | 51.81.203.63 |
| 78.8 | vless | 192.8 | 507.7 | 23.32 | 0.0 | 10.0 | 10.96 | 19.52 | Au1rxx-base64 | 104.207.152.198 |
| 78.74 | shadowsocks | 291.6 | 596.7 | 21.03 | 0.0 | 10.0 | 12.47 | 19.52 | Au1rxx-base64 | 173.244.56.9 |
| 78.7 | shadowsocks | 287.4 | 559.2 | 21.13 | 0.0 | 10.0 | 12.47 | 19.52 | Au1rxx-base64 | 173.244.56.6 |
| 78.33 | trojan | 304.1 | 752.4 | 20.74 | 0.0 | 6.59 | 13.98 | 19.52 | Au1rxx-base64 | pro-mako.rooster465.autos |
| 76.54 | shadowsocks | 293.1 | 652.4 | 20.99 | 0.0 | 10.0 | 12.47 | 19.52 | Au1rxx-base64 | 156.146.38.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.977 | 0.905 | 378 | 1865 | prefer |
| mheidari-all | 0.843 | 0.772 | 57 | 23983 | prefer |
| DeltaKronecker-all | 0.602 | 0.523 | 44 | 5372 | observe |
| ermaozi | 0.493 | 0.5 | 18 | 635 | observe |
| Surfboard-tg-mixed | 0.372 | 0.444 | 9 | 7223 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 50 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5099 | observe |
| Epodonios-all | 0.255 | None | 0 | 7642 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9946 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5723 | observe |
| barry-far-vless | 0.255 | None | 0 | 5910 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4318 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 32 |
| cn-block | TimeoutError | - | 21 |
| 204 | ProxyError | - | 12 |
| speed | ClientOSError | - | 10 |
| speed | TimeoutError | - | 6 |
| cn-block | ProxyError | - | 2 |
| geo | TimeoutError | - | 2 |
| 204 | ClientOSError | - | 2 |
| geo | ClientOSError | - | 2 |
| speed | ClientPayloadError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
