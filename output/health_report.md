# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-06-16 04:25:23 |
| 运行耗时 | 227.8s |
| 订阅源总数 | 44 |
| 健康订阅源 | 44 |
| 原始节点 | 42116 |
| 去重后节点 | 16921 |
| TCP 可达 | 1500 |
| 真实可用 | 393 |
| Verified 输出 | 300 |
| Global 输出 | 300 |
| All 输出 | 16921 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 3.0 |
| geo | 1.2 |
| tcp | 40.1 |
| real_test | 161.2 |
| generate | 22.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 21011 |
| shadowsocks | 8523 |
| trojan | 6555 |
| vmess | 5637 |
| hysteria2 | 152 |
| shadowsocksr | 94 |
| http | 86 |
| socks | 51 |
| hysteria | 6 |
| tuic | 1 |

## 评分权重

| 因子 | 权重 |
| --- | --- |
| latency | 35.0 |
| jitter | 15.0 |
| tcp | 10.0 |
| protocol_history | 20.0 |
| source_history | 20.0 |

## Top 节点评分

| 评分 | 协议 | 延迟(ms) | 抖动(ms) | 延迟分 | 抖动分 | TCP分 | 协议历史分 | 来源历史分 | 来源 | 服务器 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 63.71 | http | 679.7 | 901.7 | 16.86 | 0.0 | 9.77 | 18.7 | 18.38 | snakem982 | 84.239.49.191 |
| 63.58 | http | 683.6 | 897.0 | 16.74 | 0.0 | 9.76 | 18.7 | 18.38 | snakem982 | 84.239.14.152 |
| 63.56 | http | 684.1 | 913.2 | 16.72 | 0.0 | 9.76 | 18.7 | 18.38 | snakem982 | 84.239.49.166 |
| 63.56 | http | 684.2 | 910.9 | 16.72 | 0.0 | 9.76 | 18.7 | 18.38 | snakem982 | 84.239.49.160 |
| 63.55 | http | 684.6 | 912.4 | 16.7 | 0.0 | 9.77 | 18.7 | 18.38 | snakem982 | 84.239.49.154 |
| 63.52 | http | 684.2 | 907.5 | 16.71 | 0.0 | 9.73 | 18.7 | 18.38 | snakem982 | 84.239.14.154 |
| 63.51 | http | 684.3 | 910.0 | 16.71 | 0.0 | 9.72 | 18.7 | 18.38 | snakem982 | 84.239.49.219 |
| 63.51 | http | 685.3 | 905.1 | 16.68 | 0.0 | 9.75 | 18.7 | 18.38 | snakem982 | 84.239.14.159 |
| 63.5 | http | 686.1 | 901.7 | 16.65 | 0.0 | 9.77 | 18.7 | 18.38 | snakem982 | 84.239.49.40 |
| 63.5 | http | 686.1 | 919.0 | 16.65 | 0.0 | 9.77 | 18.7 | 18.38 | snakem982 | 84.239.49.183 |
| 63.5 | http | 686.2 | 903.3 | 16.65 | 0.0 | 9.77 | 18.7 | 18.38 | snakem982 | 84.239.49.156 |
| 63.49 | http | 686.7 | 909.8 | 16.64 | 0.0 | 9.77 | 18.7 | 18.38 | snakem982 | 84.239.49.249 |
| 63.48 | http | 686.5 | 908.0 | 16.64 | 0.0 | 9.76 | 18.7 | 18.38 | snakem982 | 84.239.49.157 |
| 63.4 | http | 689.2 | 913.8 | 16.55 | 0.0 | 9.77 | 18.7 | 18.38 | snakem982 | 84.239.49.171 |
| 63.34 | http | 691.3 | 940.2 | 16.49 | 0.0 | 9.77 | 18.7 | 18.38 | snakem982 | 84.239.49.227 |
| 63.33 | http | 691.4 | 945.6 | 16.48 | 0.0 | 9.77 | 18.7 | 18.38 | snakem982 | 84.239.49.223 |
| 63.32 | http | 688.3 | 927.9 | 16.58 | 0.0 | 9.66 | 18.7 | 18.38 | snakem982 | 84.239.49.164 |
| 63.32 | http | 691.7 | 918.5 | 16.47 | 0.0 | 9.77 | 18.7 | 18.38 | snakem982 | 84.239.49.224 |
| 63.31 | http | 692.0 | 913.7 | 16.46 | 0.0 | 9.77 | 18.7 | 18.38 | snakem982 | 84.239.49.37 |
| 63.26 | http | 693.7 | 924.7 | 16.41 | 0.0 | 9.77 | 18.7 | 18.38 | snakem982 | 84.239.49.254 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| snakem982 | 0.917 | 0.933 | 45 | 52 | prefer |
| Au1rxx-base64 | 0.5 | 0.495 | 95 | 128 | observe |
| roosterkid-openproxylist-v2ray | 0.477 | 0.469 | 32 | 150 | observe |
| Surfboard-tg-mixed | 0.365 | 0.284 | 858 | 4433 | observe |
| Barabama-yudou | 0.318 | 1.0 | 2 | 166 | observe |
| mfuu-v2ray | 0.263 | 1.0 | 1 | 203 | observe |
| Pawdroid | 0.256 | 1.0 | 1 | 13 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3000 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 3404 | observe |
| barry-far-vless | 0.255 | None | 0 | 2000 | observe |
| DeltaKronecker-all | 0.201 | 0.119 | 270 | 6499 | downweight |
| barry-far-Sub2 | 0.195 | None | 0 | 494 | observe |
| barry-far-Sub1 | 0.194 | None | 0 | 469 | observe |
| mheidari-all | 0.188 | 0.097 | 72 | 2000 | downweight |
| nscl5-all | 0.187 | 0.2 | 5 | 1017 | downweight |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ClientOSError | - | 490 |
| 204 | ProxyError | - | 311 |
| 204 | TimeoutError | - | 79 |
| geo | status | 403 | 57 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: uTLS is required by reality client | - | 56 |
| speed | ClientOSError | - | 27 |
| speed | TimeoutError | - | 24 |
| cn-block | ClientOSError | - | 14 |
| cn-block | TimeoutError | - | 11 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: ShadowsocksR is deprecated and removed in sing-box 1.6.0 | - | 8 |
| geo | status | 429 | 8 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: �N|smy���{�4�Ϛ�M�o��}ֻ{� | - | 3 |
| cn-block | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] decode config at /tmp/sb-94fb1vn3/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | - | 1 |
| sing-box exited 1 |  [31mFATAL[0m[0000] decode config at /tmp/sb-ca6fg5k9/config.json: outbounds[0].security: json: cannot unmarshal bool into Go struct field VMessOutboundOptions.security of type string | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 254 | 300 | - |
| global | False | 258 | 300 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
