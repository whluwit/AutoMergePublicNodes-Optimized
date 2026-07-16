# AutoNodes 每日报告

生成时间：2026-07-16 08:08:48

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 79016 |
| 去重后节点数 | 24361 |
| TCP 可达数 | 3000 |
| 真测通过数 | 464 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24361 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| generate | 26.1 |
| geo | 1.4 |
| probe | 48.2 |
| real_test | 104.1 |
| tcp | 32.8 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 36 | 36 | 0 | 100.0% |
| hysteria2 | 2 | 2 | 0 | 100.0% |
| shadowsocks | 101 | 90 | 11 | 89.1% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 345 | 312 | 33 | 90.4% |
| vless | 146 | 18 | 128 | 12.3% |
| vmess | 5 | 5 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 63 |
| speed:ClientOSError | 47 |
| geo:ClientOSError | 12 |
| speed:TimeoutError | 10 |
| 204:ProxyError | 9 |
| cn-block:TimeoutError | 8 |
| 204:ClientOSError | 8 |
| cn-block:ProxyError | 5 |
| 204:TimeoutError | 4 |
| cn-block:ClientOSError | 4 |
| geo:ProxyError | 2 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4499 |
| ConnectionRefusedError | 653 |
| gaierror | 242 |
| OSError | 216 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.976 | prefer | 36 | 1.0 | 61 |
| Au1rxx-base64 | 0.95 | prefer | 105 | 0.952 | 149 |
| DeltaKronecker-all | 0.82 | prefer | 310 | 0.742 | 8462 |
| Surfboard-tg-mixed | 0.635 | observe | 162 | 0.556 | 5384 |
| mheidari-all | 0.356 | observe | 19 | 0.263 | 16776 |
| xiaoji235-airport-v2ray-all | 0.325 | observe | 1 | 1.0 | 1757 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4470 |
| Epodonios-all | 0.255 | observe | 0 | None | 6507 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-AzadNet | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-v2raying | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.263 | 5 | 14 | 19 |
| Surfboard-tg-mixed | 0.556 | 90 | 72 | 162 |
| DeltaKronecker-all | 0.742 | 230 | 80 | 310 |
| Au1rxx-base64 | 0.952 | 100 | 5 | 105 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| snakem982 | 1.0 | 36 | 0 | 36 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16776 | yes | 3.82 | 0 |
| DeltaKronecker-all | 8462 | yes | 4.12 | 0 |
| SoliSpirit-all | 6804 | yes | 2.62 | 0 |
| Epodonios-all | 6507 | yes | 0.34 | 0 |
| Surfboard-tg-mixed | 5384 | yes | 3.28 | 0 |
| mahdibland-V2RayAggregator | 5262 | yes | 1.95 | 0 |
| barry-far-vless | 4742 | yes | 1.08 | 0 |
| 10ium-ScrapeCategorize-Vless | 4470 | yes | 0.84 | 0 |
| Surfboard-tg-vless | 4135 | yes | 3.1 | 0 |
| MatinGhanbari-all-sub | 3971 | yes | 1.16 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 77 |
| speed | 58 |
| 204 | 21 |
| cn-block | 17 |
