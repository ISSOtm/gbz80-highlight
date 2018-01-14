# Notepad++
1. Download the GBz80.xml file.
2. Open the "Language" menu. Click "Define your language..." at the bottom.
3. In the dialog, click the "Import" button at the top, and browse to the GBz80.xml file. Select it.
4. Now, "GBz80" will be added at the bottom of the Language menu, and associated with `.asm` and `.inc` files.

# gedit
1. Download the GBz80.lang` file.
2. Copy the file to `~/.local/share/gtksourceview-3.0/language-specs/` if installing for only you, or `${PREFIX}/share/gtksourceview-3.0/language-specs/` if installing for all users. (`${PREFIX}` can be `/usr/` or `/usr/local/` if you have installed from source).
3. Close all instances of gedit (and of all programs using gtksourceview).
4. Now, "GBz80" will be added to the language list, and associated with `.asm`, `.z80` and `.inc` files.
