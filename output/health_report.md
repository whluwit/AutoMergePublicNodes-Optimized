# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-12 03:07:14 |
| 运行耗时 | 1061.8s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 83355 |
| 去重后节点 | 23379 |
| TCP 可达 | 3000 |
| 真实可用 | 593 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 23379 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.4 |
| tcp | 40.2 |
| probe | 389.0 |
| real_test | 544.1 |
| generate | 80.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 50293 |
| vmess | 12588 |
| shadowsocks | 9823 |
| trojan | 8088 |
| hysteria2 | 1689 |
| http | 664 |
| shadowsocksr | 131 |
| socks | 54 |
| tuic | 12 |
| hysteria | 11 |
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
| 80.9 | vless | 226.6 | 592.7 | 22.53 | 0.0 | 10.0 | 10.33 | 18.04 | Au1rxx-base64 | 195.123.235.177 |
| 80.41 | vless | 248.1 | 679.2 | 22.04 | 0.0 | 10.0 | 10.33 | 18.04 | Au1rxx-base64 | 79.141.172.154 |
| 79.57 | vless | 284.1 | 640.1 | 21.2 | 0.0 | 10.0 | 10.33 | 18.04 | Au1rxx-base64 | 169.40.42.89 |
| 79.55 | vless | 285.2 | 647.2 | 21.18 | 0.0 | 10.0 | 10.33 | 18.04 | Au1rxx-base64 | 169.40.42.184 |
| 79.36 | vless | 273.3 | 669.0 | 21.45 | 0.0 | 10.0 | 10.33 | 18.04 | Au1rxx-base64 | 216.152.147.28 |
| 79.32 | vless | 294.9 | 669.8 | 20.95 | 0.0 | 10.0 | 10.33 | 18.04 | Au1rxx-base64 | 169.40.42.173 |
| 79.29 | vless | 296.3 | 738.7 | 20.92 | 0.0 | 10.0 | 10.33 | 18.04 | Au1rxx-base64 | 169.40.42.223 |
| 79.09 | vless | 305.0 | 706.4 | 20.72 | 0.0 | 10.0 | 10.33 | 18.04 | Au1rxx-base64 | 169.40.42.104 |
| 78.53 | vless | 329.0 | 885.3 | 20.16 | 0.0 | 10.0 | 10.33 | 18.04 | Au1rxx-base64 | 169.40.42.15 |
| 78.52 | hysteria2 | 297.8 | 827.6 | 20.88 | 0.0 | 10.0 | 12.78 | 15.96 | mheidari-all | 159.223.157.129 |
| 78.49 | vless | 330.9 | 813.9 | 20.12 | 0.0 | 10.0 | 10.33 | 18.04 | Au1rxx-base64 | 130.107.73.148 |
| 78.45 | vless | 332.7 | 848.8 | 20.08 | 0.0 | 10.0 | 10.33 | 18.04 | Au1rxx-base64 | 169.40.42.75 |
| 78.38 | vless | 335.7 | 858.6 | 20.01 | 0.0 | 10.0 | 10.33 | 18.04 | Au1rxx-base64 | 169.40.42.235 |
| 78.28 | vless | 339.8 | 915.3 | 19.91 | 0.0 | 10.0 | 10.33 | 18.04 | Au1rxx-base64 | 169.40.42.212 |
| 78.22 | vless | 342.6 | 932.2 | 19.85 | 0.0 | 10.0 | 10.33 | 18.04 | Au1rxx-base64 | 169.40.42.52 |
| 78.2 | vless | 277.8 | 732.5 | 21.35 | 0.0 | 10.0 | 10.33 | 18.04 | Au1rxx-base64 | 169.40.42.35 |
| 78.18 | vless | 271.7 | 712.7 | 21.49 | 0.0 | 10.0 | 10.33 | 18.04 | Au1rxx-base64 | 169.40.42.133 |
| 78.08 | shadowsocks | 277.0 | 792.6 | 21.37 | 0.0 | 10.0 | 13.17 | 18.04 | Au1rxx-base64 | 15.204.247.206 |
| 77.93 | vless | 355.0 | 975.6 | 19.56 | 0.0 | 10.0 | 10.33 | 18.04 | Au1rxx-base64 | 169.40.42.16 |
| 77.87 | vless | 357.6 | 979.1 | 19.5 | 0.0 | 10.0 | 10.33 | 18.04 | Au1rxx-base64 | 169.40.42.182 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.933 | 0.868 | 326 | 1681 | prefer |
| Surfboard-tg-mixed | 0.833 | 0.759 | 79 | 7263 | prefer |
| ermaozi | 0.732 | 0.731 | 26 | 434 | prefer |
| mheidari-all | 0.585 | 0.505 | 105 | 15597 | observe |
| DeltaKronecker-all | 0.396 | 0.315 | 549 | 6070 | observe |
| tg-oneclickvpnkeys | 0.263 | 1.0 | 1 | 194 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| 10ium-ScrapeCategorize-Vless | 0.259 | 0.333 | 3 | 4932 | observe |
| Epodonios-all | 0.255 | None | 0 | 7719 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 8501 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5889 | observe |
| barry-far-vless | 0.255 | None | 0 | 6106 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4223 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | TimeoutError | - | 239 |
| geo | ClientOSError | - | 92 |
| speed | ClientOSError | - | 51 |
| speed | TimeoutError | - | 47 |
| 204 | ProxyError | - | 23 |
| cn-block | TimeoutError | - | 17 |
| 204 | TimeoutError | - | 12 |
| 204 | ProxyConnectionError | - | 8 |
| cn-block | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 6 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
