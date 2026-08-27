# AutoNodes 每日报告

生成时间：2026-08-27 21:42:28

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 87070 |
| 去重后节点数 | 23515 |
| TCP 可达数 | 3000 |
| 真测通过数 | 440 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23515 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.0 |
| generate | 40.8 |
| geo | 1.4 |
| probe | 43.8 |
| real_test | 96.6 |
| tcp | 39.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 21 | 21 | 0 | 100.0% |
| hysteria2 | 24 | 22 | 2 | 91.7% |
| shadowsocks | 175 | 157 | 18 | 89.7% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 19 | 14 | 5 | 73.7% |
| vless | 290 | 221 | 69 | 76.2% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 31 |
| 204:TimeoutError | 20 |
| cn-block:TimeoutError | 14 |
| speed:ClientOSError | 8 |
| speed:TimeoutError | 7 |
| cn-block:ClientOSError | 5 |
| 204:ProxyError | 4 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 2 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5506 |
| ConnectionRefusedError | 946 |
| gaierror | 357 |
| OSError | 234 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.985 | prefer | 300 | 0.923 | 1622 |
| zhangkai | 0.964 | prefer | 22 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.807 | prefer | 130 | 0.731 | 6577 |
| mheidari-all | 0.617 | observe | 78 | 0.538 | 19755 |
| DeltaKronecker-all | 0.48 | observe | 4 | 1.0 | 4318 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4783 |
| Epodonios-all | 0.255 | observe | 0 | None | 6955 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3991 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7129 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5393 |

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

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.538 | 42 | 36 | 78 |
| Surfboard-tg-mixed | 0.731 | 95 | 35 | 130 |
| Au1rxx-base64 | 0.923 | 277 | 23 | 300 |
| DeltaKronecker-all | 1.0 | 4 | 0 | 4 |
| zhangkai | 1.0 | 22 | 0 | 22 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19755 | yes | 2.65 | 0 |
| SoliSpirit-all | 7129 | yes | 1.24 | 0 |
| Epodonios-all | 6955 | yes | 1.57 | 0 |
| Surfboard-tg-mixed | 6577 | yes | 2.14 | 0 |
| barry-far-vless | 5568 | yes | 0.67 | 0 |
| Surfboard-tg-vless | 5393 | yes | 2.75 | 0 |
| 10ium-ScrapeCategorize-Vless | 4783 | yes | 0.76 | 0 |
| DeltaKronecker-all | 4318 | yes | 2.75 | 0 |
| mahdibland-V2RayAggregator | 4019 | yes | 1.32 | 0 |
| MatinGhanbari-all-sub | 3991 | yes | 0.58 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 32 |
| 204 | 26 |
| cn-block | 22 |
| speed | 15 |
