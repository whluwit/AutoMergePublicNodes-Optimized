# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-17 17:41:30 |
| 运行耗时 | 109.9s |
| 订阅源总数 | 44 |
| 健康订阅源 | 44 |
| 原始节点 | 43729 |
| 去重后节点 | 18177 |
| TCP 可达 | 1500 |
| 真实可用 | 102 |
| Verified 输出 | 102 |
| Global 输出 | 106 |
| All 输出 | 18177 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.7 |
| geo | 1.2 |
| tcp | 20.0 |
| probe | 25.9 |
| real_test | 40.0 |
| generate | 19.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 22389 |
| shadowsocks | 8306 |
| trojan | 7062 |
| vmess | 5552 |
| hysteria2 | 193 |
| http | 95 |
| shadowsocksr | 87 |
| socks | 38 |
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
| 59.75 | vmess | 241.0 | 530.7 | 22.2 | 0.0 | 10.0 | 12.86 | 4.28 | Barabama-yudou | 82.198.246.233 |
| 56.46 | trojan | 395.3 | 785.5 | 18.63 | 0.0 | 10.0 | 8.12 | 12.48 | DeltaKronecker-all | 45.61.52.243 |
| 55.52 | trojan | 343.1 | 730.6 | 19.84 | 0.0 | 10.0 | 8.12 | 12.48 | DeltaKronecker-all | 207.126.167.150 |
| 53.1 | vmess | 598.5 | 843.1 | 13.92 | 0.0 | 9.69 | 12.86 | 12.48 | DeltaKronecker-all | 159.223.13.109 |
| 52.94 | http | 824.0 | 1015.7 | 8.7 | 0.0 | 9.26 | 14.44 | 17.4 | snakem982 | 84.239.49.173 |
| 52.65 | http | 842.0 | 1020.7 | 8.29 | 0.0 | 9.26 | 14.44 | 17.4 | snakem982 | 84.239.49.154 |
| 52.55 | http | 846.3 | 1032.4 | 8.19 | 0.0 | 9.27 | 14.44 | 17.4 | snakem982 | 84.239.49.162 |
| 52.36 | http | 851.8 | 1033.0 | 8.06 | 0.0 | 9.24 | 14.44 | 17.4 | snakem982 | 84.239.49.223 |
| 52.24 | http | 860.5 | 990.2 | 7.86 | 0.0 | 9.27 | 14.44 | 17.4 | snakem982 | 84.239.49.233 |
| 52.03 | http | 859.3 | 1041.7 | 7.89 | 0.0 | 9.21 | 14.44 | 17.4 | snakem982 | 84.239.49.166 |
| 51.54 | http | 873.9 | 1050.9 | 7.55 | 0.0 | 8.98 | 14.44 | 17.4 | snakem982 | 84.239.49.201 |
| 51.49 | http | 878.3 | 1068.6 | 7.45 | 0.0 | 9.06 | 14.44 | 17.4 | snakem982 | 84.239.49.199 |
| 51.37 | http | 881.6 | 1114.4 | 7.37 | 0.0 | 8.98 | 14.44 | 17.4 | snakem982 | 84.239.49.212 |
| 51.37 | http | 893.4 | 1161.0 | 7.1 | 0.0 | 9.17 | 14.44 | 17.4 | snakem982 | 84.239.49.239 |
| 51.34 | vmess | 663.3 | 1033.6 | 12.42 | 0.0 | 9.63 | 12.86 | 12.48 | DeltaKronecker-all | 51.89.41.22 |
| 51.22 | http | 893.4 | 1116.8 | 7.1 | 0.0 | 9.08 | 14.44 | 17.4 | snakem982 | 84.239.49.214 |
| 51.09 | http | 904.2 | 1193.0 | 6.85 | 0.0 | 9.24 | 14.44 | 17.4 | snakem982 | 84.239.49.178 |
| 51.05 | http | 905.5 | 1220.1 | 6.82 | 0.0 | 9.24 | 14.44 | 17.4 | snakem982 | 84.239.14.158 |
| 51.01 | http | 911.5 | 1225.8 | 6.68 | 0.0 | 9.25 | 14.44 | 17.4 | snakem982 | 84.239.49.238 |
| 50.98 | http | 911.4 | 1230.2 | 6.68 | 0.0 | 9.26 | 14.44 | 17.4 | snakem982 | 84.239.14.159 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.605 | 0.525 | 139 | 7763 | observe |
| snakem982 | 0.459 | 0.455 | 55 | 73 | observe |
| Surfboard-tg-mixed | 0.284 | 0.333 | 6 | 4729 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| Au1rxx-base64 | 0.26 | 1.0 | 1 | 118 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 2000 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3000 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 3000 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3741 | observe |
| barry-far-vless | 0.255 | None | 0 | 2000 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4541 | observe |
| mheidari-all | 0.255 | None | 0 | 2000 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| nscl5-all | 0.214 | None | 0 | 967 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 27 |
| geo | status | 429 | 27 |
| 204 | ProxyError | - | 11 |
| speed | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| 204 | TimeoutError | - | 4 |
| cn-block | ProxyError | - | 4 |
| speed | TimeoutError | - | 3 |
| cn-block | TimeoutError | - | 3 |
| geo | TimeoutError | - | 3 |
| geo | ProxyError | - | 3 |
| geo | ClientOSError | - | 2 |
| geo | status | 403 | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 110 | 102 | - |
| global | False | 111 | 106 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
