# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-07 18:52:23 |
| 运行耗时 | 248.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 100 |
| 原始节点 | 82847 |
| 去重后节点 | 23493 |
| TCP 可达 | 3000 |
| 真实可用 | 447 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23493 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.2 |
| tcp | 34.2 |
| probe | 48.5 |
| real_test | 110.7 |
| generate | 47.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47697 |
| vmess | 12814 |
| trojan | 11044 |
| shadowsocks | 9810 |
| hysteria2 | 1279 |
| shadowsocksr | 75 |
| socks | 70 |
| http | 35 |
| hysteria | 13 |
| tuic | 8 |
| anytls | 2 |

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
| 85.27 | hysteria2 | 251.7 | 703.0 | 21.95 | 0.0 | 10.0 | 14.32 | 20.0 | Au1rxx-base64 | 138.124.68.188 |
| 85.02 | hysteria2 | 252.2 | 703.9 | 21.94 | 0.0 | 9.76 | 14.32 | 20.0 | Au1rxx-base64 | usa1.spectrumproxy.shop |
| 84.26 | hysteria2 | 291.1 | 810.7 | 21.04 | 0.0 | 10.0 | 14.32 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 83.38 | trojan | 250.4 | 682.1 | 21.98 | 0.0 | 10.0 | 14.4 | 20.0 | Au1rxx-base64 | 153.75.250.171 |
| 82.2 | shadowsocks | 223.8 | 618.5 | 22.6 | 0.0 | 10.0 | 13.6 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 81.99 | shadowsocks | 232.8 | 638.5 | 22.39 | 0.0 | 10.0 | 13.6 | 20.0 | Au1rxx-base64 | 37.19.198.244 |
| 81.96 | shadowsocks | 234.2 | 649.7 | 22.36 | 0.0 | 10.0 | 13.6 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 80.13 | shadowsocks | 226.9 | 621.4 | 22.53 | 0.0 | 10.0 | 13.6 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 78.11 | shadowsocks | 282.8 | 652.2 | 21.23 | 0.0 | 10.0 | 13.6 | 20.0 | Au1rxx-base64 | 156.146.38.169 |
| 77.66 | shadowsocks | 275.7 | 633.3 | 21.4 | 0.0 | 10.0 | 13.6 | 20.0 | Au1rxx-base64 | 156.146.38.170 |
| 77.54 | shadowsocks | 290.9 | 672.3 | 21.04 | 0.0 | 10.0 | 13.6 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 77.5 | hysteria2 | 349.2 | 680.9 | 19.69 | 0.0 | 10.0 | 14.32 | 20.0 | Au1rxx-base64 | 62.210.124.146 |
| 77.03 | shadowsocks | 280.0 | 637.9 | 21.3 | 0.0 | 10.0 | 13.6 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 76.8 | vless | 274.2 | 687.4 | 21.43 | 0.0 | 10.0 | 8.37 | 20.0 | Au1rxx-base64 | 159.195.12.98 |
| 76.68 | hysteria2 | 353.7 | 665.8 | 19.59 | 0.0 | 10.0 | 14.32 | 20.0 | Au1rxx-base64 | 31.76.113.32 |
| 74.41 | shadowsocks | 318.2 | 577.3 | 20.41 | 0.0 | 10.0 | 13.6 | 20.0 | Au1rxx-base64 | 173.244.56.9 |
| 74.3 | vless | 295.9 | 853.1 | 20.93 | 0.0 | 10.0 | 8.37 | 20.0 | Au1rxx-base64 | u.cryptoofarm.com |
| 73.84 | trojan | 399.2 | 766.8 | 18.54 | 0.0 | 9.76 | 14.4 | 20.0 | Au1rxx-base64 | definite-ladybird.rooster465.autos |
| 73.52 | hysteria2 | 353.4 | 663.1 | 19.6 | 0.0 | 5.93 | 14.32 | 20.0 | Au1rxx-base64 | it-one.quiet-rogue.site |
| 73.52 | trojan | 402.7 | 679.5 | 18.45 | 0.0 | 10.0 | 14.4 | 20.0 | Au1rxx-base64 | 44.246.163.102 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.984 | 0.925 | 346 | 1543 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 25 | prefer |
| DeltaKronecker-all | 0.606 | 0.527 | 188 | 5326 | observe |
| Surfboard-tg-mixed | 0.397 | 0.417 | 12 | 6450 | observe |
| mheidari-all | 0.3 | 0.4 | 5 | 17684 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 178 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5282 | observe |
| Epodonios-all | 0.255 | None | 0 | 7082 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7593 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5170 | observe |
| barry-far-vless | 0.255 | None | 0 | 5504 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5175 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| nscl5-all | 0.246 | None | 0 | 1772 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 32 |
| 204 | TimeoutError | - | 18 |
| geo | TimeoutError | - | 17 |
| geo | ClientOSError | - | 16 |
| cn-block | TimeoutError | - | 12 |
| speed | ClientOSError | - | 9 |
| speed | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
