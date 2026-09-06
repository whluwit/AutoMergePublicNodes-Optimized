# AutoNodes 每日报告

生成时间：2026-09-06 02:39:45

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 97301 |
| 去重后节点数 | 25520 |
| TCP 可达数 | 3000 |
| 真测通过数 | 639 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 25520 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| generate | 39.9 |
| geo | 1.4 |
| probe | 78.3 |
| real_test | 158.4 |
| tcp | 42.6 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 27 | 27 | 0 | 100.0% |
| hysteria2 | 27 | 25 | 2 | 92.6% |
| shadowsocks | 181 | 176 | 5 | 97.2% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 46 | 35 | 11 | 76.1% |
| vless | 814 | 370 | 444 | 45.5% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 176 |
| speed:TimeoutError | 65 |
| cn-block:ClientOSError | 64 |
| geo:ClientOSError | 63 |
| speed:ClientOSError | 39 |
| cn-block:TimeoutError | 20 |
| 204:TimeoutError | 18 |
| 204:ProxyError | 10 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:36528: bind: address already in use | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6162 |
| ConnectionRefusedError | 993 |
| gaierror | 319 |
| OSError | 231 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.986 | prefer | 308 | 0.916 | 1827 |
| zhangkai | 0.962 | prefer | 21 | 1.0 | 144 |
| Surfboard-tg-mixed | 0.91 | prefer | 210 | 0.833 | 7416 |
| tg-oneclickvpnkeys | 0.482 | observe | 6 | 1.0 | 132 |
| mheidari-all | 0.357 | observe | 546 | 0.277 | 22409 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6965 |
| DeltaKronecker-all | 0.284 | observe | 6 | 0.333 | 6212 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4887 |
| Epodonios-all | 0.255 | observe | 0 | None | 7876 |

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
| ninja-vless | 0.0 | 0 | 2 | 2 |
| mheidari-all | 0.277 | 151 | 395 | 546 |
| DeltaKronecker-all | 0.333 | 2 | 4 | 6 |
| Surfboard-tg-mixed | 0.833 | 175 | 35 | 210 |
| Au1rxx-base64 | 0.916 | 282 | 26 | 308 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 6 | 0 | 6 |
| zhangkai | 1.0 | 21 | 0 | 21 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 22409 | yes | 3.4 | 0 |
| SoliSpirit-all | 8354 | yes | 4.47 | 0 |
| Epodonios-all | 7876 | yes | 4.62 | 0 |
| Surfboard-tg-mixed | 7416 | yes | 3.89 | 0 |
| xiaoji235-airport-v2ray-all | 6965 | yes | 2.32 | 0 |
| barry-far-vless | 6398 | yes | 1.92 | 0 |
| DeltaKronecker-all | 6212 | yes | 3.55 | 0 |
| Surfboard-tg-vless | 6183 | yes | 4.04 | 0 |
| 10ium-ScrapeCategorize-Vless | 4887 | yes | 1.77 | 0 |
| mahdibland-V2RayAggregator | 4087 | yes | 1.08 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 239 |
| speed | 105 |
| cn-block | 88 |
| 204 | 30 |
| sing-box exited 1 | 1 |
