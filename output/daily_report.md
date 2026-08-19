# AutoNodes 每日报告

生成时间：2026-08-19 06:42:42

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 100/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 82903 |
| 去重后节点数 | 22462 |
| TCP 可达数 | 3000 |
| 真测通过数 | 1393 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22462 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| generate | 31.0 |
| geo | 0.8 |
| probe | 83.1 |
| real_test | 277.1 |
| tcp | 34.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 127 | 127 | 0 | 100.0% |
| hysteria2 | 20 | 16 | 4 | 80.0% |
| shadowsocks | 164 | 154 | 10 | 93.9% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 907 | 892 | 15 | 98.3% |
| vless | 281 | 201 | 80 | 71.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 31 |
| speed:TimeoutError | 16 |
| geo:ClientOSError | 13 |
| 204:TimeoutError | 12 |
| cn-block:TimeoutError | 12 |
| cn-block:ClientOSError | 8 |
| speed:ClientOSError | 8 |
| 204:ProxyError | 7 |
| 204:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4558 |
| ConnectionRefusedError | 841 |
| gaierror | 393 |
| OSError | 17 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 792 | 0.987 | 1924 |
| mheidari-all | 1.0 | prefer | 259 | 0.931 | 16809 |
| zhangkai | 0.999 | prefer | 127 | 1.0 | 159 |
| Surfboard-tg-mixed | 0.859 | prefer | 292 | 0.781 | 6315 |
| DeltaKronecker-all | 0.535 | observe | 20 | 0.45 | 6390 |
| nscl5-all | 0.352 | observe | 6 | 0.5 | 3330 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 175 |
| Epodonios-all | 0.255 | observe | 0 | None | 7030 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.45 | 9 | 11 | 20 |
| nscl5-all | 0.5 | 3 | 3 | 6 |
| Surfboard-tg-mixed | 0.781 | 228 | 64 | 292 |
| mheidari-all | 0.931 | 241 | 18 | 259 |
| Au1rxx-base64 | 0.987 | 782 | 10 | 792 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16809 | yes | 3.2 | 0 |
| SoliSpirit-all | 7119 | yes | 3.61 | 0 |
| Epodonios-all | 7030 | yes | 3.35 | 0 |
| DeltaKronecker-all | 6390 | yes | 3.5 | 0 |
| Surfboard-tg-mixed | 6315 | yes | 2.69 | 0 |
| barry-far-vless | 5174 | yes | 1.93 | 0 |
| 10ium-ScrapeCategorize-Vless | 5067 | yes | 2.44 | 0 |
| Surfboard-tg-vless | 4850 | yes | 2.5 | 0 |
| mahdibland-V2RayAggregator | 3995 | yes | 0.87 | 0 |
| MatinGhanbari-all-sub | 3985 | yes | 2.1 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 44 |
| speed | 24 |
| 204 | 21 |
| cn-block | 20 |
