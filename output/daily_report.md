# AutoNodes 每日报告

生成时间：2026-09-26 10:51:29

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 94/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 97157 |
| 去重后节点数 | 26411 |
| TCP 可达数 | 3000 |
| 真测通过数 | 365 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 26411 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| generate | 88.7 |
| geo | 1.4 |
| probe | 229.5 |
| real_test | 164.5 |
| tcp | 43.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 37 | 14 | 23 | 37.8% |
| hysteria2 | 23 | 21 | 2 | 91.3% |
| shadowsocks | 149 | 127 | 22 | 85.2% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 34 | 30 | 4 | 88.2% |
| vless | 237 | 168 | 69 | 70.9% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 26 |
| 204:TimeoutError | 26 |
| cn-block:TimeoutError | 21 |
| cn-block:ClientOSError | 12 |
| speed:TimeoutError | 12 |
| geo:TimeoutError | 6 |
| 204:ProxyConnectionError | 5 |
| geo:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 3 |
| 204:ClientOSError | 2 |
| speed:ClientOSError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6076 |
| ConnectionRefusedError | 959 |
| gaierror | 384 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.924 | prefer | 230 | 0.861 | 1660 |
| mheidari-all | 0.896 | prefer | 74 | 0.824 | 22392 |
| Surfboard-tg-mixed | 0.709 | prefer | 130 | 0.631 | 7247 |
| DeltaKronecker-all | 0.646 | observe | 13 | 0.769 | 5512 |
| ermaozi | 0.373 | observe | 37 | 0.351 | 352 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4355 |
| Epodonios-all | 0.255 | observe | 0 | None | 7713 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3995 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9376 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5840 |

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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.351 | 13 | 24 | 37 |
| Surfboard-tg-mixed | 0.631 | 82 | 48 | 130 |
| DeltaKronecker-all | 0.769 | 10 | 3 | 13 |
| mheidari-all | 0.824 | 61 | 13 | 74 |
| Au1rxx-base64 | 0.861 | 198 | 32 | 230 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22392 | yes | 6.18 | 0 |
| SoliSpirit-all | 9376 | yes | 3.44 | 0 |
| Epodonios-all | 7713 | yes | 1.69 | 0 |
| Surfboard-tg-mixed | 7247 | yes | 4.5 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.26 | 0 |
| barry-far-vless | 6058 | yes | 1.63 | 0 |
| Surfboard-tg-vless | 5840 | yes | 3.93 | 0 |
| DeltaKronecker-all | 5512 | yes | 6.36 | 0 |
| 10ium-ScrapeCategorize-Vless | 5242 | yes | 2.23 | 0 |
| mahdibland-V2RayAggregator | 4355 | yes | 2.69 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 59 |
| cn-block | 36 |
| speed | 15 |
| geo | 13 |
