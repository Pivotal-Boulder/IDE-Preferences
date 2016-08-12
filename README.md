Pivotal Boulder IDE-Preferences
===============

Key mappings and macros for RubyMine, IntelliJ IDEA, and other JetBrains IDEs.

## 1. Clone this repo
```
cd ~/workspace
git clone https://github.com/Pivotal-Boulder/IDE-Preferences.git
```

## 2. Copy the files to your IDE preferences folder

(For RubyMine, use the path ~/Library/Preferences/RubyMine80/keymaps)

```
cp ~/workspace/IDE-Preferences/IntelliJKeymap.xml ~/Library/Preferences/IntelliJIdea15/keymaps/
```

To add the custom macros, do the same for the macros.xml:

(For RubyMine, use the path ~/Library/Preferences/RubyMine80/options)
```
cp ~/workspace/IDE-Preferences/macros.xml ~/Library/Preferences/IntelliJIdea15/options
```

To add JetBrains-style key mappings to Microsoft Visual Studio Code,
```
cp ~/workspace/IDE-Preferences/keybindings.json ~/Library/Application\ Support/Code/User/
```

## 3. Select the keymap in your IDE

Preferences (⌘,) -> Keymap -> Select "Mac OSX 11.5 + Improved" from the Keymaps dropdown
