# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-26 08:25:13 |
| 运行耗时 | 335.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 81009 |
| 去重后节点 | 22426 |
| TCP 可达 | 3000 |
| 真实可用 | 929 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22426 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.3 |
| tcp | 30.7 |
| probe | 63.2 |
| real_test | 194.0 |
| generate | 41.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45293 |
| trojan | 14699 |
| vmess | 10158 |
| shadowsocks | 10132 |
| hysteria2 | 471 |
| http | 84 |
| shadowsocksr | 76 |
| socks | 72 |
| hysteria | 13 |
| tuic | 10 |
| anytls | 1 |

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
| 80.7 | shadowsocks | 250.9 | 614.9 | 21.97 | 0.0 | 10.0 | 13.65 | 19.08 | Au1rxx-base64 | 156.146.38.167 |
| 80.66 | shadowsocks | 252.7 | 622.8 | 21.93 | 0.0 | 10.0 | 13.65 | 19.08 | Au1rxx-base64 | 156.146.38.170 |
| 80.54 | trojan | 284.0 | 651.1 | 21.2 | 0.0 | 10.0 | 13.9 | 19.08 | Au1rxx-base64 | 163.245.196.68 |
| 80.5 | shadowsocks | 259.7 | 637.6 | 21.77 | 0.0 | 10.0 | 13.65 | 19.08 | Au1rxx-base64 | 37.19.198.236 |
| 80.43 | shadowsocks | 262.6 | 646.9 | 21.7 | 0.0 | 10.0 | 13.65 | 19.08 | Au1rxx-base64 | 156.146.38.169 |
| 80.3 | shadowsocks | 268.0 | 667.9 | 21.57 | 0.0 | 10.0 | 13.65 | 19.08 | Au1rxx-base64 | 37.19.198.244 |
| 80.09 | shadowsocks | 277.4 | 687.7 | 21.36 | 0.0 | 10.0 | 13.65 | 19.08 | Au1rxx-base64 | 37.19.198.160 |
| 80.0 | shadowsocks | 281.1 | 699.8 | 21.27 | 0.0 | 10.0 | 13.65 | 19.08 | Au1rxx-base64 | 37.19.198.243 |
| 78.64 | shadowsocks | 318.1 | 830.0 | 20.41 | 0.0 | 10.0 | 13.65 | 19.08 | Au1rxx-base64 | 185.196.61.82 |
| 78.61 | shadowsocks | 254.6 | 627.8 | 21.88 | 0.0 | 10.0 | 13.65 | 19.08 | Au1rxx-base64 | 156.146.38.168 |
| 75.51 | shadowsocks | 282.7 | 590.3 | 21.23 | 0.0 | 10.0 | 13.65 | 19.08 | Au1rxx-base64 | 173.244.56.9 |
| 75.03 | shadowsocks | 313.5 | 660.7 | 20.52 | 0.0 | 10.0 | 13.65 | 19.08 | Au1rxx-base64 | 149.22.95.183 |
| 74.84 | shadowsocks | 329.0 | 717.9 | 20.16 | 0.0 | 10.0 | 13.65 | 19.08 | Au1rxx-base64 | 108.181.57.93 |
| 74.64 | shadowsocks | 302.9 | 584.4 | 20.77 | 0.0 | 10.0 | 13.65 | 19.08 | Au1rxx-base64 | 108.181.0.177 |
| 74.5 | shadowsocks | 304.1 | 597.7 | 20.74 | 0.0 | 10.0 | 13.65 | 19.08 | Au1rxx-base64 | 108.181.118.10 |
| 74.48 | trojan | 527.7 | 1405.4 | 15.56 | 0.0 | 10.0 | 13.9 | 19.08 | Au1rxx-base64 | 153.75.250.171 |
| 74.05 | hysteria2 | 391.4 | 716.1 | 18.72 | 0.0 | 9.93 | 13.64 | 19.08 | Au1rxx-base64 | 62.210.124.146 |
| 72.74 | vless | 271.1 | 675.6 | 21.5 | 0.0 | 10.0 | 5.16 | 19.08 | Au1rxx-base64 | 47.253.226.114 |
| 72.22 | trojan | 671.3 | 1875.9 | 12.24 | 0.0 | 10.0 | 13.9 | 19.08 | Au1rxx-base64 | 148.72.168.35 |
| 71.95 | vless | 434.9 | 557.5 | 17.71 | 0.0 | 10.0 | 5.16 | 19.08 | Au1rxx-base64 | 47.89.186.170 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.991 | 1.0 | 76 | 86 | prefer |
| Au1rxx-base64 | 0.952 | 0.896 | 454 | 1442 | prefer |
| mheidari-all | 0.9 | 0.823 | 231 | 17285 | prefer |
| DeltaKronecker-all | 0.826 | 0.749 | 203 | 5950 | prefer |
| Surfboard-tg-mixed | 0.664 | 0.585 | 176 | 5447 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4912 | observe |
| Epodonios-all | 0.255 | None | 0 | 6589 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3974 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6596 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4215 | observe |
| barry-far-vless | 0.255 | None | 0 | 4874 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4980 | observe |
| nscl5-all | 0.255 | None | 0 | 2896 | observe |
| xiaoji235-airport-v2ray-all | 0.24 | None | 0 | 1624 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 58 |
| cn-block | TimeoutError | - | 29 |
| speed | ClientOSError | - | 26 |
| 204 | ProxyError | - | 24 |
| speed | TimeoutError | - | 21 |
| 204 | TimeoutError | - | 19 |
| geo | ClientOSError | - | 15 |
| cn-block | ClientOSError | - | 8 |
| cn-block | ProxyError | - | 6 |
| 204 | ClientOSError | - | 4 |
| geo | ProxyError | - | 3 |
| speed | ProxyError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
