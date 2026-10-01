# AutoNodes 每日报告

生成时间：2026-10-01 22:24:49

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 98428 |
| 去重后节点数 | 27519 |
| TCP 可达数 | 3000 |
| 真测通过数 | 378 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27519 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| generate | 71.9 |
| geo | 1.5 |
| probe | 255.2 |
| real_test | 150.1 |
| tcp | 45.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 21 | 13 | 8 | 61.9% |
| hysteria2 | 23 | 23 | 0 | 100.0% |
| shadowsocks | 158 | 142 | 16 | 89.9% |
| socks | 5 | 1 | 4 | 20.0% |
| trojan | 15 | 14 | 1 | 93.3% |
| vless | 223 | 184 | 39 | 82.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:TimeoutError | 19 |
| speed:TimeoutError | 11 |
| 204:TimeoutError | 11 |
| 204:ProxyConnectionError | 9 |
| 204:ProxyError | 4 |
| cn-block:ClientOSError | 4 |
| speed:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| geo:TimeoutError | 2 |
| geo:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6440 |
| ConnectionRefusedError | 1033 |
| gaierror | 383 |
| OSError | 233 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.98 | prefer | 108 | 0.907 | 22987 |
| Au1rxx-base64 | 0.931 | prefer | 267 | 0.861 | 1818 |
| Surfboard-tg-mixed | 0.835 | prefer | 47 | 0.766 | 7183 |
| zhangkai | 0.614 | observe | 21 | 0.619 | 144 |
| DeltaKronecker-all | 0.335 | observe | 1 | 1.0 | 5603 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5324 |
| Epodonios-all | 0.255 | observe | 0 | None | 7711 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9539 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5811 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-CaV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 1 | 1 |
| zhangkai | 0.619 | 13 | 8 | 21 |
| Surfboard-tg-mixed | 0.766 | 36 | 11 | 47 |
| Au1rxx-base64 | 0.861 | 230 | 37 | 267 |
| mheidari-all | 0.907 | 98 | 10 | 108 |
| DeltaKronecker-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22987 | yes | 5.38 | 0 |
| SoliSpirit-all | 9539 | yes | 4.43 | 0 |
| Epodonios-all | 7711 | yes | 0.36 | 0 |
| Surfboard-tg-mixed | 7183 | yes | 3.51 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.13 | 0 |
| barry-far-vless | 6097 | yes | 1.57 | 0 |
| Surfboard-tg-vless | 5811 | yes | 3.68 | 0 |
| DeltaKronecker-all | 5603 | yes | 5.56 | 0 |
| 10ium-ScrapeCategorize-Vless | 5324 | yes | 0.91 | 0 |
| mahdibland-V2RayAggregator | 4310 | yes | 2.46 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 25 |
| 204 | 24 |
| speed | 15 |
| geo | 4 |
