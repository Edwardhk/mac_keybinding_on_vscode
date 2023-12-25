# mac_vscode_keybinding
Use mac keybinding on linux (for the most part)

---

To get the win key back, we need to disable all the Win+()Key combinations

1. Run the registry editor, `Win+R` > `regedit`

2. Add new registry under `HKEY_CURRENT_USER \ Software \ Microsoft \ Windows \ CurrentVersion \ Policies \ Explorer`:

`NEW` > `DWORD (32-bit) Value` > `NoWinKeys` > `Value` to `1`

3. Restart the machines

---
this