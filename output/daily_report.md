# AutoNodes 每日报告

生成时间：2026-08-02 19:07:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 81292 |
| 去重后节点数 | 22651 |
| TCP 可达数 | 3000 |
| 真测通过数 | 633 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22651 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| generate | 35.1 |
| geo | 1.3 |
| probe | 66.0 |
| real_test | 159.6 |
| tcp | 33.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| http | 143 | 143 | 0 | 100.0% |
| hysteria2 | 19 | 16 | 3 | 84.2% |
| shadowsocks | 147 | 114 | 33 | 77.6% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 23 | 22 | 1 | 95.7% |
| vless | 599 | 332 | 267 | 55.4% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 107 |
| 204:ProxyError | 50 |
| speed:TimeoutError | 43 |
| cn-block:TimeoutError | 33 |
| 204:TimeoutError | 24 |
| speed:ClientOSError | 13 |
| cn-block:ProxyError | 12 |
| geo:ClientOSError | 7 |
| 204:ClientOSError | 6 |
| cn-block:ClientOSError | 4 |
| speed:ProxyError | 3 |
| geo:ProxyError | 3 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4469 |
| ConnectionRefusedError | 798 |
| gaierror | 359 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | prefer | 143 | 1.0 | 344 |
| Au1rxx-base64 | 0.79 | prefer | 548 | 0.724 | 1651 |
| mheidari-all | 0.541 | observe | 19 | 0.474 | 18817 |
| DeltaKronecker-all | 0.507 | observe | 73 | 0.425 | 3437 |
| xiaoji235-airport-v2ray-all | 0.48 | observe | 4 | 1.0 | 3833 |
| Surfboard-tg-mixed | 0.398 | observe | 146 | 0.315 | 5169 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 179 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 56 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5486 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.315 | 46 | 100 | 146 |
| DeltaKronecker-all | 0.425 | 31 | 42 | 73 |
| mheidari-all | 0.474 | 9 | 10 | 19 |
| Au1rxx-base64 | 0.724 | 397 | 151 | 548 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 4 | 0 | 4 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 18817 | yes | 5.15 | 0 |
| SoliSpirit-all | 7116 | yes | 4.84 | 0 |
| Epodonios-all | 5783 | yes | 0.73 | 0 |
| 10ium-ScrapeCategorize-Vless | 5486 | yes | 5.09 | 0 |
| mahdibland-V2RayAggregator | 5208 | yes | 3.34 | 0 |
| Surfboard-tg-mixed | 5169 | yes | 3.62 | 0 |
| barry-far-vless | 4490 | yes | 2.98 | 0 |
| Surfboard-tg-vless | 4107 | yes | 3.76 | 0 |
| MatinGhanbari-all-sub | 3971 | yes | 3.07 | 0 |
| xiaoji235-airport-v2ray-all | 3833 | yes | 3.64 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 117 |
| 204 | 80 |
| speed | 59 |
| cn-block | 49 |
