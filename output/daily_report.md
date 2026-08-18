# AutoNodes 每日报告

生成时间：2026-08-18 18:36:56

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 93063 |
| 去重后节点数 | 24078 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1172 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24078 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| generate | 27.1 |
| geo | 1.1 |
| probe | 74.6 |
| real_test | 220.1 |
| tcp | 36.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 127 | 127 | 0 | 100.0% |
| hysteria2 | 16 | 16 | 0 | 100.0% |
| shadowsocks | 94 | 88 | 6 | 93.6% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 893 | 888 | 5 | 99.4% |
| tuic | 1 | 1 | 0 | 100.0% |
| vless | 116 | 48 | 68 | 41.4% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 35 |
| speed:TimeoutError | 14 |
| 204:TimeoutError | 8 |
| cn-block:ClientOSError | 7 |
| geo:TimeoutError | 6 |
| cn-block:TimeoutError | 5 |
| speed:ClientOSError | 2 |
| 204:ClientOSError | 1 |
| geo:ProxyError | 1 |
| 204:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4393 |
| ConnectionRefusedError | 946 |
| gaierror | 415 |
| OSError | 228 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 644 | 0.991 | 1643 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| mheidari-all | 0.922 | prefer | 461 | 0.844 | 22150 |
| Surfboard-tg-mixed | 0.801 | prefer | 13 | 1.0 | 6301 |
| nscl5-all | 0.391 | observe | 2 | 1.0 | 2992 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6329 |
| DeltaKronecker-all | 0.287 | observe | 2 | 0.5 | 5725 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5068 |
| Epodonios-all | 0.255 | observe | 0 | None | 6927 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.5 | 1 | 1 | 2 |
| mheidari-all | 0.844 | 389 | 72 | 461 |
| Au1rxx-base64 | 0.991 | 638 | 6 | 644 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 2 | 0 | 2 |
| Surfboard-tg-mixed | 1.0 | 13 | 0 | 13 |
| zhangkai | 1.0 | 127 | 0 | 127 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22150 | yes | 4.3 | 0 |
| SoliSpirit-all | 7150 | yes | 3.1 | 0 |
| Epodonios-all | 6927 | yes | 2.41 | 0 |
| xiaoji235-airport-v2ray-all | 6329 | yes | 1.52 | 0 |
| Surfboard-tg-mixed | 6301 | yes | 2.68 | 0 |
| DeltaKronecker-all | 5725 | yes | 4.13 | 0 |
| barry-far-vless | 5149 | yes | 2.18 | 0 |
| 10ium-ScrapeCategorize-Vless | 5068 | yes | 2.43 | 0 |
| Surfboard-tg-vless | 4855 | yes | 3.29 | 0 |
| mahdibland-V2RayAggregator | 4035 | yes | 0.17 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 42 |
| speed | 16 |
| cn-block | 12 |
| 204 | 10 |
