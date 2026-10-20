# AutoNodes 每日报告

生成时间：2026-10-20 21:19:33

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 94585 |
| 去重后节点数 | 26418 |
| TCP 可达数 | 3000 |
| 真测通过数 | 370 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26418 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| generate | 78.1 |
| geo | 1.5 |
| probe | 223.7 |
| real_test | 219.8 |
| tcp | 44.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 25 | 14 | 11 | 56.0% |
| hysteria2 | 10 | 10 | 0 | 100.0% |
| shadowsocks | 152 | 136 | 16 | 89.5% |
| socks | 6 | 2 | 4 | 33.3% |
| trojan | 43 | 37 | 6 | 86.0% |
| vless | 224 | 170 | 54 | 75.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 24 |
| 204:TimeoutError | 13 |
| 204:ProxyError | 12 |
| speed:ClientOSError | 12 |
| speed:TimeoutError | 10 |
| 204:ProxyConnectionError | 6 |
| cn-block:ClientOSError | 6 |
| geo:ClientOSError | 4 |
| geo:TimeoutError | 2 |
| geo:ProxyError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6667 |
| ConnectionRefusedError | 1024 |
| OSError | 234 |
| gaierror | 211 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.908 | prefer | 97 | 0.835 | 23621 |
| Au1rxx-base64 | 0.878 | prefer | 260 | 0.823 | 1438 |
| Surfboard-tg-mixed | 0.864 | prefer | 72 | 0.792 | 6945 |
| zhangkai | 0.561 | observe | 23 | 0.565 | 31 |
| DeltaKronecker-all | 0.373 | observe | 5 | 0.6 | 3519 |
| SoliSpirit-all | 0.335 | observe | 1 | 1.0 | 9871 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 74 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4967 |
| Epodonios-all | 0.255 | observe | 0 | None | 7425 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 1 | 1 |
| zhangkai | 0.565 | 13 | 10 | 23 |
| DeltaKronecker-all | 0.6 | 3 | 2 | 5 |
| Surfboard-tg-mixed | 0.792 | 57 | 15 | 72 |
| Au1rxx-base64 | 0.823 | 214 | 46 | 260 |
| mheidari-all | 0.835 | 81 | 16 | 97 |
| SoliSpirit-all | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23621 | yes | 4.18 | 0 |
| SoliSpirit-all | 9871 | yes | 2.68 | 0 |
| Epodonios-all | 7425 | yes | 4.5 | 0 |
| Surfboard-tg-mixed | 6945 | yes | 2.5 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.58 | 0 |
| barry-far-vless | 5701 | yes | 0.64 | 0 |
| Surfboard-tg-vless | 5487 | yes | 3.03 | 0 |
| 10ium-ScrapeCategorize-Vless | 4967 | yes | 0.83 | 0 |
| mahdibland-V2RayAggregator | 4127 | yes | 2.09 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.03 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 32 |
| cn-block | 30 |
| speed | 22 |
| geo | 7 |
