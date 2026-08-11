# AutoNodes 每日报告

生成时间：2026-08-11 01:23:06

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 85331 |
| 去重后节点数 | 24694 |
| TCP 可达数 | 3000 |
| 真测通过数 | 574 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24694 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| generate | 28.1 |
| geo | 1.4 |
| probe | 64.1 |
| real_test | 163.7 |
| tcp | 37.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 49 | 49 | 0 | 100.0% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 161 | 151 | 10 | 93.8% |
| socks | 10 | 8 | 2 | 80.0% |
| trojan | 155 | 136 | 19 | 87.7% |
| vless | 744 | 211 | 533 | 28.4% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 202 |
| speed:ClientOSError | 108 |
| 204:ProxyError | 85 |
| geo:ClientOSError | 74 |
| speed:TimeoutError | 40 |
| cn-block:TimeoutError | 23 |
| cn-block:ProxyError | 13 |
| 204:TimeoutError | 12 |
| geo:ProxyError | 3 |
| cn-block:ClientOSError | 2 |
| speed:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4759 |
| ConnectionRefusedError | 817 |
| gaierror | 283 |
| OSError | 227 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.964 | prefer | 50 | 0.98 | 67 |
| Surfboard-tg-mixed | 0.955 | prefer | 19 | 0.947 | 6306 |
| Au1rxx-base64 | 0.949 | prefer | 392 | 0.893 | 1464 |
| DeltaKronecker-all | 0.314 | observe | 631 | 0.233 | 5881 |
| mheidari-all | 0.307 | observe | 42 | 0.214 | 20211 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5327 |
| Epodonios-all | 0.255 | observe | 0 | None | 6946 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7525 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.214 | 9 | 33 | 42 |
| DeltaKronecker-all | 0.233 | 147 | 484 | 631 |
| Au1rxx-base64 | 0.893 | 350 | 42 | 392 |
| Surfboard-tg-mixed | 0.947 | 18 | 1 | 19 |
| zhangkai | 0.98 | 49 | 1 | 50 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20211 | yes | 5.02 | 0 |
| SoliSpirit-all | 7525 | yes | 1.68 | 0 |
| Epodonios-all | 6946 | yes | 2.49 | 0 |
| Surfboard-tg-mixed | 6306 | yes | 3.89 | 0 |
| DeltaKronecker-all | 5881 | yes | 3.26 | 0 |
| barry-far-vless | 5506 | yes | 1.88 | 0 |
| 10ium-ScrapeCategorize-Vless | 5327 | yes | 1.42 | 0 |
| mahdibland-V2RayAggregator | 5191 | yes | 3.32 | 0 |
| Surfboard-tg-vless | 5176 | yes | 3.48 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.22 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 279 |
| speed | 150 |
| 204 | 97 |
| cn-block | 38 |
