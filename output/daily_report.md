# AutoNodes 每日报告

生成时间：2026-09-08 02:52:05

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 97/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 91466 |
| 去重后节点数 | 25342 |
| TCP 可达数 | 3000 |
| 真测通过数 | 715 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25342 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| generate | 43.1 |
| geo | 1.7 |
| probe | 94.6 |
| real_test | 205.5 |
| tcp | 41.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 58 | 58 | 0 | 100.0% |
| hysteria2 | 22 | 22 | 0 | 100.0% |
| shadowsocks | 191 | 180 | 11 | 94.2% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 71 | 39 | 32 | 54.9% |
| vless | 979 | 411 | 568 | 42.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 198 |
| speed:TimeoutError | 96 |
| speed:ClientOSError | 95 |
| geo:ClientOSError | 92 |
| cn-block:ClientOSError | 73 |
| cn-block:TimeoutError | 21 |
| 204:TimeoutError | 12 |
| 204:ProxyError | 12 |
| 204:ClientOSError | 9 |
| cn-block:ProxyError | 1 |
| 204:ServerDisconnectedError | 1 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5894 |
| ConnectionRefusedError | 959 |
| gaierror | 359 |
| OSError | 235 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.995 | prefer | 41 | 1.0 | 450 |
| Au1rxx-base64 | 0.951 | prefer | 375 | 0.88 | 1834 |
| Surfboard-tg-mixed | 0.924 | prefer | 94 | 0.851 | 7423 |
| ermaozi-get_subscribe | 0.907 | prefer | 18 | 1.0 | 470 |
| DeltaKronecker-all | 0.495 | observe | 80 | 0.412 | 6417 |
| mheidari-all | 0.377 | observe | 714 | 0.297 | 22287 |
| tg-oneclickvpnkeys | 0.263 | observe | 1 | 1.0 | 196 |
| Epodonios-all | 0.255 | observe | 0 | None | 7885 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 8454 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| mfuu-v2ray | 0.025 | observe | 0 | None | 1 | 0 |
| nscl5-all | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
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
| 10ium-ScrapeCategorize-Vless | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.297 | 212 | 502 | 714 |
| DeltaKronecker-all | 0.412 | 33 | 47 | 80 |
| Surfboard-tg-mixed | 0.851 | 80 | 14 | 94 |
| Au1rxx-base64 | 0.88 | 330 | 45 | 375 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 18 | 0 | 18 |
| ermaozi | 1.0 | 41 | 0 | 41 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22287 | yes | 5.88 | 0 |
| SoliSpirit-all | 8454 | yes | 3.0 | 0 |
| Epodonios-all | 7885 | yes | 3.79 | 0 |
| Surfboard-tg-mixed | 7423 | yes | 4.7 | 0 |
| barry-far-vless | 6444 | yes | 2.16 | 0 |
| DeltaKronecker-all | 6417 | yes | 6.65 | 0 |
| Surfboard-tg-vless | 6226 | yes | 4.08 | 0 |
| xiaoji235-airport-v2ray-all | 5750 | yes | 3.97 | 0 |
| 10ium-ScrapeCategorize-Vless | 4650 | yes | 2.67 | 0 |
| mahdibland-V2RayAggregator | 4218 | yes | 1.66 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 291 |
| speed | 192 |
| cn-block | 95 |
| 204 | 34 |
