# Recipe Diagram — Crop Shooter Survival (v4)

> **Legend:** 🟢 Crop · 🔵 Natural / Coop · 🟣 Ingredient · 🔴 Food · 🔵⬜ Bottle · 🟡 Special Craft

---

## Table of Contents
1. [Crops](#crops)
2. [Natural & Coop Drops](#natural--coop-drops)
3. [Ingredients](#ingredients)
4. [Food Recipes](#food-recipes)
5. [Consumable Summary — Food & Bottles](#consumable-summary--food--bottles)
6. [Bottles](#bottles)
7. [Special Crafts](#special-crafts)
8. [Recipe Progression by Day](#recipe-progression-by-day)
9. [Use Cases — Ammo Reference](#use-cases--ammo-reference)
10. [Usage Balance](#usage-balance)

---

## Recipe Slot Rules (3 slots)

- Quy tắc ingame: **Mọi recipe luôn phải có đúng 3 slot** (3 cụm `Item ×N`).
- Nếu recipe chỉ có **2 thành phần** `A×m + B×n`, hãy **tách 1 thành phần** thành 2 slot để đủ 3:
    - `A×m + B×n` → `A×a + B×n + A×(m−a)` (với `1 ≤ a < m`)
- Ưu tiên tách thành phần có số lượng lớn hơn / dễ chia hơn.
- Ví dụ:
    - `🍇 Grape ×16 + 🍬 Sugar ×1` → `🍇 Grape ×8 + 🍬 Sugar ×1 + 🍇 Grape ×8`
    - `🛢️ Bean Oil ×3 + 🧴 Coconut Oil ×1` → `🛢️ Bean Oil ×2 + 🧴 Coconut Oil ×1 + 🛢️ Bean Oil ×1`

---

## Crops

> **Phân loại nguồn gốc:**
> - 🌾 **Crop (Trồng trọt)** — Chỉ có được qua canh tác. Không xuất hiện trong tự nhiên.
> - 🌿 **Crop / Wild** — Có thể trồng hoặc tìm thấy trong tự nhiên (Collect). **Không có yếu tố attacking** nên không bị giới hạn bởi achievement/event.
> - ⚔️ **Crop (Achievement / Event / Reward only)** — Có yếu tố attacking. Chỉ nhận được qua hoạt động cụ thể trong game (achievement, event, reward). Không thể tìm thấy tự do trong môi trường.

| Icon | Name | Unlock Day | Unlock Trigger | Source Type |
|------|------|-----------|----------------|-------------|
| 🫐 | Berry | Day 1 | — | ⚔️ Crop (Achievement / Event / Reward only) |
| 🌾 | Wheat | Day 1 | — | ⚔️ Crop (Achievement / Event / Reward only) |
| 🌱 | Bean | Day 3 | — | ⚔️ Crop (Achievement / Event / Reward only) |
| 🥕 | Carrot | Day 3 | — | ⚔️ Crop (Achievement / Event / Reward only) |
| 🥬 | Cabbage | Day 3 | — | 🌿 Crop / Wild (Collect - Field / Forest Edge) |
| 🥥 | Coconut | Day 3 | — | ⚔️ Crop (Achievement / Event / Reward only) |
| 🫚 | Beetroot | Day 5 | — | 🌿 Crop / Wild (Collect - Field) |
| 🍅 | Tomato | Day 6 | 🗡 Kill 300 monsters *(can unlock earlier)* | ⚔️ Crop (Achievement / Event / Reward only) |
| 🍇 | Grape | Day 8 | 📦 Open a Treasure Pod | ⚔️ Crop (Achievement / Event / Reward only) |
| ⭐ | Carambola | Day 10 | ⚔️ Defeat first Boss | ⚔️ Crop (Achievement / Event / Reward only) |
| 🌶️ | Chili | Day 10 | — | ⚔️ Crop (Achievement / Event / Reward only) |
| 🍎 | Apple | Day 15 | — | ⚔️ Crop (Achievement / Event / Reward only) |
| 🫑 | Pepper | Day 15 | — | ⚔️ Crop (Achievement / Event / Reward only) |
| 🌵 | Durian *(WIP)* | Day 13 | — | ⚔️ Crop (Achievement / Event / Reward only) |
| 🍈 | Noni Fruit *(WIP)* | Day 20 | — | 🌿 Crop / Wild (Collect - Forest) |
| 🍑 | Pomegranate *(WIP)* | Day 20 | — | 🌿 Crop / Wild (Collect - Forest) |

---

## Natural & Coop Drops

> **Phân loại nguồn thu thập:**
> - 🌿 **Wild** — Tìm thấy trong môi trường tự nhiên. Thu thập qua **Collect**. Không có yếu tố attacking.
> - 👾 **Drop** — Rơi ra từ enemy khi tiêu diệt.
> - 🐔 **Coop** — Sản xuất từ công trình (Coop, Apiary).

| Icon | Name | Type | Day | Source |
|------|------|------|-----|--------|
| 💀 | Monster Meat | Drop | Day 1 | 👾 Night wave drop |
| 🔧 | Metal Scrap | Wild | Day 1 | Collect - Ruins |
| 🟡 | Sand | Wild | Day 1 | Collect - Beach |
| 🌿 | Heartleaf Gelsemium | Wild | Day 1 | Collect - Ruins |
| 🔩 | Iceron | Wild | Day 1 | Collect - Surface |
| ⚡ | Power Shard | Wild | Day 1 | Collect - Surface |
| 🟤 | Guarana | Wild | Day 1 | Collect - Surface |
| 🥚 | Egg | Coop | Day 7 | 🐔 Coop reproduction *(Trigger: 🏗 Build Coop)* |
| 🍯 | Honey | Coop | Day 7 | 🤖 Apiary Gadget *(Trigger: Place first Apiary Gadget)* |
| 🖤 | Coal | Wild | Day 13 | Collect - Caves |
| 🌑 | Belladonna | Wild | Day 13 | Collect - Caves |
| 🌲 | Pine | Wild | Day 15 | Collect - Deep Caves |
| 🌿 | Hippomane mancinella | Wild | Day 16 | Collect - Deep Caves |
| 💛 | Gold Crystal | Wild | Day 20 | Collect - Mountains |
| 🌱 | Cephalotaxus Fortunei | Wild | Day 20 | Collect - Forest / Mountains |

> **Lưu ý:** Tất cả các loại thảo dược và nguyên liệu tự nhiên trong bảng này **không có yếu tố attacking** — có thể tìm thấy tự do trong môi trường qua hoạt động Collect, không bị giới hạn bởi achievement hay event.

---

## Ingredients

All crafted at ⚗️ Crafting Station.

| Icon | Name | Day | Recipe |
|------|------|-----|--------|
| 🥐 | Flour | Day 1 | 🌾 Wheat ×9 (3×3) |
| 🔋 | Power Core | Day 1 | ⚡ Power Shard ×1 + 🔧 Metal Scrap ×1 + 🔩 Iceron ×1 |
| 🛢️ | Bean Oil | Day 3 | 🌱 Bean ×9 (3×3) |
| 🧴 | Coconut Oil | Day 3 | 🥥 Coconut ×9 (3×3) |
| 🥛 | Coconut Milk | Day 3 | 🥥 Coconut ×9 (3×3) |
| 🧈 | Margarine | Day 3 | 🛢️ Bean Oil ×3 + 🧴 Coconut Oil ×1 |
| 🍬 | Sugar | Day 5 | 🫚 Beetroot ×9 (3×3) |
| 🧪 | Glass Vial Lv1 | Day 5 | 🟡 Sand ×9 (3×3) |
| 🥣 | Cabbage Sauce | Day 6 | 🥬 Cabbage ×6 + 🍬 Sugar ×1 |
| 🍦 | Cream | Day 10 | 🥛 Coconut Milk ×3 + 🍬 Sugar ×1 + 🥚 Egg ×6 |
| 🔬 | Glass Vial Lv2 | Day 15 | 🧪 Vial Lv1 ×3 (3×1) |
| ☠️ | Poison Shard | Day 16 | 🌿 Heartleaf Gelsemium ×3 + 🌱 Cephalotaxus Fortunei ×3 + 🌑 Belladonna ×3 |
| ⚗️ | Glass Vial Lv3 | Day 20 | 🔬 Vial Lv2 ×3 (3×1) |

---

## Food Recipes

All crafted at ⚗️ Crafting Station.

| Icon | Name | Day | HP | Mechanic | Recipe |
|------|------|-----|----|----------|--------|
| 🍞 | Bread | Day 5 | +5 HP | Heal | 🥐 Flour ×1 + 🍬 Sugar ×1 + 🥐 Flour ×1 |
| 🍳 | Omelet | Day 7 | +25 HP | **REGEN** — +HP regen after eating | 🥚 Egg ×9 (3×3) |
| 🥖 | Soggy Bread | Day 5 | +30 HP | **STEALTH** — Monsters ignore you temporarily | 🥐 Flour ×3 + 💀 Monster Meat ×6 |
| 🎂 | Berry Cake | Day 5 | +20 HP | **BOTTLE** → Frost Bottle | 🥐 Flour ×1 + 🫐 Berry ×8 + 🍬 Sugar ×1 |
| 🍔 | Burger Berry | Day 6 | +25 HP | **BOTTLE** → Burstger Bottle | 🍞 Bread ×1 + 🥬 Cabbage ×3 + 🫐 Berry ×9 |
| 🍡 | Sweet Grapeball | Day 8 | +20 HP | **BOTTLE** → Cluster Bottle | 🍇 Grape ×6 + 🍬 Sugar ×3 + 🥐 Flour ×6 |
| 🥪 | Bunny Burger | Day 8 | +15 HP | **CRAFT** — Ap-pleClear Ca-Rotket (1/3) | 🥕 Carrot ×6 + 🧈 Margarine ×3 + 🍞 Bread ×3 |
| 🧁 | Carrot Cake | Day 8 | +40 HP | **CRAFT** — Ap-pleClear Ca-Rotket (2/3) | 🥕 Carrot ×6 + 🥛 Coconut Milk ×3 + 🍬 Sugar ×3 |
| 🍲 | Tomato Soup | Day 10 | +75 HP ↑ | **BOTTLE** → Critical Souper | 🍅 Tomato ×6 + 🧈 Margarine ×3 + 🍬 Sugar ×3 |
| 🌭 | Burnwich | Day 13 | +35 HP | **BOTTLE** → Capsaicin Bottle | 🥐 Flour ×3 + 🌶️ Chili ×9 + 🥣 Cabbage Sauce ×3 |
| 🔥 | Hell Breath Mashed | Day 13 | +50 HP | **BOTTLE** → Atropine Bottle | 🌵 Durian ×6 + 🧈 Margarine ×3 + 🌶️ Chili ×9 |
| 🌟 | Carambola Cake | Day 13 | +60 HP | **BOTTLE** → Arc Bottle | ⭐ Carambola ×6 + 🥛 Coconut Milk ×3 + 🥣 Cabbage Sauce ×3 |
| 🥧 | Apple Pie | Day 16 | +100 HP | **CRAFT** — Ap-pleClear Ca-Rotket (3/3) | 🍎 Apple ×3 + 🥐 Flour ×3 + 🍦 Cream ×3 |
| 🥗 | Hot and Sour Salad | Day 16 | +150 HP ↑ | **BOTTLE** → Phorbol Bottle | 🍅 Tomato ×9 + ⭐ Carambola ×3 + 🫑 Pepper ×3 |
| 🍰 | Honey Cake | Day 16 | +80 HP | **BOTTLE** → Fortunei Bottle | 🍯 Honey ×6 + 🥐 Flour ×1 + 🥛 Coconut Milk ×3 |

> ↑ = includes HP regeneration effect

---

## Consumable Summary — Food & Bottles

Danh sách tất cả items có thể tiêu thụ trực tiếp, kèm hiệu ứng nhận được.

### 🍽️ Food — Ăn trực tiếp để hồi máu / nhận buff

| Icon | Name | Day | HP Restored | Bonus Effect |
|------|------|-----|------------|--------------|
| 🍞 | Bread | Day 5 | +5 HP | — |
| 🥖 | Soggy Bread | Day 5 | +30 HP | **Stealth** — quái vật bỏ qua bạn tạm thời |
| 🎂 | Berry Cake | Day 5 | +20 HP | — *(nguyên liệu Frosteratrol Bottle)* |
| 🍔 | Burger Berry | Day 6 | +25 HP | — *(nguyên liệu Burstger Bottle)* |
| 🍳 | Omelet | Day 7 | +25 HP | **Regen** — hồi HP liên tục sau khi ăn |
| 🍡 | Sweet Grapeball | Day 8 | +20 HP | — *(nguyên liệu Dynamite Bottle)* |
| 🥪 | Bunny Burger | Day 8 | +15 HP | — *(craft step 1/3)* |
| 🧁 | Carrot Cake | Day 8 | +40 HP | — *(craft step 2/3)* |
| 🍲 | Tomato Soup | Day 10 | +75 HP ↑ | **Regen** — hồi HP liên tục *(nguyên liệu Critical Souper)* |
| 🌭 | Burnwich | Day 13 | +35 HP | — *(nguyên liệu Capsaicin Bottle)* |
| 🔥 | Hell Breath Mashed | Day 13 | +50 HP | — *(nguyên liệu Atropine Bottle)* |
| 🌟 | Carambola Cake | Day 13 | +60 HP | — *(nguyên liệu Voltaic Bottle)* |
| 🥧 | Apple Pie | Day 16 | +100 HP | — *(craft step 3/3)* |
| 🥗 | Hot and Sour Salad | Day 16 | +150 HP ↑ | **Regen** — hồi HP liên tục *(nguyên liệu Phorbol Bottle)* |
| 🍰 | Honey Cake | Day 16 | +80 HP | — *(nguyên liệu Fortunei Bottle)* |

> **Lưu ý:** Food đánh dấu *(nguyên liệu Bottle)* vẫn có thể ăn trực tiếp để hồi máu — nhưng tiêu thụ nguồn cung bottle. Cân nhắc ưu tiên trước khi ăn.

### 🧪 Bottles — Sử dụng trên vũ khí để kích hoạt hiệu ứng chiến đấu

> **Quy tắc kết hợp:** Các bottle có thể phối hợp với nhau, nhưng **tối đa 2 bottle cùng lúc**.

Xem chi tiết hiệu ứng tại [mục Bottles](#bottles) bên dưới.

| Icon | Name | Tier | Duration | Effect tóm tắt |
|------|------|------|----------|----------------|
| 🧊 | Frosteratrol Bottle | T1 | 12s | Làm chậm · đóng băng · tăng dmg nhận |
| ⚡ | Burstger Bottle | T1 | 7s | Tăng tốc độ bắn, +10% bullet spread (trade-off) |
| 🎯 | Critical Souper | T2 | 7s | Crit 100% · ×2 dmg · headshot ×3.5 bonus |
| 🔆 | Capsaicin Bottle | T3 | 15s | Tăng dmg · fire trail visual · rocket proc |
| 🐍 | Atropine Bottle | T3 | 12s | Stack độc tối đa 7 lần + auto zoom out (trade-off vs zoom in) |
| 💥 | Dynamite Bottle | T3 | 8s | Proc bom gắn lên enemy, nổ AoE sau delay |
| 🟢 | Phorbol Bottle | T3 | 10s | Xuyên giáp 50% + stack 5 lần → đạn xuyên qua enemy |
| 🌩️ | Voltaic Bottle | T4 | 8s | Chain điện 4 mục tiêu |
| ☁️ | Fortunei Bottle | T4 | 20s | Cloud độc AoE · drop Fragment (heal + buff random) khi enemy bị kết liễu bởi smoke |

---

## Bottles

> **⚠️ Cơ chế chung của tất cả Bottles:** Bottle **không** tạo thêm đạn hay ném lựu đạn riêng. Hiệu ứng của bottle được kích hoạt **theo xác suất trên mỗi lượt bắn trúng mục tiêu** từ vũ khí trang bị. Bottle chỉ bổ sung lớp hiệu ứng lên đạn bắn ra — không thay đổi cơ chế bắn của vũ khí.

> **⚠️ Giới hạn kết hợp:** Có thể dùng đồng thời nhiều bottle, nhưng **tối đa 2 bottle cùng hoạt động một lúc**.

---

### Tier 1 (Day 5–8)

#### 🧊 Frosteratrol Bottle — *"Chill & Punish"*
> **Day 5 · Duration: 12s · Compatible: SMG · AR**
> *Cơ chế: Theo xác suất trên mỗi lượt bắn trúng mục tiêu — không tạo đạn hay ném lựu đạn.*

| Attribute | Value |
|-----------|-------|
| Recipe | 🎂 Berry Cake ×8 + 🧪 Vial Lv1 ×1 + 🔩 Iceron ×2 |
| Slow | **30%** movement speed reduction |
| Freeze | **10% chance** → frozen for **2.5s** |
| Damage amp (Slow) | Enemy nhận +**10%** dmg khi đang bị Slow |
| Damage amp (Freeze) | Enemy nhận +**20%** dmg khi đang bị Frozen |

**Cơ chế:** Mỗi lượt bắn trúng enemy có xác suất kích hoạt Slow (30% move speed reduction). Ngoài ra, mỗi phát có 10% cơ hội kích hoạt Freeze cứng người trong 2.5s — trong thời gian đó enemy nhận thêm 20% dmg. Enemy đang bị Slow (chưa Freeze) nhận +10% dmg.

**🎯 Best against:**
- 🏃 **Sprinter** *(cận chiến tốc độ cao)* — Frost kéo giảm tốc độ lao vào, cho thời gian xử lý
- 🛡️ **Armored Charger** *(cận chiến giáp dày)* — Freeze 2.5s tạo cửa sổ burst dmg qua giáp
- 🐝 **Swarm** *(bay theo bầy, nhỏ)* — SMG spread bắn nhiều, nhiều con bị Slow cùng lúc

---

#### ⚡ Burstger Bottle — *"Speed or Accuracy"*
> **Day 6 · Duration: 7s · Compatible: AR · SMG · Shotgun**
> *Cơ chế: Theo xác suất trên mỗi lượt bắn trúng mục tiêu — không tạo đạn hay ném lựu đạn.*

| Attribute | Value |
|-----------|-------|
| Recipe | 🍔 Burger Berry ×8 + 🧪 Vial Lv1 ×1 + 🟤 Guarana ×2 |
| Fire rate | +50% |
| Spread penalty | +**10%** bullet spread (trade-off) |

**Cơ chế:** Tăng tốc độ bắn đáng kể nhưng súng bị giãn đạn. Hiệu quả nhất khi áp sát hoặc bắn vào nhóm đông — kém hiệu quả ở xa do spread.

**🎯 Best against:**
- 👥 **Horde** *(nhóm đông, cận đến trung)* — Fire rate cao + spread rộng phủ nhiều mục tiêu
- 🪲 **Crawler** *(cận chiến mặt đất, nhỏ)* — Di chuyển nhanh khó aim, bù bằng số lượng đạn
- 🦇 **Bat Swarm** *(bay, di chuyển loạn)* — Shotgun rapidfire đặc biệt hiệu quả ở tầm gần

---

### Tier 2 (Day 10–12)

#### 🎯 Critical Souper — *"Precision Pays Off"*
> **Day 11 · Duration: 7s · Compatible: AR · Shotgun · Sniper**
> *Cơ chế: Theo xác suất trên mỗi lượt bắn trúng mục tiêu — không tạo đạn hay ném lựu đạn.*

| Attribute | Value |
|-----------|-------|
| Recipe | 🍲 Tomato Soup ×8 + 🧪 Vial Lv1 ×1 + 🌱 Cephalotaxus Fortunei ×2 *(unlock Day 20)* |
| Crit rate | 100% (mọi phát đều crit) |
| Crit multiplier | ×**2** base damage |
| Headshot bonus | Headshot thêm ×**1.75** trên nền crit → tổng ×**3.5** |

**Cơ chế:** Trong thời gian hiệu lực, mọi phát đạn đều critical. Nhắm đầu nhận thêm headshot multiplier — tổng damage lên tới 3.5× base. Reward trực tiếp cho kỹ năng aim.

**🎯 Best against:**
- 🧟 **Elite Zombie** *(cận chiến, HP cao)* — Crit burst rút ngắn thời gian hạ
- 🦅 **Aerial Sniper** *(bay, tấn công từ xa)* — Sniper + Crit headshot = one-shot potential
- 🐉 **Mini-Boss** *(bất kỳ loại)* — Window 7s crit lý tưởng để burst phase boss

---

### Tier 3 (Day 13–16)

#### 🔆 Capsaicin Bottle — *"Fire & Rockets"*
> **Day 13 · Duration: 15s · Compatible: Flamethrower · AR**
> *Cơ chế: Theo xác suất trên mỗi lượt bắn trúng mục tiêu — không tạo đạn hay ném lựu đạn.*

| Attribute | Value |
|-----------|-------|
| Recipe | 🌭 Burnwich ×8 + 🧪 Vial Lv1 ×1 + 🖤 Coal ×2 *(Coal unlock Day 13)* |
| Damage bonus | +30% base damage |
| Fire trail | Visual effect — vệt lửa theo đường đạn *(không gây dmg, chỉ effect)* |
| Rocket proc | **8% chance** mỗi phát → bắn thêm rocket mini gây **250% base dmg** |

**Cơ chế:** Mỗi viên đạn có 8% xác suất spawn thêm một rocket mini theo sau, gây 250% base damage khi trúng mục tiêu. Không thể kiểm soát nhưng tạo burst damage bất ngờ. Fire trail chỉ là hiệu ứng hình ảnh ấn tượng — không stack dmg.

**🎯 Best against:**
- 🧱 **Tanky Ground** *(cận chiến, giáp trung)* — Rocket proc xuyên qua HP pool dày
- 🐛 **Tunneler** *(cận chiến, nổi lên đất)* — Flamethrower phủ vùng xung quanh điểm xuất hiện
- 🚁 **Hoverer** *(bay thấp, tiếp cận dần)* — AR + 30% dmg + rocket proc hạ nhanh trước khi vào tầm

---

#### 🐍 Atropine Bottle — *"Commit or Reset"*
> **Day 13 · Duration: 12s · Compatible: Toxic Grenade**
> *Cơ chế: Theo xác suất trên mỗi lượt bắn trúng mục tiêu — không tạo đạn hay ném lựu đạn.*

| Attribute | Value |
|-----------|-------|
| Recipe | 🔥 Hell Breath Mashed ×8 + 🧪 Vial Lv1 ×1 + 🌑 Belladonna ×2 *(unlock Day 13)* |
| Stack damage | +20% base dmg mỗi stack (tối đa **7 stack = +140%**) |
| Stack reset | Đổi sang mục tiêu khác → stack **归零 ngay lập tức** |
| Auto-reset | Không bắn trúng enemy trong **4s** → stack tự giảm về 0 |
| Auto zoom | **Zoom out** tự động khi bottle active *(trade-off: tầm nhìn rộng hơn nhưng mất focus gần)* |

**Cơ chế:** Bắn liên tục vào cùng một enemy để stack độc. Chuyển sang enemy khác hoặc ngừng bắn quá 4s sẽ reset toàn bộ stack. Yêu cầu focus mục tiêu — càng commit càng mạnh. Camera tự động zoom out khi bottle active: tầm nhìn rộng hơn giúp quan sát môi trường, nhưng mất ưu thế focus cận chiến (trade-off).

> **Ví dụ:** Bắn E1 đủ 5 stack → quay sang E2 → E1 mất hết stack. Nếu quay lại E1 sau 4s → phải build lại từ đầu.

**🎯 Best against:**
- 🐘 **Brute** *(cận chiến, HP rất cao, chậm)* — Di chuyển chậm → dễ duy trì stack
- 🕷️ **Spitter** *(tầm xa, đứng yên khi bắn)* — Ít di chuyển → stack tích lũy nhanh
- 🧱 **Armored Walker** *(cận chiến, tiến thẳng)* — Hướng di chuyển dự đoán được → dễ focus

---

#### 💥 Dynamite Bottle — *"Tag & Detonate"*
> **Day 15 · Duration: 8s · Compatible: Grenade · Shotgun**
> *Cơ chế: Theo xác suất trên mỗi lượt bắn trúng mục tiêu — không tạo đạn hay ném lựu đạn.*

| Attribute | Value |
|-----------|-------|
| Recipe | 🍡 Sweet Grapeball ×8 + 🔬 Vial Lv2 ×1 + 🌲 Pine ×2 *(unlock Day 15, chứa Colophony)* |
| Bomb proc | **8% chance** mỗi phát → gắn bom lên enemy |
| Bomb detonation | Sau **1.5s** → nổ AoE **150% base dmg**, bán kính **3m** |
| Max bombs | Một enemy chỉ mang **1 bom** tại một thời điểm |

**Cơ chế:** Khi bắn trúng, có 8% cơ hội gắn bom vào enemy. Sau 1.5s bom phát nổ gây AoE sát thương — có thể chain nếu các enemy đứng gần nhau. Delay tạo cơ hội tactical: đẩy enemy vào đám đông trước khi nổ.

**🎯 Best against:**
- 👥 **Clustered Horde** *(nhóm đông đứng gần nhau)* — AoE chain tối đa hiệu quả
- 🐢 **Slow Tank** *(cận chiến, chậm)* — Delay 1.5s không ảnh hưởng khi enemy chậm
- 🦴 **Skeleton Archer** *(tầm xa, đứng tụ lại)* — Shotgun tầm trung gắn bom, AoE phủ cả nhóm

---

#### 🟢 Phorbol Bottle — *"Strip the Armor"*
> **Day 16 · Duration: 10s · Compatible: Shotgun · Sniper**
> *Cơ chế: Theo xác suất trên mỗi lượt bắn trúng mục tiêu — không tạo đạn hay ném lựu đạn.*

| Attribute | Value |
|-----------|-------|
| Recipe | 🥗 Hot and Sour Salad ×10 + 🔬 Vial Lv2 ×1 + 🌿 Hippomane mancinella ×2 *(unlock Day 16)* |
| Armor penetration | Bỏ qua **50%** chỉ số phòng thủ của enemy |
| Pierce stack | Tích lũy đến **5 stack** → đạn **xuyên qua enemy**, tác động enemy phía sau |
| Pierce range | Range xuyên = **khoảng cách Player → Enemy × 1.2** *(chỉ xuyên enemy, không xuyên tường/địa hình)* |

**Cơ chế:** Mọi viên đạn tự động xuyên qua 50% armor của mục tiêu — đặc biệt hiệu quả với enemy giáp dày. Tích lũy stack sau mỗi phát bắn trúng. Khi đủ 5 stack, đạn bắt đầu xuyên qua enemy và tác động enemy đứng phía sau; tầm xuyên bằng 1.2× khoảng cách từ player đến enemy bị bắn trúng. Stack reset khi hết duration.

**🎯 Best against:**
- 🛡️ **Heavy Armored** *(cận/xa, phòng thủ cao)* — Armor pen 50% là counter trực tiếp
- 🦖 **Boss-type** *(mọi kiểu di chuyển, HP và armor đều cao)* — Kết hợp armor pen + pierce = DPS bền
- 🤖 **Mech Enemy** *(tấn công từ xa, giáp cứng)* — Sniper + Phorbol = burst xuyên giáp + xuyên hàng

---

### Tier 4 (Day 20+)

#### 🌩️ Voltaic Bottle — *"Chain Reaction"*
> **Day 20 · Duration: 8s · Compatible: SMG**
> *Cơ chế: Theo xác suất trên mỗi lượt bắn trúng mục tiêu — không tạo đạn hay ném lựu đạn.*

| Attribute | Value |
|-----------|-------|
| Recipe | 🌟 Carambola Cake ×10 + ⚗️ Vial Lv3 ×1 + 💛 Gold Crystal ×2 |
| Chain targets | Phóng điện chain sang **4** mục tiêu gần nhau |
| Chain damage | **60% base dmg** mỗi bước chain |
| Chain range | ~4m giữa các mục tiêu |

**Cơ chế:** Mỗi viên đạn trúng mục tiêu đầu tiên sẽ chain điện sang tối đa 3 enemy xung quanh (tổng 4 mục tiêu gồm target gốc), mỗi chain giảm 60% base dmg. Hiệu quả nhất khi enemy đứng gần nhau.

**🎯 Best against:**
- 🐝 **Flying Swarm** *(bay theo bầy, di chuyển cụm)* — Chain điện lý tưởng khi chúng bay sát nhau
- 🧟 **Zombie Horde** *(cận chiến, đi thành nhóm)* — SMG rapid fire + chain = clear nhóm nhanh
- 🦇 **Bat Colony** *(bay, cụm dày)* — Tầm chain 4m đủ phủ toàn bộ đàn

---

#### ☁️ Fortunei Bottle — *"Plague & Plunder"*
> **Day 21 · Duration: 20s · Compatible: All weapons**
> *Cơ chế: Theo xác suất trên mỗi lượt bắn trúng mục tiêu — không tạo đạn hay ném lựu đạn.*

| Attribute | Value |
|-----------|-------|
| Recipe | 🍰 Honey Cake ×6 + ⚗️ Vial Lv3 ×1 + ☠️ Poison Shard ×3 |
| Smoke proc | **30% chance** mỗi lượt bắn → tạo vùng khói trên enemy bị bắn trúng |
| Cloud damage | **10 dmg/s**, bán kính **5m AoE**, duration **20s** |
| Kill drop — Fragment | Enemy bị kết liễu **trong khi đang bị smoke** → rơi **Fragment** |
| Fragment effect | Khi nhặt: **hồi HP ngẫu nhiên** hoặc nhận **Buff ngẫu nhiên** (+10% dmg / +15% atk speed / +10% move speed, 5s, tối đa 10 stack) — **random một trong hai** |

**Cơ chế:** Mỗi lượt bắn trúng enemy có 30% cơ hội tạo vùng khói 5m AoE, gây 10 dmg/s trong 20s. Khi enemy chết trong khi đang bị smoke, rơi Fragment. Nhặt Fragment nhận ngẫu nhiên một trong hai hiệu ứng: hồi HP hoặc buff chiến đấu (5s, tối đa 10 stack).

**🎯 Best against:**
- 🐌 **Slow Brute** *(cận chiến, chậm, HP cao)* — Ở lâu trong smoke → nhận đủ dmg/s + fragment rơi nhiều
- 🦟 **Insect Swarm** *(bay thấp, HP thấp, đông)* — HP thấp chết nhanh trong smoke → nhiều Fragment rơi
- 🧙 **Necromancer** *(tầm xa, triệu hồi đám đông)* — 30% proc trên mỗi phát → spam smoke phủ điểm triệu hồi, farm fragment liên tục

---

## Special Crafts

| Icon | Name | Day | Recipe | Effect |
|------|------|-----|--------|--------|
| 🚀 | Ap-pleClear Ca-Rotket | Day 16 | 🥪 Bunny Burger ×1 + 🧁 Carrot Cake ×1 + 🥧 Apple Pie ×1 | Summon a giant carrot rocket carrying apple bombs. Massive AoE — destroys all enemies in range. One-use per night, long cooldown. |

> **Unlock path:** Bunny Burger (1/3) → Carrot Cake (2/3) → Apple Pie (3/3)

---

## Recipe Progression by Day

```
DAY 1
  Crops:       🫐 Berry · 🌾 Wheat
  Natural:     💀 Monster Meat · 🔩 Iceron · 🟡 Sand · 🌿 Heartleaf Gelsemium · 🔧 Metal Scrap · ⚡ Power Shard · 🟤 Guarana
  Ingredients: 🥐 Flour · 🔋 Power Core

DAY 3
  Crops:       🌱 Bean · 🥕 Carrot · 🥬 Cabbage · 🥥 Coconut
  Ingredients: 🛢️ Bean Oil · 🧴 Coconut Oil · 🧈 Margarine · 🥛 Coconut Milk

DAY 5
  Crops:       🫚 Beetroot
  Ingredients: 🍬 Sugar · 🧪 Glass Vial Lv1
  Food:        🍞 Bread · 🥖 Soggy Bread · 🎂 Berry Cake
  Bottle:      🧊 Frosteratrol Bottle

DAY 6
  Crops:       🍅 Tomato  [Trigger: Kill 300 monsters]
  Ingredients: 🥣 Cabbage Sauce
  Food:        🍔 Burger Berry
  Bottle:      ⚡ Burstger Bottle  [requires 🟤 Guarana]

DAY 7
  Natural:     🍯 Honey  [Trigger: Place first Apiary Gadget]
  Natural:     🥚 Egg  [Trigger: Build Coop]
  Food:        🍳 Omelet

DAY 8
  Crops:       🍇 Grape  [Trigger: Open a Treasure Pod]
  Food:        🍡 Sweet Grapeball · 🥪 Bunny Burger · 🧁 Carrot Cake

DAY 10
  Crops:       ⭐ Carambola  [Trigger: Defeat first Boss] · 🌶️ Chili
  Ingredients: 🍦 Cream
  Food:        🍲 Tomato Soup

DAY 11
  Bottle:      🎯 Critical Souper  [requires 🌱 Cephalotaxus Fortunei — available Day 20, bottle unlocks when ingredient is obtained]

DAY 13
  Crops:       🌵 Durian (WIP)
  Natural:     🖤 Coal · 🌑 Belladonna
  Food:        🌭 Burnwich · 🔥 Hell Breath Mashed · 🌟 Carambola Cake
  Bottle:      🔆 Capsaicin Bottle · 🐍 Atropine Bottle  [Atropine requires 🌑 Belladonna]

DAY 15
  Crops:       🍎 Apple · 🫑 Pepper
  Natural:     🌲 Pine  *(chứa Colophony)*
  Ingredients: 🔬 Glass Vial Lv2  [3× Vial Lv1]
  Bottle:      💥 Dynamite Bottle  [requires 🌲 Pine]

DAY 16
  Natural:     🌿 Hippomane mancinella
  Ingredients: ☠️ Poison Shard
  Food:        🥧 Apple Pie · 🥗 Hot and Sour Salad · 🍰 Honey Cake
  Bottle:      🟢 Phorbol Bottle  [requires 🌿 Hippomane mancinella]
  Special:     🚀 Ap-pleClear Ca-Rotket

DAY 20
  Crops:       🍈 Noni Fruit (WIP) · 🍑 Pomegranate (WIP)
  Natural:     💛 Gold Crystal · 🌱 Cephalotaxus Fortunei
  Ingredients: ⚗️ Glass Vial Lv3  [3× Vial Lv2]
  Bottle:      🌩️ Voltaic Bottle

DAY 21
  Bottle:      ☁️ Fortunei Bottle  [requires ☠️ Poison Shard Day 16]
```

---

## Use Cases — Ammo Reference

Crops can be used directly as ammunition:

| Crop | Gun Type |
|------|----------|
| 🫐 Berry | AR |
| 🌾 Wheat | SMG |
| 🍅 Tomato | Shotgun |
| 🌱 Bean | SMG |
| 🥥 Coconut | Grenade (Apple-type) |
| ⭐ Carambola | Sniper |
| 🌶️ Chili | Flamethrower |
| 🍎 Apple | Grenade |
| 🫑 Pepper | Toxic Grenade |
| 🍇 Grape | *(special)* |
| 🌵 Durian | TBD |
| 🍈 Noni Fruit | TBD |
| 🍑 Pomegranate | TBD |

---

## Usage Balance

Total quantity of each item consumed across all recipes.

### Bảng tổng hợp lượng tiêu thụ (ước tính theo công thức hiện tại)

| Item | Total Used | Tier |
|------|-----------|------|
| 🥐 Flour | ~45 | **Common** |
| 🍬 Sugar | ~38 | **Common** |
| 🥛 Coconut Milk | ~29 | **Common** |
| 🥕 Carrot | ~18 | **Mid** |
| 🍅 Tomato | ~21 | **Common** |
| 🫐 Berry | ~17 | **Mid** |
| 🥚 Egg | ~15 | **Mid** |
| 🌶️ Chili | ~18 | **Mid** |
| ⭐ Carambola | ~15 | **Mid** |
| 🧈 Margarine | ~17 | **Mid** |
| 🥬 Cabbage | ~12 | **Mid** |
| 🍯 Honey | ~6 | **Niche** |
| 🍇 Grape | ~6 | **Niche** |
| 🍎 Apple | ~3 | **Niche** |
| 🌵 Durian | ~6 | **Niche** |
| 🍞 Bread | ~4 | **Niche** |
| 🧪 Vial Lv1 | ~8 | **Mid** |
| 🔬 Vial Lv2 | ~5 | **Niche** |
| ⚗️ Vial Lv3 | ~2 | **Niche** |
| ☠️ Poison Shard | ~3 | **Niche** |
| 🌿 Heartleaf Gelsemium | ~3 | **Niche** |
| 🌱 Cephalotaxus Fortunei | ~5 | **Niche** |
| 🌑 Belladonna | ~5 | **Niche** |
| 🌲 Pine | ~2 | **Niche** |
| 🌿 Hippomane mancinella | ~2 | **Niche** |
| 💛 Gold Crystal | ~2 | **Niche** |
| 🔩 Iceron | ~3 | **Niche** |
| 🟤 Guarana | ~4 | **Niche** |
| 🖤 Coal | ~2 | **Niche** |

### Tier Definitions

| Tier | Quantity | Notes |
|------|----------|-------|
| **Staple** | 50+ | Core staple — ensure stable farm supply |
| **Common** | 20–49 | Versatile mid-tier. Balanced across recipes |
| **Mid** | 8–19 | Healthy usage — no bottleneck expected |
| **Niche** | < 8 | Late-game or specific use — scarcity via grow time is intentional |

### Key Balance Notes

- **Flour, Sugar, Coconut Milk** là top-tier demand items (Common range). Nên ưu tiên farm Wheat, Beetroot, Coconut từ sớm.
- **Carrot, Tomato, Chili, Margarine, Carambola, Berry** nằm ở mid-range — cần cân đối, không bị bottleneck nhưng cũng không được lơ là.
- **Durian** (Day 13 crop mới) đã có demand rõ ràng qua Hell Breath Mashed — không phải WIP idle; đảm bảo có nguồn cung khi mở khóa Day 13.
- **Glass Vial** không còn phụ thuộc vào Ruby hay Gold Crystal — progression hoàn toàn tuyến tính (Sand → Lv1 → ×3 Lv2 → ×3 Lv3). Bottleneck duy nhất là Sand (Day 1, luôn có sẵn).
- **Poison Shard** (Day 16) dùng 3 thảo dược Wild (Heartleaf, Cephalotaxus, Belladonna) — tất cả đều Collect, không bị chặn bởi achievement. Dễ farm hơn version trước.
- **Egg** dùng ở Cream (Day 10) và Omelet (Day 7) — Coop cần được build trước Day 7. Không có bottleneck nếu Coop up đúng thời điểm.
- **Các Niche items** (Pine, Hippomane, Gold Crystal, Coal, Guarana) chỉ dùng trong 1–2 recipe specific — scarcity là intentional, không cần farm lớn.
- **Fortunei Bottle** (T4) chỉ cần Honey Cake + Vial Lv3 + Poison Shard — không còn phụ thuộc Acid Shard. Unlock path gọn hơn.
- **Không còn Circuit, Wood, Stone, Ruby** trong bất kỳ recipe nào — loại bỏ hoàn toàn dependency vào builder resources.
