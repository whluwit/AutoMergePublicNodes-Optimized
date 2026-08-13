# AutoNodes 每日报告

生成时间：2026-08-13 19:02:43

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 80477 |
| 去重后节点数 | 22570 |
| TCP 可达数 | 3000 |
| 真测通过数 | 850 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22570 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| generate | 40.4 |
| geo | 1.5 |
| probe | 67.8 |
| real_test | 181.5 |
| tcp | 34.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 21 | 21 | 0 | 100.0% |
| shadowsocks | 149 | 136 | 13 | 91.3% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 327 | 325 | 2 | 99.4% |
| vless | 317 | 235 | 82 | 74.1% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 27 |
| geo:TimeoutError | 16 |
| cn-block:TimeoutError | 13 |
| geo:ClientOSError | 9 |
| 204:ClientOSError | 8 |
| 204:ProxyError | 7 |
| speed:ClientOSError | 6 |
| cn-block:ClientOSError | 5 |
| speed:TimeoutError | 4 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4439 |
| ConnectionRefusedError | 786 |
| gaierror | 289 |
| OSError | 22 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | prefer | 128 | 1.0 | 159 |
| Au1rxx-base64 | 0.975 | prefer | 618 | 0.911 | 1639 |
| mheidari-all | 0.883 | prefer | 115 | 0.809 | 16814 |
| Surfboard-tg-mixed | 0.821 | prefer | 56 | 0.75 | 6036 |
| DeltaKronecker-all | 0.734 | prefer | 24 | 0.667 | 4878 |
| ninja-vless | 0.56 | observe | 8 | 0.875 | 1791 |
| roosterkid-openproxylist-v2ray | 0.261 | observe | 1 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5203 |
| Epodonios-all | 0.255 | observe | 0 | None | 6692 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| abc-configs-readme-latest30 | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.667 | 16 | 8 | 24 |
| Surfboard-tg-mixed | 0.75 | 42 | 14 | 56 |
| mheidari-all | 0.809 | 93 | 22 | 115 |
| ninja-vless | 0.875 | 7 | 1 | 8 |
| Au1rxx-base64 | 0.911 | 563 | 55 | 618 |
| roosterkid-openproxylist-v2ray | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 128 | 0 | 128 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 16814 | yes | 3.8 | 0 |
| SoliSpirit-all | 7892 | yes | 4.01 | 0 |
| Epodonios-all | 6692 | yes | 5.53 | 0 |
| Surfboard-tg-mixed | 6036 | yes | 4.28 | 0 |
| 10ium-ScrapeCategorize-Vless | 5203 | yes | 3.16 | 0 |
| mahdibland-V2RayAggregator | 5197 | yes | 2.9 | 0 |
| barry-far-vless | 5103 | yes | 2.25 | 0 |
| DeltaKronecker-all | 4878 | yes | 4.43 | 0 |
| Surfboard-tg-vless | 4739 | yes | 4.44 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.38 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 42 |
| geo | 26 |
| cn-block | 20 |
| speed | 12 |
