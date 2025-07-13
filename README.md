# GeyserModelEngineBlockbenchPacker-MultiExport

A fork of [GeyserModelEngineBlockbenchPacker](https://github.com/GeyserExtensionists/GeyserModelEngineBlockbenchPacker) with the goal of supporting **multi-export** from Blockbench.

This version allows you to export **all open projects** at once into a single zip file, making it easier to work with multi-model setups.

---

## 🔧 Installation

Install this plugin like any other Blockbench plugin.

> ⚠️ **Recommendation:**  
> It is highly recommended to also install the [original packer](https://github.com/GeyserExtensionists/GeyserModelEngineBlockbenchPacker) for **single-project exports**, as this fork is optimized specifically for multi-export.

---

## 🚀 How to Use

1. Open **Blockbench** and install this plugin.
2. You will see a new menu option:  
   **`File > Export > Export GeyserModelEngine Model (All open projects)`**
3. Open as many Blockbench projects as you want to export.
4. Click the new export option to begin the multi-export process.
5. Choose the destination for the output `.zip` file.
6. After export, Blockbench will display a **"Export complete!"** notification.
7. The output file will be named like:  
   **`geyser_model_pack_${Date.now()}.zip`**
8. Inside the zip file, each open project will have its own folder containing its exported files.

---

## 📁 Output Structure

```
geyser_model_pack_${Date.now()}.zip
├── ProjectOne/
│ ├── model.geo.json
│ ├── texture.png
│ └── ...
├── ProjectTwo/
│ ├── model.geo.json
│ ├── texture.png
│ └── ...
└── ...
```


---

## 🙏 Credits

- Original plugin by: [GeyserExtensionists](https://github.com/GeyserExtensionists)  
- Multi-export fork by: [ElMand-o](https://github.com/ElMand-o)
