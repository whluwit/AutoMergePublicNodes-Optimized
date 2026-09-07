# AutoNodes 每日报告

生成时间：2026-09-07 02:37:55

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 93994 |
| 去重后节点数 | 24749 |
| TCP 可达数 | 3000 |
| 真测通过数 | 630 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24749 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| generate | 38.5 |
| geo | 1.4 |
| probe | 77.9 |
| real_test | 173.3 |
| tcp | 42.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 3 | 1 | 75.0% |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 20 | 19 | 1 | 95.0% |
| shadowsocks | 189 | 182 | 7 | 96.3% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 24 | 20 | 4 | 83.3% |
| vless | 774 | 378 | 396 | 48.8% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 108 |
| cn-block:ClientOSError | 80 |
| geo:ClientOSError | 73 |
| speed:TimeoutError | 70 |
| speed:ClientOSError | 33 |
| cn-block:TimeoutError | 16 |
| 204:TimeoutError | 11 |
| 204:ClientOSError | 10 |
| 204:ProxyError | 9 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5857 |
| ConnectionRefusedError | 1010 |
| gaierror | 343 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 317 | 0.943 | 1835 |
| zhangkai | 0.926 | prefer | 23 | 0.957 | 144 |
| Surfboard-tg-mixed | 0.846 | prefer | 216 | 0.769 | 7305 |
| xiaoji235-airport-v2ray-all | 0.391 | observe | 2 | 1.0 | 5750 |
| mheidari-all | 0.373 | observe | 469 | 0.292 | 21249 |
| tg-LonUp_M | 0.318 | observe | 2 | 1.0 | 176 |
| Epodonios-all | 0.255 | observe | 0 | None | 7766 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8335 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6046 |

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

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.208 | 7 | 0.143 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.143 | 1 | 6 | 7 |
| mheidari-all | 0.292 | 137 | 332 | 469 |
| tg-oneclickvpnkeys | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.769 | 166 | 50 | 216 |
| Au1rxx-base64 | 0.943 | 299 | 18 | 317 |
| zhangkai | 0.957 | 22 | 1 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 21249 | yes | 3.79 | 0 |
| SoliSpirit-all | 8335 | yes | 3.63 | 0 |
| Epodonios-all | 7766 | yes | 1.18 | 0 |
| Surfboard-tg-mixed | 7305 | yes | 2.79 | 0 |
| barry-far-vless | 6261 | yes | 1.99 | 0 |
| Surfboard-tg-vless | 6046 | yes | 3.39 | 0 |
| DeltaKronecker-all | 5856 | yes | 4.33 | 0 |
| xiaoji235-airport-v2ray-all | 5750 | yes | 2.02 | 0 |
| 10ium-ScrapeCategorize-Vless | 4791 | yes | 2.59 | 0 |
| mahdibland-V2RayAggregator | 4138 | yes | 1.22 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 182 |
| speed | 103 |
| cn-block | 97 |
| 204 | 30 |
