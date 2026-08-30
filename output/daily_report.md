# AutoNodes 每日报告

生成时间：2026-08-30 15:59:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 95/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 79852 |
| 去重后节点数 | 21843 |
| TCP 可达数 | 3000 |
| 真测通过数 | 580 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21843 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| generate | 29.3 |
| geo | 1.4 |
| probe | 54.4 |
| real_test | 114.0 |
| tcp | 35.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 24 | 23 | 1 | 95.8% |
| hysteria2 | 18 | 16 | 2 | 88.9% |
| shadowsocks | 151 | 134 | 17 | 88.7% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 18 | 17 | 1 | 94.4% |
| vless | 453 | 386 | 67 | 85.2% |
| vmess | 4 | 3 | 1 | 75.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 19 |
| cn-block:TimeoutError | 18 |
| geo:ClientOSError | 16 |
| geo:TimeoutError | 8 |
| 204:ProxyError | 7 |
| speed:ClientOSError | 7 |
| cn-block:ProxyError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 3 |
| speed:TimeoutError | 2 |
| speed:ClientPayloadError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4909 |
| ConnectionRefusedError | 896 |
| gaierror | 261 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 1.0 | prefer | 333 | 0.955 | 1804 |
| zhangkai | 0.964 | prefer | 22 | 1.0 | 144 |
| DeltaKronecker-all | 0.847 | prefer | 131 | 0.771 | 5576 |
| Surfboard-tg-mixed | 0.831 | prefer | 171 | 0.754 | 7004 |
| mheidari-all | 0.643 | observe | 10 | 0.9 | 15115 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4762 |
| Epodonios-all | 0.255 | observe | 0 | None | 7409 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7533 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5872 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.5 | 1 | 1 | 2 |
| Surfboard-tg-mixed | 0.754 | 129 | 42 | 171 |
| DeltaKronecker-all | 0.771 | 101 | 30 | 131 |
| mheidari-all | 0.9 | 9 | 1 | 10 |
| Au1rxx-base64 | 0.955 | 318 | 15 | 333 |
| zhangkai | 1.0 | 22 | 0 | 22 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 15115 | yes | 3.19 | 0 |
| SoliSpirit-all | 7533 | yes | 4.09 | 0 |
| Epodonios-all | 7409 | yes | 3.41 | 0 |
| Surfboard-tg-mixed | 7004 | yes | 1.06 | 0 |
| barry-far-vless | 6056 | yes | 1.64 | 0 |
| Surfboard-tg-vless | 5872 | yes | 2.67 | 0 |
| DeltaKronecker-all | 5576 | yes | 3.45 | 0 |
| 10ium-ScrapeCategorize-Vless | 4762 | yes | 2.66 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 2.51 | 0 |
| mahdibland-V2RayAggregator | 3949 | yes | 1.12 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 30 |
| cn-block | 26 |
| geo | 25 |
| speed | 10 |
