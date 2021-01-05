# ![logo](https://raw.githubusercontent.com/azerothcore/azerothcore.github.io/master/images/logo-github.png) AzerothCore
## 赌徒 NPC
- Latest build status with azerothcore: [![Build Status](https://github.com/azerothcore/mod-npc-gambler/workflows/core-build/badge.svg?branch=master&event=push)](https://github.com/azerothcore/mod-npc-gambler)

_This module was created for [StygianCore](https://rebrand.ly/stygiancoreproject). A World of Warcraft 3.3.5a Solo/LAN repack by StygianTheBest | [GitHub](https://rebrand.ly/stygiangithub) | [Website](https://rebrand.ly/stygianthebest))_
_This module has now being ported to AzerothCore by gtao725 (https://github.com/gtao725/)._

### 描述

嘿，我叫瘦子。你简直幸运吗?这个NPC将允许玩家在配置中定义的铜、银或金上赌博。这是玩家赚点外快的好方法。

- Config:
    - 设置赌注和头奖金额
    - 启用/禁用硬币类型(金，银，铜)
    - 设置硬币类型为赌博
- 掷出50或更高点数将赢得双倍赌注!
- 少于50的输掉双倍的赌注!
- 前10次掷中100分就中头奖了!
- 为了打击垃圾邮件，每个会话的前10卷只能中头奖。
- 对于连续输掉5次的玩家会有一些帮助。

### To-Do

- 和显示头奖得主/日期。
- 从玩家的损失中创建彩票。

### Data

- Type: NPC
- Script: gamble_npc
- Config: Yes
- SQL: Yes
    - NPC ID: 601020

### Version

- v2019.04.17 - Fix display of win/lose amount for values 100 or above, applicable to copper/silver/gold
- v2019.04.15 - Ported to AzerothCore by gtao725 (https://github.com/gtao725/)
- v2019.02.13 - Redesign, Add Coin Type Options, Update AI
- v2018.12.09 - Update config
- v2017.08.10 - Release


### CREDITS

![Styx](https://stygianthebest.github.io/assets/img/avatar/avatar-128.jpg "Styx")
![StygianCore](https://stygianthebest.github.io/assets/img/projects/stygiancore/StygianCore.png "StygianCore")

##### This module was created for [StygianCore](https://rebrand.ly/stygiancoreproject). A World of Warcraft 3.3.5a Solo/LAN repack by StygianTheBest | [GitHub](https://rebrand.ly/stygiangithub) | [Website](https://rebrand.ly/stygianthebest))

#### Additional Credits

- [Blizzard Entertainment](http://blizzard.com)
- [TrinityCore](https://github.com/TrinityCore/TrinityCore/blob/3.3.5/THANKS)
- [SunwellCore](http://www.azerothcore.org/pages/sunwell.pl/)
- [AzerothCore](https://github.com/AzerothCore/azerothcore-wotlk/graphs/contributors)
- [OregonCore](https://wiki.oregon-core.net/)
- [Wowhead.com](http://wowhead.com)
- [OwnedCore](http://ownedcore.com/)
- [ModCraft.io](http://modcraft.io/)
- [MMO Society](https://www.mmo-society.com/)
- [AoWoW](https://wotlk.evowow.com/)
- [More credits are cited in the sources](https://github.com/StygianTheBest)

### LICENSE

This code and content is released under the [GNU AGPL v3](https://github.com/azerothcore/azerothcore-wotlk/blob/master/LICENSE-AGPL3).
