# AutoNodes 每日报告

生成时间：2026-07-08 08:23:49

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 83152 |
| 去重后节点数 | 24718 |
| TCP 可达数 | 3000 |
| 真测通过数 | 362 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24718 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| generate | 33.7 |
| geo | 1.4 |
| probe | 44.0 |
| real_test | 95.6 |
| tcp | 31.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 5 | 4 | 1 | 80.0% |
| shadowsocks | 91 | 75 | 16 | 82.4% |
| socks | 6 | 4 | 2 | 66.7% |
| trojan | 154 | 127 | 27 | 82.5% |
| vless | 269 | 110 | 159 | 40.9% |
| vmess | 6 | 6 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 81 |
| geo:TimeoutError | 50 |
| geo:ClientOSError | 22 |
| 204:TimeoutError | 16 |
| speed:TimeoutError | 9 |
| cn-block:TimeoutError | 7 |
| 204:ClientOSError | 6 |
| cn-block:ClientOSError | 6 |
| 204:ProxyError | 4 |
| speed:ProxyError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4507 |
| ConnectionRefusedError | 817 |
| OSError | 170 |
| gaierror | 91 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| DeltaKronecker-all | 0.826 | prefer | 136 | 0.75 | 8321 |
| Au1rxx-base64 | 0.826 | prefer | 65 | 0.831 | 134 |
| Surfboard-tg-mixed | 0.623 | observe | 302 | 0.543 | 5828 |
| xiaoji235-airport-v2ray-all | 0.349 | observe | 3 | 0.667 | 3640 |
| mheidari-all | 0.297 | observe | 21 | 0.19 | 17974 |
| Epodonios-all | 0.255 | observe | 0 | None | 6817 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3971 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6807 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 4349 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ermaozi | 0.175 | observe | 0 | None | 0 | 11 |
| ermaozi-get_subscribe | 0.175 | observe | 0 | None | 0 | 11 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.19 | 4 | 17 | 21 |
| Surfboard-tg-mixed | 0.543 | 164 | 138 | 302 |
| xiaoji235-airport-v2ray-all | 0.667 | 2 | 1 | 3 |
| DeltaKronecker-all | 0.75 | 102 | 34 | 136 |
| Au1rxx-base64 | 0.831 | 54 | 11 | 65 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17974 | yes | 2.69 | 0 |
| DeltaKronecker-all | 8321 | yes | 5.18 | 0 |
| Epodonios-all | 6817 | yes | 3.68 | 0 |
| SoliSpirit-all | 6807 | yes | 2.07 | 0 |
| Surfboard-tg-mixed | 5828 | yes | 1.48 | 0 |
| mahdibland-V2RayAggregator | 5352 | yes | 1.29 | 0 |
| barry-far-vless | 4981 | yes | 1.76 | 0 |
| 10ium-ScrapeCategorize-Vless | 4408 | yes | 0.7 | 0 |
| Surfboard-tg-vless | 4349 | yes | 2.15 | 0 |
| MatinGhanbari-all-sub | 3971 | yes | 1.85 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 92 |
| geo | 73 |
| 204 | 26 |
| cn-block | 14 |
