# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.2.0 |
| 更新时间 | 2026-06-11 23:53:59 |
| 运行耗时 | 202.1s |
| 订阅源总数 | 44 |
| 健康订阅源 | 44 |
| 原始节点 | 39955 |
| 去重后节点 | 15027 |
| TCP 可达 | 1500 |
| 真实可用 | 280 |
| Verified 输出 | 280 |
| Global 输出 | 284 |
| All 输出 | 15027 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.0 |
| geo | 1.2 |
| tcp | 35.8 |
| real_test | 136.9 |
| generate | 25.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 20391 |
| shadowsocks | 7985 |
| trojan | 6037 |
| vmess | 5130 |
| hysteria2 | 184 |
| shadowsocksr | 90 |
| http | 86 |
| socks | 41 |
| hysteria | 6 |
| anytls | 4 |
| tuic | 1 |

## Top 节点评分

| 评分 | 协议 | 延迟(ms) | 抖动(ms) | 来源 | 服务器 |
| --- | --- | --- | --- | --- | --- |
| 57.46 | shadowsocks | 445.2 | 195.9 | Au1rxx-base64 | 149.22.87.241 |
| 56.9 | shadowsocks | 446.8 | 210.5 | Au1rxx-base64 | 149.22.87.240 |
| 56.42 | shadowsocks | 245.5 | 487.5 | Au1rxx-base64 | 173.244.56.9 |
| 55.11 | shadowsocks | 285.8 | 610.2 | Au1rxx-base64 | 173.244.56.6 |
| 54.59 | shadowsocks | 302.0 | 521.2 | Au1rxx-base64 | 149.22.95.183 |
| 54.56 | vmess | 218.3 | 465.6 | Barabama-yudou | 82.198.246.233 |
| 53.55 | shadowsocks | 334.1 | 581.5 | Au1rxx-base64 | 156.146.38.168 |
| 53.4 | shadowsocks | 338.5 | 602.1 | Au1rxx-base64 | 156.146.38.167 |
| 53.29 | shadowsocks | 342.2 | 612.6 | Au1rxx-base64 | 156.146.38.169 |
| 53.15 | shadowsocks | 346.4 | 618.9 | Au1rxx-base64 | 156.146.38.170 |
| 51.77 | vless | 356.9 | 617.5 | Au1rxx-base64 | 34.222.27.94 |
| 51.73 | vless | 570.0 | 213.5 | Au1rxx-base64 | 103.134.35.107 |
| 51.49 | shadowsocks | 230.2 | 488.6 | mheidari-all | 192.3.196.182 |
| 51.33 | vless | 557.1 | 92.8 | roosterkid-openproxylist-v2ray | 47.86.55.200 |
| 51.33 | vless | 575.7 | 218.8 | Au1rxx-base64 | 13.193.215.148 |
| 51.07 | vless | 378.4 | 811.5 | Au1rxx-base64 | 15.204.97.214 |
| 50.54 | shadowsocks | 208.9 | 433.1 | DeltaKronecker-all | 107.172.219.230 |
| 49.59 | shadowsocks | 456.1 | 653.4 | Au1rxx-base64 | 37.19.198.236 |
| 49.57 | shadowsocks | 456.8 | 648.9 | Au1rxx-base64 | 37.19.198.160 |
| 49.49 | shadowsocks | 459.4 | 648.2 | Au1rxx-base64 | 37.19.198.244 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.958 | 0.977 | 43 | 52 | prefer |
| Au1rxx-base64 | 0.565 | 0.563 | 71 | 88 | observe |
| roosterkid-openproxylist-v2ray | 0.296 | 0.276 | 29 | 150 | observe |
| mheidari-all | 0.291 | 0.204 | 93 | 2000 | observe |
| Surfboard-tg-mixed | 0.29 | 0.209 | 694 | 4225 | observe |
| Epodonios-all | 0.255 | None | 0 | 3000 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3000 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3224 | observe |
| barry-far-vless | 0.255 | None | 0 | 2000 | observe |
| Barabama-yudou | 0.214 | 0.5 | 2 | 166 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |
| barry-far-Sub2 | 0.195 | None | 0 | 501 | observe |
| barry-far-Sub1 | 0.194 | None | 0 | 473 | observe |
| mfuu-v2ray | 0.19 | None | 0 | 387 | observe |
| MatinGhanbari-super-sub | 0.183 | None | 0 | 199 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ClientOSError | - | 517 |
| 204 | ProxyError | - | 359 |
| geo | status | 429 | 145 |
| 204 | TimeoutError | - | 62 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | - | 51 |
| geo | status | 403 | 32 |
| cn-block | ClientOSError | - | 11 |
| cn-block | TimeoutError | - | 9 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | - | 8 |
| speed | ClientOSError | - | 6 |
| speed | TimeoutError | - | 4 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �N|smy���{�4�Ϛ�M�o��}ֻ{� | - | 3 |
| sing-box exited 1 |  [31mFATAL[0m[0000] decode config at /tmp/sb-poh3xm1p/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | - | 1 |
| sing-box exited 1 |  [31mFATAL[0m[0000] decode config at /tmp/sb-id3kpisk/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | - | 1 |
| sing-box exited 1 |  [31mFATAL[0m[0000] decode config at /tmp/sb-w_amhs5o/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 300 | 280 | - |
| global | False | 300 | 284 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
