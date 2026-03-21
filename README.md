# 🐢 Turtle WoW – Remove Annoying Sounds

This small project removes specific annoying sounds from **Turtle WoW** by overriding them with empty `.wav` files.  
No addons, no MPQ editing, and no client modification required.

---

## 📦 Installation

1. Download or clone this repository.  
2. Locate your Turtle WoW installation folder.  
   - Examples:  
     **Windows:** C:\Games\TurtleWOW\  
     **Linux/Wine:** ~/.wine/drive_c/Program Files/TurtleWOW/
3. Place the **Sound/** folder directly inside your Turtle WoW directory so the structure looks like this:
```
TurtleWOW/  
    └── Sound/  
        └── Creature/  
            ├── DuckQuack1.wav  
            ├── DuckQuack2.wav  
            ├── DuckQuack3.wav  
            ├── DuckQuack4.wav  
            ├── DuckQuack5.wav  
            └── DuckQuack6.wav  
```
4. Launch the game — the annoying duck sounds are now muted.

---

## 🗑️ Uninstallation

Just delete the **Sound/** folder or the specific files you no longer want muted.  
The game will automatically fall back to the original sounds.

---

## 🛠️ Customization

Want to mute other sounds?

1. Find the original sound path (via MPQ tools, WoWTools, or existing addons).  
2. Recreate the folder structure inside `Sound/`.  
3. Add an empty `.wav` file with the same filename.
