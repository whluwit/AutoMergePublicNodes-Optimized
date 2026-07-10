# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-10 09:30:12 |
| 运行耗时 | 200.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 75290 |
| 去重后节点 | 23405 |
| TCP 可达 | 3000 |
| 真实可用 | 339 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23405 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.5 |
| tcp | 31.1 |
| probe | 45.3 |
| real_test | 90.2 |
| generate | 27.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 42436 |
| trojan | 12410 |
| vmess | 10646 |
| shadowsocks | 9155 |
| hysteria2 | 262 |
| shadowsocksr | 142 |
| http | 135 |
| socks | 90 |
| hysteria | 8 |
| anytls | 5 |
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
| 77.93 | shadowsocks | 224.5 | 502.0 | 22.58 | 0.0 | 10.0 | 14.15 | 15.2 | Au1rxx-base64 | 173.244.56.6 |
| 77.91 | shadowsocks | 203.7 | 490.7 | 23.06 | 0.0 | 10.0 | 14.15 | 15.2 | Au1rxx-base64 | 108.181.118.10 |
| 77.84 | shadowsocks | 206.9 | 488.8 | 22.99 | 0.0 | 10.0 | 14.15 | 15.2 | Au1rxx-base64 | 108.181.0.177 |
| 77.64 | shadowsocks | 236.9 | 571.1 | 22.29 | 0.0 | 10.0 | 14.15 | 15.2 | Au1rxx-base64 | 149.22.95.183 |
| 77.63 | shadowsocks | 237.3 | 487.7 | 22.28 | 0.0 | 10.0 | 14.15 | 15.2 | Au1rxx-base64 | 173.244.56.9 |
| 75.68 | trojan | 219.7 | 460.2 | 22.69 | 0.0 | 10.0 | 13.89 | 15.28 | Surfboard-tg-mixed | 209.208.227.208 |
| 73.54 | shadowsocks | 290.2 | 658.4 | 21.06 | 0.0 | 10.0 | 14.15 | 15.2 | Au1rxx-base64 | 156.146.38.168 |
| 73.53 | vless | 171.6 | 460.0 | 23.81 | 0.0 | 10.0 | 5.44 | 15.28 | Surfboard-tg-mixed | 198.41.209.87 |
| 73.43 | vless | 175.9 | 445.6 | 23.71 | 0.0 | 10.0 | 5.44 | 15.28 | Surfboard-tg-mixed | 104.16.9.20 |
| 72.98 | vless | 238.5 | 417.5 | 22.26 | 0.0 | 10.0 | 5.44 | 15.28 | Surfboard-tg-mixed | 64.23.143.23 |
| 72.66 | shadowsocks | 304.7 | 647.8 | 20.73 | 0.0 | 10.0 | 14.15 | 15.2 | Au1rxx-base64 | 156.146.38.167 |
| 72.4 | trojan | 305.0 | 647.7 | 20.72 | 0.0 | 10.0 | 13.89 | 14.44 | DeltaKronecker-all | 64.94.95.117 |
| 72.35 | trojan | 317.7 | 696.7 | 20.42 | 0.0 | 10.0 | 13.89 | 14.44 | DeltaKronecker-all | 64.94.95.115 |
| 72.32 | shadowsocks | 326.6 | 754.4 | 20.22 | 0.0 | 10.0 | 14.15 | 15.2 | Au1rxx-base64 | 156.146.38.169 |
| 71.9 | trojan | 354.7 | 804.4 | 19.57 | 0.0 | 10.0 | 13.89 | 14.44 | DeltaKronecker-all | 45.32.195.168 |
| 71.76 | trojan | 354.4 | 790.8 | 19.57 | 0.0 | 10.0 | 13.89 | 14.44 | DeltaKronecker-all | 45.32.198.247 |
| 71.58 | vless | 219.4 | 588.0 | 22.7 | 0.0 | 10.0 | 5.44 | 14.44 | DeltaKronecker-all | 104.17.90.246 |
| 70.97 | trojan | 420.8 | 996.7 | 18.04 | 0.0 | 10.0 | 13.89 | 15.2 | Au1rxx-base64 | 149.28.241.235 |
| 70.62 | trojan | 388.6 | 753.7 | 18.78 | 0.0 | 10.0 | 13.89 | 15.28 | Surfboard-tg-mixed | 162.159.8.101 |
| 68.82 | shadowsocks | 362.1 | 703.7 | 19.39 | 0.0 | 10.0 | 14.15 | 15.2 | Au1rxx-base64 | 198.98.53.130 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | 1.0 | 36 | 61 | prefer |
| Au1rxx-base64 | 0.924 | 1.0 | 19 | 75 | prefer |
| DeltaKronecker-all | 0.843 | 0.766 | 192 | 7600 | prefer |
| Surfboard-tg-mixed | 0.74 | 0.662 | 204 | 5466 | prefer |
| nscl5-all | 0.301 | 1.0 | 1 | 1148 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4165 | observe |
| Epodonios-all | 0.255 | None | 0 | 6278 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3976 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6680 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4082 | observe |
| barry-far-vless | 0.255 | None | 0 | 4587 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5391 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| xiaoji235-airport-v2ray-all | 0.228 | None | 0 | 1319 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 42 |
| geo | TimeoutError | - | 26 |
| 204 | ProxyError | - | 15 |
| 204 | ClientOSError | - | 8 |
| 204 | TimeoutError | - | 8 |
| speed | TimeoutError | - | 8 |
| geo | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 4 |
| cn-block | TimeoutError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
