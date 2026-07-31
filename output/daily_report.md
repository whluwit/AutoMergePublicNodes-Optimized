# AutoNodes 每日报告

生成时间：2026-07-31 08:46:36

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 77155 |
| 去重后节点数 | 22419 |
| TCP 可达数 | 3000 |
| 真测通过数 | 403 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22419 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| generate | 30.0 |
| geo | 1.3 |
| probe | 53.3 |
| real_test | 102.2 |
| tcp | 31.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 80 | 80 | 0 | 100.0% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 151 | 124 | 27 | 82.1% |
| socks | 10 | 5 | 5 | 50.0% |
| trojan | 39 | 33 | 6 | 84.6% |
| vless | 259 | 146 | 113 | 56.4% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 60 |
| 204:TimeoutError | 26 |
| speed:TimeoutError | 19 |
| geo:ClientOSError | 11 |
| cn-block:TimeoutError | 11 |
| speed:ClientOSError | 10 |
| 204:ClientOSError | 6 |
| 204:ProxyError | 4 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4513 |
| ConnectionRefusedError | 754 |
| OSError | 221 |
| gaierror | 216 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.992 | prefer | 81 | 1.0 | 110 |
| Au1rxx-base64 | 0.882 | prefer | 197 | 0.832 | 1319 |
| Surfboard-tg-mixed | 0.734 | prefer | 154 | 0.656 | 5242 |
| mheidari-all | 0.66 | observe | 16 | 0.688 | 16339 |
| DeltaKronecker-all | 0.506 | observe | 99 | 0.424 | 5144 |
| xiaoji235-airport-v2ray-all | 0.282 | observe | 2 | 0.5 | 1861 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 175 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 45 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5507 |
| Epodonios-all | 0.255 | observe | 0 | None | 5918 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-ArV2ray | 0.175 | observe | 0 | None | 0 | 5 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| nscl5-all | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.424 | 42 | 57 | 99 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| roosterkid-openproxylist-v2ray | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.656 | 101 | 53 | 154 |
| mheidari-all | 0.688 | 11 | 5 | 16 |
| Au1rxx-base64 | 0.832 | 164 | 33 | 197 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16339 | yes | 3.79 | 0 |
| SoliSpirit-all | 6473 | yes | 2.32 | 0 |
| Epodonios-all | 5918 | yes | 3.94 | 0 |
| 10ium-ScrapeCategorize-Vless | 5507 | yes | 0.61 | 0 |
| Surfboard-tg-mixed | 5242 | yes | 2.65 | 0 |
| DeltaKronecker-all | 5144 | yes | 2.6 | 0 |
| mahdibland-V2RayAggregator | 5074 | yes | 2.21 | 0 |
| barry-far-vless | 4510 | yes | 1.04 | 0 |
| Surfboard-tg-vless | 4146 | yes | 2.82 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.69 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 71 |
| 204 | 36 |
| speed | 30 |
| cn-block | 16 |
