# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-02 19:07:31 |
| 运行耗时 | 303.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 101 |
| 原始节点 | 81292 |
| 去重后节点 | 22651 |
| TCP 可达 | 3000 |
| 真实可用 | 633 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22651 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| geo | 1.3 |
| tcp | 33.9 |
| probe | 66.0 |
| real_test | 159.6 |
| generate | 35.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49651 |
| vmess | 12554 |
| shadowsocks | 10276 |
| trojan | 7745 |
| hysteria2 | 736 |
| http | 165 |
| socks | 72 |
| shadowsocksr | 71 |
| hysteria | 10 |
| anytls | 7 |
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
| 81.95 | http | 333.8 | 921.1 | 20.05 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.21 |
| 81.83 | http | 338.9 | 936.1 | 19.93 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.7 |
| 81.8 | http | 340.3 | 941.9 | 19.9 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.8 |
| 81.51 | http | 352.7 | 977.6 | 19.61 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.23 |
| 81.42 | http | 356.6 | 992.1 | 19.52 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.5 |
| 81.31 | http | 361.3 | 1006.5 | 19.41 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.20 |
| 81.24 | http | 364.7 | 1015.2 | 19.34 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 156.146.59.25 |
| 78.56 | hysteria2 | 232.4 | 644.0 | 22.4 | 0.0 | 10.0 | 11.88 | 15.38 | Au1rxx-base64 | 159.223.157.129 |
| 78.45 | hysteria2 | 241.5 | 667.3 | 22.19 | 0.0 | 10.0 | 11.88 | 15.38 | Au1rxx-base64 | 138.124.68.188 |
| 77.14 | hysteria2 | 250.3 | 688.1 | 21.98 | 0.0 | 8.9 | 11.88 | 15.38 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 75.83 | vless | 275.4 | 730.4 | 21.4 | 0.0 | 10.0 | 9.05 | 15.38 | Au1rxx-base64 | 167.17.69.171 |
| 75.65 | shadowsocks | 229.4 | 628.0 | 22.47 | 0.0 | 10.0 | 11.8 | 15.38 | Au1rxx-base64 | 37.19.198.236 |
| 75.63 | shadowsocks | 230.0 | 632.5 | 22.45 | 0.0 | 10.0 | 11.8 | 15.38 | Au1rxx-base64 | 37.19.198.244 |
| 75.59 | http | 341.0 | 608.6 | 19.88 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.213 |
| 75.58 | vless | 286.3 | 727.4 | 21.15 | 0.0 | 10.0 | 9.05 | 15.38 | Au1rxx-base64 | 159.195.12.98 |
| 75.37 | http | 356.5 | 618.8 | 19.53 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.218 |
| 75.25 | http | 349.4 | 632.0 | 19.69 | 0.0 | 10.0 | 14.9 | 20.0 | zhangkai | 138.199.35.197 |
| 74.39 | shadowsocks | 283.7 | 796.4 | 21.21 | 0.0 | 10.0 | 11.8 | 15.38 | Au1rxx-base64 | 37.19.198.243 |
| 73.77 | vless | 278.0 | 686.4 | 21.34 | 0.0 | 10.0 | 9.05 | 15.38 | Au1rxx-base64 | 216.152.147.28 |
| 72.85 | vless | 322.2 | 629.0 | 20.32 | 0.0 | 10.0 | 9.05 | 13.8 | Surfboard-tg-mixed | 45.206.5.122 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | 1.0 | 143 | 344 | prefer |
| Au1rxx-base64 | 0.79 | 0.724 | 548 | 1651 | prefer |
| mheidari-all | 0.541 | 0.474 | 19 | 18817 | observe |
| DeltaKronecker-all | 0.507 | 0.425 | 73 | 3437 | observe |
| xiaoji235-airport-v2ray-all | 0.48 | 1.0 | 4 | 3833 | observe |
| Surfboard-tg-mixed | 0.398 | 0.315 | 146 | 5169 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 179 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 56 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5486 | observe |
| Epodonios-all | 0.255 | None | 0 | 5783 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3971 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7116 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4107 | observe |
| barry-far-vless | 0.255 | None | 0 | 4490 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 107 |
| 204 | ProxyError | - | 50 |
| speed | TimeoutError | - | 43 |
| cn-block | TimeoutError | - | 33 |
| 204 | TimeoutError | - | 24 |
| speed | ClientOSError | - | 13 |
| cn-block | ProxyError | - | 12 |
| geo | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 4 |
| speed | ProxyError | - | 3 |
| geo | ProxyError | - | 3 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
