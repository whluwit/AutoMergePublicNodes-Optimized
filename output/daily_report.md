# AutoNodes 每日报告

生成时间：2026-10-05 13:33:58

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 98585 |
| 去重后节点数 | 27254 |
| TCP 可达数 | 3000 |
| 真测通过数 | 439 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27254 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| generate | 72.3 |
| geo | 1.5 |
| probe | 238.3 |
| real_test | 159.6 |
| tcp | 46.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 2 | 2 | 50.0% |
| http | 70 | 40 | 30 | 57.1% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 166 | 150 | 16 | 90.4% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 95 | 84 | 11 | 88.4% |
| vless | 176 | 145 | 31 | 82.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 30 |
| 204:TimeoutError | 18 |
| cn-block:TimeoutError | 14 |
| geo:ClientOSError | 7 |
| speed:ClientOSError | 7 |
| speed:TimeoutError | 5 |
| cn-block:ClientOSError | 4 |
| geo:TimeoutError | 4 |
| 204:ClientOSError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6387 |
| ConnectionRefusedError | 1030 |
| gaierror | 379 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.969 | prefer | 297 | 0.899 | 1816 |
| mheidari-all | 0.942 | prefer | 56 | 0.875 | 23423 |
| Surfboard-tg-mixed | 0.885 | prefer | 80 | 0.812 | 7151 |
| DeltaKronecker-all | 0.771 | prefer | 19 | 0.737 | 5300 |
| ermaozi | 0.594 | observe | 74 | 0.568 | 701 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5111 |
| Epodonios-all | 0.255 | observe | 0 | None | 7645 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9196 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.333 | 1 | 2 | 3 |
| ermaozi | 0.568 | 42 | 32 | 74 |
| DeltaKronecker-all | 0.737 | 14 | 5 | 19 |
| Surfboard-tg-mixed | 0.812 | 65 | 15 | 80 |
| mheidari-all | 0.875 | 49 | 7 | 56 |
| Au1rxx-base64 | 0.899 | 267 | 30 | 297 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23423 | yes | 5.42 | 0 |
| SoliSpirit-all | 9196 | yes | 2.06 | 0 |
| Epodonios-all | 7645 | yes | 6.54 | 0 |
| Surfboard-tg-mixed | 7151 | yes | 3.71 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.76 | 0 |
| barry-far-vless | 5930 | yes | 1.11 | 0 |
| Surfboard-tg-vless | 5695 | yes | 3.22 | 0 |
| DeltaKronecker-all | 5300 | yes | 4.6 | 0 |
| 10ium-ScrapeCategorize-Vless | 5111 | yes | 0.72 | 0 |
| mahdibland-V2RayAggregator | 4375 | yes | 2.85 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 50 |
| cn-block | 18 |
| speed | 13 |
| geo | 11 |
