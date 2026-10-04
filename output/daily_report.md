# AutoNodes 每日报告

生成时间：2026-10-04 11:52:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 99550 |
| 去重后节点数 | 27349 |
| TCP 可达数 | 3000 |
| 真测通过数 | 369 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 27349 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| generate | 84.4 |
| geo | 1.0 |
| probe | 308.2 |
| real_test | 155.7 |
| tcp | 47.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 2 | 1 | 66.7% |
| http | 24 | 15 | 9 | 62.5% |
| hysteria2 | 8 | 7 | 1 | 87.5% |
| shadowsocks | 143 | 123 | 20 | 86.0% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 93 | 87 | 6 | 93.5% |
| vless | 166 | 133 | 33 | 80.1% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyConnectionError | 16 |
| cn-block:TimeoutError | 16 |
| 204:TimeoutError | 10 |
| cn-block:ClientOSError | 7 |
| speed:TimeoutError | 5 |
| speed:ClientOSError | 4 |
| geo:TimeoutError | 4 |
| 204:ProxyError | 3 |
| cn-block:ProxyError | 2 |
| speed:ClientPayloadError | 1 |
| geo:ProxyError | 1 |
| 204:ClientOSError | 1 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6656 |
| ConnectionRefusedError | 1094 |
| gaierror | 364 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.98 | prefer | 279 | 0.91 | 1816 |
| Surfboard-tg-mixed | 0.863 | prefer | 67 | 0.791 | 7269 |
| mheidari-all | 0.834 | prefer | 55 | 0.764 | 23332 |
| ermaozi | 0.641 | observe | 24 | 0.625 | 646 |
| DeltaKronecker-all | 0.344 | observe | 12 | 0.333 | 5267 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5173 |
| Epodonios-all | 0.255 | observe | 0 | None | 7796 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9804 |

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
| DeltaKronecker-all | 0.333 | 4 | 8 | 12 |
| ermaozi | 0.625 | 15 | 9 | 24 |
| mheidari-all | 0.764 | 42 | 13 | 55 |
| Surfboard-tg-mixed | 0.791 | 53 | 14 | 67 |
| Au1rxx-base64 | 0.91 | 254 | 25 | 279 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23332 | yes | 6.56 | 0 |
| SoliSpirit-all | 9804 | yes | 3.69 | 0 |
| Epodonios-all | 7796 | yes | 6.87 | 0 |
| Surfboard-tg-mixed | 7269 | yes | 4.35 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.97 | 0 |
| barry-far-vless | 6148 | yes | 1.32 | 0 |
| Surfboard-tg-vless | 5821 | yes | 4.11 | 0 |
| DeltaKronecker-all | 5267 | yes | 4.42 | 0 |
| 10ium-ScrapeCategorize-Vless | 5173 | yes | 1.85 | 0 |
| mahdibland-V2RayAggregator | 4338 | yes | 3.31 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 30 |
| cn-block | 25 |
| speed | 10 |
| geo | 6 |
