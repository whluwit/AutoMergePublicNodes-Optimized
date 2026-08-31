# AutoNodes 每日报告

生成时间：2026-08-31 03:14:16

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 79054 |
| 去重后节点数 | 21836 |
| TCP 可达数 | 3000 |
| 真测通过数 | 692 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21836 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| generate | 32.1 |
| geo | 1.5 |
| probe | 59.0 |
| real_test | 153.7 |
| tcp | 35.5 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 24 | 23 | 1 | 95.8% |
| hysteria2 | 16 | 16 | 0 | 100.0% |
| shadowsocks | 158 | 150 | 8 | 94.9% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 47 | 36 | 11 | 76.6% |
| vless | 711 | 461 | 250 | 64.8% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 100 |
| geo:ClientOSError | 50 |
| cn-block:TimeoutError | 29 |
| speed:TimeoutError | 23 |
| 204:TimeoutError | 21 |
| speed:ClientOSError | 20 |
| 204:ProxyError | 15 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 4 |
| cn-block:ClientOSError | 2 |
| speed:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4920 |
| ConnectionRefusedError | 856 |
| gaierror | 329 |
| OSError | 19 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.985 | prefer | 320 | 0.916 | 1804 |
| zhangkai | 0.967 | prefer | 24 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.874 | prefer | 216 | 0.796 | 6864 |
| mheidari-all | 0.734 | prefer | 18 | 0.722 | 14559 |
| DeltaKronecker-all | 0.576 | observe | 379 | 0.496 | 5576 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| Epodonios-all | 0.255 | observe | 0 | None | 7271 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7626 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.496 | 188 | 191 | 379 |
| mheidari-all | 0.722 | 13 | 5 | 18 |
| Surfboard-tg-mixed | 0.796 | 172 | 44 | 216 |
| Au1rxx-base64 | 0.916 | 293 | 27 | 320 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14559 | yes | 4.45 | 0 |
| SoliSpirit-all | 7626 | yes | 4.81 | 0 |
| Epodonios-all | 7271 | yes | 3.08 | 0 |
| Surfboard-tg-mixed | 6864 | yes | 3.35 | 0 |
| barry-far-vless | 5957 | yes | 2.34 | 0 |
| Surfboard-tg-vless | 5770 | yes | 3.86 | 0 |
| DeltaKronecker-all | 5576 | yes | 4.31 | 0 |
| 10ium-ScrapeCategorize-Vless | 4762 | yes | 2.82 | 0 |
| mahdibland-V2RayAggregator | 4041 | yes | 1.36 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.44 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 151 |
| speed | 45 |
| 204 | 40 |
| cn-block | 35 |
