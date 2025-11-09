# AusBull Leader Mod for Civilization VI

## 模组介绍 / Mod Description

**中文：**
澳洲大牛牛（AusBull）是一个全新的澳大利亚文明领袖，为《文明VI：风云变幻》扩展包设计。

**English:**
AusBull is a new leader for the Australian civilization, designed for Civilization VI: Gathering Storm expansion.

---

## 领袖特性 / Leader Ability

### 牛气冲天 (Bullish Momentum)

**效果 / Effect:**
- 所有军事单位 **-2 战斗力** / All military units **-2 Combat Strength**
- 所有军事单位 **+2 行动力** / All military units **+2 Movement**

---

## 继承特性 / Inherited Traits

澳洲大牛牛完全继承约翰·柯廷的所有特性：
AusBull inherits all traits from John Curtin:

- **文明特性 / Civilization Ability:** Land Down Under
- **特色改良 / Unique Improvement:** Outback Station
- **特色单位 / Unique Unit:** Digger
- **城市名称 / City Names:** 所有澳大利亚城市名称 / All Australian city names

---

## 系统要求 / Requirements

- **游戏版本 / Game Version:** Civilization VI
- **必需DLC / Required DLC:** Gathering Storm (风云变幻)
- **仅支持规则集 / Ruleset:** Expansion 2 only

---

## 安装方法 / Installation

1. 将整个 `AusBullLeader` 文件夹复制到你的 Civ6 Mods 目录 / Copy the entire `AusBullLeader` folder to your Civ6 Mods directory
   - Windows: `Documents\My Games\Sid Meier's Civilization VI\Mods\`
   - Mac: `~/Library/Application Support/Sid Meier's Civilization VI/Mods/`
   - Linux: `~/.local/share/aspyr-media/Sid Meier's Civilization VI/Mods/`

2. 启动游戏并在主菜单的"额外内容"中启用本模组 / Launch the game and enable the mod in "Additional Content" from the main menu

3. 创建新游戏时选择澳大利亚文明和澳洲大牛牛领袖 / Select Australia civilization and AusBull leader when creating a new game

---

### 目录结构
```
AusBullLeader/
├── AusBullLeader.civ6proj        # ModBuddy项目文件（核心配置）
├── Data/                          # 游戏数据文件夹
│   ├── AusBull_Leaders.xml       # 领袖定义和游戏机制
│   └── AusBull_Config.xml        # 前端配置
└── Text/                          # 本地化文本文件夹
    ├── AusBull_Text_zh_Hans_CN.xml        # 游戏内中文文本
    ├── AusBull_Text_en_US.xml             # 游戏内英文文本
    ├── AusBull_ConfigText_zh_Hans_CN.xml  # Mod描述中文
    └── AusBull_ConfigText_en_US.xml       # Mod描述英文
```

---

## 技术细节 / Technical Details

### 修正器 / Modifiers

- **Combat Penalty:** `MODIFIER_PLAYER_UNITS_ADJUST_COMBAT_STRENGTH` with Value="-2"
- **Movement Bonus:** `MODIFIER_PLAYER_UNITS_ADJUST_MOVEMENT` with Value="2"

### 领袖继承 / Leader Inheritance

通过 `InheritFrom="LEADER_CURTIN"` 实现对约翰·柯廷的完全继承
Full inheritance from John Curtin via `InheritFrom="LEADER_CURTIN"`

---

## 版本历史 / Version History

### Version 1.0
- 初始发布 / Initial release
- 实现牛气冲天特性 / Implemented Bullish Momentum trait
- 支持中英文本地化 / Chinese and English localization support

---

## 作者 / Author

**dimweak**

---

## 许可 / License

本模组仅供学习和娱乐使用。
This mod is for educational and entertainment purposes only.

---

## 反馈 / Feedback

如有问题或建议，请在项目页面提交 Issue。
For issues or suggestions, please submit an issue on the project page.
