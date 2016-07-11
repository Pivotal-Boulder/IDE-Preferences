Pivotal Boulder IDE-Preferences
===============

Key mappings and macros for RubyMine, IntelliJ IDEA, and other JetBrains IDEs.

## 1. Clone this repo
```
cd ~/workspace
git clone https://github.com/Pivotal-Boulder/IDE-Preferences.git
```

## 2. Copy the files to your IDE preferences folder

(For RubyMine, use the path ~/Library/Preferences/RubyMine80/keymaps/ you might need to make the folder)

```
cp ~/workspace/IDE-Preferences/IntelliJKeymap.xml ~/Library/Preferences/IntelliJIdea15/keymaps/
```

To add the custom macros, do the same for the macros.xml:

(For RubyMine, use the path ~/Library/Preferences/RubyMine80/options/)
```
cp ~/workspace/IDE-Preferences/macros.xml ~/Library/Preferences/IntelliJIdea15/options
```

## 3. Restart the IDE

If you have a current IDE instance open you need to restart it or figure out how to manually reload the keymap options.

## 4. Select the keymap in your IDE

Preferences (⌘,) -> Keymap -> Select "Mac OSX 10.5 + Improved" from the Keymaps dropdown
