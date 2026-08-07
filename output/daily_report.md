# AutoNodes 每日报告

生成时间：2026-08-07 07:11:18

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 89355 |
| 去重后节点数 | 24213 |
| TCP 可达数 | 3000 |
| 真测通过数 | 440 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24213 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| generate | 34.5 |
| geo | 1.4 |
| probe | 50.0 |
| real_test | 96.1 |
| tcp | 36.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 169 | 159 | 10 | 94.1% |
| socks | 18 | 12 | 6 | 66.7% |
| trojan | 158 | 147 | 11 | 93.0% |
| vless | 173 | 85 | 88 | 49.1% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 43 |
| geo:ClientOSError | 24 |
| speed:TimeoutError | 14 |
| 204:TimeoutError | 10 |
| speed:ClientOSError | 9 |
| cn-block:TimeoutError | 9 |
| 204:ProxyError | 4 |
| cn-block:ProxyError | 1 |
| cn-block:ClientOSError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5088 |
| ConnectionRefusedError | 811 |
| gaierror | 253 |
| OSError | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 368 | 0.954 | 1258 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| DeltaKronecker-all | 0.58 | observe | 34 | 0.5 | 5326 |
| Surfboard-tg-mixed | 0.499 | observe | 84 | 0.417 | 6241 |
| mheidari-all | 0.421 | observe | 42 | 0.333 | 20715 |
| nscl5-all | 0.278 | observe | 2 | 0.5 | 1772 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| xiaoji235-airport-v2ray-all | 0.259 | observe | 3 | 0.333 | 5184 |
| Epodonios-all | 0.255 | observe | 0 | None | 6539 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.333 | 1 | 2 | 3 |
| mheidari-all | 0.333 | 14 | 28 | 42 |
| Surfboard-tg-mixed | 0.417 | 35 | 49 | 84 |
| nscl5-all | 0.5 | 1 | 1 | 2 |
| DeltaKronecker-all | 0.5 | 17 | 17 | 34 |
| Au1rxx-base64 | 0.954 | 351 | 17 | 368 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20715 | yes | 4.19 | 0 |
| SoliSpirit-all | 7511 | yes | 3.62 | 0 |
| Epodonios-all | 6539 | yes | 5.12 | 0 |
| Surfboard-tg-mixed | 6241 | yes | 3.65 | 0 |
| DeltaKronecker-all | 5326 | yes | 3.98 | 0 |
| barry-far-vless | 5297 | yes | 0.8 | 0 |
| 10ium-ScrapeCategorize-Vless | 5282 | yes | 1.48 | 0 |
| mahdibland-V2RayAggregator | 5247 | yes | 2.22 | 0 |
| xiaoji235-airport-v2ray-all | 5184 | yes | 1.41 | 0 |
| Surfboard-tg-vless | 4967 | yes | 3.46 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 67 |
| speed | 23 |
| 204 | 15 |
| cn-block | 11 |
