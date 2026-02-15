# Minimal Kiwi Darker

A darker variant of the popular Minimal Kiwi theme for Visual Studio Code. This theme takes the beloved kiwi green aesthetic and deepens the background colors for even better contrast and reduced eye strain during long coding sessions.
---
![Preview](https://github.com/umbrix-dev/minimal-kiwi-darker/blob/main/assets/ui.png)

### Features
- Darker backgrounds
- Perfect constract - Enhanced readibility with deeper blacks
- Maintining original colors - Keeps the original accent colors
- Consistent UI - All elements match the darker backgrounds
- Eye strain reduction - Optimized for even longer coding sessions

### Installation
#### This theme can currently only be installed from VSIX
1. Download the latest .vsix file from the [releases](https://github.com/umbrix-dev/minimal-kiwi-darker/releases/tag/Release)
2. Open VS Code
3. Press ```Ctrl+Shift+P``` (Windows/Linux) or ```Cmd+Shift+P``` (Mac)
4. Type "Extensions: Install from VSIX"
5. Select the downloaded .vsix file
6. Restart VS Code
7. Go to File > Preferences > Color Theme
8. Select "Minimal Kiwi Darker"

### Customization
#### You can further customize colors by:
1. Opening Command Palette (```Ctrl+Shift+P``` / ```Cmd+Shift+P``` )
2. Searching for "Preferences: Open Settings (JSON)"
3. Adding color overrides:

```json
{
  "workbench.colorCustomizations": {
    "[Minimal Kiwi Darker]": {
      "editor.background": "#000000",  // Even darker if you want
      "sideBar.background": "#050505"
    }
  }
}
``` 

### Credits
#### Inspired by the original [Minimal Kiwi](https://marketplace.visualstudio.com/items?itemName=PranjalKumar.minimal-kiwi) theme by Pranjal Kumar.

### License
#### MIT License - Feel free to fork and mofiy!

### Support
#### If you enjoy this theme, consider:
- Starring the Github repo
- Reporting issues or suggesting improvements

---

**Enjoy coding in the dark!**
