# AutoNodes 每日报告

生成时间：2026-08-11 12:57:25

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 101/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 84076 |
| 去重后节点数 | 24347 |
| TCP 可达数 | 3000 |
| 真测通过数 | 535 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 24347 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| generate | 38.0 |
| geo | 1.4 |
| probe | 48.2 |
| real_test | 129.2 |
| tcp | 36.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 128 | 128 | 0 | 100.0% |
| hysteria2 | 17 | 14 | 3 | 82.4% |
| shadowsocks | 154 | 139 | 15 | 90.3% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 138 | 129 | 9 | 93.5% |
| vless | 188 | 121 | 67 | 64.4% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:TimeoutError | 26 |
| 204:ProxyError | 14 |
| geo:ClientOSError | 13 |
| 204:TimeoutError | 11 |
| speed:ClientOSError | 11 |
| cn-block:TimeoutError | 7 |
| geo:TimeoutError | 6 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4394 |
| ConnectionRefusedError | 819 |
| gaierror | 345 |
| OSError | 229 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.999 | prefer | 128 | 1.0 | 159 |
| Au1rxx-base64 | 0.904 | prefer | 393 | 0.847 | 1449 |
| DeltaKronecker-all | 0.745 | prefer | 17 | 0.765 | 5522 |
| Surfboard-tg-mixed | 0.743 | prefer | 81 | 0.667 | 6149 |
| mheidari-all | 0.474 | observe | 10 | 0.6 | 20194 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5419 |
| Epodonios-all | 0.255 | observe | 0 | None | 6769 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7316 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| xiaoji235-airport-v2ray-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.6 | 6 | 4 | 10 |
| Surfboard-tg-mixed | 0.667 | 54 | 27 | 81 |
| DeltaKronecker-all | 0.765 | 13 | 4 | 17 |
| Au1rxx-base64 | 0.847 | 333 | 60 | 393 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 128 | 0 | 128 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 20194 | yes | 3.56 | 0 |
| SoliSpirit-all | 7316 | yes | 2.42 | 0 |
| Epodonios-all | 6769 | yes | 1.93 | 0 |
| Surfboard-tg-mixed | 6149 | yes | 2.77 | 0 |
| DeltaKronecker-all | 5522 | yes | 3.7 | 0 |
| 10ium-ScrapeCategorize-Vless | 5419 | yes | 1.66 | 0 |
| barry-far-vless | 5245 | yes | 1.3 | 0 |
| mahdibland-V2RayAggregator | 5209 | yes | 1.8 | 0 |
| Surfboard-tg-vless | 4944 | yes | 2.45 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 2.18 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 37 |
| 204 | 29 |
| geo | 20 |
| cn-block | 10 |
