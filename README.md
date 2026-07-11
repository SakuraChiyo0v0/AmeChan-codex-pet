# AmeChan

[English](README.en.md)

AmeChan 是一只兼容 Codex v2 的动态桌宠。她戴着深红色兔耳兜帽与白色蝴蝶结，留有灰色侧刘海，并拥有小巧的蝙蝠翼。

## 内容一览

- `pet.json`：Codex 宠物配置文件。
- `spritesheet.webp`：v2 精灵表，共 8 列 × 11 行；每格为 192 × 208 像素。
- `contact-sheet-extended.png`：所有动作与方向帧的总览图。
- `gifs/`：九种标准动作、两行方向动画，以及完整 16 方向循环的 GIF 预览。
- `qa/`：已脱敏的结构验证、透明边缘处理、方向语义和视觉 QA 记录。

## 动作 GIF

每种标准状态都有独立 GIF：`idle`、`running-right`、`running-left`、`waving`、`jumping`、`failed`、`waiting`、`running` 与 `review`。

方向系统则由以下 GIF 展示：

- `look-row-9.gif`：从上方到右下方的八个方向。
- `look-row-10.gif`：从下方到左上方的八个方向。
- `look-loop.gif`：完整的 16 方向循环。

## 兼容性

该宠物使用 `spriteVersionNumber: 2`，精灵表尺寸为 1536 × 2288，背景为透明，并已通过 v2 结构验证与最终视觉 QA。

## 使用说明

1. 保持 `pet.json` 与 `spritesheet.webp` 位于同一宠物目录中。
2. 将该目录放入 Codex 的自定义宠物位置，或使用 Codex 的宠物导入方式添加它。
3. 重启 Codex，或在宠物选择器中先切换到其他宠物再切回 `AmeChan`。
4. 选中 `AmeChan` 后，即可查看九种状态动画和 16 方向注视效果。
