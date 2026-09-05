# AutoNodes 每日报告

生成时间：2026-09-05 19:55:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 96449 |
| 去重后节点数 | 25551 |
| TCP 可达数 | 3000 |
| 真测通过数 | 503 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25551 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| generate | 41.9 |
| geo | 1.4 |
| probe | 93.0 |
| real_test | 123.6 |
| tcp | 41.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 30 | 27 | 3 | 90.0% |
| hysteria2 | 25 | 23 | 2 | 92.0% |
| shadowsocks | 156 | 144 | 12 | 92.3% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 15 | 13 | 2 | 86.7% |
| vless | 469 | 291 | 178 | 62.0% |
| vmess | 4 | 3 | 1 | 75.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| cn-block:ClientOSError | 57 |
| 204:TimeoutError | 51 |
| geo:ClientOSError | 32 |
| cn-block:TimeoutError | 22 |
| 204:ProxyError | 11 |
| 204:ClientOSError | 7 |
| speed:ClientOSError | 5 |
| speed:TimeoutError | 4 |
| geo:TimeoutError | 4 |
| 204:ProxyConnectionError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5458 |
| ConnectionRefusedError | 1010 |
| gaierror | 345 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.926 | prefer | 23 | 0.957 | 144 |
| Au1rxx-base64 | 0.888 | prefer | 354 | 0.819 | 1764 |
| Surfboard-tg-mixed | 0.83 | prefer | 146 | 0.753 | 7188 |
| mheidari-all | 0.521 | observe | 168 | 0.44 | 22630 |
| tg-oneclickvpnkeys | 0.39 | observe | 7 | 0.714 | 132 |
| DeltaKronecker-all | 0.287 | observe | 2 | 0.5 | 6212 |
| xiaoji235-airport-v2ray-all | 0.287 | observe | 2 | 0.5 | 6965 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4887 |
| Epodonios-all | 0.255 | observe | 0 | None | 7653 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| mheidari-all | 0.44 | 74 | 94 | 168 |
| DeltaKronecker-all | 0.5 | 1 | 1 | 2 |
| xiaoji235-airport-v2ray-all | 0.5 | 1 | 1 | 2 |
| tg-oneclickvpnkeys | 0.714 | 5 | 2 | 7 |
| Surfboard-tg-mixed | 0.753 | 110 | 36 | 146 |
| Au1rxx-base64 | 0.819 | 290 | 64 | 354 |
| zhangkai | 0.957 | 22 | 1 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22630 | yes | 6.2 | 0 |
| SoliSpirit-all | 8188 | yes | 3.76 | 0 |
| Epodonios-all | 7653 | yes | 1.71 | 0 |
| Surfboard-tg-mixed | 7188 | yes | 4.31 | 0 |
| xiaoji235-airport-v2ray-all | 6965 | yes | 3.4 | 0 |
| barry-far-vless | 6249 | yes | 2.56 | 0 |
| DeltaKronecker-all | 6212 | yes | 5.22 | 0 |
| Surfboard-tg-vless | 6027 | yes | 3.81 | 0 |
| 10ium-ScrapeCategorize-Vless | 4887 | yes | 2.09 | 0 |
| mahdibland-V2RayAggregator | 4087 | yes | 0.37 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| cn-block | 81 |
| 204 | 72 |
| geo | 38 |
| speed | 9 |
