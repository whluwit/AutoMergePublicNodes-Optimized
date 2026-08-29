# AutoNodes 每日报告

生成时间：2026-08-29 20:23:49

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 79278 |
| 去重后节点数 | 21317 |
| TCP 可达数 | 3000 |
| 真测通过数 | 568 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 21317 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| generate | 39.9 |
| geo | 1.4 |
| probe | 57.2 |
| real_test | 120.9 |
| tcp | 35.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 26 | 26 | 0 | 100.0% |
| hysteria2 | 22 | 19 | 3 | 86.4% |
| shadowsocks | 166 | 154 | 12 | 92.8% |
| socks | 8 | 6 | 2 | 75.0% |
| trojan | 22 | 17 | 5 | 77.3% |
| vless | 420 | 343 | 77 | 81.7% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 25 |
| cn-block:TimeoutError | 21 |
| geo:ClientOSError | 14 |
| 204:ProxyError | 9 |
| speed:TimeoutError | 9 |
| geo:TimeoutError | 7 |
| cn-block:ClientOSError | 5 |
| speed:ClientOSError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4925 |
| ConnectionRefusedError | 857 |
| gaierror | 322 |
| OSError | 21 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.983 | prefer | 353 | 0.915 | 1756 |
| DeltaKronecker-all | 0.937 | prefer | 26 | 0.885 | 4926 |
| zhangkai | 0.929 | prefer | 24 | 0.958 | 144 |
| Surfboard-tg-mixed | 0.838 | prefer | 159 | 0.761 | 6924 |
| mheidari-all | 0.825 | prefer | 100 | 0.75 | 14908 |
| tg-oneclickvpnkeys | 0.364 | observe | 3 | 1.0 | 155 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4635 |
| Epodonios-all | 0.255 | observe | 0 | None | 7291 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7802 |

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
| nscl5-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.75 | 75 | 25 | 100 |
| Surfboard-tg-mixed | 0.761 | 121 | 38 | 159 |
| DeltaKronecker-all | 0.885 | 23 | 3 | 26 |
| Au1rxx-base64 | 0.915 | 323 | 30 | 353 |
| zhangkai | 0.958 | 23 | 1 | 24 |
| tg-oneclickvpnkeys | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14908 | yes | 3.87 | 0 |
| SoliSpirit-all | 7802 | yes | 4.4 | 0 |
| Epodonios-all | 7291 | yes | 3.33 | 0 |
| Surfboard-tg-mixed | 6924 | yes | 4.86 | 0 |
| barry-far-vless | 5901 | yes | 2.81 | 0 |
| Surfboard-tg-vless | 5706 | yes | 4.49 | 0 |
| DeltaKronecker-all | 4926 | yes | 6.03 | 0 |
| 10ium-ScrapeCategorize-Vless | 4635 | yes | 2.6 | 0 |
| mahdibland-V2RayAggregator | 4012 | yes | 3.11 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 3.09 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 37 |
| cn-block | 28 |
| geo | 21 |
| speed | 13 |
