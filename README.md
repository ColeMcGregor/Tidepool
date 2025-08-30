# Tidepool 

**Tidepool** is a tile-based exploration game about chasing the ocean as it recedes, uncovering hidden pools of shells and sea life, and racing back before the tide returns.

---

##  Gameplay

- **Explore the beach** as the tide goes out, revealing wet sand, pools, and treasures.  
- **Collect** shells, starfish, crabs, pearls, fossils, and more.  
- **Navigate terrain**:
  - Dry/Wet Sand: walkable
  - Pools: collectable
  - Water: requires swimming
  - Boulder: must go around  
- **Risk & Reward**: The farther you venture, the rarer and more valuable the finds.  
- **Beware the tide**: If it catches you, you’ll be swept into the water and lose **2/3 of your inventory** at random.  

---

##  Features (planned)

- Tile-based world grid with distinct cell types (Water, Sand, Pools, Boulder).  
- Dynamic **tide system** (Ebb → Slack → Flood).  
- Randomized **spawn tables** for pool contents.  
- Inventory, scoring, and collection mechanics.  
- HUD showing tide phase, clock, and collected items.  
- Sound & animation feedback.  

---


##  Structure

- **Core** – event bus, time, RNG  
- **World** – grid, cells, tide model, spawn tables  
- **Systems** – tide, movement, collection, hazards, inventory  
- **Entities** – player, items  
- **Rendering/UI** – sprites, HUD, sounds  
- **Persistence** – save/load  



---

## 📜 License

MIT License. See [LICENSE](LICENSE) for details.
