# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-30 19:51:59 |
| 运行耗时 | 188.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 103 |
| 原始节点 | 75830 |
| 去重后节点 | 23069 |
| TCP 可达 | 3000 |
| 真实可用 | 174 |
| Verified 输出 | 174 |
| Global 输出 | 184 |
| All 输出 | 23069 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| geo | 1.4 |
| tcp | 30.9 |
| probe | 50.8 |
| real_test | 75.6 |
| generate | 25.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 42752 |
| trojan | 13002 |
| vmess | 10273 |
| shadowsocks | 9171 |
| hysteria2 | 281 |
| shadowsocksr | 149 |
| http | 135 |
| socks | 60 |
| hysteria | 6 |
| tuic | 1 |

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
| 76.46 | shadowsocks | 237.2 | 600.2 | 22.29 | 0.0 | 10.0 | 12.17 | 16.0 | Au1rxx-base64 | 156.146.38.168 |
| 76.4 | shadowsocks | 239.6 | 576.9 | 22.23 | 0.0 | 10.0 | 12.17 | 16.0 | Au1rxx-base64 | 156.146.38.169 |
| 76.22 | shadowsocks | 247.6 | 620.9 | 22.05 | 0.0 | 10.0 | 12.17 | 16.0 | Au1rxx-base64 | 156.146.38.167 |
| 73.97 | shadowsocks | 248.1 | 611.2 | 22.03 | 0.0 | 10.0 | 12.17 | 16.0 | Au1rxx-base64 | 156.146.38.170 |
| 73.81 | trojan | 241.8 | 587.9 | 22.18 | 0.0 | 10.0 | 9.85 | 14.78 | DeltaKronecker-all | 64.94.95.115 |
| 73.3 | shadowsocks | 294.1 | 695.7 | 20.97 | 0.0 | 10.0 | 12.17 | 16.0 | Au1rxx-base64 | 37.19.198.244 |
| 72.69 | trojan | 264.4 | 625.4 | 21.66 | 0.0 | 10.0 | 9.85 | 14.78 | DeltaKronecker-all | 64.94.95.114 |
| 72.53 | shadowsocks | 291.0 | 680.1 | 21.04 | 0.0 | 10.0 | 12.17 | 16.0 | Au1rxx-base64 | 37.19.198.243 |
| 72.23 | shadowsocks | 287.3 | 670.4 | 21.13 | 0.0 | 10.0 | 12.17 | 16.0 | Au1rxx-base64 | 37.19.198.160 |
| 71.69 | shadowsocks | 285.8 | 668.5 | 21.16 | 0.0 | 10.0 | 12.17 | 16.0 | Au1rxx-base64 | 37.19.198.236 |
| 70.76 | shadowsocks | 291.7 | 563.7 | 21.03 | 0.0 | 10.0 | 12.17 | 16.0 | Au1rxx-base64 | 173.244.56.9 |
| 70.7 | shadowsocks | 308.1 | 714.2 | 20.64 | 0.0 | 10.0 | 12.17 | 16.0 | Au1rxx-base64 | 108.181.57.93 |
| 70.5 | vless | 317.8 | 688.3 | 20.42 | 0.0 | 10.0 | 8.88 | 14.78 | DeltaKronecker-all | 104.25.161.29 |
| 70.35 | shadowsocks | 315.8 | 670.8 | 20.47 | 0.0 | 10.0 | 12.17 | 16.0 | Au1rxx-base64 | 173.244.56.6 |
| 69.72 | shadowsocks | 310.1 | 607.2 | 20.6 | 0.0 | 10.0 | 12.17 | 16.0 | Au1rxx-base64 | 149.22.95.183 |
| 69.44 | vless | 303.0 | 697.3 | 20.76 | 0.0 | 10.0 | 8.88 | 14.78 | DeltaKronecker-all | 162.159.252.15 |
| 69.25 | shadowsocks | 315.1 | 682.1 | 20.48 | 0.0 | 10.0 | 12.17 | 16.0 | Au1rxx-base64 | 108.181.0.177 |
| 69.21 | shadowsocks | 285.3 | 563.7 | 21.17 | 0.0 | 10.0 | 12.17 | 16.0 | Au1rxx-base64 | 108.181.118.10 |
| 68.26 | shadowsocks | 389.0 | 925.7 | 18.77 | 0.0 | 10.0 | 12.17 | 13.34 | mheidari-all | 198.98.53.130 |
| 68.11 | shadowsocks | 360.1 | 941.5 | 19.44 | 0.0 | 10.0 | 12.17 | 16.0 | Au1rxx-base64 | 172.234.202.34 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.854 | 0.867 | 45 | 83 | prefer |
| mheidari-all | 0.807 | 0.742 | 31 | 15848 | prefer |
| Surfboard-tg-mixed | 0.459 | 0.376 | 93 | 5645 | observe |
| xiaoji235-airport-v2ray-all | 0.303 | 1.0 | 1 | 1204 | observe |
| nscl5-all | 0.3 | 1.0 | 1 | 1136 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| abc-configs-readme-latest30 | 0.256 | 1.0 | 1 | 19 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4139 | observe |
| Epodonios-all | 0.255 | None | 0 | 6581 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3977 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6636 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4233 | observe |
| barry-far-vless | 0.255 | None | 0 | 4802 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5373 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 171 |
| 204 | TimeoutError | - | 52 |
| 204 | ProxyError | - | 23 |
| cn-block | TimeoutError | - | 15 |
| geo | ClientOSError | - | 9 |
| geo | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 9 |
| cn-block | ProxyError | - | 5 |
| speed | TimeoutError | - | 5 |
| geo | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 174 | - |
| global | False | 300 | 184 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
