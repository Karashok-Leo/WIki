# 融锻 / Fusion Smithing

## 🪄介绍

这个模组添加了一种新的锻造模板——融锻模板，允许你将一件物品的NBT数据（包括附魔）转移到另一件物品上。

![Screenshot](assets/fusion-smithing/smithing.png)

### 战利品表

你可以在末地城的宝箱里获得融锻模板。

![Screenshot](assets/fusion-smithing/loot_table.png)

### 合成配方

![Screenshot](assets/fusion-smithing/recipe.png)

## ⚙️配置

### 初始配置文件：

```
{  
  "injected_loot_table": "minecraft:chests/end_city_treasure"
}
```

如果你不想让融锻模板出现在末地城的宝箱里，只需要将injected_loot_table条目修改为其他的战利品表，或者只是留空。

### 如何适配更多的物品？

只需制作一个用于添加配方的数据包即可。

## ✉️反馈

如果有任何Bug或建议，请反馈到Github的Issue页面。