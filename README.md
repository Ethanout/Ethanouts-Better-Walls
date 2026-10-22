# Ethanout's Better Walls

作者：Ethanout

这是一个 Minecraft Java Edition 资源包。它修复石砖墙在调试棒切换到非法连接状态时出现的侧面缺失或透明问题。

## 支持版本

- Minecraft Java Edition 1.20.1
- Minecraft Java Edition 26.3
- 资源包格式范围：15 到 97

## 实现方式

资源包只覆盖以下两个原版模型：

- `minecraft:block/stone_brick_wall_side`
- `minecraft:block/stone_brick_wall_side_tall`

模型直接定义六个面的石砖纹理，并设置粒子纹理。资源包不包含 Mojang 的纹理文件，也不修改其他墙体。

## 使用方法

1. 将 ZIP 文件放入 `.minecraft/resourcepacks`。
2. 在游戏的资源包菜单中启用 `Ethanout's Better Walls`。
3. 使用调试棒测试石砖墙的连接状态。

## 许可证

本项目代码和模型文件使用 MIT License 发布。详见 `LICENSE`。

本资源包不包含 Mojang 的原版纹理文件。
