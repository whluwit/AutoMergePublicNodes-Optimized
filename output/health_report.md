# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-30 20:30:41 |
| 运行耗时 | 275.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 79396 |
| 去重后节点 | 21771 |
| TCP 可达 | 3000 |
| 真实可用 | 579 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 21771 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.5 |
| tcp | 34.5 |
| probe | 59.9 |
| real_test | 131.2 |
| generate | 42.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 49824 |
| vmess | 10739 |
| shadowsocks | 10275 |
| trojan | 6677 |
| hysteria2 | 1513 |
| http | 168 |
| shadowsocksr | 120 |
| socks | 66 |
| hysteria | 7 |
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
| 84.93 | vless | 242.2 | 655.5 | 22.17 | 0.0 | 10.0 | 12.76 | 20.0 | Au1rxx-base64 | ql6k-m23nix.logicara.top |
| 84.8 | vless | 247.7 | 634.1 | 22.04 | 0.0 | 10.0 | 12.76 | 20.0 | Au1rxx-base64 | 169.40.42.52 |
| 84.77 | vless | 249.1 | 656.0 | 22.01 | 0.0 | 10.0 | 12.76 | 20.0 | Au1rxx-base64 | 169.40.42.223 |
| 84.52 | vless | 259.9 | 683.6 | 21.76 | 0.0 | 10.0 | 12.76 | 20.0 | Au1rxx-base64 | 38.77.133.141 |
| 84.46 | vless | 262.7 | 686.6 | 21.7 | 0.0 | 10.0 | 12.76 | 20.0 | Au1rxx-base64 | 169.40.42.232 |
| 84.44 | vless | 263.6 | 667.5 | 21.68 | 0.0 | 10.0 | 12.76 | 20.0 | Au1rxx-base64 | 172.105.104.54 |
| 84.41 | vless | 264.7 | 627.3 | 21.65 | 0.0 | 10.0 | 12.76 | 20.0 | Au1rxx-base64 | 195.211.99.49 |
| 84.39 | vless | 265.8 | 694.9 | 21.63 | 0.0 | 10.0 | 12.76 | 20.0 | Au1rxx-base64 | 169.40.42.75 |
| 84.28 | vless | 270.5 | 709.8 | 21.52 | 0.0 | 10.0 | 12.76 | 20.0 | Au1rxx-base64 | 169.40.42.235 |
| 84.17 | hysteria2 | 227.0 | 627.5 | 22.52 | 0.0 | 10.0 | 12.75 | 20.0 | Au1rxx-base64 | 159.223.157.129 |
| 83.6 | vless | 286.1 | 627.1 | 21.16 | 0.0 | 10.0 | 12.76 | 20.0 | Au1rxx-base64 | 169.40.42.163 |
| 83.58 | vless | 267.8 | 700.4 | 21.58 | 0.0 | 10.0 | 12.76 | 20.0 | Au1rxx-base64 | 169.40.42.168 |
| 83.39 | vless | 262.4 | 634.8 | 21.7 | 0.0 | 10.0 | 12.76 | 20.0 | Au1rxx-base64 | 195.211.99.45 |
| 83.11 | vless | 320.7 | 816.4 | 20.35 | 0.0 | 10.0 | 12.76 | 20.0 | Au1rxx-base64 | 169.40.42.133 |
| 83.09 | vless | 322.0 | 885.1 | 20.33 | 0.0 | 10.0 | 12.76 | 20.0 | Au1rxx-base64 | 79.127.243.217 |
| 82.83 | vless | 333.0 | 827.0 | 20.07 | 0.0 | 10.0 | 12.76 | 20.0 | Au1rxx-base64 | 169.40.42.35 |
| 82.72 | vless | 337.5 | 859.6 | 19.96 | 0.0 | 10.0 | 12.76 | 20.0 | Au1rxx-base64 | 169.40.42.74 |
| 82.37 | vless | 252.5 | 658.4 | 21.93 | 0.0 | 10.0 | 12.76 | 20.0 | Au1rxx-base64 | 169.40.42.184 |
| 82.24 | vless | 355.3 | 841.7 | 19.55 | 0.0 | 10.0 | 12.76 | 20.0 | Au1rxx-base64 | 169.40.42.179 |
| 82.2 | vless | 358.9 | 849.5 | 19.47 | 0.0 | 10.0 | 12.76 | 20.0 | Au1rxx-base64 | 169.40.42.89 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.99 | 0.92 | 337 | 1804 | prefer |
| zhangkai | 0.929 | 0.958 | 24 | 144 | prefer |
| Surfboard-tg-mixed | 0.862 | 0.786 | 154 | 7004 | prefer |
| DeltaKronecker-all | 0.764 | 0.686 | 169 | 5576 | prefer |
| mheidari-all | 0.664 | 1.0 | 9 | 14482 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4762 | observe |
| Epodonios-all | 0.255 | None | 0 | 7411 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7545 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5872 | observe |
| barry-far-vless | 0.255 | None | 0 | 6057 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4041 | observe |
| Au1rxx-clash | 0.247 | None | 0 | 1804 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| cn-block | TimeoutError | - | 28 |
| 204 | TimeoutError | - | 26 |
| 204 | ProxyError | - | 15 |
| geo | ClientOSError | - | 12 |
| speed | ClientOSError | - | 9 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 5 |
| speed | TimeoutError | - | 5 |
| geo | TimeoutError | - | 3 |
| geo | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
