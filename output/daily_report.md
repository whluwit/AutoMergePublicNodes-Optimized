# AutoNodes 每日报告

生成时间：2026-09-08 10:33:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 91316 |
| 去重后节点数 | 25264 |
| TCP 可达数 | 3000 |
| 真测通过数 | 568 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25264 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| generate | 45.4 |
| geo | 1.4 |
| probe | 86.9 |
| real_test | 126.5 |
| tcp | 42.7 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 74 | 72 | 2 | 97.3% |
| hysteria2 | 25 | 23 | 2 | 92.0% |
| shadowsocks | 181 | 160 | 21 | 88.4% |
| socks | 7 | 6 | 1 | 85.7% |
| trojan | 18 | 13 | 5 | 72.2% |
| vless | 387 | 289 | 98 | 74.7% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 23 |
| cn-block:TimeoutError | 22 |
| 204:TimeoutError | 21 |
| speed:TimeoutError | 19 |
| 204:ProxyError | 13 |
| cn-block:ClientOSError | 11 |
| geo:TimeoutError | 7 |
| 204:ClientOSError | 5 |
| speed:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5615 |
| ConnectionRefusedError | 971 |
| gaierror | 461 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.982 | prefer | 54 | 0.981 | 450 |
| Au1rxx-base64 | 0.935 | prefer | 327 | 0.869 | 1726 |
| ermaozi-get_subscribe | 0.894 | prefer | 19 | 0.947 | 470 |
| Surfboard-tg-mixed | 0.852 | prefer | 178 | 0.775 | 7431 |
| mheidari-all | 0.755 | prefer | 78 | 0.679 | 22334 |
| DeltaKronecker-all | 0.605 | observe | 38 | 0.526 | 6097 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 212 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4657 |
| Epodonios-all | 0.255 | observe | 0 | None | 7885 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.526 | 20 | 18 | 38 |
| mheidari-all | 0.679 | 53 | 25 | 78 |
| Surfboard-tg-mixed | 0.775 | 138 | 40 | 178 |
| Au1rxx-base64 | 0.869 | 284 | 43 | 327 |
| ermaozi-get_subscribe | 0.947 | 18 | 1 | 19 |
| ermaozi | 0.981 | 53 | 1 | 54 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22334 | yes | 6.4 | 0 |
| SoliSpirit-all | 8811 | yes | 4.32 | 0 |
| Epodonios-all | 7885 | yes | 5.25 | 0 |
| Surfboard-tg-mixed | 7431 | yes | 4.31 | 0 |
| barry-far-vless | 6423 | yes | 1.93 | 0 |
| Surfboard-tg-vless | 6201 | yes | 3.81 | 0 |
| DeltaKronecker-all | 6097 | yes | 5.39 | 0 |
| 10ium-ScrapeCategorize-Vless | 4657 | yes | 3.35 | 0 |
| mahdibland-V2RayAggregator | 4209 | yes | 0.79 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.71 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 39 |
| cn-block | 35 |
| geo | 30 |
| speed | 25 |
