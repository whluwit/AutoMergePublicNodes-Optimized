# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-08-29 05:24:44 |
| 运行耗时 | 280.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 96 |
| 原始节点 | 76982 |
| 去重后节点 | 20854 |
| TCP 可达 | 3000 |
| 真实可用 | 706 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 20854 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.5 |
| tcp | 35.2 |
| probe | 57.8 |
| real_test | 143.1 |
| generate | 36.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 47615 |
| vmess | 10687 |
| shadowsocks | 10510 |
| trojan | 6258 |
| hysteria2 | 1544 |
| http | 174 |
| shadowsocksr | 128 |
| socks | 56 |
| hysteria | 7 |
| tuic | 3 |

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
| 83.98 | vless | 208.8 | 514.3 | 22.94 | 0.0 | 10.0 | 11.82 | 19.22 | Au1rxx-base64 | 166.88.186.151 |
| 83.3 | vless | 195.1 | 492.7 | 23.26 | 0.0 | 10.0 | 11.82 | 19.22 | Au1rxx-base64 | 192.220.9.89 |
| 81.51 | vless | 213.7 | 519.8 | 22.83 | 0.0 | 10.0 | 11.82 | 19.22 | Au1rxx-base64 | 64.23.229.123 |
| 81.0 | shadowsocks | 218.4 | 506.2 | 22.72 | 0.0 | 10.0 | 13.06 | 19.22 | Au1rxx-base64 | 173.244.56.6 |
| 79.74 | vless | 286.2 | 639.9 | 21.15 | 0.0 | 10.0 | 11.82 | 19.22 | Au1rxx-base64 | 216.227.161.95 |
| 79.65 | shadowsocks | 242.1 | 586.9 | 22.17 | 0.0 | 10.0 | 13.06 | 19.22 | Au1rxx-base64 | 156.146.38.169 |
| 79.42 | hysteria2 | 313.6 | 698.4 | 20.52 | 0.0 | 10.0 | 13.33 | 19.22 | Au1rxx-base64 | 159.223.157.129 |
| 79.4 | vless | 190.7 | 481.9 | 23.36 | 0.0 | 10.0 | 11.82 | 19.22 | Au1rxx-base64 | 172.239.67.156 |
| 79.36 | vless | 192.5 | 501.4 | 23.32 | 0.0 | 10.0 | 11.82 | 19.22 | Au1rxx-base64 | 172.233.139.46 |
| 79.36 | vless | 192.5 | 500.9 | 23.32 | 0.0 | 10.0 | 11.82 | 19.22 | Au1rxx-base64 | 172.239.67.231 |
| 79.31 | vless | 194.6 | 500.9 | 23.27 | 0.0 | 10.0 | 11.82 | 19.22 | Au1rxx-base64 | 172.235.38.85 |
| 79.28 | vless | 196.2 | 510.7 | 23.24 | 0.0 | 10.0 | 11.82 | 19.22 | Au1rxx-base64 | 172.233.156.118 |
| 79.27 | trojan | 195.9 | 517.9 | 23.24 | 0.0 | 10.0 | 11.13 | 19.22 | Au1rxx-base64 | 14.1.28.76 |
| 79.27 | vless | 196.6 | 517.2 | 23.23 | 0.0 | 10.0 | 11.82 | 19.22 | Au1rxx-base64 | 172.235.43.210 |
| 79.11 | vless | 203.5 | 505.7 | 23.07 | 0.0 | 10.0 | 11.82 | 19.22 | Au1rxx-base64 | 172.236.252.35 |
| 78.92 | vless | 204.5 | 565.2 | 23.04 | 0.0 | 9.84 | 11.82 | 19.22 | Au1rxx-base64 | us5-r.link-t7.com |
| 78.9 | vless | 212.5 | 511.0 | 22.86 | 0.0 | 10.0 | 11.82 | 19.22 | Au1rxx-base64 | 45.33.107.60 |
| 78.88 | vless | 213.2 | 498.3 | 22.84 | 0.0 | 10.0 | 11.82 | 19.22 | Au1rxx-base64 | 173.230.155.55 |
| 78.81 | vless | 216.4 | 509.2 | 22.77 | 0.0 | 10.0 | 11.82 | 19.22 | Au1rxx-base64 | 192.155.87.188 |
| 78.74 | vless | 362.0 | 885.8 | 19.4 | 0.0 | 10.0 | 11.82 | 19.22 | Au1rxx-base64 | 15.204.97.216 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.967 | 1.0 | 24 | 144 | prefer |
| Au1rxx-base64 | 0.94 | 0.868 | 395 | 1828 | prefer |
| Surfboard-tg-mixed | 0.881 | 0.804 | 199 | 6733 | prefer |
| DeltaKronecker-all | 0.825 | 0.748 | 135 | 4065 | prefer |
| mheidari-all | 0.81 | 0.735 | 98 | 14598 | prefer |
| tg-oneclickvpnkeys | 0.405 | 1.0 | 4 | 127 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| roosterkid-openproxylist-v2ray | 0.261 | 1.0 | 1 | 150 | observe |
| Epodonios-all | 0.255 | None | 0 | 7084 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 7191 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5530 | observe |
| barry-far-vless | 0.255 | None | 0 | 5694 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4093 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1828 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| speed | TimeoutError | - | 33 |
| cn-block | TimeoutError | - | 31 |
| 204 | TimeoutError | - | 23 |
| geo | ClientOSError | - | 20 |
| geo | TimeoutError | - | 15 |
| cn-block | ClientOSError | - | 12 |
| 204 | ProxyError | - | 7 |
| speed | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 4 |
| 204 | ClientOSError | - | 3 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 300 | - |
| global | False | 300 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
