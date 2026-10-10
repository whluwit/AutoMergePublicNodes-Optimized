# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-10 17:03:10 |
| 运行耗时 | 747.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97961 |
| 去重后节点 | 27259 |
| TCP 可达 | 3000 |
| 真实可用 | 407 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27259 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.1 |
| geo | 1.4 |
| tcp | 47.1 |
| probe | 278.4 |
| real_test | 326.0 |
| generate | 86.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57819 |
| vmess | 15693 |
| shadowsocks | 11669 |
| trojan | 10476 |
| hysteria2 | 1491 |
| http | 519 |
| shadowsocksr | 167 |
| socks | 72 |
| anytls | 32 |
| hysteria | 16 |
| tuic | 7 |

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
| 84.68 | hysteria2 | 210.2 | 221.9 | 22.91 | 6.68 | 10.0 | 12.63 | 18.8 | Au1rxx-base64 | 45.32.10.7 |
| 82.41 | vless | 210.9 | 548.2 | 22.9 | 0.0 | 10.0 | 10.71 | 18.8 | Au1rxx-base64 | 15.204.97.197 |
| 82.23 | vless | 218.3 | 562.0 | 22.72 | 0.0 | 10.0 | 10.71 | 18.8 | Au1rxx-base64 | 15.204.97.216 |
| 81.43 | shadowsocks | 210.0 | 565.4 | 22.92 | 0.0 | 10.0 | 13.71 | 18.8 | Au1rxx-base64 | 149.22.95.183 |
| 80.71 | hysteria2 | 233.2 | 294.7 | 22.38 | 3.95 | 9.46 | 12.63 | 18.8 | Au1rxx-base64 | vp3.yysyy.online |
| 80.32 | shadowsocks | 236.1 | 641.4 | 22.31 | 0.0 | 10.0 | 13.71 | 18.8 | Au1rxx-base64 | 5.78.51.123 |
| 79.7 | hysteria2 | 265.9 | 311.3 | 21.62 | 3.33 | 10.0 | 12.63 | 18.8 | Au1rxx-base64 | 158.101.148.79 |
| 79.53 | vless | 237.9 | 531.9 | 22.27 | 0.0 | 10.0 | 10.71 | 18.8 | Au1rxx-base64 | 47.251.108.158 |
| 79.17 | trojan | 225.4 | 552.9 | 22.56 | 0.0 | 8.88 | 13.43 | 18.8 | Au1rxx-base64 | alert-titmouse.rooster465.autos |
| 78.8 | trojan | 283.9 | 727.7 | 21.21 | 0.0 | 8.86 | 13.43 | 18.8 | Au1rxx-base64 | pro-mako.rooster465.autos |
| 77.74 | vless | 412.4 | 1100.5 | 18.23 | 0.0 | 10.0 | 10.71 | 18.8 | Au1rxx-base64 | 51.81.203.63 |
| 77.28 | vless | 216.3 | 558.2 | 22.77 | 0.0 | 10.0 | 10.71 | 18.8 | Au1rxx-base64 | 15.204.97.219 |
| 75.91 | hysteria2 | 262.0 | 309.9 | 21.71 | 3.38 | 6.19 | 12.63 | 18.8 | Au1rxx-base64 | open.2ml.bid |
| 75.62 | vless | 272.2 | 582.9 | 21.48 | 0.0 | 10.0 | 10.71 | 18.8 | Au1rxx-base64 | 195.123.240.65 |
| 75.62 | http | 278.4 | 562.9 | 21.33 | 0.0 | 10.0 | 12.69 | 17.72 | zhangkai | 138.199.35.198 |
| 75.61 | shadowsocks | 277.9 | 324.3 | 21.34 | 2.84 | 10.0 | 13.71 | 18.8 | Au1rxx-base64 | 149.22.87.240 |
| 75.54 | shadowsocks | 277.7 | 329.5 | 21.35 | 2.64 | 10.0 | 13.71 | 18.8 | Au1rxx-base64 | 149.22.87.241 |
| 75.51 | hysteria2 | 354.8 | 750.1 | 19.57 | 0.0 | 10.0 | 12.63 | 18.8 | Au1rxx-base64 | 129.213.91.185 |
| 75.42 | trojan | 362.0 | 272.4 | 19.4 | 4.78 | 10.0 | 13.43 | 18.8 | Au1rxx-base64 | 13.231.247.130 |
| 74.68 | trojan | 316.7 | 334.1 | 20.45 | 2.47 | 9.49 | 13.43 | 18.8 | Au1rxx-base64 | optimal-penguin.rooster465.autos |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.933 | 0.86 | 365 | 1857 | prefer |
| zhangkai | 0.886 | 0.913 | 23 | 144 | prefer |
| mheidari-all | 0.743 | 0.667 | 96 | 23714 | prefer |
| Surfboard-tg-mixed | 0.446 | 0.8 | 5 | 7171 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4999 | observe |
| Epodonios-all | 0.255 | None | 0 | 7647 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9352 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5676 | observe |
| barry-far-vless | 0.255 | None | 0 | 5861 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4347 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.249 | None | 0 | 1857 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 23 |
| 204 | TimeoutError | - | 21 |
| speed | ClientOSError | - | 16 |
| 204 | ProxyConnectionError | - | 14 |
| 204 | ProxyError | - | 9 |
| speed | TimeoutError | - | 9 |
| 204 | ClientOSError | - | 5 |
| geo | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| geo | TimeoutError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
