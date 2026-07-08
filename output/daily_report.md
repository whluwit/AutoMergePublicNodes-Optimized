# AutoNodes 每日报告

生成时间：2026-07-08 13:55:31

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 102/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 2/105 |
| 原始节点数 | 83182 |
| 去重后节点数 | 24779 |
| TCP 可达数 | 3000 |
| 真测通过数 | 229 |
| verified 输出数 | 229 |
| global 输出数 | 242 |
| all 输出数 | 24779 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| generate | 29.1 |
| geo | 1.3 |
| probe | 42.6 |
| real_test | 77.8 |
| tcp | 31.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 5 | 4 | 1 | 80.0% |
| shadowsocks | 65 | 55 | 10 | 84.6% |
| socks | 6 | 4 | 2 | 66.7% |
| trojan | 96 | 67 | 29 | 69.8% |
| vless | 173 | 58 | 115 | 33.5% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 65 |
| geo:TimeoutError | 26 |
| 204:ProxyError | 18 |
| cn-block:TimeoutError | 12 |
| 204:TimeoutError | 10 |
| 204:ClientOSError | 8 |
| cn-block:ClientOSError | 6 |
| geo:ClientOSError | 5 |
| speed:TimeoutError | 4 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4306 |
| ConnectionRefusedError | 829 |
| gaierror | 212 |
| OSError | 170 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.827 | prefer | 60 | 0.833 | 116 |
| DeltaKronecker-all | 0.582 | observe | 257 | 0.502 | 8321 |
| Surfboard-tg-mixed | 0.482 | observe | 14 | 0.5 | 5948 |
| xiaoji235-airport-v2ray-all | 0.4 | observe | 4 | 0.75 | 3640 |
| mheidari-all | 0.337 | observe | 13 | 0.308 | 17790 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4408 |
| Epodonios-all | 0.255 | observe | 0 | None | 6852 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3974 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6934 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 10 |
| ermaozi | 0.175 | observe | 0 | None | 0 | 3 |
| ermaozi-get_subscribe | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.308 | 4 | 9 | 13 |
| Surfboard-tg-mixed | 0.5 | 7 | 7 | 14 |
| DeltaKronecker-all | 0.502 | 129 | 128 | 257 |
| xiaoji235-airport-v2ray-all | 0.75 | 3 | 1 | 4 |
| Au1rxx-base64 | 0.833 | 50 | 10 | 60 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17790 | yes | 3.82 | 0 |
| DeltaKronecker-all | 8321 | yes | 3.5 | 0 |
| SoliSpirit-all | 6934 | yes | 2.4 | 0 |
| Epodonios-all | 6852 | yes | 0.88 | 0 |
| Surfboard-tg-mixed | 5948 | yes | 3.34 | 0 |
| mahdibland-V2RayAggregator | 5352 | yes | 1.21 | 0 |
| barry-far-vless | 4939 | yes | 1.28 | 0 |
| 10ium-ScrapeCategorize-Vless | 4408 | yes | 1.56 | 0 |
| Surfboard-tg-vless | 4400 | yes | 2.18 | 0 |
| MatinGhanbari-all-sub | 3974 | yes | 1.37 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 69 |
| 204 | 36 |
| geo | 33 |
| cn-block | 19 |
