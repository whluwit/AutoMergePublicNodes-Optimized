# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-22 05:06:41 |
| 运行耗时 | 249.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 105 |
| 原始节点 | 74096 |
| 去重后节点 | 22723 |
| TCP 可达 | 3000 |
| 真实可用 | 633 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22723 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.3 |
| tcp | 30.9 |
| probe | 52.6 |
| real_test | 132.3 |
| generate | 27.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 43583 |
| trojan | 10058 |
| shadowsocks | 9945 |
| vmess | 9851 |
| hysteria2 | 252 |
| http | 182 |
| shadowsocksr | 162 |
| socks | 55 |
| hysteria | 6 |
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
| 79.68 | shadowsocks | 201.2 | 507.5 | 23.12 | 0.0 | 10.0 | 13.62 | 16.94 | Au1rxx-base64 | 173.244.56.9 |
| 79.4 | shadowsocks | 191.8 | 466.7 | 23.34 | 0.0 | 10.0 | 13.62 | 16.94 | Au1rxx-base64 | 108.181.0.177 |
| 79.39 | shadowsocks | 192.2 | 466.4 | 23.33 | 0.0 | 10.0 | 13.62 | 16.94 | Au1rxx-base64 | 108.181.118.10 |
| 78.58 | shadowsocks | 248.9 | 655.2 | 22.02 | 0.0 | 10.0 | 13.62 | 16.94 | Au1rxx-base64 | 173.244.56.6 |
| 78.45 | shadowsocks | 254.5 | 623.3 | 21.89 | 0.0 | 10.0 | 13.62 | 16.94 | Au1rxx-base64 | 156.146.38.169 |
| 78.24 | shadowsocks | 263.4 | 641.0 | 21.68 | 0.0 | 10.0 | 13.62 | 16.94 | Au1rxx-base64 | 156.146.38.167 |
| 77.79 | vless | 192.9 | 501.0 | 23.31 | 0.0 | 10.0 | 9.54 | 16.94 | Au1rxx-base64 | a.cflive.top |
| 77.2 | trojan | 308.7 | 685.6 | 20.63 | 0.0 | 10.0 | 12.13 | 16.94 | Au1rxx-base64 | 207.126.167.241 |
| 76.51 | shadowsocks | 255.8 | 628.6 | 21.86 | 0.0 | 10.0 | 13.62 | 16.94 | Au1rxx-base64 | 156.146.38.170 |
| 76.44 | trojan | 241.5 | 631.2 | 22.19 | 0.0 | 10.0 | 12.13 | 14.62 | DeltaKronecker-all | 207.126.167.150 |
| 75.27 | trojan | 248.7 | 647.8 | 22.02 | 0.0 | 10.0 | 12.13 | 14.62 | DeltaKronecker-all | 45.61.58.89 |
| 74.93 | shadowsocks | 258.8 | 635.1 | 21.79 | 0.0 | 10.0 | 13.62 | 14.62 | DeltaKronecker-all | 107.172.219.230 |
| 74.89 | shadowsocks | 371.1 | 1049.2 | 19.19 | 0.0 | 10.0 | 13.62 | 16.58 | mheidari-all | 167.160.90.51 |
| 74.79 | vless | 345.6 | 834.0 | 19.78 | 0.0 | 10.0 | 9.54 | 16.94 | Au1rxx-base64 | 15.204.97.219 |
| 74.64 | shadowsocks | 289.4 | 730.6 | 21.08 | 0.0 | 10.0 | 13.62 | 16.94 | Au1rxx-base64 | 156.146.38.168 |
| 74.19 | vless | 348.2 | 838.5 | 19.72 | 0.0 | 10.0 | 9.54 | 16.94 | Au1rxx-base64 | 15.204.97.214 |
| 73.52 | vless | 322.3 | 711.3 | 20.32 | 0.0 | 10.0 | 9.54 | 16.94 | Au1rxx-base64 | 34.213.172.16 |
| 71.49 | shadowsocks | 354.3 | 725.3 | 19.58 | 0.0 | 10.0 | 13.62 | 16.94 | Au1rxx-base64 | 37.19.198.236 |
| 71.4 | trojan | 390.4 | 902.4 | 18.74 | 0.0 | 10.0 | 12.13 | 16.58 | mheidari-all | 64.94.95.118 |
| 71.39 | shadowsocks | 306.7 | 358.3 | 20.68 | 1.56 | 9.89 | 13.62 | 16.94 | Au1rxx-base64 | 149.22.87.204 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.991 | 1.0 | 69 | 131 | prefer |
| mheidari-all | 0.865 | 0.787 | 380 | 14957 | prefer |
| Au1rxx-base64 | 0.797 | 0.796 | 108 | 149 | prefer |
| DeltaKronecker-all | 0.726 | 0.647 | 269 | 7452 | prefer |
| Surfboard-tg-mixed | 0.373 | 0.6 | 5 | 4738 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4494 | observe |
| Epodonios-all | 0.255 | None | 0 | 7244 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3980 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6973 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3632 | observe |
| barry-far-vless | 0.255 | None | 0 | 4479 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4505 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 78 |
| geo | TimeoutError | - | 69 |
| geo | ClientOSError | - | 14 |
| 204 | ProxyError | - | 8 |
| cn-block | TimeoutError | - | 8 |
| 204 | TimeoutError | - | 8 |
| speed | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
