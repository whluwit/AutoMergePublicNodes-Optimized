# AutoNodes 每日报告

生成时间：2026-06-30 19:52:18

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 103/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 75830 |
| 去重后节点数 | 23069 |
| TCP 可达数 | 3000 |
| 真测通过数 | 174 |
| verified 输出数 | 174 |
| global 输出数 | 184 |
| all 输出数 | 23069 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.1 |
| generate | 25.3 |
| geo | 1.4 |
| probe | 50.8 |
| real_test | 75.6 |
| tcp | 30.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 95 | 76 | 19 | 80.0% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 274 | 32 | 242 | 11.7% |
| vless | 65 | 24 | 41 | 36.9% |
| vmess | 4 | 3 | 1 | 75.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 171 |
| 204:TimeoutError | 52 |
| 204:ProxyError | 23 |
| cn-block:TimeoutError | 15 |
| geo:ClientOSError | 9 |
| geo:TimeoutError | 9 |
| 204:ClientOSError | 9 |
| cn-block:ProxyError | 5 |
| speed:TimeoutError | 5 |
| geo:ProxyError | 4 |
| cn-block:ClientOSError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4421 |
| ConnectionRefusedError | 625 |
| OSError | 132 |
| gaierror | 116 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.854 | prefer | 45 | 0.867 | 83 |
| mheidari-all | 0.807 | prefer | 31 | 0.742 | 15848 |
| Surfboard-tg-mixed | 0.459 | observe | 93 | 0.376 | 5645 |
| xiaoji235-airport-v2ray-all | 0.303 | observe | 1 | 1.0 | 1204 |
| nscl5-all | 0.3 | observe | 1 | 1.0 | 1136 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| abc-configs-readme-latest30 | 0.256 | observe | 1 | 1.0 | 19 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4139 |
| Epodonios-all | 0.255 | observe | 0 | None | 6581 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| 10ium-HighSpeed | 0.161 | observe | 1 | 0.0 | 0 | 839 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| chromego_merge | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| peasoft-NoMoreWalls | 0.175 | observe | 0 | None | 0 | 3 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.221 | 268 | 0.138 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.138 | 37 | 231 | 268 |
| Surfboard-tg-mixed | 0.376 | 35 | 58 | 93 |
| mheidari-all | 0.742 | 23 | 8 | 31 |
| Au1rxx-base64 | 0.867 | 39 | 6 | 45 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| abc-configs-readme-latest30 | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15848 | yes | 2.86 | 0 |
| DeltaKronecker-all | 7352 | yes | 4.31 | 0 |
| SoliSpirit-all | 6636 | yes | 2.74 | 0 |
| Epodonios-all | 6581 | yes | 2.42 | 0 |
| Surfboard-tg-mixed | 5645 | yes | 2.1 | 0 |
| mahdibland-V2RayAggregator | 5373 | yes | 1.78 | 0 |
| barry-far-vless | 4802 | yes | 1.25 | 0 |
| Surfboard-tg-vless | 4233 | yes | 2.26 | 0 |
| 10ium-ScrapeCategorize-Vless | 4139 | yes | 1.53 | 0 |
| MatinGhanbari-all-sub | 3977 | yes | 2.54 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| real_ok_drop_50pct | real-test ok dropped from 451 to 174 |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 176 |
| 204 | 84 |
| cn-block | 22 |
| geo | 22 |
