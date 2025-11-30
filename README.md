# Basic 5e 2025 Layout for Obsidian Fantasy Statblocks

This custom layout brings the aesthetic of the **2025 Monster Manual** to your Obsidian vault. It is designed to match the new official styling as closely as possible, featuring dynamic headers, refined typography, and print-quality spacing.

---

## ✨ Features

### **2025 Official Styling**  
Meticulously tweaked borders, fonts, and spacing to match the latest 5e design language.

### **Smart Dynamic Header**
- **No Image:** The monster name and type span the full width.  
- **Image Present:** The text automatically wraps to the left while the image pins to the top-right corner.

### **Advanced Data Parsing**  
Built-in handling for newer 5e.tools data formats ensures smooth rendering of complex properties while maintaining full compatibility with standard CLI tool data.

### **Clean List Formatting**  
Messy text blocks (like multi-attack descriptions or spell lists) are automatically re-styled into readable, bolded lists.

### **Print-Ready**  
“Aggressive” CSS fixes remove unnecessary padding for crisp, compact statblocks.

---

## 📥 Installation Guide

You do **not** need to write any code — simply import the provided JSON file.

### **1. Download the Layout**
Ensure you have the **`Basic 5e 2025 Layout.json`** file saved to your computer.

### **2. Import into Obsidian**
1. Open **Obsidian Settings**.  
2. Navigate to **Fantasy Statblocks** in the plugin list.  
3. Scroll to the **Layouts** section.  
4. Click **Import Layout** (download arrow icon).  
5. Select the `Basic 5e 2025 Layout.json` file.  
6. Restart Obsidian

The layout should now appear in your list of available layouts and can be set as a default layout.

> [!warning]
> **Do not try to import a layout with parenthesis `()` or other symbols.**  
> Doing so can cause issues with the plugin.  
> [Related issue](https://github.com/javalent/fantasy-statblocks/issues/511)


---

## 🧰 Usage

To use this style, specify the layout name in your statblock code block:

```statblock
layout: Basic 5e 2025
name: Beholder
image: [[MyBeholderImage.png]]
stats:
```

## ⚠️ Compatibility & Limitations
### ITS Theme

This layout does not currently support specific ITS Theme styling features. It is fully functional and usable in its current state, but it may not inherit ITS-specific aesthetic overrides or custom theme hooks.

### Image Aspect Ratio

For the best results, ensure your monster images are cropped square or close to square. While the layout will handle most aspect ratios gracefully, square or near-square images produce the most consistent visual results.

## 📸 Screenshots

## Samples
![Kraken](https://github.com/matthttam/fantasy-statblocks-layout-2025/blob/v1.0.4/screenshots/Kraken%20(XMM).png?raw=true)

![Kenku](https://github.com/matthttam/fantasy-statblocks-layout-2025/blob/v1.0.4/screenshots/Kenku%20(XMM).png?raw=true)

![Druid](https://github.com/matthttam/fantasy-statblocks-layout-2025/blob/v1.0.4/screenshots/Druid%20(XMM).png?raw=true)

![Beholder](https://github.com/matthttam/fantasy-statblocks-layout-2025/blob/v1.0.4/screenshots/Beholder%20(XMM).png?raw=true)

## 🐞 Known Issues

- **Legendary Actions description loads slightly late.**  
  This is mostly a non-issue but worth noting: the description text for Legendary Actions appears moments after the rest of the block because there is no clean injection point *after* the trait header in the layout.



