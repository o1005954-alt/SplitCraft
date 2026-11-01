# TextExploder

> **Instant Kinetic Typography Layer Splitter for EffectCraft**

TextExploder is a lightweight, high-performance automation script panel (`.jsx`) built specifically for the open-source **EffectCraft** ecosystem. It eliminates the tedious process of manually cutting, duplicating, and aligning text strings for kinetic typography, motion graphics, and lyrical videos. 

With one click, it non-destructively breaks apart single text layers into individual characters, words, or lines while perfectly preserving their visual layout positions and typographical styles.

---

## 🔥 Core Features

*   **⚡ Multiple Split Horizons**
    Choose exactly how you want your kinetic sequences structured:
    *   **By Character:** Splits text into isolated glyphs—perfect for cascading letter popups.
    *   **By Word:** Separates phrases by whitespace boundaries—ideal for modern rhythmic typography.
    *   **By Line:** Divides paragraphs by carriage breaks—optimized for lower-thirds and captions.

*   **📐 Intelligent Spatial Matrix Locking**
    Enabling *"Match Character Anchor Positions"* mathematically analyzes the text bounds (`sourceRectAtTime`). Each generated sub-string or word is dynamically repositioned so that it aligns flawlessly over its exact pixel location in the original unbroken sentence.

*   **🎨 True Style Inheritance**
    New child layers instantly inherit font families, weights, font sizes, fill tracking matrices, leading baselines, and layout hierarchies from the parent node.

*   **🛡️ Non-Destructive Workflow**
    Toggle between archiving your master sentence block cleanly or disabling/deleting it automatically after processing. Full engine fallback checks ensure any action can be entirely rolled back with a single stroke of `Ctrl + Z` or `Cmd + Z`.

---

## 💾 Installation Guide

To install TextExploder, place the script inside the application's native script UI directory:

1. **Download/Save the file:** Save your generated script file as `TextExploder.jsx`.
2. **Deploy to Folder:** Drop the file into the designated ScriptUI Panels folder:
   * **Windows:** `C:\Program Files\EffectCraft\Support Files\Scripts\ScriptUI Panels\`
   * **macOS:** `/Applications/EffectCraft/Scripts/ScriptUI Panels/`
   * or go to **file** then **scripts** then **install script ui** then chose the file then chose it on the window panel
3. **Initialize the UI:** 
   * Open or restart EffectCraft.
   * Navigate to the top application menu bar: **Window > TextExploder.jsx**.
   * Snap or dock the floating UI palette anywhere inside your custom panel layout space.

---

## 🚀 How to Use It

1. Type out your text phrase using a standard native Text Layer.
2. Select the layer on your timeline panel.
3. Open the **TextExploder** pane.
4. Set the **Split Mode** dropdown (e.g., *By Word*).
5. Configure your anchor tracking preferences and hit **Explode Text Layer**.

---

## ⚙️ System Requirements

* Developed for **EffectCraft (v0.17.0+)** or compatible ExtendScript ECMAScript 3 engine layers.
* No external modules or libraries required.
