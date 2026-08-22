# AutoNodes 每日报告

生成时间：2026-08-22 18:27:01

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 99/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 4/103 |
| 原始节点数 | 86107 |
| 去重后节点数 | 23819 |
| TCP 可达数 | 3000 |
| 真测通过数 | 730 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 23819 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.2 |
| generate | 35.9 |
| geo | 1.5 |
| probe | 61.9 |
| real_test | 153.3 |
| tcp | 40.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 114 | 114 | 0 | 100.0% |
| hysteria2 | 21 | 20 | 1 | 95.2% |
| shadowsocks | 164 | 145 | 19 | 88.4% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 173 | 164 | 9 | 94.8% |
| vless | 369 | 285 | 84 | 77.2% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:TimeoutError | 28 |
| cn-block:TimeoutError | 28 |
| geo:TimeoutError | 18 |
| geo:ClientOSError | 11 |
| 204:ProxyError | 8 |
| speed:ClientOSError | 6 |
| cn-block:ClientOSError | 6 |
| speed:TimeoutError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:48638: bind: address already in use | 1 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 5132 |
| ConnectionRefusedError | 1023 |
| gaierror | 678 |
| OSError | 230 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.997 | prefer | 113 | 1.0 | 144 |
| Au1rxx-base64 | 0.99 | prefer | 499 | 0.918 | 1853 |
| mheidari-all | 0.865 | prefer | 77 | 0.792 | 14443 |
| Surfboard-tg-mixed | 0.751 | prefer | 138 | 0.674 | 6394 |
| tg-oneclickvpnkeys | 0.318 | observe | 2 | 1.0 | 176 |
| DeltaKronecker-all | 0.291 | observe | 12 | 0.25 | 5015 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5096 |
| Epodonios-all | 0.255 | observe | 0 | None | 6973 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3990 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 7145 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| abc-configs-readme-latest30 | 0.025 | observe | 0 | None | 1 | 0 |
| snakem982 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-An0nymousTeam | 0.025 | observe | 0 | None | 1 | 0 |
| tg-Letiranbreath | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2rayngVpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-abc_configs | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ernoxin_shop | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-OutlineReleasedKey | 0.13 | observe | 1 | 0.0 | 0 | 58 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-OutlineReleasedKey | 0.0 | 0 | 1 | 1 |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 2 | 2 |
| DeltaKronecker-all | 0.25 | 3 | 9 | 12 |
| Surfboard-tg-mixed | 0.674 | 93 | 45 | 138 |
| mheidari-all | 0.792 | 61 | 16 | 77 |
| Au1rxx-base64 | 0.918 | 458 | 41 | 499 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 113 | 0 | 113 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14443 | yes | 3.86 | 0 |
| SoliSpirit-all | 7145 | yes | 3.36 | 0 |
| Epodonios-all | 6973 | yes | 3.52 | 0 |
| Surfboard-tg-mixed | 6394 | yes | 2.75 | 0 |
| xiaoji235-airport-v2ray-all | 5974 | yes | 3.99 | 0 |
| barry-far-vless | 5527 | yes | 2.3 | 0 |
| Surfboard-tg-vless | 5216 | yes | 2.89 | 0 |
| 10ium-ScrapeCategorize-Vless | 5096 | yes | 2.58 | 0 |
| DeltaKronecker-all | 5015 | yes | 3.61 | 0 |
| mahdibland-V2RayAggregator | 4074 | yes | 1.94 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 39 |
| cn-block | 35 |
| geo | 30 |
| speed | 11 |
| sing-box exited 1 | 1 |
