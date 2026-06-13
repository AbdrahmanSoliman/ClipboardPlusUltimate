# Clipboard Plus Ultimate | Play Mode Save
[![Latest Release](https://img.shields.io/badge/release-v1.1.2-orange)](https://assetstore.unity.com/packages/slug/311565)
[![Documentation](https://img.shields.io/badge/documentation-available-blue)](https://github.com/AbdrahmanSoliman/ClipboardPlusUltimate/blob/master/Docs~/Documentation/Clipboard%20Plus%20Ultimate%20Documentation.pdf)

A powerful Unity editor extension that preserves your play mode changes and manages component configurations. Save component states during play mode and manage them alongside your component clipboard system.

## Features
- 🔄 Auto-save & snapshot support for play mode changes
- 📋 Advanced component copying and pasting
- 🎯 Value-level operations for precise control
- 🔍 Smart search functionality
- ⭐ Favorites system for frequently used clips
- ⚡ Streamlined workflow with keyboard shortcuts

## Requirements
- Unity 2020.3+

## Installation

### Unity Asset Store
Get it from the [Unity Asset Store](https://assetstore.unity.com/packages/slug/311565)

## Getting Started

Open Clipboard Plus using:
- Unity menu: Window → Clipboard Plus
- Keyboard shortcut: `Alt + W`

![Clipboard Plus Ultimate](https://github.com/AbdrahmanSoliman/ClipboardPlusUltimate/blob/master/Docs~/Images/clipboard_plus_ultimate_window.png)

## Core Features

### Play Mode Save
#### **Auto Save**
Records all changes to component values during play mode and applies them when you exit play mode.
- **Context Menu**: Right-click any component → Clipboard Plus → Auto Save
<img src="https://github.com/AbdrahmanSoliman/ClipboardPlusUltimate/blob/master/Docs~/Gifs/auto_save_context_menu.gif" alt="Auto Save via Context Menu" style="width: 20cm; height: auto;">

- **Drag & Drop**: Drag components directly to the Clipboard Plus window (Play Mode tab) → Auto Save 
<img src="https://github.com/AbdrahmanSoliman/ClipboardPlusUltimate/blob/master/Docs~/Gifs/auto_save_drag_drop.gif" alt="Auto Save via Drag and Drop" style="width: 20cm; height: auto;">

#### **Save Snapshot**
Takes a copy of component values during play mode and applies them when you exit play mode. You can update the snapshot whenever you want during play mode.
- **Context Menu**: Right-click any component → Clipboard Plus → Save Snapshot
<img src="https://github.com/AbdrahmanSoliman/ClipboardPlusUltimate/blob/master/Docs~/Gifs/save_snapshot_context_menu.gif" alt="Save Snapshot via Context Menu" style="width: 20cm; height: auto;">

- **Drag & Drop**: Drag components directly to the Clipboard Plus window (Play Mode tab) → Save Snapshot
<img src="https://github.com/AbdrahmanSoliman/ClipboardPlusUltimate/blob/master/Docs~/Gifs/save_snapshot_drag_drop.gif" alt="Save Snapshot via Drag and Drop" style="width: 20cm; height: auto;">

#### **Auto Save + Save Snapshot**
<img src="https://github.com/AbdrahmanSoliman/ClipboardPlusUltimate/blob/master/Docs~/Gifs/auto_save_and_save_snapshot.gif" alt="Save Snapshot via Drag and Drop" style="width: 20cm; height: auto;">

### Component Management

#### **Copying Components**
- **Context Menu**: Right-click any component → Clipboard Plus → Copy
<img src="https://github.com/AbdrahmanSoliman/ClipboardPlusUltimate/blob/master/Docs~/Gifs/right_click_component_copy.gif" alt="Right Click Component Copy" style="width: 16cm; height: auto;">

- **Drag & Drop**: Drag components directly to the Clipboard Plus window
<img src="https://github.com/AbdrahmanSoliman/ClipboardPlusUltimate/blob/master/Docs~/Gifs/drag_drop_component_clipboard.gif" alt="Drag and Drop" style="width: 16cm; height: auto;">

- **Bulk Copy**: Select a GameObject and press `Alt + 2` to copy all components

#### **Pasting Components**
- **Selective Paste**: Right-click target component → Clipboard Plus → Paste
<img src="https://github.com/AbdrahmanSoliman/ClipboardPlusUltimate/blob/master/Docs~/Gifs/right_click_component_paste_select.gif" alt="Selective Paste" style="width: 16cm; height: auto;">

- **Quick Paste**: Right-click target component → Clipboard Plus → Quick Paste
<img src="https://github.com/AbdrahmanSoliman/ClipboardPlusUltimate/blob/master/Docs~/Gifs/right_click_component_paste_quick.gif" alt="Quick Paste" style="width: 16cm; height: auto;">

### Value Operations

#### **Copying Values**
- Expand a clip → Right-click a value → Copy
<img src="https://github.com/AbdrahmanSoliman/ClipboardPlusUltimate/blob/master/Docs~/Gifs/right_click_value_copy.gif" alt="Copy Value Operation" style="width: 16cm; height: auto;">

#### **Pasting Values**
- Right-click the target field → Paste
<img src="https://github.com/AbdrahmanSoliman/ClipboardPlusUltimate/blob/master/Docs~/Gifs/right_click_value_paste.gif" alt="Paste Value Operation" style="width: 16cm; height: auto;">

- Keyboard Shortcut: Select the target field → `Ctrl + V`

### Utility Features

#### **Search Functionality**
- Filter by Component Name
- Filter by GameObject Name
- Combined search

<img src="https://github.com/AbdrahmanSoliman/ClipboardPlusUltimate/blob/master/Docs~/Gifs/search_filter_demo.gif" alt="Search Demo" style="width: auto; height: 12cm;">

#### **Favorites System**
- Mark frequently used clips as favorites
- Quick access to favorite clips

<img src="https://github.com/AbdrahmanSoliman/ClipboardPlusUltimate/blob/master/Docs~/Gifs/favorites_system_demo.gif" alt="Favorites System Demo" style="width: auto; height: 12cm;">

## Contributing
Pull requests are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request directly.

## Support
Need help? Contact: abdelrahmann.soliman@gmail.com