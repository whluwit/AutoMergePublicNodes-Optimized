# AutoNodes 每日报告

生成时间：2026-07-26 19:08:53

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 84027 |
| 去重后节点数 | 22059 |
| TCP 可达数 | 3000 |
| 真测通过数 | 688 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22059 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| generate | 43.9 |
| geo | 1.3 |
| probe | 64.6 |
| real_test | 166.9 |
| tcp | 31.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 6 | 6 | 0 | 100.0% |
| http | 76 | 76 | 0 | 100.0% |
| hysteria2 | 11 | 11 | 0 | 100.0% |
| shadowsocks | 116 | 89 | 27 | 76.7% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 400 | 367 | 33 | 91.8% |
| vless | 397 | 138 | 259 | 34.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 114 |
| speed:ClientOSError | 81 |
| cn-block:TimeoutError | 36 |
| 204:TimeoutError | 24 |
| geo:ClientOSError | 21 |
| speed:TimeoutError | 16 |
| cn-block:ClientOSError | 10 |
| 204:ProxyError | 7 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 4 |
| geo:ProxyError | 4 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4368 |
| ConnectionRefusedError | 710 |
| gaierror | 276 |
| OSError | 219 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.991 | prefer | 76 | 1.0 | 86 |
| Au1rxx-base64 | 0.964 | prefer | 446 | 0.906 | 1507 |
| mheidari-all | 0.519 | observe | 278 | 0.439 | 19379 |
| Surfboard-tg-mixed | 0.496 | observe | 164 | 0.415 | 5487 |
| tg-oneclickvpnkeys | 0.483 | observe | 6 | 1.0 | 164 |
| DeltaKronecker-all | 0.404 | observe | 35 | 0.314 | 4320 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 3959 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4912 |
| Epodonios-all | 0.255 | observe | 0 | None | 6631 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3967 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigV2rayNG | 0.135 | observe | 1 | 0.0 | 0 | 200 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 9 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| tg-ConfigV2rayNG | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.314 | 11 | 24 | 35 |
| Surfboard-tg-mixed | 0.415 | 68 | 96 | 164 |
| mheidari-all | 0.439 | 122 | 156 | 278 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| Au1rxx-base64 | 0.906 | 404 | 42 | 446 |
| tg-oneclickvpnkeys | 1.0 | 6 | 0 | 6 |
| zhangkai | 1.0 | 76 | 0 | 76 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19379 | yes | 4.29 | 0 |
| Epodonios-all | 6631 | yes | 2.6 | 0 |
| SoliSpirit-all | 6559 | yes | 2.81 | 0 |
| Surfboard-tg-mixed | 5487 | yes | 2.2 | 0 |
| mahdibland-V2RayAggregator | 5003 | yes | 1.99 | 0 |
| 10ium-ScrapeCategorize-Vless | 4912 | yes | 2.48 | 0 |
| barry-far-vless | 4894 | yes | 2.04 | 0 |
| DeltaKronecker-all | 4320 | yes | 4.24 | 0 |
| Surfboard-tg-vless | 4235 | yes | 2.32 | 0 |
| MatinGhanbari-all-sub | 3967 | yes | 2.59 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 139 |
| speed | 97 |
| cn-block | 50 |
| 204 | 36 |
