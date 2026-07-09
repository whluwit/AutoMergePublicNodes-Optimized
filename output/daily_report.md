# AutoNodes 每日报告

生成时间：2026-07-09 09:34:11

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 79180 |
| 去重后节点数 | 23776 |
| TCP 可达数 | 3000 |
| 真测通过数 | 308 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23776 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| generate | 39.7 |
| geo | 1.3 |
| probe | 46.4 |
| real_test | 72.8 |
| tcp | 31.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 4 | 4 | 0 | 100.0% |
| shadowsocks | 112 | 100 | 12 | 89.3% |
| socks | 9 | 8 | 1 | 88.9% |
| trojan | 217 | 133 | 84 | 61.3% |
| vless | 82 | 21 | 61 | 25.6% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:ClientOSError | 41 |
| 204:ProxyError | 29 |
| geo:TimeoutError | 24 |
| 204:ClientOSError | 16 |
| cn-block:ProxyError | 10 |
| geo:ProxyError | 9 |
| geo:ClientOSError | 8 |
| 204:TimeoutError | 6 |
| speed:ProxyError | 5 |
| cn-block:ClientOSError | 5 |
| cn-block:TimeoutError | 3 |
| speed:TimeoutError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4264 |
| ConnectionRefusedError | 829 |
| gaierror | 316 |
| OSError | 175 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| mheidari-all | 0.809 | prefer | 83 | 0.735 | 17088 |
| Surfboard-tg-mixed | 0.74 | prefer | 98 | 0.663 | 5778 |
| Au1rxx-base64 | 0.723 | prefer | 76 | 0.724 | 128 |
| DeltaKronecker-all | 0.598 | observe | 168 | 0.518 | 7533 |
| xiaoji235-airport-v2ray-all | 0.48 | observe | 4 | 1.0 | 2703 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4306 |
| Epodonios-all | 0.255 | observe | 0 | None | 6686 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3976 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6293 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ermaozi | 0.175 | observe | 0 | None | 0 | 2 |
| ermaozi-get_subscribe | 0.175 | observe | 0 | None | 0 | 2 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.518 | 87 | 81 | 168 |
| Surfboard-tg-mixed | 0.663 | 65 | 33 | 98 |
| Au1rxx-base64 | 0.724 | 55 | 21 | 76 |
| mheidari-all | 0.735 | 61 | 22 | 83 |
| xiaoji235-airport-v2ray-all | 1.0 | 4 | 0 | 4 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 17088 | yes | 3.04 | 0 |
| DeltaKronecker-all | 7533 | yes | 3.45 | 0 |
| Epodonios-all | 6686 | yes | 1.29 | 0 |
| SoliSpirit-all | 6293 | yes | 2.13 | 0 |
| Surfboard-tg-mixed | 5778 | yes | 2.44 | 0 |
| mahdibland-V2RayAggregator | 5440 | yes | 1.65 | 0 |
| barry-far-vless | 4851 | yes | 1.15 | 0 |
| 10ium-ScrapeCategorize-Vless | 4306 | yes | 1.47 | 0 |
| Surfboard-tg-vless | 4286 | yes | 1.87 | 0 |
| MatinGhanbari-all-sub | 3976 | yes | 0.94 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 51 |
| speed | 48 |
| geo | 41 |
| cn-block | 18 |
