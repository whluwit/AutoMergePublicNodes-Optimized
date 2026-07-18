# AutoNodes 每日报告

生成时间：2026-07-18 07:46:56

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 98/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 80045 |
| 去重后节点数 | 21570 |
| TCP 可达数 | 3000 |
| 真测通过数 | 847 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21570 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| generate | 19.4 |
| geo | 0.8 |
| probe | 61.9 |
| real_test | 184.4 |
| tcp | 30.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 3 | 3 | 0 | 100.0% |
| shadowsocks | 162 | 144 | 18 | 88.9% |
| socks | 6 | 4 | 2 | 66.7% |
| trojan | 602 | 575 | 27 | 95.5% |
| vless | 417 | 85 | 332 | 20.4% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 193 |
| speed:ClientOSError | 105 |
| cn-block:TimeoutError | 19 |
| speed:TimeoutError | 18 |
| geo:ClientOSError | 13 |
| 204:TimeoutError | 13 |
| 204:ClientOSError | 7 |
| cn-block:ClientOSError | 6 |
| 204:ProxyError | 4 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4134 |
| ConnectionRefusedError | 680 |
| gaierror | 234 |
| OSError | 217 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.951 | prefer | 125 | 0.952 | 150 |
| DeltaKronecker-all | 0.908 | prefer | 161 | 0.832 | 3620 |
| mheidari-all | 0.726 | prefer | 589 | 0.647 | 19158 |
| Surfboard-tg-mixed | 0.641 | observe | 308 | 0.562 | 5509 |
| xiaoji235-airport-v2ray-all | 0.438 | observe | 3 | 1.0 | 4321 |
| nscl5-all | 0.334 | observe | 1 | 1.0 | 1976 |
| Epodonios-all | 0.255 | observe | 0 | None | 6683 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3974 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6902 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-v2raying | 0.025 | observe | 0 | None | 1 | 0 |
| tg-LonUp_M | 0.135 | observe | 1 | 0.0 | 0 | 179 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-LonUp_M | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.562 | 173 | 135 | 308 |
| mheidari-all | 0.647 | 381 | 208 | 589 |
| DeltaKronecker-all | 0.832 | 134 | 27 | 161 |
| Au1rxx-base64 | 0.952 | 119 | 6 | 125 |
| nscl5-all | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 3 | 0 | 3 |
| zhangkai | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19158 | yes | 3.24 | 0 |
| SoliSpirit-all | 6902 | yes | 2.98 | 0 |
| Epodonios-all | 6683 | yes | 3.43 | 0 |
| Surfboard-tg-mixed | 5509 | yes | 1.71 | 0 |
| mahdibland-V2RayAggregator | 5334 | yes | 1.8 | 0 |
| barry-far-vless | 4807 | yes | 0.88 | 0 |
| 10ium-ScrapeCategorize-Vless | 4371 | yes | 1.72 | 0 |
| xiaoji235-airport-v2ray-all | 4321 | yes | 1.25 | 0 |
| Surfboard-tg-vless | 4187 | yes | 2.01 | 0 |
| MatinGhanbari-all-sub | 3974 | yes | 1.33 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 206 |
| speed | 124 |
| cn-block | 25 |
| 204 | 24 |
