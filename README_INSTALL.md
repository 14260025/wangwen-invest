# 王文投资方法论 · 安装与跨终端同步说明

> 技能名：`wangwen-invest`
> 来源：《万倍叔：日斗投资王文的财富心得》提炼的深度价值投资体系（供需元规则 + 五维选股 + 头部扩产红线）

## 目录结构

```
wangwen-invest/
├── SKILL.md                       # 技能主文件（触发条件 + 完整框架）
├── references/
│   ├── supply_demand_cycle.md      # 供求关系判断行业周期·核心方法
│   ├── analysis_template.md        # 实操分析模板（直接套用）
│   └── methodology.md              # 完整速查手册（含经典案例）
└── README_INSTALL.md              # 本文件
```

## 在任意终端安装（方式一：Git 克隆，推荐）

将本仓库克隆到各终端的 CodeBuddy skills 目录即可，技能会自动被识别：

```bash
# 终端 A / B / C ... 任选其一，克隆到 skills 目录
git clone <本仓库地址> ~/.codebuddy/skills/wangwen-invest

# 或若使用项目级 skills 目录
git clone <本仓库地址> /你的项目/.codebuddy/skills/wangwen-invest
```

克隆后无需额外配置，对话中提及"用王文方法论分析XX""供求关系判断行业周期"等即会触发。

## 在任意终端安装（方式二：手动拷贝）

```bash
cp -r wangwen-invest ~/.codebuddy/skills/
```

## 验证安装

在 CodeBuddy 对话中输入：
> "用王文的方法看看煤炭现在是不是上升通道"

若能给出"供需格局诊断 + 周期位置 + 五维体检 + 操作策略"的结构化分析，即安装成功。

## 触发话术

- "用王文方法论分析某股票/行业"
- "按日斗投资思路判断XX行业周期"
- "用供求关系分析面板/铝/煤行业"
- "王文的五维选股怎么套到XX上"
- "踏雪寻梅，现在哪些行业在下行周期值得关注"

## 更新同步

```bash
cd ~/.codebuddy/skills/wangwen-invest
git pull   # 拉取最新版本
```
