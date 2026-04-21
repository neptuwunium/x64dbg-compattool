# x96dbg-compattool

A compatibility tool to bootstrap and launch x96dbg instead of the game via Steam.

## usage

```
cd "/home/${USER}/.steam/steam/compatibilitytools.d/"
git clone https://github.com/neptuwunium/x64dbg-compattool.git
```

- Edit `boot-x96dbg` to point to the correct proton (read `NOTE:` comments).
- Restart or start steam, right click game select "Properties..."
- Select "Compatibility" tab, check "Force the use of a specific Steam Paly compatibility tool"
- Select "x96dbg" in the dropdown
