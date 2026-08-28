# AutoNodes 每日报告

生成时间：2026-08-28 08:47:06

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 4/102 |
| 原始节点数 | 81032 |
| 去重后节点数 | 23362 |
| TCP 可达数 | 3000 |
| 真测通过数 | 505 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23362 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| generate | 37.5 |
| geo | 1.4 |
| probe | 54.4 |
| real_test | 124.4 |
| tcp | 39.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 24 | 24 | 0 | 100.0% |
| hysteria2 | 23 | 21 | 2 | 91.3% |
| shadowsocks | 177 | 151 | 26 | 85.3% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 29 | 26 | 3 | 89.7% |
| vless | 422 | 279 | 143 | 66.1% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 39 |
| 204:TimeoutError | 26 |
| cn-block:TimeoutError | 22 |
| geo:TimeoutError | 22 |
| speed:ClientOSError | 20 |
| speed:TimeoutError | 17 |
| 204:ProxyError | 15 |
| cn-block:ClientOSError | 8 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5265 |
| ConnectionRefusedError | 963 |
| gaierror | 431 |
| OSError | 232 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.967 | prefer | 24 | 1.0 | 144 |
| Au1rxx-base64 | 0.952 | prefer | 304 | 0.882 | 1822 |
| Surfboard-tg-mixed | 0.826 | prefer | 136 | 0.75 | 6427 |
| mheidari-all | 0.771 | prefer | 53 | 0.698 | 14456 |
| DeltaKronecker-all | 0.57 | observe | 149 | 0.49 | 4318 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 87 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4783 |
| Epodonios-all | 0.255 | observe | 0 | None | 6791 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3990 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6921 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | xiaoji235-airport-v2ray-all | 0.133 | 12 | 0.0 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 12 | 12 |
| DeltaKronecker-all | 0.49 | 73 | 76 | 149 |
| mheidari-all | 0.698 | 37 | 16 | 53 |
| Surfboard-tg-mixed | 0.75 | 102 | 34 | 136 |
| Au1rxx-base64 | 0.882 | 268 | 36 | 304 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 24 | 0 | 24 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14456 | yes | 5.4 | 0 |
| SoliSpirit-all | 6921 | yes | 4.03 | 0 |
| Epodonios-all | 6791 | yes | 4.49 | 0 |
| Surfboard-tg-mixed | 6427 | yes | 3.69 | 0 |
| barry-far-vless | 5416 | yes | 3.24 | 0 |
| Surfboard-tg-vless | 5241 | yes | 3.48 | 0 |
| 10ium-ScrapeCategorize-Vless | 4783 | yes | 3.49 | 0 |
| DeltaKronecker-all | 4318 | yes | 4.82 | 0 |
| mahdibland-V2RayAggregator | 4061 | yes | 0.77 | 0 |
| MatinGhanbari-all-sub | 3990 | yes | 3.05 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 63 |
| 204 | 43 |
| speed | 37 |
| cn-block | 33 |
