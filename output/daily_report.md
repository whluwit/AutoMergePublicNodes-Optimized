# AutoNodes 每日报告

生成时间：2026-08-25 01:04:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/1 |
| 清理建议：优先/观察 | 3/103 |
| 原始节点数 | 83622 |
| 去重后节点数 | 23844 |
| TCP 可达数 | 3000 |
| 真测通过数 | 691 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23844 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.7 |
| generate | 36.6 |
| geo | 1.4 |
| probe | 58.1 |
| real_test | 164.7 |
| tcp | 38.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 21 | 21 | 0 | 100.0% |
| hysteria2 | 23 | 23 | 0 | 100.0% |
| shadowsocks | 220 | 206 | 14 | 93.6% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 43 | 34 | 9 | 79.1% |
| vless | 855 | 401 | 454 | 46.9% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 190 |
| geo:ClientOSError | 92 |
| speed:TimeoutError | 91 |
| speed:ClientOSError | 42 |
| cn-block:TimeoutError | 23 |
| 204:ProxyError | 11 |
| 204:ClientOSError | 10 |
| 204:TimeoutError | 9 |
| cn-block:ClientOSError | 5 |
| 204:ServerDisconnectedError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5290 |
| ConnectionRefusedError | 887 |
| gaierror | 288 |
| OSError | 229 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.966 | prefer | 450 | 0.896 | 1799 |
| zhangkai | 0.964 | prefer | 22 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.864 | prefer | 197 | 0.787 | 6570 |
| mheidari-all | 0.316 | observe | 455 | 0.235 | 19487 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4899 |
| Epodonios-all | 0.255 | observe | 0 | None | 7074 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3988 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7045 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5352 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Parsashonam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| downweight | DeltaKronecker-all | 0.169 | 43 | 0.07 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.07 | 3 | 40 | 43 |
| mheidari-all | 0.235 | 107 | 348 | 455 |
| Surfboard-tg-mixed | 0.787 | 155 | 42 | 197 |
| Au1rxx-base64 | 0.896 | 403 | 47 | 450 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 22 | 0 | 22 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19487 | yes | 4.55 | 0 |
| Epodonios-all | 7074 | yes | 5.06 | 0 |
| SoliSpirit-all | 7045 | yes | 2.88 | 0 |
| Surfboard-tg-mixed | 6570 | yes | 3.3 | 0 |
| DeltaKronecker-all | 5914 | yes | 4.55 | 0 |
| barry-far-vless | 5640 | yes | 2.59 | 0 |
| Surfboard-tg-vless | 5352 | yes | 3.12 | 0 |
| 10ium-ScrapeCategorize-Vless | 4899 | yes | 2.31 | 0 |
| mahdibland-V2RayAggregator | 4132 | yes | 1.24 | 0 |
| MatinGhanbari-all-sub | 3988 | yes | 2.42 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 283 |
| speed | 134 |
| 204 | 32 |
| cn-block | 29 |
