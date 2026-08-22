# AutoNodes 每日报告

生成时间：2026-08-22 06:36:56

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 91268 |
| 去重后节点数 | 23596 |
| TCP 可达数 | 3000 |
| 真测通过数 | 768 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23596 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.7 |
| generate | 37.7 |
| geo | 1.4 |
| probe | 62.2 |
| real_test | 178.6 |
| tcp | 39.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 111 | 111 | 0 | 100.0% |
| hysteria2 | 16 | 14 | 2 | 87.5% |
| shadowsocks | 203 | 187 | 16 | 92.1% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 179 | 170 | 9 | 95.0% |
| vless | 547 | 283 | 264 | 51.7% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 110 |
| geo:ClientOSError | 77 |
| speed:TimeoutError | 38 |
| speed:ClientOSError | 18 |
| 204:TimeoutError | 12 |
| 204:ProxyError | 11 |
| cn-block:ClientOSError | 10 |
| cn-block:TimeoutError | 9 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:40499: bind: address already in use | 1 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5286 |
| ConnectionRefusedError | 924 |
| gaierror | 724 |
| OSError | 226 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.997 | prefer | 111 | 1.0 | 144 |
| Au1rxx-base64 | 0.985 | prefer | 447 | 0.935 | 1299 |
| Surfboard-tg-mixed | 0.866 | prefer | 157 | 0.79 | 6140 |
| mheidari-all | 0.427 | observe | 315 | 0.346 | 21732 |
| nscl5-all | 0.335 | observe | 1 | 1.0 | 3321 |
| ninja-vless | 0.279 | observe | 2 | 0.5 | 1791 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 151 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5096 |
| Epodonios-all | 0.255 | observe | 0 | None | 6730 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3992 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.223 | 26 | 0.115 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.115 | 3 | 23 | 26 |
| mheidari-all | 0.346 | 109 | 206 | 315 |
| ninja-vless | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.79 | 124 | 33 | 157 |
| Au1rxx-base64 | 0.935 | 418 | 29 | 447 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 111 | 0 | 111 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21732 | yes | 4.53 | 0 |
| SoliSpirit-all | 7142 | yes | 4.44 | 0 |
| Epodonios-all | 6730 | yes | 5.82 | 0 |
| Surfboard-tg-mixed | 6140 | yes | 3.27 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 1.44 | 0 |
| barry-far-vless | 5264 | yes | 2.37 | 0 |
| 10ium-ScrapeCategorize-Vless | 5096 | yes | 2.37 | 0 |
| DeltaKronecker-all | 5015 | yes | 4.66 | 0 |
| Surfboard-tg-vless | 4954 | yes | 4.71 | 0 |
| mahdibland-V2RayAggregator | 4074 | yes | 0.75 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 188 |
| speed | 57 |
| 204 | 25 |
| cn-block | 22 |
| sing-box exited 1 | 1 |
