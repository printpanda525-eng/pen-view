# Pen View 2.0

Pen View is a Blender add-on designed to improve viewport workflow for artists using pen tablets, compact keyboards, or laptops without a numeric keypad.

It provides fast access to viewport controls, mode switching, sculpt brushes, and measurement guides through a customizable popup interface.

<table align="center">
  <tr>
    <td align="center">
      <img src="image/pen-popup.png" width="300" />
      <br><b>Main Popup</b>
    </td>
    <td align="center">
      <img src="image/pen-brushes.png" width="300" />
      <br><b>Brush Popup</b>
    </td>
  </tr>
</table>

---

## Features

### Viewport Controls
- View orientation shortcuts (Top, Bottom, Front, Back, Left, Right)
- Object, Edit, and Sculpt mode switching
- Move, Rotate, and Scale gizmo selection
- 90-degree rotation helper (X, Y, Z axes)

### Overlays
- Wireframe overlay with opacity control
- Viewport wireframe and X-Ray toggle
- Face orientation overlay

### Selection (Edit Mode)
- Vertex, Edge, and Face selection modes
- Grow / Shrink selection (Expand / Contract)

### Sculpt Brushes
- Customizable brush slot panel (up to 7 brushes) via the N Panel
- Quick popup with your configured brushes, grouped by category
- Full brush library organized by category: General, Paint, Simulation, Tools
- 2-column grid layout per category

### Guides
- Proportional 3D measurement guide
- Drag to place, click to move, clear with one button

### Hide / Unhide
- Hide selection (H), hide unselected (Shift+H), unhide all (Alt+H)
- Works in both Object and Edit mode

---

## Default Shortcuts

| Shortcut | Action |
|---|---|
| `Shift + Q` | Open main popup |
| `Ctrl + Shift + Q` | Open brush popup |
| `Shift + M` | Start measurement guide |
| `Alt + M` | Clear measurement guide |

All shortcuts can be reassigned in Blender's keymap editor under **Edit → Preferences → Keymap**.

---

## Installation

Pen View must be installed as a **classic Blender add-on**, not through the Extensions system.

1. Download the repository as a ZIP file from GitHub.
2. Extract the ZIP file.
3. Copy the `pen_view` folder into your Blender addons directory:

**Windows:**
```
C:\Users\<username>\AppData\Roaming\Blender Foundation\Blender\5.1\scripts\addons\
```

4. Open Blender.
5. Go to **Edit → Preferences → Add-ons**.
6. Search for **Pen View** and enable it.

> ⚠️ Installing through Blender's Extensions system is not supported and will prevent the add-on from working correctly.

---

## Usage

1. Install and enable the add-on.
2. In the **N Panel → Pen View tab**, add up to 7 brushes to your quick slots.
3. Use `Shift + Q` to open the main viewport popup.
4. Use `Ctrl + Shift + Q` to open your configured brush popup.

---

## Blender Version

- Blender 5.1 or newer

---

## License

GNU General Public License v3 or later (GPL-3.0-or-later)
