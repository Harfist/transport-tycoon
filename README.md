# Transport Tycoon: Automation

An isometric and 2D top-down browser-based transport simulation built with vanilla HTML5 Canvas, JavaScript, and the Web Audio API.

Live Demo: [harfist.github.io/transport-tycoon](https://harfist.github.io/transport-tycoon/)

## Core Mechanics & Features

### 1. Construction & Transport Networks
- **Paved Streets ($20):** Edge-to-edge 4-way bitmask autotiled asphalt streets with curbed borders and yellow dashed centerlines.
- **Road Bridges ($80):** Laying streets across water automatically builds elevated road bridges with support piers and safety railings.
- **Railroads ($35):** Dual steel rails with wooden sleepers and charcoal ballast autotiling in 4 directions.
- **Railway Trestle Bridges ($120):** Laying rails across water automatically constructs timber/steel trestle bridges.
- **Railroad Level Crossings:** Laying roads over rails (or vice versa) creates functional level crossings for both vehicles and trains.
- **Train Stations ($600):** Platform, gabled roof canopy, and clock tower. Connect stations with rails to activate high-speed express train lines.
- **Town Founding ($2,000) & Housing ($150):** Expand municipal borders, increase local population, and unlock subsidies.

### 2. Supply Chains & Industries
- **Primary Producers:**
  - ⛏️ **Coal Mines:** Extracted ore delivered to Factories ($240 payout).
  - 🌾 **Farms:** Grain & dairy delivered to Town Markets ($210 payout).
  - 🌲 **Forest & Sawmills:** Timber logs delivered to Factories ($220 payout).
- **Secondary Processing:**
  - 🏭 **Manufacturing Plants:** Consume Coal & Timber to produce Manufactured Goods ($350 payout).
- **Automation:** Connecting producers to consumers with roads or rails automatically launches dedicated cargo trucks or freight trains.

### 3. Fleet & Logistics Management
- Dedicated **Fleet Manager** modal inspecting all active Delivery Vans, Cargo Trucks, and Express Trains.
- View real-time speed, assigned route, cargo load, and lifetime earnings.
- Camera vehicle locator tool and fleet-wide engine upgrades (+25% speed).

### 4. Persistence & Tools
- **Auto-Save:** Saves game state to browser `localStorage` every 45 seconds.
- **Manual Save & Load:** Instant browser save slot restoration.
- **JSON Export & Import:** Download complete game saves as `.json` or import previously exported territories.
- **Procedural Map Generator:** Presets from Tiny (20x20) to Continental World (160x160) with custom water and tree density sliders.
