# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-09 20:29:26 |
| 运行耗时 | 626.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 83566 |
| 去重后节点 | 22095 |
| TCP 可达 | 3000 |
| 真实可用 | 440 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 22095 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| geo | 1.4 |
| tcp | 36.4 |
| probe | 275.0 |
| real_test | 220.6 |
| generate | 86.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50893 |
| vmess | 12154 |
| shadowsocks | 10140 |
| trojan | 7990 |
| hysteria2 | 1638 |
| http | 554 |
| shadowsocksr | 126 |
| socks | 53 |
| hysteria | 8 |
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
| 82.84 | vless | 245.6 | 621.5 | 22.09 | 0.0 | 10.0 | 11.07 | 19.68 | Au1rxx-base64 | 195.123.235.177 |
| 82.53 | vless | 259.2 | 709.2 | 21.78 | 0.0 | 10.0 | 11.07 | 19.68 | Au1rxx-base64 | 47.253.226.114 |
| 81.76 | vless | 263.2 | 649.7 | 21.69 | 0.0 | 10.0 | 11.07 | 19.68 | Au1rxx-base64 | 169.40.42.212 |
| 80.89 | vless | 290.9 | 691.1 | 21.04 | 0.0 | 10.0 | 11.07 | 19.68 | Au1rxx-base64 | 169.40.42.225 |
| 80.87 | vless | 330.7 | 820.1 | 20.12 | 0.0 | 10.0 | 11.07 | 19.68 | Au1rxx-base64 | 169.40.42.89 |
| 80.86 | shadowsocks | 261.4 | 643.2 | 21.73 | 0.0 | 10.0 | 13.95 | 19.68 | Au1rxx-base64 | 38.180.135.156 |
| 80.23 | shadowsocks | 288.5 | 797.9 | 21.1 | 0.0 | 10.0 | 13.95 | 19.68 | Au1rxx-base64 | 15.204.246.189 |
| 79.7 | vless | 257.9 | 645.4 | 21.81 | 0.0 | 10.0 | 11.07 | 19.68 | Au1rxx-base64 | 169.40.42.95 |
| 79.35 | vless | 396.6 | 1045.7 | 18.6 | 0.0 | 10.0 | 11.07 | 19.68 | Au1rxx-base64 | 169.40.42.202 |
| 79.25 | shadowsocks | 331.0 | 843.5 | 20.12 | 0.0 | 10.0 | 13.95 | 19.68 | Au1rxx-base64 | 51.79.64.198 |
| 79.11 | shadowsocks | 326.2 | 894.9 | 20.23 | 0.0 | 10.0 | 13.95 | 19.68 | Au1rxx-base64 | 15.204.246.132 |
| 78.98 | vless | 366.7 | 925.5 | 19.29 | 0.0 | 10.0 | 11.07 | 19.68 | Au1rxx-base64 | 169.40.42.15 |
| 78.83 | shadowsocks | 332.4 | 818.4 | 20.08 | 0.0 | 10.0 | 13.95 | 19.68 | Au1rxx-base64 | 51.79.85.185 |
| 78.81 | vless | 381.6 | 899.8 | 18.94 | 0.0 | 10.0 | 11.07 | 19.68 | Au1rxx-base64 | 169.40.42.229 |
| 78.79 | vless | 370.8 | 903.2 | 19.2 | 0.0 | 10.0 | 11.07 | 19.68 | Au1rxx-base64 | 169.40.42.179 |
| 78.78 | shadowsocks | 280.0 | 633.8 | 21.3 | 0.0 | 10.0 | 13.95 | 19.68 | Au1rxx-base64 | 156.146.38.168 |
| 78.55 | shadowsocks | 288.4 | 666.4 | 21.1 | 0.0 | 10.0 | 13.95 | 19.68 | Au1rxx-base64 | 156.146.38.169 |
| 78.41 | hysteria2 | 244.5 | 656.2 | 22.12 | 0.0 | 10.0 | 13.75 | 13.64 | mheidari-all | 159.223.157.129 |
| 78.41 | shadowsocks | 278.1 | 633.2 | 21.34 | 0.0 | 10.0 | 13.95 | 19.68 | Au1rxx-base64 | 156.146.38.170 |
| 78.27 | shadowsocks | 373.4 | 963.8 | 19.14 | 0.0 | 10.0 | 13.95 | 19.68 | Au1rxx-base64 | 51.222.141.125 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.976 | 0.918 | 305 | 1527 | prefer |
| mheidari-all | 0.92 | 0.87 | 23 | 16196 | prefer |
| ermaozi | 0.844 | 0.852 | 27 | 410 | prefer |
| Surfboard-tg-mixed | 0.782 | 0.705 | 139 | 7393 | prefer |
| DeltaKronecker-all | 0.642 | 0.567 | 30 | 5187 | observe |
| tg-oneclickvpnkeys | 0.317 | 1.0 | 2 | 147 | observe |
| Epodonios-all | 0.255 | None | 0 | 7839 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8955 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6033 | observe |
| barry-far-vless | 0.255 | None | 0 | 6253 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4247 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.236 | None | 0 | 1527 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | TimeoutError | - | 21 |
| cn-block | TimeoutError | - | 16 |
| 204 | ProxyError | - | 12 |
| cn-block | ClientOSError | - | 10 |
| speed | ClientOSError | - | 7 |
| geo | ClientOSError | - | 6 |
| geo | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 3 |
| speed | TimeoutError | - | 3 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
