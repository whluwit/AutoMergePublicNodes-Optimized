# AutoNodes 每日报告

生成时间：2026-08-26 12:45:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 5/102 |
| 原始节点数 | 78614 |
| 去重后节点数 | 22194 |
| TCP 可达数 | 3000 |
| 真测通过数 | 520 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22194 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| generate | 39.9 |
| geo | 1.5 |
| probe | 52.6 |
| real_test | 113.0 |
| tcp | 34.9 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 25 | 25 | 0 | 100.0% |
| hysteria2 | 29 | 26 | 3 | 89.7% |
| shadowsocks | 172 | 158 | 14 | 91.9% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 33 | 30 | 3 | 90.9% |
| vless | 356 | 278 | 78 | 78.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| speed:TimeoutError | 32 |
| cn-block:TimeoutError | 16 |
| 204:TimeoutError | 13 |
| 204:ProxyError | 9 |
| speed:ClientOSError | 8 |
| geo:ClientOSError | 6 |
| 204:ClientOSError | 3 |
| geo:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 2 |
| cn-block:ClientOSError | 2 |
| geo:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:37154: bind: address already in use | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4285 |
| ConnectionRefusedError | 864 |
| gaierror | 444 |
| OSError | 30 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 1.0 | prefer | 29 | 1.0 | 14222 |
| Au1rxx-base64 | 0.976 | prefer | 327 | 0.899 | 1988 |
| zhangkai | 0.966 | prefer | 23 | 1.0 | 144 |
| DeltaKronecker-all | 0.92 | prefer | 48 | 0.854 | 6107 |
| Surfboard-tg-mixed | 0.761 | prefer | 183 | 0.683 | 6518 |
| nscl5-all | 0.475 | observe | 5 | 1.0 | 887 |
| tg-oneclickvpnkeys | 0.319 | observe | 2 | 1.0 | 206 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4825 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1992 |

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
| Surfboard-tg-mixed | 0.683 | 125 | 58 | 183 |
| DeltaKronecker-all | 0.854 | 41 | 7 | 48 |
| Au1rxx-base64 | 0.899 | 294 | 33 | 327 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |
| nscl5-all | 1.0 | 5 | 0 | 5 |
| zhangkai | 1.0 | 23 | 0 | 23 |
| mheidari-all | 1.0 | 29 | 0 | 29 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14222 | yes | 5.61 | 0 |
| SoliSpirit-all | 7145 | yes | 4.31 | 0 |
| Epodonios-all | 7010 | yes | 0.68 | 0 |
| Surfboard-tg-mixed | 6518 | yes | 3.91 | 0 |
| DeltaKronecker-all | 6107 | yes | 5.14 | 0 |
| barry-far-vless | 5628 | yes | 2.72 | 0 |
| Surfboard-tg-vless | 5376 | yes | 5.01 | 0 |
| 10ium-ScrapeCategorize-Vless | 4825 | yes | 3.75 | 0 |
| MatinGhanbari-all-sub | 3988 | yes | 3.58 | 0 |
| mahdibland-V2RayAggregator | 3981 | yes | 3.52 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| speed | 42 |
| 204 | 25 |
| cn-block | 20 |
| geo | 11 |
| sing-box exited 1 | 1 |
