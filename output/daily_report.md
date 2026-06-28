# AutoNodes 每日报告

生成时间：2026-06-28 19:16:53

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 105/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 76407 |
| 去重后节点数 | 22880 |
| TCP 可达数 | 3000 |
| 真测通过数 | 470 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22880 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| generate | 30.3 |
| geo | 1.4 |
| probe | 58.3 |
| real_test | 137.5 |
| tcp | 30.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 113 | 82 | 31 | 72.6% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 110 | 36 | 74 | 32.7% |
| vless | 427 | 309 | 118 | 72.4% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 75 |
| 204:ProxyError | 31 |
| 204:TimeoutError | 29 |
| 204:ClientOSError | 23 |
| speed:TimeoutError | 17 |
| cn-block:ClientOSError | 11 |
| geo:ClientOSError | 9 |
| geo:TimeoutError | 9 |
| cn-block:TimeoutError | 8 |
| cn-block:ProxyError | 5 |
| geo:ProxyError | 5 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4402 |
| ConnectionRefusedError | 659 |
| gaierror | 137 |
| OSError | 122 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.828 | prefer | 299 | 0.749 | 16170 |
| Au1rxx-base64 | 0.778 | prefer | 38 | 0.789 | 78 |
| Surfboard-tg-mixed | 0.671 | observe | 228 | 0.592 | 5075 |
| DeltaKronecker-all | 0.553 | observe | 91 | 0.473 | 6788 |
| nscl5-all | 0.302 | observe | 1 | 1.0 | 1174 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4327 |
| Epodonios-all | 0.255 | observe | 0 | None | 7720 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3982 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-CaV2ray | 0.175 | observe | 0 | None | 0 | 12 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Parsashonam | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.473 | 43 | 48 | 91 |
| Surfboard-tg-mixed | 0.592 | 135 | 93 | 228 |
| mheidari-all | 0.749 | 224 | 75 | 299 |
| Au1rxx-base64 | 0.789 | 30 | 8 | 38 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16170 | yes | 3.79 | 0 |
| Epodonios-all | 7720 | yes | 2.18 | 0 |
| SoliSpirit-all | 7087 | yes | 2.31 | 0 |
| DeltaKronecker-all | 6788 | yes | 4.0 | 0 |
| mahdibland-V2RayAggregator | 5325 | yes | 1.8 | 0 |
| Surfboard-tg-mixed | 5075 | yes | 2.34 | 0 |
| barry-far-vless | 4558 | yes | 1.93 | 0 |
| 10ium-ScrapeCategorize-Vless | 4327 | yes | 1.76 | 0 |
| MatinGhanbari-all-sub | 3982 | yes | 2.02 | 0 |
| Surfboard-tg-vless | 3780 | yes | 2.51 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 94 |
| 204 | 83 |
| cn-block | 24 |
| geo | 23 |
