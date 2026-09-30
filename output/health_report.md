# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-30 11:58:33 |
| 运行耗时 | 595.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 96627 |
| 去重后节点 | 26883 |
| TCP 可达 | 3000 |
| 真实可用 | 389 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 26883 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| geo | 1.5 |
| tcp | 44.9 |
| probe | 287.5 |
| real_test | 167.7 |
| generate | 86.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58612 |
| vmess | 15276 |
| shadowsocks | 11290 |
| trojan | 9078 |
| hysteria2 | 1429 |
| http | 639 |
| shadowsocksr | 171 |
| socks | 72 |
| anytls | 37 |
| hysteria | 15 |
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
| 77.64 | shadowsocks | 260.3 | 657.5 | 21.75 | 0.0 | 10.0 | 13.17 | 17.22 | Au1rxx-base64 | 140.82.63.79 |
| 77.07 | shadowsocks | 263.4 | 715.4 | 21.68 | 0.0 | 10.0 | 13.17 | 17.22 | Au1rxx-base64 | 37.19.198.236 |
| 77.03 | shadowsocks | 262.0 | 712.4 | 21.71 | 0.0 | 8.93 | 13.17 | 17.22 | Au1rxx-base64 | 37.19.198.244 |
| 76.45 | shadowsocks | 311.7 | 836.3 | 20.56 | 0.0 | 10.0 | 13.17 | 17.22 | Au1rxx-base64 | 15.204.246.132 |
| 75.46 | hysteria2 | 282.5 | 572.7 | 21.24 | 0.0 | 10.0 | 13.27 | 17.22 | Au1rxx-base64 | 192.255.128.123 |
| 75.33 | shadowsocks | 278.8 | 645.3 | 21.32 | 0.0 | 10.0 | 13.17 | 17.22 | Au1rxx-base64 | 156.146.38.167 |
| 75.13 | shadowsocks | 261.0 | 707.3 | 21.74 | 0.0 | 10.0 | 13.17 | 17.22 | Au1rxx-base64 | 37.19.198.243 |
| 73.89 | vless | 274.0 | 685.6 | 21.44 | 0.0 | 10.0 | 5.23 | 17.22 | Au1rxx-base64 | 169.40.42.52 |
| 73.83 | vless | 276.3 | 729.2 | 21.38 | 0.0 | 10.0 | 5.23 | 17.22 | Au1rxx-base64 | 136.0.213.120 |
| 73.71 | shadowsocks | 325.8 | 788.2 | 20.24 | 0.0 | 10.0 | 13.17 | 17.22 | Au1rxx-base64 | 156.146.38.170 |
| 73.49 | vless | 291.0 | 757.7 | 21.04 | 0.0 | 10.0 | 5.23 | 17.22 | Au1rxx-base64 | 185.95.231.156 |
| 73.36 | vless | 296.5 | 734.2 | 20.91 | 0.0 | 10.0 | 5.23 | 17.22 | Au1rxx-base64 | 66.70.179.198 |
| 73.22 | vless | 275.8 | 723.9 | 21.39 | 0.0 | 9.38 | 5.23 | 17.22 | Au1rxx-base64 | usa-3.letsconnectpoint.com |
| 73.04 | shadowsocks | 458.9 | 1241.4 | 17.15 | 0.0 | 10.0 | 13.17 | 17.22 | Au1rxx-base64 | 15.204.233.41 |
| 72.99 | shadowsocks | 374.8 | 990.3 | 19.1 | 0.0 | 10.0 | 13.17 | 17.22 | Au1rxx-base64 | 51.222.200.165 |
| 72.73 | shadowsocks | 317.2 | 807.1 | 20.43 | 0.0 | 10.0 | 13.17 | 17.22 | Au1rxx-base64 | 66.23.204.219 |
| 72.64 | vless | 328.0 | 881.1 | 20.19 | 0.0 | 10.0 | 5.23 | 17.22 | Au1rxx-base64 | 137.184.218.169 |
| 72.43 | vless | 336.9 | 839.3 | 19.98 | 0.0 | 10.0 | 5.23 | 17.22 | Au1rxx-base64 | 169.40.42.16 |
| 72.36 | vless | 340.0 | 915.6 | 19.91 | 0.0 | 10.0 | 5.23 | 17.22 | Au1rxx-base64 | 159.89.87.21 |
| 72.24 | shadowsocks | 277.6 | 647.3 | 21.35 | 0.0 | 10.0 | 13.17 | 13.98 | Surfboard-tg-mixed | 156.146.38.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.937 | 0.872 | 47 | 22755 | prefer |
| Au1rxx-base64 | 0.852 | 0.784 | 278 | 1752 | prefer |
| ermaozi | 0.746 | 0.741 | 54 | 335 | prefer |
| Surfboard-tg-mixed | 0.714 | 0.636 | 121 | 6952 | prefer |
| DeltaKronecker-all | 0.602 | 0.588 | 17 | 5434 | observe |
| tg-oneclickvpnkeys | 0.36 | 1.0 | 3 | 53 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5327 | observe |
| Epodonios-all | 0.255 | None | 0 | 7458 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9375 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5632 | observe |
| barry-far-vless | 0.255 | None | 0 | 5879 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4183 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 49 |
| 204 | TimeoutError | - | 15 |
| geo | TimeoutError | - | 14 |
| cn-block | TimeoutError | - | 13 |
| 204 | ProxyError | - | 12 |
| cn-block | ClientOSError | - | 11 |
| speed | TimeoutError | - | 7 |
| geo | ClientOSError | - | 5 |
| 204 | ProxyConnectionError | - | 4 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
