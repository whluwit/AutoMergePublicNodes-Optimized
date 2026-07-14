# AutoNodes 每日报告

生成时间：2026-07-14 02:04:55

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 44/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 77026 |
| 去重后节点数 | 23604 |
| TCP 可达数 | 3000 |
| 真测通过数 | 381 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23604 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.7 |
| generate | 20.9 |
| geo | 1.3 |
| probe | 41.6 |
| real_test | 72.2 |
| tcp | 31.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 105 | 101 | 4 | 96.2% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 216 | 194 | 22 | 89.8% |
| vless | 149 | 42 | 107 | 28.2% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 55 |
| speed:ClientOSError | 32 |
| geo:ClientOSError | 24 |
| speed:TimeoutError | 11 |
| 204:ClientOSError | 4 |
| cn-block:TimeoutError | 3 |
| cn-block:ClientOSError | 3 |
| 204:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4133 |
| ConnectionRefusedError | 641 |
| gaierror | 322 |
| OSError | 196 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Surfboard-tg-mixed | 0.848 | prefer | 136 | 0.772 | 5561 |
| mheidari-all | 0.847 | prefer | 84 | 0.774 | 16309 |
| DeltaKronecker-all | 0.755 | prefer | 250 | 0.676 | 7926 |
| xiaoji235-airport-v2ray-all | 0.4 | observe | 4 | 0.75 | 3836 |
| nscl5-all | 0.325 | observe | 3 | 0.667 | 1412 |
| Au1rxx-base64 | 0.26 | observe | 1 | 1.0 | 119 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 3897 |
| Epodonios-all | 0.255 | observe | 0 | None | 6563 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3971 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-Ahmedhamoomi_Servers | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-BESTFORBEST66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigV2rayNG | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CryptoGuardVPN | 0.025 | observe | 0 | None | 1 | 0 |
| tg-DarkVPNpro | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.667 | 2 | 1 | 3 |
| DeltaKronecker-all | 0.676 | 169 | 81 | 250 |
| xiaoji235-airport-v2ray-all | 0.75 | 3 | 1 | 4 |
| Surfboard-tg-mixed | 0.772 | 105 | 31 | 136 |
| mheidari-all | 0.774 | 65 | 19 | 84 |
| Au1rxx-base64 | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16309 | yes | 3.66 | 0 |
| DeltaKronecker-all | 7926 | yes | 3.82 | 0 |
| Epodonios-all | 6563 | yes | 1.67 | 0 |
| SoliSpirit-all | 6476 | yes | 1.74 | 0 |
| Surfboard-tg-mixed | 5561 | yes | 2.04 | 0 |
| mahdibland-V2RayAggregator | 5454 | yes | 0.25 | 0 |
| barry-far-vless | 4885 | yes | 0.99 | 0 |
| Surfboard-tg-vless | 4279 | yes | 2.63 | 0 |
| MatinGhanbari-all-sub | 3971 | yes | 1.49 | 0 |
| 10ium-ScrapeCategorize-Vless | 3897 | yes | 1.19 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 79 |
| speed | 43 |
| 204 | 6 |
| cn-block | 6 |
