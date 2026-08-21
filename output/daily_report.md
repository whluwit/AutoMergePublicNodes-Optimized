# AutoNodes 每日报告

生成时间：2026-08-21 18:35:59

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 93267 |
| 去重后节点数 | 23290 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1127 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23290 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 19.1 |
| generate | 37.7 |
| geo | 1.2 |
| probe | 67.2 |
| real_test | 225.3 |
| tcp | 38.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 113 | 113 | 0 | 100.0% |
| hysteria2 | 21 | 21 | 0 | 100.0% |
| shadowsocks | 159 | 140 | 19 | 88.1% |
| socks | 6 | 3 | 3 | 50.0% |
| trojan | 649 | 639 | 10 | 98.5% |
| vless | 268 | 209 | 59 | 78.0% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 18 |
| geo:TimeoutError | 18 |
| cn-block:TimeoutError | 16 |
| speed:TimeoutError | 9 |
| 204:ProxyError | 9 |
| geo:ClientOSError | 7 |
| speed:ClientOSError | 6 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:32671: bind: address already in use | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4862 |
| ConnectionRefusedError | 935 |
| gaierror | 557 |
| OSError | 224 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 673 | 0.967 | 1933 |
| zhangkai | 0.997 | prefer | 112 | 1.0 | 144 |
| mheidari-all | 0.98 | prefer | 219 | 0.904 | 21956 |
| Surfboard-tg-mixed | 0.862 | prefer | 204 | 0.784 | 6453 |
| nscl5-all | 0.391 | observe | 2 | 1.0 | 3031 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-oneclickvpnkeys | 0.262 | observe | 1 | 1.0 | 177 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5148 |
| Epodonios-all | 0.255 | observe | 0 | None | 7154 |

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
| downweight | DeltaKronecker-all | 0.226 | 5 | 0.2 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.2 | 1 | 4 | 5 |
| Surfboard-tg-mixed | 0.784 | 160 | 44 | 204 |
| mheidari-all | 0.904 | 198 | 21 | 219 |
| Au1rxx-base64 | 0.967 | 651 | 22 | 673 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 112 | 0 | 112 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21956 | yes | 5.16 | 0 |
| SoliSpirit-all | 7163 | yes | 2.9 | 0 |
| Epodonios-all | 7154 | yes | 5.36 | 0 |
| Surfboard-tg-mixed | 6453 | yes | 3.11 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 1.48 | 0 |
| barry-far-vless | 5535 | yes | 1.04 | 0 |
| Surfboard-tg-vless | 5214 | yes | 3.58 | 0 |
| 10ium-ScrapeCategorize-Vless | 5148 | yes | 1.71 | 0 |
| DeltaKronecker-all | 4433 | yes | 5.87 | 0 |
| mahdibland-V2RayAggregator | 4091 | yes | 2.86 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 31 |
| geo | 25 |
| cn-block | 19 |
| speed | 16 |
| sing-box exited 1 | 1 |
