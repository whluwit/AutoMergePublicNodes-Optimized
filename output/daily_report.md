# AutoNodes 每日报告

生成时间：2026-08-07 18:52:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 82847 |
| 去重后节点数 | 23493 |
| TCP 可达数 | 3000 |
| 真测通过数 | 447 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23493 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| generate | 47.8 |
| geo | 1.2 |
| probe | 48.5 |
| real_test | 110.7 |
| tcp | 34.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 22 | 21 | 1 | 95.5% |
| shadowsocks | 135 | 116 | 19 | 85.9% |
| socks | 6 | 2 | 4 | 33.3% |
| trojan | 144 | 140 | 4 | 97.2% |
| vless | 243 | 145 | 98 | 59.7% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 32 |
| 204:TimeoutError | 18 |
| geo:TimeoutError | 17 |
| geo:ClientOSError | 16 |
| cn-block:TimeoutError | 12 |
| speed:ClientOSError | 9 |
| speed:TimeoutError | 8 |
| 204:ClientOSError | 6 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4626 |
| ConnectionRefusedError | 846 |
| gaierror | 365 |
| OSError | 225 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.984 | prefer | 346 | 0.925 | 1543 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 25 |
| DeltaKronecker-all | 0.606 | observe | 188 | 0.527 | 5326 |
| Surfboard-tg-mixed | 0.397 | observe | 12 | 0.417 | 6450 |
| mheidari-all | 0.3 | observe | 5 | 0.4 | 17684 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 178 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5282 |
| Epodonios-all | 0.255 | observe | 0 | None | 7082 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7593 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.4 | 2 | 3 | 5 |
| Surfboard-tg-mixed | 0.417 | 5 | 7 | 12 |
| DeltaKronecker-all | 0.527 | 99 | 89 | 188 |
| Au1rxx-base64 | 0.925 | 320 | 26 | 346 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17684 | yes | 4.16 | 0 |
| SoliSpirit-all | 7593 | yes | 4.73 | 0 |
| Epodonios-all | 7082 | yes | 5.74 | 0 |
| Surfboard-tg-mixed | 6450 | yes | 3.04 | 0 |
| barry-far-vless | 5504 | yes | 2.55 | 0 |
| DeltaKronecker-all | 5326 | yes | 4.99 | 0 |
| 10ium-ScrapeCategorize-Vless | 5282 | yes | 2.91 | 0 |
| xiaoji235-airport-v2ray-all | 5184 | yes | 2.48 | 0 |
| mahdibland-V2RayAggregator | 5175 | yes | 2.38 | 0 |
| Surfboard-tg-vless | 5170 | yes | 2.84 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 56 |
| geo | 35 |
| cn-block | 19 |
| speed | 17 |
