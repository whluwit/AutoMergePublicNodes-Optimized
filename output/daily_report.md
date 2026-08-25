# AutoNodes 每日报告

生成时间：2026-08-25 18:37:12

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 77879 |
| 去重后节点数 | 22524 |
| TCP 可达数 | 3000 |
| 真测通过数 | 568 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22524 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| generate | 38.3 |
| geo | 1.4 |
| probe | 52.6 |
| real_test | 111.3 |
| tcp | 36.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 22 | 22 | 0 | 100.0% |
| hysteria2 | 23 | 22 | 1 | 95.7% |
| shadowsocks | 169 | 160 | 9 | 94.7% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 37 | 31 | 6 | 83.8% |
| vless | 443 | 329 | 114 | 74.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:TimeoutError | 47 |
| geo:TimeoutError | 19 |
| 204:TimeoutError | 17 |
| cn-block:TimeoutError | 16 |
| geo:ClientOSError | 11 |
| 204:ProxyError | 8 |
| speed:ClientOSError | 6 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4853 |
| ConnectionRefusedError | 870 |
| gaierror | 385 |
| OSError | 23 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.964 | prefer | 22 | 1.0 | 144 |
| Au1rxx-base64 | 0.903 | prefer | 432 | 0.845 | 1502 |
| mheidari-all | 0.851 | prefer | 68 | 0.779 | 14446 |
| DeltaKronecker-all | 0.846 | prefer | 45 | 0.778 | 6340 |
| Surfboard-tg-mixed | 0.779 | prefer | 131 | 0.702 | 6434 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4912 |
| Epodonios-all | 0.255 | observe | 0 | None | 6936 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7007 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
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
| Surfboard-tg-mixed | 0.702 | 92 | 39 | 131 |
| DeltaKronecker-all | 0.778 | 35 | 10 | 45 |
| mheidari-all | 0.779 | 53 | 15 | 68 |
| Au1rxx-base64 | 0.845 | 365 | 67 | 432 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 22 | 0 | 22 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14446 | yes | 3.65 | 0 |
| SoliSpirit-all | 7007 | yes | 2.01 | 0 |
| Epodonios-all | 6936 | yes | 3.84 | 0 |
| Surfboard-tg-mixed | 6434 | yes | 2.84 | 0 |
| DeltaKronecker-all | 6340 | yes | 4.55 | 0 |
| barry-far-vless | 5564 | yes | 0.78 | 0 |
| Surfboard-tg-vless | 5291 | yes | 4.01 | 0 |
| 10ium-ScrapeCategorize-Vless | 4912 | yes | 0.96 | 0 |
| mahdibland-V2RayAggregator | 4119 | yes | 2.36 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.61 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 53 |
| geo | 30 |
| 204 | 27 |
| cn-block | 22 |
