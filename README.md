# Arrows Combat Plugin

**Arrows Combat** revolutionizes Unreal Engine combat development. This highly optimized, plug-and-play plugin provides a complete and customizable combat system, ideal for rapid prototyping or full-scale production in hack-and-slash, adventure, and action games. Enjoy flexibility and performance straight out of the box.

<img width="128" height="128" alt="Icon128" src="https://github.com/user-attachments/assets/2e04d47c-a493-402a-9292-b32ea810acc6" />

| UE 5.3 | UE 5.4 | UE 5.5 | UE 5.6 |
|--------|--------|--------|--------|
| ⏳ Soon | ⏳ Soon | ✅ Supported | ⏳ Soon |

marketplace link : [coming soon].

- [📘 Open full documentation](https://github.com/NfuDev/ArrowsCombatSystem-Documentation/wiki)

---

## ✨ Features
- Attach **ArrowsCombatComponent** to any character to enable combat capabilities with no extra coding required.
- Use **Fighting Style** assets to define attack rules, execution conditions, and animation flow. These assets allow montages to be reused across multiple characters sharing the same style.
- Supports **combos, input buffering, and reaction syncing** for responsive combat.
- Includes **custom AnimNotifyStates** for managing input dead zones, damage periods, hit reactions, and execution syncing.
- Can be used with enemy's AI with simple API
- Customized motion warping notifies for easy combat-driven root motion, and you don't have to worry about setting it up.

---

## 🚀 Quick Start
1. Add an **ArrowsCombatComponent** to your character.
2. Create **Body Definition** and **Fighting Style** assets and populate them with attack, execution, and reaction data.
3. Assign the assets to the component.
4. Add the provided **combat notifies** (e.g., DamagePeriod, InputDeadZone) to your animation montages.
5. Bind to the exposed Delegates the logics you need for each case (e.g, OnOwnerDied, OnPreformedExecution...).
6. <u>with that you are ready to play in PIE and test your fighting style , the system does all the inputs binding behind the scene for you.</u>

---

Copyright Arrows Interactive Systems, nightfall16@2025. All Rights Reserved.

