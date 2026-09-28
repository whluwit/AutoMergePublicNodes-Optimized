# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-09-28 23:01:44 |
| 运行耗时 | 526.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 94 |
| 原始节点 | 97528 |
| 去重后节点 | 27014 |
| TCP 可达 | 3000 |
| 真实可用 | 432 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 27014 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| geo | 1.5 |
| tcp | 44.1 |
| probe | 242.9 |
| real_test | 155.5 |
| generate | 74.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59907 |
| vmess | 14923 |
| shadowsocks | 11428 |
| trojan | 8882 |
| hysteria2 | 1459 |
| http | 635 |
| shadowsocksr | 170 |
| socks | 77 |
| anytls | 24 |
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
| 82.62 | vless | 235.8 | 670.1 | 22.32 | 0.0 | 10.0 | 11.82 | 18.48 | Au1rxx-base64 | 79.141.172.154 |
| 82.55 | vless | 238.6 | 605.1 | 22.25 | 0.0 | 10.0 | 11.82 | 18.48 | Au1rxx-base64 | 195.123.235.177 |
| 82.46 | vless | 242.5 | 683.4 | 22.16 | 0.0 | 10.0 | 11.82 | 18.48 | Au1rxx-base64 | 47.90.153.88 |
| 82.12 | vless | 257.2 | 674.4 | 21.82 | 0.0 | 10.0 | 11.82 | 18.48 | Au1rxx-base64 | 169.40.42.224 |
| 81.94 | vless | 265.1 | 631.7 | 21.64 | 0.0 | 10.0 | 11.82 | 18.48 | Au1rxx-base64 | 195.211.98.43 |
| 81.29 | vless | 293.1 | 743.2 | 20.99 | 0.0 | 10.0 | 11.82 | 18.48 | Au1rxx-base64 | 66.70.179.198 |
| 81.0 | vless | 305.9 | 768.5 | 20.7 | 0.0 | 10.0 | 11.82 | 18.48 | Au1rxx-base64 | 169.40.42.168 |
| 80.93 | vless | 308.9 | 854.6 | 20.63 | 0.0 | 10.0 | 11.82 | 18.48 | Au1rxx-base64 | 159.89.87.21 |
| 80.79 | vless | 314.6 | 867.2 | 20.49 | 0.0 | 10.0 | 11.82 | 18.48 | Au1rxx-base64 | 137.184.218.169 |
| 80.06 | vless | 346.3 | 940.1 | 19.76 | 0.0 | 10.0 | 11.82 | 18.48 | Au1rxx-base64 | 169.40.42.15 |
| 79.97 | vless | 350.2 | 905.6 | 19.67 | 0.0 | 10.0 | 11.82 | 18.48 | Au1rxx-base64 | 169.40.42.16 |
| 79.95 | vless | 351.1 | 946.6 | 19.65 | 0.0 | 10.0 | 11.82 | 18.48 | Au1rxx-base64 | 169.40.42.35 |
| 79.89 | vless | 353.7 | 834.1 | 19.59 | 0.0 | 10.0 | 11.82 | 18.48 | Au1rxx-base64 | 169.40.42.52 |
| 79.83 | vless | 356.3 | 917.8 | 19.53 | 0.0 | 10.0 | 11.82 | 18.48 | Au1rxx-base64 | 169.40.42.202 |
| 79.75 | vless | 359.8 | 859.8 | 19.45 | 0.0 | 10.0 | 11.82 | 18.48 | Au1rxx-base64 | 169.40.42.223 |
| 79.72 | vless | 361.2 | 938.7 | 19.42 | 0.0 | 10.0 | 11.82 | 18.48 | Au1rxx-base64 | 169.40.42.104 |
| 79.68 | vless | 362.8 | 930.7 | 19.38 | 0.0 | 10.0 | 11.82 | 18.48 | Au1rxx-base64 | 169.40.42.95 |
| 79.44 | vless | 373.3 | 953.6 | 19.14 | 0.0 | 10.0 | 11.82 | 18.48 | Au1rxx-base64 | 169.40.42.232 |
| 79.32 | vless | 378.4 | 1032.7 | 19.02 | 0.0 | 10.0 | 11.82 | 18.48 | Au1rxx-base64 | 185.95.231.233 |
| 79.14 | vless | 305.3 | 769.0 | 20.71 | 0.0 | 10.0 | 11.82 | 18.48 | Au1rxx-base64 | 169.40.42.235 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.922 | 0.858 | 351 | 1674 | prefer |
| mheidari-all | 0.901 | 0.826 | 115 | 22856 | prefer |
| Surfboard-tg-mixed | 0.734 | 0.857 | 14 | 7142 | prefer |
| ermaozi | 0.514 | 0.5 | 30 | 344 | observe |
| DeltaKronecker-all | 0.465 | 0.714 | 7 | 5428 | observe |
| tg-oneclickvpnkeys | 0.316 | 1.0 | 2 | 121 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5326 | observe |
| Epodonios-all | 0.255 | None | 0 | 7535 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9706 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5799 | observe |
| barry-far-vless | 0.255 | None | 0 | 6027 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4237 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | ClientOSError | - | 32 |
| 204 | ProxyError | - | 17 |
| cn-block | TimeoutError | - | 14 |
| 204 | TimeoutError | - | 9 |
| speed | TimeoutError | - | 5 |
| 204 | ProxyConnectionError | - | 4 |
| cn-block | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| geo | TimeoutError | - | 3 |
| geo | ClientOSError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
