# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-31 03:13:59 |
| 运行耗时 | 287.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 97 |
| 原始节点 | 79054 |
| 去重后节点 | 21836 |
| TCP 可达 | 3000 |
| 真实可用 | 692 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21836 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.5 |
| tcp | 35.5 |
| probe | 59.0 |
| real_test | 153.7 |
| generate | 32.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49547 |
| vmess | 10784 |
| shadowsocks | 10155 |
| trojan | 6625 |
| hysteria2 | 1557 |
| http | 168 |
| shadowsocksr | 126 |
| socks | 82 |
| hysteria | 7 |
| tuic | 3 |

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
| 85.13 | vless | 194.7 | 509.5 | 23.27 | 0.0 | 10.0 | 12.06 | 19.8 | Au1rxx-base64 | 172.233.156.118 |
| 85.05 | vless | 198.2 | 509.9 | 23.19 | 0.0 | 10.0 | 12.06 | 19.8 | Au1rxx-base64 | 172.233.156.123 |
| 84.94 | vless | 202.9 | 502.1 | 23.08 | 0.0 | 10.0 | 12.06 | 19.8 | Au1rxx-base64 | 70.39.196.142 |
| 84.8 | vless | 209.2 | 520.6 | 22.94 | 0.0 | 10.0 | 12.06 | 19.8 | Au1rxx-base64 | 216.167.21.162 |
| 84.5 | vless | 221.9 | 531.5 | 22.64 | 0.0 | 10.0 | 12.06 | 19.8 | Au1rxx-base64 | 74.207.245.124 |
| 84.45 | vless | 224.2 | 525.3 | 22.59 | 0.0 | 10.0 | 12.06 | 19.8 | Au1rxx-base64 | 173.255.242.56 |
| 84.44 | vless | 224.7 | 536.4 | 22.58 | 0.0 | 10.0 | 12.06 | 19.8 | Au1rxx-base64 | 45.33.62.226 |
| 84.41 | vless | 226.0 | 598.8 | 22.55 | 0.0 | 10.0 | 12.06 | 19.8 | Au1rxx-base64 | 172.236.252.35 |
| 84.27 | vless | 232.1 | 472.4 | 22.41 | 0.0 | 10.0 | 12.06 | 19.8 | Au1rxx-base64 | 216.167.21.32 |
| 84.1 | vless | 239.0 | 570.7 | 22.24 | 0.0 | 10.0 | 12.06 | 19.8 | Au1rxx-base64 | 45.33.107.237 |
| 83.8 | vless | 252.0 | 595.5 | 21.94 | 0.0 | 10.0 | 12.06 | 19.8 | Au1rxx-base64 | 192.155.87.188 |
| 83.33 | http | 191.3 | 479.9 | 23.35 | 0.0 | 10.0 | 14.4 | 18.58 | zhangkai | 138.199.35.216 |
| 82.56 | vless | 245.8 | 572.7 | 22.09 | 0.0 | 10.0 | 12.06 | 19.8 | Au1rxx-base64 | 45.33.62.166 |
| 82.43 | vless | 214.9 | 570.6 | 22.8 | 0.0 | 10.0 | 12.06 | 19.8 | Au1rxx-base64 | 172.233.139.46 |
| 82.37 | vless | 232.1 | 534.0 | 22.41 | 0.0 | 10.0 | 12.06 | 19.8 | Au1rxx-base64 | 50.116.9.184 |
| 81.82 | vless | 220.4 | 511.7 | 22.68 | 0.0 | 10.0 | 12.06 | 19.8 | Au1rxx-base64 | 64.23.229.123 |
| 81.51 | hysteria2 | 225.9 | 512.2 | 22.55 | 0.0 | 10.0 | 13.5 | 19.8 | Au1rxx-base64 | 66.94.121.46 |
| 81.43 | shadowsocks | 245.0 | 590.3 | 22.11 | 0.0 | 10.0 | 13.74 | 19.8 | Au1rxx-base64 | 156.146.38.167 |
| 81.43 | shadowsocks | 254.5 | 617.6 | 21.89 | 0.0 | 10.0 | 13.74 | 19.8 | Au1rxx-base64 | 156.146.38.168 |
| 81.29 | shadowsocks | 260.3 | 598.5 | 21.75 | 0.0 | 10.0 | 13.74 | 19.8 | Au1rxx-base64 | 156.146.38.170 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.985 | 0.916 | 320 | 1804 | prefer |
| zhangkai | 0.967 | 1.0 | 24 | 144 | prefer |
| Surfboard-tg-mixed | 0.874 | 0.796 | 216 | 6864 | prefer |
| mheidari-all | 0.734 | 0.722 | 18 | 14559 | prefer |
| DeltaKronecker-all | 0.576 | 0.496 | 379 | 5576 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Epodonios-all | 0.255 | None | 0 | 7271 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7626 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5770 | observe |
| barry-far-vless | 0.255 | None | 0 | 5957 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4041 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1804 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 100 |
| geo | ClientOSError | - | 50 |
| cn-block | TimeoutError | - | 29 |
| speed | TimeoutError | - | 23 |
| 204 | TimeoutError | - | 21 |
| speed | ClientOSError | - | 20 |
| 204 | ProxyError | - | 15 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 2 |
| speed | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
