# AutoNodes 每日报告

生成时间：2026-09-11 10:41:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 84419 |
| 去重后节点数 | 23232 |
| TCP 可达数 | 3000 |
| 真测通过数 | 427 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23232 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| generate | 77.3 |
| geo | 1.6 |
| probe | 266.3 |
| real_test | 287.2 |
| tcp | 38.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 43 | 32 | 11 | 74.4% |
| hysteria2 | 10 | 10 | 0 | 100.0% |
| shadowsocks | 154 | 140 | 14 | 90.9% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 38 | 23 | 15 | 60.5% |
| vless | 314 | 218 | 96 | 69.4% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 31 |
| 204:TimeoutError | 20 |
| speed:TimeoutError | 20 |
| 204:ProxyError | 18 |
| geo:TimeoutError | 12 |
| speed:ClientOSError | 10 |
| cn-block:ClientOSError | 9 |
| cn-block:TimeoutError | 6 |
| 204:ClientOSError | 5 |
| 204:ProxyConnectionError | 4 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:36936: bind: address already in use | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4937 |
| ConnectionRefusedError | 893 |
| gaierror | 573 |
| OSError | 30 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.947 | prefer | 280 | 0.879 | 1772 |
| Surfboard-tg-mixed | 0.778 | prefer | 127 | 0.701 | 7422 |
| ermaozi | 0.728 | prefer | 43 | 0.721 | 431 |
| mheidari-all | 0.641 | observe | 64 | 0.562 | 15701 |
| DeltaKronecker-all | 0.549 | observe | 47 | 0.468 | 6070 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| ermaozi-get_subscribe | 0.273 | observe | 1 | 1.0 | 461 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 199 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4932 |
| Epodonios-all | 0.255 | observe | 0 | None | 7889 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.468 | 22 | 25 | 47 |
| mheidari-all | 0.562 | 36 | 28 | 64 |
| Surfboard-tg-mixed | 0.701 | 89 | 38 | 127 |
| ermaozi | 0.721 | 31 | 12 | 43 |
| Au1rxx-base64 | 0.879 | 246 | 34 | 280 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15701 | yes | 5.33 | 0 |
| SoliSpirit-all | 8749 | yes | 4.76 | 0 |
| Epodonios-all | 7889 | yes | 0.29 | 0 |
| Surfboard-tg-mixed | 7422 | yes | 4.65 | 0 |
| barry-far-vless | 6213 | yes | 2.81 | 0 |
| DeltaKronecker-all | 6070 | yes | 5.22 | 0 |
| Surfboard-tg-vless | 5995 | yes | 4.32 | 0 |
| 10ium-ScrapeCategorize-Vless | 4932 | yes | 3.11 | 0 |
| mahdibland-V2RayAggregator | 4223 | yes | 0.38 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.29 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 47 |
| geo | 44 |
| speed | 30 |
| cn-block | 15 |
| sing-box exited 1 | 1 |
