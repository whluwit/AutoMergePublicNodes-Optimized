# AutoNodes 每日报告

生成时间：2026-09-30 11:58:57

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 96627 |
| 去重后节点数 | 26883 |
| TCP 可达数 | 3000 |
| 真测通过数 | 389 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26883 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| generate | 86.2 |
| geo | 1.5 |
| probe | 287.5 |
| real_test | 167.7 |
| tcp | 44.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 55 | 41 | 14 | 74.5% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 157 | 141 | 16 | 89.8% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 17 | 12 | 5 | 70.6% |
| vless | 270 | 174 | 96 | 64.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 49 |
| 204:TimeoutError | 15 |
| geo:TimeoutError | 14 |
| cn-block:TimeoutError | 13 |
| 204:ProxyError | 12 |
| cn-block:ClientOSError | 11 |
| speed:TimeoutError | 7 |
| geo:ClientOSError | 5 |
| 204:ProxyConnectionError | 4 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6109 |
| ConnectionRefusedError | 997 |
| gaierror | 367 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.937 | prefer | 47 | 0.872 | 22755 |
| Au1rxx-base64 | 0.852 | prefer | 278 | 0.784 | 1752 |
| ermaozi | 0.746 | prefer | 54 | 0.741 | 335 |
| Surfboard-tg-mixed | 0.714 | prefer | 121 | 0.636 | 6952 |
| DeltaKronecker-all | 0.602 | observe | 17 | 0.588 | 5434 |
| tg-oneclickvpnkeys | 0.36 | observe | 3 | 1.0 | 53 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7458 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9375 |

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
| ninja-vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.588 | 10 | 7 | 17 |
| Surfboard-tg-mixed | 0.636 | 77 | 44 | 121 |
| ermaozi | 0.741 | 40 | 14 | 54 |
| Au1rxx-base64 | 0.784 | 218 | 60 | 278 |
| mheidari-all | 0.872 | 41 | 6 | 47 |
| tg-oneclickvpnkeys | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22755 | yes | 6.43 | 0 |
| SoliSpirit-all | 9375 | yes | 2.48 | 0 |
| Epodonios-all | 7458 | yes | 3.68 | 0 |
| Surfboard-tg-mixed | 6952 | yes | 4.51 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.07 | 0 |
| barry-far-vless | 5879 | yes | 1.15 | 0 |
| Surfboard-tg-vless | 5632 | yes | 6.63 | 0 |
| DeltaKronecker-all | 5434 | yes | 7.07 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 0.95 | 0 |
| mahdibland-V2RayAggregator | 4183 | yes | 3.19 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 56 |
| 204 | 32 |
| cn-block | 25 |
| geo | 20 |
