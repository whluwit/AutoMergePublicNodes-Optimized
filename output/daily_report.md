# AutoNodes 每日报告

生成时间：2026-07-29 08:38:05

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 78927 |
| 去重后节点数 | 22698 |
| TCP 可达数 | 3000 |
| 真测通过数 | 682 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22698 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| generate | 30.4 |
| geo | 1.4 |
| probe | 70.6 |
| real_test | 209.8 |
| tcp | 32.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 95 | 95 | 0 | 100.0% |
| hysteria2 | 13 | 13 | 0 | 100.0% |
| shadowsocks | 190 | 136 | 54 | 71.6% |
| socks | 5 | 4 | 1 | 80.0% |
| trojan | 51 | 43 | 8 | 84.3% |
| vless | 868 | 391 | 477 | 45.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 201 |
| cn-block:TimeoutError | 77 |
| speed:ClientOSError | 65 |
| speed:TimeoutError | 57 |
| 204:ProxyError | 46 |
| geo:ClientOSError | 41 |
| 204:TimeoutError | 32 |
| cn-block:ProxyError | 7 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 6 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4223 |
| ConnectionRefusedError | 735 |
| gaierror | 326 |
| OSError | 225 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.996 | prefer | 96 | 1.0 | 167 |
| Au1rxx-base64 | 0.795 | prefer | 269 | 0.747 | 1232 |
| Surfboard-tg-mixed | 0.734 | prefer | 24 | 0.667 | 5709 |
| DeltaKronecker-all | 0.526 | observe | 810 | 0.446 | 5519 |
| mheidari-all | 0.402 | observe | 19 | 0.316 | 16908 |
| xiaoji235-airport-v2ray-all | 0.329 | observe | 1 | 1.0 | 1861 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5118 |
| Epodonios-all | 0.255 | observe | 0 | None | 6451 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3973 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.316 | 6 | 13 | 19 |
| DeltaKronecker-all | 0.446 | 361 | 449 | 810 |
| Surfboard-tg-mixed | 0.667 | 16 | 8 | 24 |
| Au1rxx-base64 | 0.747 | 201 | 68 | 269 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 96 | 0 | 96 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16908 | yes | 4.56 | 0 |
| Epodonios-all | 6451 | yes | 2.19 | 0 |
| SoliSpirit-all | 6039 | yes | 2.71 | 0 |
| Surfboard-tg-mixed | 5709 | yes | 3.92 | 0 |
| DeltaKronecker-all | 5519 | yes | 4.48 | 0 |
| 10ium-ScrapeCategorize-Vless | 5118 | yes | 1.49 | 0 |
| mahdibland-V2RayAggregator | 5089 | yes | 2.35 | 0 |
| barry-far-vless | 4902 | yes | 1.7 | 0 |
| Surfboard-tg-vless | 4501 | yes | 4.08 | 0 |
| MatinGhanbari-all-sub | 3973 | yes | 2.65 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 244 |
| speed | 122 |
| cn-block | 90 |
| 204 | 84 |
