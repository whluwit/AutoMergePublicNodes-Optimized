# AutoNodes 每日报告

生成时间：2026-08-25 06:42:27

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 96/107 |
| 清理建议：禁用/降权 | 0/0 |
| 清理建议：优先/观察 | 3/104 |
| 原始节点数 | 78216 |
| 去重后节点数 | 22272 |
| TCP 可达数 | 3000 |
| 真测通过数 | 635 |
| verified 输出数 | 300 |
| global 输出数 | 300 |
| all 输出数 | 22272 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.9 |
| generate | 46.2 |
| geo | 1.4 |
| probe | 56.3 |
| real_test | 123.1 |
| tcp | 35.3 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 22 | 22 | 0 | 100.0% |
| hysteria2 | 21 | 21 | 0 | 100.0% |
| shadowsocks | 218 | 204 | 14 | 93.6% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 44 | 37 | 7 | 84.1% |
| vless | 504 | 347 | 157 | 68.8% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:TimeoutError | 63 |
| 204:TimeoutError | 31 |
| speed:TimeoutError | 24 |
| speed:ClientOSError | 18 |
| geo:ClientOSError | 15 |
| cn-block:TimeoutError | 12 |
| 204:ProxyError | 6 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound/socks[socks-in]: listen tcp 127.0.0.1:33531: bind: address already in use | 1 |
| geo:parse | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 4666 |
| ConnectionRefusedError | 802 |
| gaierror | 337 |
| OSError | 17 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.964 | prefer | 22 | 1.0 | 144 |
| Au1rxx-base64 | 0.929 | prefer | 501 | 0.862 | 1700 |
| Surfboard-tg-mixed | 0.805 | prefer | 136 | 0.728 | 6406 |
| DeltaKronecker-all | 0.604 | observe | 82 | 0.524 | 6340 |
| mheidari-all | 0.602 | observe | 65 | 0.523 | 14480 |
| roosterkid-openproxylist-v2ray | 0.406 | observe | 4 | 1.0 | 150 |
| 10ium-ScrapeCategorize-Vless | 0.335 | observe | 1 | 1.0 | 4912 |
| Epodonios-all | 0.255 | observe | 0 | None | 6925 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3987 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 6957 |

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
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| 10ium-HighSpeed | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.523 | 34 | 31 | 65 |
| DeltaKronecker-all | 0.524 | 43 | 39 | 82 |
| Surfboard-tg-mixed | 0.728 | 99 | 37 | 136 |
| Au1rxx-base64 | 0.862 | 432 | 69 | 501 |
| 10ium-ScrapeCategorize-Vless | 1.0 | 1 | 0 | 1 |
| roosterkid-openproxylist-v2ray | 1.0 | 4 | 0 | 4 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 14480 | yes | 4.27 | 0 |
| SoliSpirit-all | 6957 | yes | 3.07 | 0 |
| Epodonios-all | 6925 | yes | 4.48 | 0 |
| Surfboard-tg-mixed | 6406 | yes | 3.33 | 0 |
| DeltaKronecker-all | 6340 | yes | 5.2 | 0 |
| barry-far-vless | 5525 | yes | 1.87 | 0 |
| Surfboard-tg-vless | 5245 | yes | 4.73 | 0 |
| 10ium-ScrapeCategorize-Vless | 4912 | yes | 1.68 | 0 |
| mahdibland-V2RayAggregator | 4119 | yes | 0.21 | 0 |
| MatinGhanbari-all-sub | 3987 | yes | 1.45 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 79 |
| speed | 42 |
| 204 | 39 |
| cn-block | 19 |
| sing-box exited 1 | 1 |
