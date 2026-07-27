# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-27 19:25:18 |
| 运行耗时 | 297.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 85908 |
| 去重后节点 | 22911 |
| TCP 可达 | 3000 |
| 真实可用 | 748 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22911 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.1 |
| tcp | 31.6 |
| probe | 64.2 |
| real_test | 165.4 |
| generate | 30.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49142 |
| trojan | 15468 |
| vmess | 10445 |
| shadowsocks | 9904 |
| hysteria2 | 680 |
| shadowsocksr | 107 |
| socks | 65 |
| http | 63 |
| hysteria | 15 |
| anytls | 11 |
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
| 81.67 | shadowsocks | 215.5 | 515.5 | 22.79 | 0.0 | 10.0 | 13.06 | 19.82 | Au1rxx-base64 | 173.244.56.9 |
| 81.46 | shadowsocks | 224.7 | 514.1 | 22.58 | 0.0 | 10.0 | 13.06 | 19.82 | Au1rxx-base64 | 149.22.95.183 |
| 81.23 | shadowsocks | 234.6 | 569.6 | 22.35 | 0.0 | 10.0 | 13.06 | 19.82 | Au1rxx-base64 | 173.244.56.6 |
| 80.35 | shadowsocks | 251.0 | 640.4 | 21.97 | 0.0 | 10.0 | 13.06 | 19.82 | Au1rxx-base64 | 108.181.0.177 |
| 76.95 | vless | 167.5 | 464.7 | 23.9 | 0.0 | 10.0 | 6.61 | 16.44 | Surfboard-tg-mixed | 64.23.143.23 |
| 76.07 | trojan | 333.7 | 672.0 | 20.05 | 0.0 | 10.0 | 14.24 | 19.82 | Au1rxx-base64 | 163.245.196.68 |
| 76.01 | shadowsocks | 303.3 | 667.6 | 20.76 | 0.0 | 10.0 | 13.06 | 19.82 | Au1rxx-base64 | 156.146.38.167 |
| 75.79 | shadowsocks | 317.9 | 717.5 | 20.42 | 0.0 | 10.0 | 13.06 | 19.82 | Au1rxx-base64 | 156.146.38.170 |
| 75.46 | shadowsocks | 462.3 | 1278.9 | 17.08 | 0.0 | 10.0 | 13.06 | 19.82 | Au1rxx-base64 | 108.181.118.10 |
| 75.35 | trojan | 295.0 | 578.5 | 20.95 | 0.0 | 10.0 | 14.24 | 16.16 | DeltaKronecker-all | 91.193.58.9 |
| 75.02 | shadowsocks | 272.9 | 281.8 | 21.46 | 4.43 | 9.94 | 13.06 | 19.82 | Au1rxx-base64 | 149.22.87.241 |
| 74.59 | hysteria2 | 356.3 | 723.2 | 19.53 | 0.0 | 10.0 | 11.25 | 19.82 | Au1rxx-base64 | 159.223.157.129 |
| 74.4 | shadowsocks | 296.5 | 350.6 | 20.92 | 1.85 | 9.94 | 13.06 | 19.82 | Au1rxx-base64 | 149.22.87.204 |
| 74.18 | vless | 174.2 | 457.9 | 23.75 | 0.0 | 10.0 | 6.61 | 19.82 | Au1rxx-base64 | 172.67.174.37 |
| 74.12 | trojan | 398.6 | 946.5 | 18.55 | 0.0 | 10.0 | 14.24 | 19.82 | Au1rxx-base64 | 64.94.95.118 |
| 73.76 | trojan | 412.9 | 981.2 | 18.22 | 0.0 | 10.0 | 14.24 | 19.82 | Au1rxx-base64 | 64.94.95.114 |
| 73.6 | shadowsocks | 292.4 | 340.7 | 21.01 | 2.22 | 9.94 | 13.06 | 19.82 | Au1rxx-base64 | 149.22.87.240 |
| 73.6 | trojan | 401.3 | 951.9 | 18.49 | 0.0 | 10.0 | 14.24 | 19.82 | Au1rxx-base64 | 64.94.95.117 |
| 73.55 | trojan | 342.9 | 538.6 | 19.84 | 0.0 | 10.0 | 14.24 | 16.16 | DeltaKronecker-all | 104.129.166.27 |
| 73.33 | trojan | 329.1 | 337.7 | 20.16 | 2.34 | 10.0 | 14.24 | 16.16 | DeltaKronecker-all | 91.193.58.62 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.996 | 0.938 | 450 | 1499 | prefer |
| zhangkai | 0.987 | 1.0 | 59 | 74 | prefer |
| mheidari-all | 0.839 | 0.762 | 143 | 19371 | prefer |
| DeltaKronecker-all | 0.617 | 0.537 | 134 | 5643 | observe |
| Surfboard-tg-mixed | 0.552 | 0.472 | 178 | 5739 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 3959 | observe |
| MatinGhanbari-super-sub | 0.263 | 1.0 | 1 | 199 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4831 | observe |
| Epodonios-all | 0.255 | None | 0 | 6710 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3970 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6251 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4648 | observe |
| barry-far-vless | 0.255 | None | 0 | 5170 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4997 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 84 |
| speed | ClientOSError | - | 42 |
| 204 | TimeoutError | - | 24 |
| geo | ClientOSError | - | 17 |
| cn-block | TimeoutError | - | 16 |
| 204 | ProxyError | - | 12 |
| cn-block | ClientOSError | - | 8 |
| speed | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 3 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
