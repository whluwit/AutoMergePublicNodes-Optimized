# AutoNodes 每日报告

生成时间：2026-09-11 15:55:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 83937 |
| 去重后节点数 | 23204 |
| TCP 可达数 | 3000 |
| 真测通过数 | 418 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23204 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| generate | 82.3 |
| geo | 1.3 |
| probe | 260.4 |
| real_test | 253.2 |
| tcp | 40.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 35 | 24 | 11 | 68.6% |
| hysteria2 | 23 | 23 | 0 | 100.0% |
| shadowsocks | 159 | 146 | 13 | 91.8% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 13 | 11 | 2 | 84.6% |
| vless | 342 | 212 | 130 | 62.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 58 |
| 204:ProxyError | 23 |
| cn-block:TimeoutError | 19 |
| 204:TimeoutError | 17 |
| speed:ClientOSError | 10 |
| speed:TimeoutError | 10 |
| geo:TimeoutError | 8 |
| cn-block:ClientOSError | 7 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:46534: bind: address already in use | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5582 |
| ConnectionRefusedError | 899 |
| gaierror | 411 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.903 | prefer | 254 | 0.835 | 1763 |
| mheidari-all | 0.787 | prefer | 73 | 0.712 | 15708 |
| Surfboard-tg-mixed | 0.768 | prefer | 136 | 0.691 | 7370 |
| ermaozi | 0.757 | prefer | 29 | 0.759 | 377 |
| DeltaKronecker-all | 0.548 | observe | 75 | 0.467 | 6070 |
| tg-oneclickvpnkeys | 0.32 | observe | 2 | 1.0 | 228 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4932 |
| Epodonios-all | 0.255 | observe | 0 | None | 7833 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8539 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | ermaozi-get_subscribe | 0.162 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.2 | 1 | 4 | 5 |
| DeltaKronecker-all | 0.467 | 35 | 40 | 75 |
| Surfboard-tg-mixed | 0.691 | 94 | 42 | 136 |
| mheidari-all | 0.712 | 52 | 21 | 73 |
| ermaozi | 0.759 | 22 | 7 | 29 |
| Au1rxx-base64 | 0.835 | 212 | 42 | 254 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15708 | yes | 3.91 | 0 |
| SoliSpirit-all | 8539 | yes | 2.9 | 0 |
| Epodonios-all | 7833 | yes | 2.48 | 0 |
| Surfboard-tg-mixed | 7370 | yes | 3.33 | 0 |
| barry-far-vless | 6192 | yes | 2.01 | 0 |
| DeltaKronecker-all | 6070 | yes | 4.1 | 0 |
| Surfboard-tg-vless | 5979 | yes | 3.1 | 0 |
| 10ium-ScrapeCategorize-Vless | 4932 | yes | 2.11 | 0 |
| mahdibland-V2RayAggregator | 4223 | yes | 0.62 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.33 | 0 |

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
| geo | 68 |
| 204 | 41 |
| cn-block | 28 |
| speed | 20 |
| sing-box exited 1 | 1 |
