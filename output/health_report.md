# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-30 15:59:17 |
| 运行耗时 | 238.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 79852 |
| 去重后节点 | 21843 |
| TCP 可达 | 3000 |
| 真实可用 | 580 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21843 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| geo | 1.4 |
| tcp | 35.0 |
| probe | 54.4 |
| real_test | 114.0 |
| generate | 29.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50236 |
| vmess | 10874 |
| shadowsocks | 10221 |
| trojan | 6621 |
| hysteria2 | 1514 |
| http | 170 |
| shadowsocksr | 123 |
| socks | 78 |
| hysteria | 7 |
| tuic | 7 |
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
| 82.22 | shadowsocks | 225.1 | 573.5 | 22.57 | 0.0 | 10.0 | 13.65 | 20.0 | Au1rxx-base64 | 156.146.38.168 |
| 81.99 | shadowsocks | 234.7 | 578.7 | 22.34 | 0.0 | 10.0 | 13.65 | 20.0 | Au1rxx-base64 | 156.146.38.167 |
| 81.37 | vless | 276.8 | 614.3 | 21.37 | 0.0 | 10.0 | 12.45 | 20.0 | Au1rxx-base64 | 195.211.99.49 |
| 79.74 | vless | 282.1 | 574.9 | 21.25 | 0.0 | 10.0 | 12.45 | 20.0 | Au1rxx-base64 | 172.233.156.118 |
| 79.69 | vless | 395.4 | 955.3 | 18.62 | 0.0 | 10.0 | 12.45 | 20.0 | Au1rxx-base64 | 45.138.100.226 |
| 79.67 | shadowsocks | 286.6 | 696.4 | 21.14 | 0.0 | 10.0 | 13.65 | 20.0 | Au1rxx-base64 | 37.19.198.243 |
| 79.5 | vless | 306.8 | 676.7 | 20.68 | 0.0 | 10.0 | 12.45 | 20.0 | Au1rxx-base64 | 64.23.229.123 |
| 79.43 | vless | 297.5 | 599.8 | 20.89 | 0.0 | 10.0 | 12.45 | 20.0 | Au1rxx-base64 | 172.239.67.231 |
| 79.26 | shadowsocks | 289.4 | 698.4 | 21.08 | 0.0 | 10.0 | 13.65 | 20.0 | Au1rxx-base64 | 37.19.198.236 |
| 79.25 | vless | 293.9 | 691.3 | 20.97 | 0.0 | 8.38 | 12.45 | 20.0 | Au1rxx-base64 | ql6k-m23nix.logicara.top |
| 79.25 | shadowsocks | 298.2 | 656.8 | 20.88 | 0.0 | 10.0 | 13.65 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 79.22 | vless | 290.1 | 577.2 | 21.06 | 0.0 | 10.0 | 12.45 | 20.0 | Au1rxx-base64 | 172.235.38.85 |
| 79.18 | vless | 369.9 | 683.5 | 19.21 | 0.0 | 10.0 | 12.45 | 20.0 | Au1rxx-base64 | 169.40.42.212 |
| 78.92 | vless | 417.7 | 807.0 | 18.11 | 0.0 | 10.0 | 12.45 | 20.0 | Au1rxx-base64 | 38.180.242.205 |
| 78.83 | vless | 338.3 | 780.0 | 19.95 | 0.0 | 10.0 | 12.45 | 20.0 | Au1rxx-base64 | 169.40.42.182 |
| 78.79 | vless | 315.2 | 602.7 | 20.48 | 0.0 | 10.0 | 12.45 | 20.0 | Au1rxx-base64 | 216.167.21.162 |
| 78.78 | hysteria2 | 294.6 | 712.7 | 20.96 | 0.0 | 10.0 | 13.57 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 78.72 | vless | 313.2 | 649.3 | 20.53 | 0.0 | 10.0 | 12.45 | 20.0 | Au1rxx-base64 | 70.39.196.142 |
| 78.72 | trojan | 398.4 | 1028.0 | 18.55 | 0.0 | 10.0 | 14.17 | 20.0 | Au1rxx-base64 | 64.94.95.118 |
| 78.71 | vless | 373.5 | 746.6 | 19.13 | 0.0 | 10.0 | 12.45 | 20.0 | Au1rxx-base64 | 169.40.42.223 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.955 | 333 | 1804 | prefer |
| zhangkai | 0.964 | 1.0 | 22 | 144 | prefer |
| DeltaKronecker-all | 0.847 | 0.771 | 131 | 5576 | prefer |
| Surfboard-tg-mixed | 0.831 | 0.754 | 171 | 7004 | prefer |
| mheidari-all | 0.643 | 0.9 | 10 | 15115 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4762 | observe |
| Epodonios-all | 0.255 | None | 0 | 7409 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7533 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5872 | observe |
| barry-far-vless | 0.255 | None | 0 | 6056 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 3949 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1804 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 19 |
| cn-block | TimeoutError | - | 18 |
| geo | ClientOSError | - | 16 |
| geo | TimeoutError | - | 8 |
| 204 | ProxyError | - | 7 |
| speed | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| speed | TimeoutError | - | 2 |
| speed | ClientPayloadError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
