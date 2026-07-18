# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-18 13:10:41 |
| 运行耗时 | 388.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 81258 |
| 去重后节点 | 22073 |
| TCP 可达 | 3000 |
| 真实可用 | 846 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22073 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.1 |
| tcp | 32.0 |
| probe | 77.1 |
| real_test | 241.4 |
| generate | 31.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47868 |
| trojan | 11787 |
| vmess | 10744 |
| shadowsocks | 10249 |
| hysteria2 | 330 |
| shadowsocksr | 126 |
| socks | 76 |
| http | 55 |
| hysteria | 14 |
| tuic | 7 |
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
| 81.53 | shadowsocks | 195.5 | 492.3 | 23.25 | 0.0 | 10.0 | 13.26 | 19.02 | Au1rxx-base64 | 173.244.56.9 |
| 81.5 | shadowsocks | 196.7 | 495.0 | 23.22 | 0.0 | 10.0 | 13.26 | 19.02 | Au1rxx-base64 | 173.244.56.6 |
| 80.95 | shadowsocks | 199.2 | 483.1 | 23.17 | 0.0 | 10.0 | 13.26 | 19.02 | Au1rxx-base64 | 108.181.118.10 |
| 80.51 | shadowsocks | 218.2 | 537.1 | 22.73 | 0.0 | 10.0 | 13.26 | 19.02 | Au1rxx-base64 | 108.181.0.177 |
| 79.87 | shadowsocks | 251.7 | 604.3 | 21.95 | 0.0 | 10.0 | 13.26 | 19.02 | Au1rxx-base64 | 156.146.38.168 |
| 79.46 | shadowsocks | 266.0 | 646.8 | 21.62 | 0.0 | 10.0 | 13.26 | 19.02 | Au1rxx-base64 | 156.146.38.167 |
| 79.32 | shadowsocks | 259.8 | 641.3 | 21.76 | 0.0 | 10.0 | 13.26 | 19.02 | Au1rxx-base64 | 156.146.38.169 |
| 78.03 | shadowsocks | 260.5 | 640.2 | 21.75 | 0.0 | 10.0 | 13.26 | 19.02 | Au1rxx-base64 | 156.146.38.170 |
| 76.88 | trojan | 216.9 | 530.3 | 22.76 | 0.0 | 10.0 | 14.3 | 18.16 | DeltaKronecker-all | 104.16.99.215 |
| 76.02 | shadowsocks | 287.4 | 613.2 | 21.12 | 0.0 | 10.0 | 13.26 | 19.02 | Au1rxx-base64 | 149.22.95.183 |
| 75.23 | trojan | 394.5 | 291.0 | 18.65 | 4.09 | 9.25 | 14.3 | 19.02 | Au1rxx-base64 | immune-mullet.rooster465.autos |
| 75.17 | trojan | 343.5 | 341.0 | 19.83 | 2.21 | 9.86 | 14.3 | 19.02 | Au1rxx-base64 | 13.115.249.38 |
| 75.16 | trojan | 294.5 | 617.1 | 20.96 | 0.0 | 10.0 | 14.3 | 19.02 | Au1rxx-base64 | nearby-muskrat.rooster465.autos |
| 75.12 | trojan | 387.0 | 300.0 | 18.82 | 3.75 | 9.31 | 14.3 | 19.02 | Au1rxx-base64 | innocent-rattler.rooster465.autos |
| 75.09 | trojan | 347.6 | 340.1 | 19.73 | 2.25 | 9.83 | 14.3 | 19.02 | Au1rxx-base64 | 13.115.80.163 |
| 75.08 | trojan | 345.0 | 342.0 | 19.79 | 2.18 | 9.83 | 14.3 | 19.02 | Au1rxx-base64 | 13.115.229.63 |
| 75.0 | trojan | 343.9 | 344.6 | 19.82 | 2.08 | 9.83 | 14.3 | 19.02 | Au1rxx-base64 | 35.77.91.8 |
| 75.0 | trojan | 347.4 | 343.0 | 19.73 | 2.14 | 9.83 | 14.3 | 19.02 | Au1rxx-base64 | 3.112.231.253 |
| 74.86 | trojan | 343.2 | 349.1 | 19.83 | 1.91 | 9.83 | 14.3 | 19.02 | Au1rxx-base64 | 18.177.140.248 |
| 74.86 | trojan | 344.6 | 348.5 | 19.8 | 1.93 | 9.85 | 14.3 | 19.02 | Au1rxx-base64 | 176.34.18.166 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | 1.0 | 36 | 61 | prefer |
| mheidari-all | 0.925 | 0.847 | 418 | 19072 | prefer |
| Au1rxx-base64 | 0.883 | 0.882 | 136 | 150 | prefer |
| Surfboard-tg-mixed | 0.815 | 0.738 | 149 | 5677 | prefer |
| xiaoji235-airport-v2ray-all | 0.438 | 1.0 | 3 | 4321 | observe |
| DeltaKronecker-all | 0.335 | 0.254 | 870 | 4096 | observe |
| nscl5-all | 0.287 | 0.5 | 2 | 1976 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4371 | observe |
| Epodonios-all | 0.255 | None | 0 | 6767 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3976 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7257 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 4291 | observe |
| barry-far-vless | 0.255 | None | 0 | 4927 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 5334 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 388 |
| geo | TimeoutError | - | 228 |
| geo | ClientOSError | - | 47 |
| cn-block | TimeoutError | - | 26 |
| 204 | ProxyError | - | 19 |
| 204 | TimeoutError | - | 18 |
| 204 | ClientOSError | - | 11 |
| speed | TimeoutError | - | 10 |
| cn-block | ClientOSError | - | 8 |
| cn-block | ProxyError | - | 7 |
| geo | ProxyError | - | 6 |
| speed | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
