# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-02 10:33:04 |
| 运行耗时 | 285.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 95 |
| 原始节点 | 82426 |
| 去重后节点 | 23484 |
| TCP 可达 | 3000 |
| 真实可用 | 626 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23484 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.9 |
| geo | 1.4 |
| tcp | 38.0 |
| probe | 68.4 |
| real_test | 135.5 |
| generate | 38.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 51619 |
| vmess | 11175 |
| shadowsocks | 9890 |
| trojan | 7812 |
| hysteria2 | 1562 |
| http | 144 |
| shadowsocksr | 126 |
| socks | 80 |
| tuic | 11 |
| hysteria | 7 |

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
| 82.19 | shadowsocks | 245.7 | 607.5 | 22.09 | 0.0 | 10.0 | 14.42 | 19.68 | Au1rxx-base64 | 156.146.38.168 |
| 82.13 | shadowsocks | 248.1 | 626.4 | 22.03 | 0.0 | 10.0 | 14.42 | 19.68 | Au1rxx-base64 | 156.146.38.170 |
| 82.13 | shadowsocks | 248.2 | 618.8 | 22.03 | 0.0 | 10.0 | 14.42 | 19.68 | Au1rxx-base64 | 156.146.38.169 |
| 82.04 | shadowsocks | 252.4 | 627.8 | 21.94 | 0.0 | 10.0 | 14.42 | 19.68 | Au1rxx-base64 | 156.146.38.167 |
| 80.59 | shadowsocks | 280.8 | 666.6 | 21.28 | 0.0 | 10.0 | 14.42 | 19.68 | Au1rxx-base64 | 37.19.198.236 |
| 78.57 | vless | 275.5 | 654.9 | 21.4 | 0.0 | 10.0 | 7.49 | 19.68 | Au1rxx-base64 | 195.211.99.45 |
| 78.29 | vless | 287.7 | 636.5 | 21.12 | 0.0 | 10.0 | 7.49 | 19.68 | Au1rxx-base64 | 195.211.99.49 |
| 77.72 | vless | 312.4 | 749.5 | 20.55 | 0.0 | 10.0 | 7.49 | 19.68 | Au1rxx-base64 | 38.180.242.205 |
| 76.84 | http | 292.8 | 604.2 | 21.0 | 0.0 | 10.0 | 14.4 | 18.58 | zhangkai | 138.199.35.198 |
| 76.55 | http | 291.3 | 589.6 | 21.03 | 0.0 | 10.0 | 14.4 | 18.58 | zhangkai | 138.199.35.216 |
| 76.26 | hysteria2 | 411.3 | 1009.1 | 18.26 | 0.0 | 10.0 | 13.42 | 19.68 | Au1rxx-base64 | 66.94.121.46 |
| 76.13 | shadowsocks | 353.1 | 716.7 | 19.61 | 0.0 | 10.0 | 14.42 | 19.68 | Au1rxx-base64 | 173.244.56.9 |
| 76.02 | shadowsocks | 343.3 | 720.6 | 19.83 | 0.0 | 10.0 | 14.42 | 19.68 | Au1rxx-base64 | 173.244.56.6 |
| 75.87 | shadowsocks | 292.0 | 691.6 | 21.02 | 0.0 | 10.0 | 14.42 | 19.68 | Au1rxx-base64 | 37.19.198.243 |
| 75.79 | shadowsocks | 285.1 | 534.0 | 21.18 | 0.0 | 10.0 | 14.42 | 19.68 | Au1rxx-base64 | 108.181.118.10 |
| 75.49 | shadowsocks | 361.4 | 840.8 | 19.41 | 0.0 | 10.0 | 14.42 | 19.68 | Au1rxx-base64 | 38.180.135.156 |
| 75.48 | shadowsocks | 295.1 | 525.7 | 20.95 | 0.0 | 10.0 | 14.42 | 19.68 | Au1rxx-base64 | 108.181.0.177 |
| 75.3 | vless | 347.7 | 654.9 | 19.73 | 0.0 | 10.0 | 7.49 | 19.68 | Au1rxx-base64 | 169.40.42.179 |
| 75.13 | shadowsocks | 295.2 | 606.3 | 20.95 | 0.0 | 10.0 | 14.42 | 19.68 | Au1rxx-base64 | 149.22.95.183 |
| 75.06 | vless | 280.5 | 641.9 | 21.29 | 0.0 | 10.0 | 7.49 | 19.68 | Au1rxx-base64 | 172.105.104.54 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.967 | 0.896 | 405 | 1826 | prefer |
| zhangkai | 0.966 | 1.0 | 23 | 144 | prefer |
| Surfboard-tg-mixed | 0.865 | 0.789 | 161 | 6989 | prefer |
| mheidari-all | 0.744 | 0.667 | 141 | 15813 | prefer |
| DeltaKronecker-all | 0.609 | 0.531 | 32 | 7295 | observe |
| tg-oneclickvpnkeys | 0.259 | 1.0 | 1 | 102 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 47 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4765 | observe |
| Epodonios-all | 0.255 | None | 0 | 7428 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7727 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5862 | observe |
| barry-far-vless | 0.255 | None | 0 | 6070 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4066 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1826 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 24 |
| cn-block | TimeoutError | - | 23 |
| speed | TimeoutError | - | 20 |
| geo | ClientOSError | - | 19 |
| 204 | TimeoutError | - | 17 |
| speed | ClientOSError | - | 12 |
| cn-block | ClientOSError | - | 9 |
| 204 | ProxyError | - | 7 |
| 204 | ClientOSError | - | 5 |
| speed | ProxyError | - | 3 |
| cn-block | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
