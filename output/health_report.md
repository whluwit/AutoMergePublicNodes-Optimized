# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-17 19:04:16 |
| 运行耗时 | 230.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 79988 |
| 去重后节点 | 25147 |
| TCP 可达 | 3000 |
| 真实可用 | 348 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 25147 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.4 |
| geo | 1.0 |
| tcp | 34.3 |
| probe | 54.7 |
| real_test | 101.5 |
| generate | 34.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45631 |
| trojan | 13164 |
| vmess | 10866 |
| shadowsocks | 9819 |
| hysteria2 | 271 |
| shadowsocksr | 123 |
| socks | 52 |
| http | 51 |
| hysteria | 8 |
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
| 76.53 | shadowsocks | 240.6 | 634.2 | 22.21 | 0.0 | 10.0 | 11.0 | 17.32 | Au1rxx-base64 | 37.19.198.243 |
| 76.46 | shadowsocks | 243.6 | 642.5 | 22.14 | 0.0 | 10.0 | 11.0 | 17.32 | Au1rxx-base64 | 37.19.198.160 |
| 73.51 | shadowsocks | 241.6 | 640.8 | 22.19 | 0.0 | 10.0 | 11.0 | 17.32 | Au1rxx-base64 | 37.19.198.236 |
| 73.39 | shadowsocks | 290.6 | 662.5 | 21.05 | 0.0 | 10.0 | 11.0 | 17.32 | Au1rxx-base64 | 156.146.38.167 |
| 72.57 | shadowsocks | 289.6 | 663.3 | 21.07 | 0.0 | 10.0 | 11.0 | 17.32 | Au1rxx-base64 | 156.146.38.169 |
| 71.62 | shadowsocks | 287.2 | 660.7 | 21.13 | 0.0 | 10.0 | 11.0 | 17.32 | Au1rxx-base64 | 156.146.38.168 |
| 70.42 | shadowsocks | 288.6 | 772.6 | 21.1 | 0.0 | 10.0 | 11.0 | 17.32 | Au1rxx-base64 | 37.19.198.244 |
| 69.86 | trojan | 366.5 | 629.5 | 19.3 | 0.0 | 10.0 | 13.24 | 13.32 | DeltaKronecker-all | 104.16.100.215 |
| 69.41 | shadowsocks | 353.9 | 912.2 | 19.59 | 0.0 | 10.0 | 11.0 | 13.32 | DeltaKronecker-all | 50.114.177.235 |
| 69.07 | shadowsocks | 331.1 | 595.5 | 20.11 | 0.0 | 10.0 | 11.0 | 17.32 | Au1rxx-base64 | 173.244.56.9 |
| 68.59 | shadowsocks | 329.2 | 570.1 | 20.16 | 0.0 | 10.0 | 11.0 | 17.32 | Au1rxx-base64 | 173.244.56.6 |
| 67.94 | shadowsocks | 365.4 | 702.4 | 19.32 | 0.0 | 10.0 | 11.0 | 17.32 | Au1rxx-base64 | 108.181.0.177 |
| 67.79 | shadowsocks | 353.9 | 650.6 | 19.59 | 0.0 | 10.0 | 11.0 | 17.32 | Au1rxx-base64 | 108.181.118.10 |
| 67.46 | shadowsocks | 344.3 | 644.6 | 19.81 | 0.0 | 10.0 | 11.0 | 17.32 | Au1rxx-base64 | 149.22.95.183 |
| 67.26 | shadowsocks | 289.0 | 660.5 | 21.09 | 0.0 | 10.0 | 11.0 | 17.32 | Au1rxx-base64 | 156.146.38.170 |
| 66.86 | trojan | 380.3 | 613.3 | 18.98 | 0.0 | 10.0 | 13.24 | 13.64 | Surfboard-tg-mixed | 104.16.71.48 |
| 66.29 | shadowsocks | 365.3 | 917.4 | 19.32 | 0.0 | 10.0 | 11.0 | 13.32 | DeltaKronecker-all | 185.196.61.82 |
| 65.86 | http | 633.8 | 908.1 | 13.11 | 0.0 | 9.78 | 14.61 | 19.52 | zhangkai | 193.176.84.31 |
| 65.45 | shadowsocks | 352.7 | 941.7 | 19.61 | 0.0 | 10.0 | 11.0 | 9.34 | mheidari-all | 108.181.57.93 |
| 65.27 | trojan | 494.1 | 472.1 | 16.34 | 0.0 | 9.25 | 13.24 | 17.32 | Au1rxx-base64 | 35.72.9.75 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.896 | 0.896 | 134 | 150 | prefer |
| Surfboard-tg-mixed | 0.797 | 0.72 | 118 | 5558 | prefer |
| mheidari-all | 0.538 | 0.455 | 22 | 16753 | observe |
| DeltaKronecker-all | 0.507 | 0.427 | 225 | 8967 | observe |
| xiaoji235-airport-v2ray-all | 0.322 | 1.0 | 1 | 1680 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4428 | observe |
| Epodonios-all | 0.255 | None | 0 | 6514 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6777 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4258 | observe |
| barry-far-vless | 0.255 | None | 0 | 4875 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5263 | observe |
| nscl5-all | 0.248 | None | 0 | 1821 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 109 |
| 204 | TimeoutError | - | 25 |
| speed | ClientOSError | - | 20 |
| cn-block | TimeoutError | - | 12 |
| speed | TimeoutError | - | 6 |
| geo | ClientOSError | - | 6 |
| 204 | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
