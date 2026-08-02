# AutoNodes 每日报告

生成时间：2026-08-02 13:15:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 78300 |
| 去重后节点数 | 22849 |
| TCP 可达数 | 3000 |
| 真测通过数 | 639 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22849 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| generate | 36.4 |
| geo | 1.4 |
| probe | 67.2 |
| real_test | 166.9 |
| tcp | 34.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 142 | 142 | 0 | 100.0% |
| hysteria2 | 22 | 18 | 4 | 81.8% |
| shadowsocks | 148 | 117 | 31 | 79.1% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 27 | 23 | 4 | 85.2% |
| vless | 555 | 335 | 220 | 60.4% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 92 |
| speed:TimeoutError | 43 |
| 204:TimeoutError | 29 |
| cn-block:TimeoutError | 28 |
| speed:ClientOSError | 24 |
| geo:ClientOSError | 19 |
| 204:ClientOSError | 9 |
| 204:ProxyError | 7 |
| cn-block:ClientOSError | 6 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4522 |
| ConnectionRefusedError | 799 |
| gaierror | 349 |
| OSError | 225 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 1.0 | prefer | 142 | 1.0 | 344 |
| Au1rxx-base64 | 0.769 | prefer | 562 | 0.703 | 1670 |
| Surfboard-tg-mixed | 0.69 | observe | 121 | 0.612 | 5249 |
| DeltaKronecker-all | 0.423 | observe | 65 | 0.338 | 4549 |
| mheidari-all | 0.4 | observe | 4 | 0.75 | 16891 |
| nscl5-all | 0.262 | observe | 2 | 0.5 | 1354 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 57 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5486 |
| Epodonios-all | 0.255 | observe | 0 | None | 5857 |

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
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.338 | 22 | 43 | 65 |
| nscl5-all | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.612 | 74 | 47 | 121 |
| Au1rxx-base64 | 0.703 | 395 | 167 | 562 |
| mheidari-all | 0.75 | 3 | 1 | 4 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 142 | 0 | 142 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16891 | yes | 5.23 | 0 |
| SoliSpirit-all | 6807 | yes | 3.5 | 0 |
| Epodonios-all | 5857 | yes | 3.32 | 0 |
| 10ium-ScrapeCategorize-Vless | 5486 | yes | 1.83 | 0 |
| Surfboard-tg-mixed | 5249 | yes | 3.98 | 0 |
| mahdibland-V2RayAggregator | 5071 | yes | 2.63 | 0 |
| DeltaKronecker-all | 4549 | yes | 3.08 | 0 |
| barry-far-vless | 4517 | yes | 1.29 | 0 |
| Surfboard-tg-vless | 4140 | yes | 3.61 | 0 |
| MatinGhanbari-all-sub | 3975 | yes | 1.58 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 112 |
| speed | 67 |
| 204 | 45 |
| cn-block | 37 |
