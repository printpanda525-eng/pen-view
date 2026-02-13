# Pen View

Pen View is a lightweight Blender add-on designed to improve viewport navigation and workflow for pen tablet users, compact keyboards, and laptops without a numeric keypad.

The add-on provides quick access to common view, mode, and overlay tools through a customizable interface, allowing users to choose between a Pie Menu or a floating Popup UI.

⚠️ This add-on requires classic Blender add-on installation to enable both interface modes.  
Blender Extensions are not compatible with this hybrid add-on.
C:\Users\your user\AppData\Roaming\Blender Foundation\Blender\5.0\scripts\addons

---

## Features

- View orientation controls (Top, Front, Side, Bottom)
- Quick access to Object, Edit, and Sculpt modes
- Mesh selection mode buttons (Vertex, Edge, Face) in Edit Mode
- Overlay toggles for Wireframe, X-Ray, and Face Orientation
- Two interface modes: Pie Menu or Popup
- Designed for pen tablets and laptops without numpad

---

## Interface Modes

Pen View offers two interface styles:

- **Pie Menu UI**  
  Radial menu optimized for pen tablet workflows and fast directional access.

- **Popup UI**  
  Lightweight floating popup displayed at the cursor position.

The interface mode can be selected in the add-on preferences.

<table align="center">
  <tr>
    <td align="center">
      <img src="image/pen-pie.png" width="300" />
      <br><b>Pie menu</b>
    </td>
    <td align="center">
      <img src="image/pen-tarj.png" width="300" />
      <br><b>Popup</b>
    </td>
  </tr>
</table>



---

## Installation

Pen View must currently be installed as a classic Blender add-on.

Due to limitations in Blender’s new Extensions system (4.x), modular add-ons that use dynamic routing and Add-on Preferences may not function correctly when installed as Extensions.

### Recommended Installation Method (Classic Add-on)

1. Download the repository as a ZIP file from GitHub.
2. Extract the ZIP file.
3. Copy the `pen_view` folder into your Blender addons directory:

   C:\Users\<username>\AppData\Roaming\Blender Foundation\Blender\4.x\scripts\addons\


   **Windows:**
   
5. Open Blender.
6. Go to **Edit → Preferences → Add-ons**.
7. Enable **Pen View**.
8. Open the add-on preferences and select your desired interface mode (Pie Menu or Popup).

---

## Assign a Shortcut (Required)

Pen View does not automatically assign a shortcut.

To activate it:

1. Go to **Edit → Preferences → Keymap**.
2. In the search bar, type: `penview`
3. Click **Add New**.
4. Set the Operator to:
5. Assign your preferred shortcut (for example: `Q`, `Shift+Space`, or a stylus button).

Now the add-on will open either the Pie Menu or Popup interface depending on your selected UI Mode.

---

⚠ Installing through Blender’s new Extensions system may prevent the UI mode switching from working correctly.



---

## Unsupported installation method

Installing Pen View through Blender Extensions will result in a limited version where interface preferences are not available.

This is a current limitation of Blender Extensions, not a bug in the add-on.

---

## Usage

The add-on is accessed via a custom shortcut assigned by the user.

The shortcut opens either the Pie Menu or the Popup UI at the cursor position, depending on the selected interface mode.

All tools are executed directly and do not override Blender’s default keymap behavior.

---

## UI Location

- Shortcut-only interface (no permanent panels)

---

## Blender Version

- Blender 5.0 or newer

---

## License

GNU General Public License v3 or later (GPL-3.0-or-later)
