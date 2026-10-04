# Cheems — Codex 虚拟宠物 / Cheems — A Codex Pet

**喜欢吃薯条的 Cheems，供 Codex 使用的动画虚拟宠物。**

**A fries-loving Cheems animated companion for Codex.**

这是大家都喜爱的 Cheems。现实中的 Cheems 已经去了天堂，但它会一直陪伴我们。Cheems 爱吃薯条的设定来自于 B 站 UP 主「清竹莫叶」的作品，希望大家的生命不再迷茫。

This is the Cheems we all love. The real Cheems has gone to heaven, but he will always be with us. This Cheems' love of fries is inspired by the work of Bilibili creator 清竹莫叶. May we all find our way in life.

## 动画预览 / Animation previews

| 日常吃薯条 / Idle snack | 电脑前吃薯条 / Snack at the laptop |
| --- | --- |
| ![Cheems 日常吃薯条 / Cheems eating fries](preview-idle.gif) | ![Cheems 在电脑前吃薯条 / Cheems snacking at the laptop](preview-review.gif) |

## 中文

### 安装到 Codex

适用于支持自定义 v2 宠物的 Codex 桌面客户端。

下载 `Cheems-Codex-Pet-v1.0.0.zip`，将压缩包拖入 Codex 对话，输入：**“安装并加载压缩包中的 Cheems 宠物。”** 也可按以下步骤手动安装。

#### 手动安装

1. 下载 `Cheems-Codex-Pet-v1.0.0.zip` 并解压，或下载仓库中的 `pet.json` 和 `cheems.png`。
2. 在 Codex 数据目录的 `pets` 文件夹下创建 `cheems` 文件夹，将 `pet.json` 和 `cheems.png` 放入其中。
3. 打开客户端的宠物设置，刷新自定义宠物列表，选择 **Cheems — Codex 虚拟宠物 / Cheems — A Codex Pet**。

默认安装位置：

| 系统 | 文件夹 |
| --- | --- |
| Windows | `%USERPROFILE%\.codex\pets\cheems\` |
| macOS / Linux | `~/.codex/pets/cheems/` |

如果设置了 `CODEX_HOME`，请使用该目录下的 `pets/cheems/`。确保两个文件直接位于 `cheems` 文件夹中，没有多嵌套一层。`pet.json` 中的 `spriteVersionNumber` 必须保留为 `2`。

### 动作与角色

- **日常：** 胸前贴着一包薯条，薯条从嘴边分段缩短、消失，配合两下很轻的点头。
- **工作：** 电脑贴在身前，沿用与日常和其他状态完全相同的身体底图；另有电脑前吃薯条的动画，薯条逐段送入口中，配合两次极轻的点动，身前没有薯条包。
- **等待确认：** 文件与签字笔贴在身前。
- **打招呼与移动：** 轻轻点头，左右移动时保持克制。保留原本四肢，没有额外的手，也没有跳跃表演。
- **视线跟随：** 包含 16 个方向的姿势，保持坐姿。

这只 Cheems 高冷、聪明，情感丰富但表达内敛。

### 动画调度

客户端决定何时显示日常、工作、等待确认或其他状态。这个资源包提供对应画面，不修改客户端的状态优先级、鼠标交互或触发间隔。因此，即使有任务正在执行，也不能保证宠物始终显示电脑。

### 文件说明

| 文件 | 用途 |
| --- | --- |
| `pet.json` | Codex 本地自定义宠物清单 |
| `cheems.png` | 完整透明 v2 动画精灵图，1536 × 2288 像素 |
| `preview-idle.gif` | 日常吃薯条预览 |
| `preview-review.gif` | 电脑前吃薯条预览 |
| `SHA256SUMS.txt` | 文件完整性校验值 |

GIF 用于预览，实际宠物使用 `cheems.png`。

## English

### Install in Codex

Requires a Codex desktop client that supports custom v2 pets.

Download `Cheems-Codex-Pet-v1.0.0.zip`, drag the ZIP into a Codex conversation, and enter: **“Install and load the Cheems pet from this ZIP.”** Alternatively, follow the manual installation steps below.

#### Manual installation

1. Download and extract `Cheems-Codex-Pet-v1.0.0.zip`, or download `pet.json` and `cheems.png` from the repository.
2. Create a `cheems` folder inside the `pets` folder in your Codex data directory. Place `pet.json` and `cheems.png` directly inside it.
3. Open the client's pet settings, refresh the custom pet list, and select **Cheems — Codex 虚拟宠物 / Cheems — A Codex Pet**.

Default locations:

| System | Folder |
| --- | --- |
| Windows | `%USERPROFILE%\.codex\pets\cheems\` |
| macOS / Linux | `~/.codex/pets/cheems/` |

If `CODEX_HOME` is set, use `pets/cheems/` inside that directory instead. Keep both files directly in the `cheems` folder, without an extra nested folder. Keep `spriteVersionNumber` set to `2` in `pet.json`.

### Character and animations

- **Idle:** A packet of fries rests against the chest. A fry shortens into the mouth, accompanied by two tiny nods.
- **Work:** A laptop sits in front of Cheems, over the same body used in idle and every other state. A separate laptop animation shows a fry gradually disappearing into the mouth with two tiny movements, without a fries packet.
- **Waiting for confirmation:** A document and signing pen appear in front of the chest.
- **Greeting and movement:** Small nods and restrained movement. The original four limbs are preserved, with no extra hands or jumping performance.
- **Pointer tracking:** Sixteen directional poses preserve the seated silhouette.

Cheems is cool and clever, with a rich inner life and understated reactions.

### Animation scheduling

The client chooses when to show idle, working, waiting, and other states. This asset package supplies their artwork; it does not change the client's state priorities, pointer interactions, or trigger intervals. An active task therefore does not guarantee that the pet always displays the laptop.

### Included files

| File | Purpose |
| --- | --- |
| `pet.json` | Manifest for a local Codex custom pet |
| `cheems.png` | Complete transparent v2 sprite sheet, 1536 × 2288 pixels |
| `preview-idle.gif` | Idle snack preview |
| `preview-review.gif` | Laptop snack preview |
| `SHA256SUMS.txt` | File integrity checksums |

The GIFs are previews. The installed pet uses `cheems.png`.

## 格式 / Format

v2 · PNG · 1536 × 2288 px · 8 × 11 cells · 192 × 208 px per cell · 73 poses

## 官方参考 / Official references

- [Pets: settings and custom pets](https://learn.chatgpt.com/docs/pets)
- [Codex pet installation links and v2 support](https://learn.chatgpt.com/docs/reference/commands#pets)
