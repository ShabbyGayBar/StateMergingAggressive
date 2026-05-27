# 维多利亚3省份合并

![Steam Subscriptions](https://img.shields.io/steam/subscriptions/3553174702?logo=steam)
![Steam Downloads](https://img.shields.io/steam/downloads/3553174702?logo=steam)

一个省份合并模组，合并了部分地区。

**警告**：由于合并了大量省份，本模组**不保证**任何原版游戏体验的完整性。本模组可能会导致部分日志和事件无法触发或完成，如有此类问题请**自行适应**。

建筑、人口等数据都保留原样。但是因为合并了各个省份，所以整体陆军、海军、征税等加成在省份上的数值上限都减少了，所以通过加 buff 的方式弥补了一部分回来。

因技术力有限，被合并的省份的城市、建筑模型都会消失。

被合并的省份的代码会消失，可能会导致部分日志和事件无法触发或完成，如有此 BUG 请在 Issues 中提出。 

另外，buff 是按被合并的省份的数量给的，但是因为有些省份实在太小了，我认为它们本来就不应该算一个省份，所以给 buff 时没有计入。

## 当前已经合并的省份

![Currently Merged States](../figures/Merge_States_current.png)

所有对省份的改动请参照 [merge_states.json](../merge_states.json)。

其中，每个键代表了模组中存在的省份代码，对应的值代表了要合并到这个省份的原版省份代码。

## 安装方法

- 在 [Steam 创意工坊](https://steamcommunity.com/sharedfiles/filedetails/?id=3553174702) 订阅本模组。
或者
- 在 [Paradox 官网](https://mods.paradoxplaza.com/mods/113894/Any) 下载本模组。
或者
- 下载模组的 zip 文件并解压到维多利亚3的模组文件夹中（通常位于 `Documents\Pardox Interactive\Victoria 3\mod`）。

## 提交反馈

如果您有任何反馈，请参考本模组的[普通版](https://github.com/ShabbyGayBar/StateMerging)的 issue 板块。

## 兼容性：

跟任何修改了
- common\history\buildings\
- common\history\pops\
- common\history\states\
- map_data\state_regions\

下的文件的模组都不兼容

<details>

<summary>其他对游戏进程影响较小的文件的改动</summary>

- common/ai_strategies
- common/buildings
- common/character_templates
- common/coat_of_arms/template_lists
- common/company_types
- common/country_creation
- common/country_definitions
- common/country_formation
- common/decisions
- common/dynamic_country_map_colors
- common/dynamic_country_names
- common/geographic_regions
- common/flag_definitions
- common/history/countries
- common/history/global
- common/history/diplomatic_plays
- common/history/military_formations
- common/journal_entries
- common/mobilization_options
- common/on_actions
- common/political_movements
- common/scripted_buttons
- common/scripted_effects
- common/scripted_progress_bars
- common/scripted_triggers
- events
- events/agitators_events
- events/american_civil_war
- events/balkans_events
- events/brazil
- events/iberia_events
- events/india_events
- events/japan_events
- events/soi_events
- gfx/map/city_data/city_types

</details>

## 相关链接

- 如果您希望只合并**更少**的省份，您可以选择使用本模组的普通版：
  - [Github](https://github.com/ShabbyGayBar/StateMerging), 或
  - [Steam 创意工坊](https://steamcommunity.com/sharedfiles/filedetails/?id=3371693463), 或
  - [Paradox 官网](https://mods.paradoxplaza.com/mods/120868/Any).
- 如果您希望**尽可能少地**合并省份，您可以选择使用本模组的**保守版**：
  - [Github](https://github.com/ShabbyGayBar/StateMergingMinimal), 或
  - [Steam 创意工坊](https://steamcommunity.com/sharedfiles/filedetails/?id=3432100126), 或
  - [Paradox 官网](https://mods.paradoxplaza.com/mods/113894/Any).
- 如果您希望制作自己的省份合并模组，您可以使用[省份合并自动化脚本及教程](https://github.com/ShabbyGayBar/StateMerger).

## 致谢

* 感谢原作者 [思考的肾结核](https://steamcommunity.com/profiles/76561198104682926) 制作的最初版本 [省份合并模组](https://steamcommunity.com/sharedfiles/filedetails/?id=3254683348)。

## 软件许可证

本模组使用 [MIT LICENSE](../LICENSE) 授权。
