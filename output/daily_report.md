# AutoNodes 每日报告

生成时间：2026-07-11 13:12:43

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 76309 |
| 去重后节点数 | 24020 |
| TCP 可达数 | 3000 |
| 真测通过数 | 293 |
| verified 输出数 | 293 |
| global 输出数 | 300 |
| all 输出数 | 24020 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| generate | 43.5 |
| geo | 1.6 |
| probe | 45.4 |
| real_test | 118.2 |
| tcp | 31.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 124 | 107 | 17 | 86.3% |
| socks | 8 | 6 | 2 | 75.0% |
| trojan | 189 | 105 | 84 | 55.6% |
| vless | 62 | 30 | 32 | 48.4% |
| vmess | 7 | 7 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 26 |
| cn-block:TimeoutError | 18 |
| 204:ProxyError | 16 |
| speed:ClientOSError | 15 |
| geo:TimeoutError | 13 |
| cn-block:ClientOSError | 13 |
| geo:ClientOSError | 9 |
| cn-block:ProxyError | 7 |
| 204:ClientOSError | 6 |
| geo:ProxyError | 6 |
| speed:ProxyError | 5 |
| speed:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4327 |
| ConnectionRefusedError | 663 |
| gaierror | 280 |
| OSError | 190 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.929 | prefer | 38 | 0.947 | 106 |
| Surfboard-tg-mixed | 0.823 | prefer | 99 | 0.747 | 5543 |
| mheidari-all | 0.682 | observe | 81 | 0.605 | 16307 |
| DeltaKronecker-all | 0.636 | observe | 169 | 0.556 | 7969 |
| Barabama-yudou | 0.318 | observe | 2 | 1.0 | 166 |
| nscl5-all | 0.303 | observe | 1 | 1.0 | 1207 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 3953 |
| Epodonios-all | 0.255 | observe | 0 | None | 6467 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-v2raying | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 6 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.556 | 94 | 75 | 169 |
| mheidari-all | 0.605 | 49 | 32 | 81 |
| Surfboard-tg-mixed | 0.747 | 74 | 25 | 99 |
| Au1rxx-base64 | 0.947 | 36 | 2 | 38 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 2 | 0 | 2 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16307 | yes | 3.62 | 0 |
| DeltaKronecker-all | 7969 | yes | 3.78 | 0 |
| SoliSpirit-all | 6512 | yes | 2.12 | 0 |
| Epodonios-all | 6467 | yes | 1.21 | 0 |
| Surfboard-tg-mixed | 5543 | yes | 1.97 | 0 |
| mahdibland-V2RayAggregator | 5423 | yes | 1.73 | 0 |
| barry-far-vless | 4696 | yes | 1.34 | 0 |
| Surfboard-tg-vless | 4147 | yes | 2.79 | 0 |
| MatinGhanbari-all-sub | 3974 | yes | 1.86 | 0 |
| 10ium-ScrapeCategorize-Vless | 3953 | yes | 1.53 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 48 |
| cn-block | 38 |
| geo | 28 |
| speed | 21 |
