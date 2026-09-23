---
title: eCNH 2025 常用 SKILL 清单
token: eCNH 华夏币
chain: Solana
contract: 7GQnqthWKa5v2GqXYWhmgWZY5mCRrniwK3Xuinm9GKw5
version: 2025
default_language: en
supported_languages:
  - en
  - zh-CN
  - es
  - fr
  - ar
  - ru
---

# eCNH 2025 常用 SKILL 清单

> **eCNH 华夏币** 是部署在 **Solana** 区块链上的 SPL 代币，与离岸人民币（CNH）相关联。  
> 合约地址：`7GQnqthWKa5v2GqXYWhmgWZY5mCRrniwK3Xuinm9GKw5`  
> 本清单共收录 **100 个常用 SKILL**，按功能分为四大类，每类 25 个，可直接用于网站/APP 的技能展示模块。

---

## 目录

1. [钱包与资产管理 SKILL（1–25）](#一钱包与资产管理-skill125)
2. [DEX 交易与 DeFi SKILL（26–50）](#二dex-交易与-defi-skill2650)
3. [安全验证与审计 SKILL（51–75）](#三安全验证与审计-skill5175)
4. [区块链浏览器与数据工具 SKILL（76–100）](#四区块链浏览器与数据工具-skill76100)
5. [网站/APP 集成建议](#网站app-集成建议)
6. [免责声明](#免责声明)

---

## 一、钱包与资产管理 SKILL（1–25）

| 编号 | SKILL 名称 | 功能说明 | 常用工具 |
|:---:|:---|:---|:---|
| 1 | 创建 Solana 钱包 | 生成新的 Solana 密钥对，获得公钥与私钥 | Phantom / Solflare |
| 2 | 导入钱包 | 通过助记词或私钥恢复钱包 | Phantom / Solflare |
| 3 | 导出私钥 | 导出钱包私钥用于备份 | Phantom |
| 4 | 查看 SOL 余额 | 查询钱包中的 SOL 余额 | Solscan / Solana Explorer |
| 5 | 查看 SPL 代币余额 | 查询钱包中所有 SPL 代币的余额 | Solscan / Solflare |
| 6 | 添加 eCNH 代币 | 将 eCNH 合约地址添加到钱包代币列表 | Phantom / Solflare |
| 7 | 复制 eCNH 合约地址 | 一键复制 eCNH 合约地址 | 本项目网站 |
| 8 | 转账 SOL | 向其他 Solana 地址发送 SOL | Phantom / Solflare |
| 9 | 转账 eCNH | 向其他 Solana 地址发送 eCNH 代币 | Phantom / Solflare |
| 10 | 批量转账 eCNH | 向多个地址批量发送 eCNH | Solana CLI / Solflare |
| 11 | 创建关联代币账户 | 为 eCNH 创建 ATA（关联代币账户） | Solana CLI / spl-token |
| 12 | 关闭关联代币账户 | 关闭不再使用的 eCNH ATA 以回收租金 | Solana CLI |
| 13 | 查看交易历史 | 查询钱包的链上交易记录 | Solscan / SolanaFM |
| 14 | 查看代币持有者分布 | 分析 eCNH 的持币地址分布 | Solscan / Orb |
| 15 | 查看代币总供应量 | 查询 eCNH 的总供应量与流通量 | Solscan / DexPaprika |
| 16 | 查看代币精度 | 查看 eCNH 的小数位数 | Solscan |
| 17 | 查看代币 Mint 权限 | 检查 eCNH 的 Mint Authority 是否已撤销 | Solscan / RugCheck |
| 18 | 查看代币冻结权限 | 检查 eCNH 的 Freeze Authority 状态 | Solscan / RugCheck |
| 19 | 质押 SOL | 将 SOL 委托给验证者获取收益 | Solana Beach / Phantom |
| 20 | 取消质押 SOL | 解除 SOL 质押 | Phantom / Solflare |
| 21 | 查看质押收益 | 查询质押的 SOL 收益 | Solana Beach |
| 22 | 切换验证者 | 将质押的 SOL 委托到其他验证者 | Phantom / Solflare |
| 23 | 创建多签钱包 | 创建需要多个签名才能执行交易的钱包 | Squads |
| 24 | 硬件钱包连接 | 将 Ledger 等硬件钱包连接到 Solana | Ledger Live / Phantom |
| 25 | 钱包安全审计 | 检查钱包授权与潜在风险 | Solflare / Revoke.cash |

---

## 二、DEX 交易与 DeFi SKILL（26–50）

| 编号 | SKILL 名称 | 功能说明 | 常用工具 |
|:---:|:---|:---|:---|
| 26 | 查看 eCNH 实时价格 | 查询 eCNH 当前 USD 价格 | DexPaprika / DexScreener |
| 27 | 查看 eCNH 价格变动 | 查看 5m / 1h / 6h / 24h 价格变动 | DexPaprika |
| 28 | 查看 eCNH 流动性 | 查询 eCNH 各池的总流动性 | DexPaprika / Orca |
| 29 | 查看 eCNH 24h 交易量 | 查询 eCNH 24 小时交易量 | DexPaprika |
| 30 | 查看 eCNH 交易笔数 | 查询 24 小时交易笔数 | OrbMarkets |
| 31 | 在 Jupiter 上 swap | 通过 Jupiter 聚合器交换 eCNH | Jupiter |
| 32 | 在 Orca 上 swap | 通过 Orca AMM 交换 eCNH | Orca |
| 33 | 在 Raydium 上 swap | 通过 Raydium AMM 交换 eCNH | Raydium |
| 34 | 在 Meteora 上 swap | 通过 Meteora 动态流动性池交换 eCNH | Meteora |
| 35 | 设置滑点 | 调整 swap 的滑点容忍度 | Jupiter / Orca |
| 36 | 设置交易优先级费 | 调整交易的优先费以加快确认 | Phantom / Jupiter |
| 37 | 查看 eCNH 最优路由 | 查看聚合器给出的最优 swap 路径 | Jupiter |
| 38 | 添加 eCNH 流动性 | 向 eCNH 池添加流动性 | Orca / Raydium |
| 39 | 移除 eCNH 流动性 | 从 eCNH 池中移除流动性 | Orca / Raydium |
| 40 | 查看 LP 仓位 | 查询持有的 eCNH LP 代币仓位 | Orca / Raydium |
| 41 | 查看 LP 收益 | 查询提供流动性获得的费用收益 | Orca |
| 42 | 查看 eCNH/PYUSD 池 | 查看 Orca 上的 eCNH/PYUSD 池状态 | Orca |
| 43 | 查看 eCNH/USDC 池 | 查看 Orca 上的 eCNH/USDC 池状态 | Orca |
| 44 | 限价单交易 | 设置 eCNH 限价买入/卖出单 | Jupiter / Raydium |
| 45 | DCA 定投 eCNH | 设置定期定额买入 eCNH | Jupiter |
| 46 | 查看 eCNH K 线 | 查看 eCNH 的蜡烛图数据 | DexScreener / DexPaprika |
| 47 | 查看 eCNH 深度图 | 查看 eCNH 订单簿深度 | Raydium |
| 48 | 桥接资产到 Solana | 从其他链桥接资产到 Solana | Wormhole / Portal |
| 49 | 查看跨链桥状态 | 查询跨链桥交易进度 | Wormhole |
| 50 | 查看 DeFi 总锁仓量 | 查看 eCNH 相关池的 TVL | DeFiLlama |

---

## 三、安全验证与审计 SKILL（51–75）

| 编号 | SKILL 名称 | 功能说明 | 常用工具 |
|:---:|:---|:---|:---|
| 51 | 验证 eCNH 合约 | 在浏览器上确认合约地址与代币信息 | Solscan |
| 52 | 检查 Mint Authority | 确认 eCNH 的铸币权限是否已撤销 | Solscan |
| 53 | 检查 Freeze Authority | 确认 eCNH 的冻结权限是否已撤销 | Solscan |
| 54 | 检查 LP 锁定状态 | 查看 eCNH 流动性池是否已锁定 | RugCheck |
| 55 | 检查持币集中度 | 分析前 10 地址的持仓占比 | Solscan / Orb |
| 56 | 检查蜜罐风险 | 检测 eCNH 是否为蜜罐代币 | RugCheck / Honeypot.is |
| 57 | 检查代币权限 | 全面审计 eCNH 的链上权限 | RugCheck |
| 58 | 检查交易税 | 检测 eCNH 的买卖税费 | DexScreener |
| 59 | 检查合约是否开源 | 确认 eCNH 合约代码是否已验证 | Solscan |
| 60 | 检查创建者历史 | 查看 eCNH 创建者的历史项目 | Solscan |
| 61 | 检查代币创建时间 | 查看 eCNH 的链上创建日期 | OrbMarkets |
| 62 | 检查代币创建者地址 | 查看 eCNH 的创建者钱包地址 | Solscan |
| 63 | 检查代币元数据 | 查看 eCNH 的名称、符号、图标等元数据 | Solscan / Metaplex |
| 64 | 检查代币描述 | 查看 eCNH 链上描述内容 | OrbMarkets |
| 65 | 检查代币小数位 | 确认 eCNH 的小数位数配置 | Solscan |
| 66 | 检查代币总供应量 | 确认 eCNH 总供应量是否合理 | Solscan |
| 67 | 检查流动性变化 | 监控 eCNH 流动性池的实时变化 | DexPaprika |
| 68 | 检查大额交易 | 监控 eCNH 的大额转账 | Solscan |
| 69 | 检查异常交易 | 识别可疑的 eCNH 交易模式 | Orb |
| 70 | 撤销代币授权 | 撤销对 eCNH 的合约授权 | Solflare / Revoke.cash |
| 71 | 检查钱包授权 | 查看钱包中对 eCNH 的所有授权 | Solflare |
| 72 | 检查钓鱼链接 | 验证 DEX 链接是否为官方地址 | 手动核实 |
| 73 | 检查合约漏洞 | 使用安全工具扫描 eCNH 合约 | Sec3 / Ottersec |
| 74 | 检查代币是否可增发 | 确认 eCNH 是否可被增发 | Solscan |
| 75 | 检查代币是否可冻结 | 确认 eCNH 是否可被冻结 | Solscan |

---

## 四、区块链浏览器与数据工具 SKILL（76–100）

| 编号 | SKILL 名称 | 功能说明 | 常用工具 |
|:---:|:---|:---|:---|
| 76 | 在 Solscan 查询 eCNH | 查看 eCNH 代币页面 | Solscan |
| 77 | 在 Solana Explorer 查询 | 使用官方浏览器查询 eCNH | Solana Explorer |
| 78 | 在 Orb 查询 eCNH | 使用 AI 驱动的浏览器查询 | Orb（Helius） |
| 79 | 在 SolanaFM 查询 | 使用支持 CSV 导出的浏览器查询 | SolanaFM |
| 80 | 在 Solana Beach 查询 | 查看 Solana 网络健康状况 | Solana Beach |
| 81 | 在 OKX Link 查询 | 使用多语言浏览器查询 | OKX Link |
| 82 | 使用 X-Ray 解析交易 | 将复杂交易转为可读摘要 | X-Ray |
| 83 | 在 Jito 查询 MEV | 查看 eCNH 交易的 MEV Bundle | Jito Explorer |
| 84 | 在 Solanascan 查询 | 使用开源社区浏览器查询 | Solanascan |
| 85 | 在 Metaplex 查询 NFT | 查看 eCNH 相关的 NFT 资产 | Metaplex Core |
| 86 | 导出交易记录 | 导出 eCNH 交易历史为 CSV | SolanaFM |
| 87 | 查看代币统计 | 查看 eCNH 的统计面板 | DexPaprika |
| 88 | 查看代币页面 | 查看 eCNH 的聚合信息页面 | OrbMarkets |
| 89 | 查看代币 FAQ | 查看 eCNH 的常见问题解答 | OrbMarkets |
| 90 | 查看代币市场列表 | 查看 eCNH 的所有交易市场 | OrbMarkets |
| 91 | 查看代币交易对 | 查看 eCNH 的所有交易对 | DexPaprika |
| 92 | 查看代币价格图表 | 查看 eCNH 的价格走势图 | DexScreener |
| 93 | 设置价格提醒 | 设置 eCNH 价格变动提醒 | DexScreener / 本项目 APP |
| 94 | 查看代币新闻 | 查看 eCNH 相关新闻动态 | 本项目网站 |
| 95 | 查看代币社区 | 查看 eCNH 的社区讨论 | 本项目网站 |
| 96 | 查看代币文档 | 查看 eCNH 的项目文档 | eCNH 官网 |
| 97 | 查看代币路线图 | 查看 eCNH 的发展路线图 | eCNH 官网 |
| 98 | 查看代币审计报告 | 查看 eCNH 的第三方审计报告 | 本项目网站 |
| 99 | 提交代币信息更新 | 向浏览器提交 eCNH 信息更新 | Solscan |
| 100 | 报告代币问题 | 向社区报告 eCNH 的异常情况 | 本项目网站 |

---

## 网站/APP 集成建议

在 eCNH 2025 网站或 APP 中，建议按以下方式呈现这 100 个 SKILL：

- **分类展示**：使用四个标签页（钱包、DeFi、安全、浏览器），每个标签页展示 25 个技能卡片。卡片包含技能编号、名称、说明和对应工具链接。
- **搜索过滤**：在技能列表顶部添加搜索框，支持按关键词过滤（如输入“流动性”显示所有流动性相关技能）。
- **多语言支持**：为每个技能的 `name` 和 `description` 添加六种语言的翻译键，复用现有的 `I18N` 翻译系统。默认语言为英语，支持中文（简体）、西班牙语、法语、阿拉伯语、俄语。
- **数据驱动渲染**：将 100 个技能定义为 `SKILLS` 数组，每条包含 `id`、`category`、`nameKey`、`descKey`、`tool`、`url` 字段，通过 `renderSkills()` 函数动态生成卡片。
- **样式复用**：技能卡片可以直接复用现有的 `.card` 样式，保持与 DEX、浏览器卡片一致的视觉风格。

---

## 免责声明

eCNH 当前 24 小时交易量为 **$0.00**，总流动性约 **$20.90K**，Orca 上的 eCNH/BNB 池流动性为 **$0.00**。本清单中的 SKILL 及工具列表是基于 Solana 生态整体市场数据整理的导航参考，不代表 eCNH 已在所有平台上线或具有可交易流动性。加密货币投资风险极高，请勿仅依赖本页面信息做出决策。本清单不构成任何财务建议。

---

*文档版本：2025 · 适用于 eCNH 2025 网站/APP*
