# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-22 01:03:46 |
| 运行耗时 | 392.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 99 |
| 原始节点 | 93034 |
| 去重后节点 | 23011 |
| TCP 可达 | 3000 |
| 真实可用 | 1098 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23011 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| geo | 0.8 |
| tcp | 38.5 |
| probe | 69.0 |
| real_test | 230.8 |
| generate | 47.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51079 |
| trojan | 19044 |
| shadowsocks | 10508 |
| vmess | 10281 |
| hysteria2 | 1571 |
| shadowsocksr | 200 |
| http | 167 |
| socks | 124 |
| anytls | 32 |
| hysteria | 15 |
| tuic | 13 |

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
| 82.85 | vless | 267.8 | 703.8 | 21.58 | 0.0 | 10.0 | 11.67 | 19.6 | mheidari-all | 204.48.20.223 |
| 82.6 | vless | 288.7 | 627.4 | 21.09 | 0.0 | 10.0 | 11.67 | 20.0 | Au1rxx-base64 | 169.40.42.232 |
| 82.52 | vless | 299.4 | 660.2 | 20.85 | 0.0 | 10.0 | 11.67 | 20.0 | Au1rxx-base64 | 169.40.42.16 |
| 82.39 | vless | 280.3 | 709.6 | 21.29 | 0.0 | 10.0 | 11.67 | 20.0 | Au1rxx-base64 | 169.40.42.35 |
| 82.27 | vless | 292.7 | 761.3 | 21.0 | 0.0 | 10.0 | 11.67 | 19.6 | mheidari-all | 169.40.42.182 |
| 82.15 | vless | 315.1 | 774.1 | 20.48 | 0.0 | 10.0 | 11.67 | 20.0 | Au1rxx-base64 | 169.40.42.225 |
| 82.1 | vless | 269.9 | 636.2 | 21.53 | 0.0 | 10.0 | 11.67 | 20.0 | Au1rxx-base64 | 195.211.98.214 |
| 81.97 | vless | 278.0 | 646.1 | 21.34 | 0.0 | 10.0 | 11.67 | 19.6 | mheidari-all | 195.211.99.45 |
| 81.87 | vless | 327.3 | 888.4 | 20.2 | 0.0 | 10.0 | 11.67 | 20.0 | Au1rxx-base64 | 137.184.218.169 |
| 81.82 | hysteria2 | 250.7 | 680.9 | 21.97 | 0.0 | 10.0 | 14.35 | 19.6 | mheidari-all | 159.223.157.129 |
| 81.36 | vless | 337.3 | 890.5 | 19.97 | 0.0 | 10.0 | 11.67 | 20.0 | Au1rxx-base64 | 169.40.42.104 |
| 81.31 | vless | 255.8 | 562.6 | 21.86 | 0.0 | 10.0 | 11.67 | 19.6 | mheidari-all | 216.227.161.95 |
| 81.31 | vless | 351.5 | 881.4 | 19.64 | 0.0 | 10.0 | 11.67 | 20.0 | Au1rxx-base64 | 169.40.42.229 |
| 80.94 | shadowsocks | 247.4 | 617.4 | 22.05 | 0.0 | 10.0 | 13.14 | 20.0 | Au1rxx-base64 | 155.138.136.240 |
| 80.84 | vless | 299.4 | 727.3 | 20.85 | 0.0 | 10.0 | 11.67 | 20.0 | Au1rxx-base64 | 216.152.147.28 |
| 80.82 | vless | 372.5 | 992.6 | 19.15 | 0.0 | 10.0 | 11.67 | 20.0 | Au1rxx-base64 | 169.40.42.133 |
| 80.72 | vless | 377.1 | 776.3 | 19.05 | 0.0 | 10.0 | 11.67 | 20.0 | Au1rxx-base64 | 169.40.42.231 |
| 80.64 | shadowsocks | 271.1 | 735.3 | 21.5 | 0.0 | 10.0 | 13.14 | 20.0 | Au1rxx-base64 | 37.19.198.160 |
| 80.53 | shadowsocks | 254.4 | 628.6 | 21.89 | 0.0 | 10.0 | 13.14 | 20.0 | Au1rxx-base64 | 38.180.135.156 |
| 80.25 | trojan | 354.7 | 878.5 | 19.57 | 0.0 | 10.0 | 14.75 | 19.6 | mheidari-all | 64.74.163.118 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | 0.927 | 633 | 1933 | prefer |
| zhangkai | 0.997 | 1.0 | 110 | 144 | prefer |
| Surfboard-tg-mixed | 0.863 | 0.81 | 21 | 6379 | prefer |
| mheidari-all | 0.606 | 0.526 | 717 | 21889 | observe |
| DeltaKronecker-all | 0.361 | 0.4 | 10 | 4245 | observe |
| ninja-vless | 0.327 | 1.0 | 1 | 1791 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 162 | observe |
| nscl5-all | 0.259 | 0.333 | 3 | 3321 | observe |
| Epodonios-all | 0.255 | None | 0 | 7089 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3987 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7131 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5190 | observe |
| barry-far-vless | 0.255 | None | 0 | 5511 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4091 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 5974 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 123 |
| geo | ClientOSError | - | 97 |
| speed | TimeoutError | - | 86 |
| 204 | ProxyError | - | 40 |
| speed | ClientOSError | - | 25 |
| cn-block | TimeoutError | - | 13 |
| 204 | TimeoutError | - | 7 |
| cn-block | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
