# AutoNodes 每日报告

生成时间：2026-08-26 19:45:28

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 89591 |
| 去重后节点数 | 24383 |
| TCP 可达数 | 3000 |
| 真测通过数 | 439 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24383 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| generate | 29.6 |
| geo | 1.5 |
| probe | 47.9 |
| real_test | 93.3 |
| tcp | 38.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 23 | 0 | 100.0% |
| hysteria2 | 26 | 24 | 2 | 92.3% |
| shadowsocks | 92 | 88 | 4 | 95.7% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 29 | 27 | 2 | 93.1% |
| vless | 368 | 276 | 92 | 75.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 37 |
| cn-block:TimeoutError | 14 |
| speed:TimeoutError | 13 |
| 204:TimeoutError | 11 |
| speed:ClientOSError | 10 |
| 204:ProxyError | 9 |
| geo:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| cn-block:ClientOSError | 2 |
| 204:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5010 |
| ConnectionRefusedError | 1002 |
| gaierror | 458 |
| OSError | 237 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.952 | prefer | 360 | 0.875 | 1979 |
| zhangkai | 0.922 | prefer | 22 | 0.955 | 144 |
| Surfboard-tg-mixed | 0.714 | prefer | 12 | 0.917 | 6645 |
| mheidari-all | 0.68 | observe | 133 | 0.602 | 19290 |
| DeltaKronecker-all | 0.643 | observe | 10 | 0.9 | 6107 |
| tg-oneclickvpnkeys | 0.32 | observe | 2 | 1.0 | 218 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4825 |
| Epodonios-all | 0.255 | observe | 0 | None | 7011 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |

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
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.602 | 80 | 53 | 133 |
| Au1rxx-base64 | 0.875 | 315 | 45 | 360 |
| DeltaKronecker-all | 0.9 | 9 | 1 | 10 |
| Surfboard-tg-mixed | 0.917 | 11 | 1 | 12 |
| zhangkai | 0.955 | 21 | 1 | 22 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 19290 | yes | 5.35 | 0 |
| SoliSpirit-all | 7313 | yes | 3.95 | 0 |
| Epodonios-all | 7011 | yes | 1.49 | 0 |
| Surfboard-tg-mixed | 6645 | yes | 4.83 | 0 |
| DeltaKronecker-all | 6107 | yes | 5.2 | 0 |
| barry-far-vless | 5698 | yes | 2.04 | 0 |
| Surfboard-tg-vless | 5444 | yes | 4.57 | 0 |
| xiaoji235-airport-v2ray-all | 5418 | yes | 2.7 | 0 |
| 10ium-ScrapeCategorize-Vless | 4825 | yes | 2.88 | 0 |
| mahdibland-V2RayAggregator | 4011 | yes | 0.51 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 41 |
| speed | 23 |
| 204 | 21 |
| cn-block | 18 |
