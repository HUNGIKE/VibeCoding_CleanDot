# Red Dot Mini Game

## 繁體中文

這是使用 LLM（Large Language Model）進行 *vibe coding* 開發，並搭配少量人工調整完成的小型瀏覽器遊戲。

這個README.md 也是簡單敘述後，由 LLM 協助產生的。


### 遊戲說明

玩家控制畫面中的紅點，在灰色區域中移動：

- 🔴 紅點：玩家控制的角色
- 🟡 黃點：需要被清除，碰到後會轉變為藍點
- 🔵 藍點：會移動並反彈，碰到會導致失敗
- 🟢 綠點：提供短暫無敵效果，可累加（有上限）

設計上刻意保持簡單，但透過：
- 隨機角度反彈
- 時間型無敵機制
- 視覺化狀態提示（圓環）

讓遊戲具有基本的變化性與策略性。

---

## English

This is a small browser game created using LLM (Large Language Model) *vibe coding*, with a small amount of manual refinement.

This README.md was also generated with the help of an LLM based on a simple description.


### Game Description

The player controls a red dot moving inside a gray area:

- 🔴 Red Dot: Player-controlled character
- 🟡 Yellow Dots: Targets to clear; they turn into blue dots when touched
- 🔵 Blue Dots: Moving hazards that bounce around; touching them results in failure
- 🟢 Green Dots: Provide temporary invincibility; can stack (with a cap)

The design is intentionally simple, but enhanced through:
- Slight randomness in reflection angles
- Time-based invincibility mechanics
- Visual state indicator (circular gauge)

This creates a basic level of variation and strategy in gameplay.

