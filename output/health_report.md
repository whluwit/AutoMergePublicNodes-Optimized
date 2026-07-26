# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-07-26 13:15:00 |
| 运行耗时 | 313.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 102 |
| 原始节点 | 81237 |
| 去重后节点 | 22616 |
| TCP 可达 | 3000 |
| 真实可用 | 675 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22616 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.3 |
| tcp | 31.8 |
| probe | 68.6 |
| real_test | 163.5 |
| generate | 42.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 45504 |
| trojan | 14859 |
| vmess | 10089 |
| shadowsocks | 10029 |
| hysteria2 | 497 |
| http | 84 |
| shadowsocksr | 71 |
| socks | 69 |
| hysteria | 15 |
| anytls | 12 |
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
| 80.37 | shadowsocks | 198.1 | 490.6 | 23.19 | 0.0 | 10.0 | 12.64 | 19.04 | Au1rxx-base64 | 108.181.0.177 |
| 80.19 | shadowsocks | 205.9 | 496.2 | 23.01 | 0.0 | 10.0 | 12.64 | 19.04 | Au1rxx-base64 | 108.181.118.10 |
| 76.74 | shadowsocks | 286.0 | 654.9 | 21.16 | 0.0 | 10.0 | 12.64 | 19.04 | Au1rxx-base64 | 156.146.38.170 |
| 76.67 | shadowsocks | 280.1 | 645.4 | 21.29 | 0.0 | 10.0 | 12.64 | 19.04 | Au1rxx-base64 | 156.146.38.169 |
| 76.5 | shadowsocks | 285.0 | 663.5 | 21.18 | 0.0 | 10.0 | 12.64 | 19.04 | Au1rxx-base64 | 156.146.38.167 |
| 76.15 | vless | 194.0 | 476.1 | 23.29 | 0.0 | 10.0 | 7.34 | 16.52 | DeltaKronecker-all | 104.16.9.20 |
| 76.1 | shadowsocks | 279.8 | 281.0 | 21.3 | 4.46 | 9.9 | 12.64 | 19.04 | Au1rxx-base64 | 149.22.87.204 |
| 76.03 | shadowsocks | 191.2 | 514.3 | 23.35 | 0.0 | 10.0 | 12.64 | 19.04 | Au1rxx-base64 | 173.244.56.6 |
| 76.02 | vless | 199.5 | 475.7 | 23.16 | 0.0 | 10.0 | 7.34 | 16.52 | DeltaKronecker-all | 172.67.209.126 |
| 75.86 | shadowsocks | 261.0 | 546.4 | 21.74 | 0.0 | 10.0 | 12.64 | 19.04 | Au1rxx-base64 | 149.22.95.183 |
| 75.53 | shadowsocks | 285.9 | 661.7 | 21.16 | 0.0 | 10.0 | 12.64 | 19.04 | Au1rxx-base64 | 156.146.38.168 |
| 75.32 | trojan | 344.6 | 328.3 | 19.8 | 2.69 | 9.91 | 13.87 | 19.04 | Au1rxx-base64 | 95.85.94.17 |
| 75.27 | trojan | 340.5 | 331.8 | 19.89 | 2.56 | 9.9 | 13.87 | 19.04 | Au1rxx-base64 | 31.223.184.125 |
| 75.16 | trojan | 343.0 | 333.4 | 19.84 | 2.5 | 9.91 | 13.87 | 19.04 | Au1rxx-base64 | 31.223.184.82 |
| 75.05 | trojan | 335.6 | 340.5 | 20.01 | 2.23 | 9.9 | 13.87 | 19.04 | Au1rxx-base64 | 31.223.184.149 |
| 75.0 | trojan | 335.8 | 342.2 | 20.0 | 2.17 | 9.91 | 13.87 | 19.04 | Au1rxx-base64 | 95.85.94.142 |
| 74.96 | trojan | 335.7 | 342.9 | 20.01 | 2.14 | 9.91 | 13.87 | 19.04 | Au1rxx-base64 | 31.223.184.218 |
| 74.87 | trojan | 337.1 | 344.8 | 19.97 | 2.07 | 9.91 | 13.87 | 19.04 | Au1rxx-base64 | 95.85.94.96 |
| 74.87 | trojan | 342.4 | 337.9 | 19.85 | 2.33 | 9.89 | 13.87 | 19.04 | Au1rxx-base64 | 95.85.94.112 |
| 74.15 | vless | 280.4 | 734.4 | 21.29 | 0.0 | 10.0 | 7.34 | 16.52 | DeltaKronecker-all | 104.25.161.29 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.99 | 1.0 | 75 | 86 | prefer |
| Au1rxx-base64 | 0.969 | 0.912 | 432 | 1462 | prefer |
| Surfboard-tg-mixed | 0.757 | 0.69 | 29 | 5591 | prefer |
| mheidari-all | 0.686 | 0.607 | 163 | 17011 | observe |
| tg-oneclickvpnkeys | 0.519 | 1.0 | 7 | 149 | observe |
| DeltaKronecker-all | 0.456 | 0.375 | 208 | 5950 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| ermaozi | 0.256 | 1.0 | 1 | 30 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4912 | observe |
| Epodonios-all | 0.255 | None | 0 | 6731 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3973 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 6620 | observe |
| barry-far-vless | 0.255 | None | 0 | 4837 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4980 | observe |
| nscl5-all | 0.255 | None | 0 | 2896 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 73 |
| 204 | TimeoutError | - | 52 |
| 204 | ProxyError | - | 31 |
| cn-block | TimeoutError | - | 27 |
| speed | ClientOSError | - | 23 |
| geo | ClientOSError | - | 16 |
| speed | TimeoutError | - | 9 |
| cn-block | ClientOSError | - | 9 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
