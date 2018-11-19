Pivotal Boulder IDE-Preferences
===============

Key mappings and macros for RubyMine, IntelliJ IDEA, and other JetBrains IDEs.

## 1. Clone this repo
```
cd ~/workspace
git clone https://github.com/Pivotal-Boulder/IDE-Preferences.git
```

## 2. Copy the files to your IDE preferences folder

#### IntelliJ

Keymap:

```
mkdir -p ~/Library/Preferences/IntelliJIdea2017.3/keymaps/
cp ~/workspace/IDE-Preferences/IntelliJKeymap.xml ~/Library/Preferences/IntelliJIdea2017.3/keymaps/
```

Macros:
```
cp ~/workspace/IDE-Preferences/macros.xml ~/Library/Preferences/IntelliJIdea2017.3/options/
```

#### RubyMine

Keymap:
```
mkdir -p ~/Library/Preferences/RubyMine2017.3/keymaps/
cp ~/workspace/IDE-Preferences/IntelliJKeymap.xml ~/Library/Preferences/RubyMine2017.3/keymaps/
```

Macros:
```
cp ~/workspace/IDE-Preferences/macros.xml ~/Library/Preferences/RubyMine2017.3/options/
```

#### Rider

Keymap:
```
mkdir -p ~/Library/Preferences/Rider2017.3/keymaps/
cp ~/workspace/IDE-Preferences/IntelliJKeymap.xml ~/Library/Preferences/Rider2017.3/keymaps/
```

Macros:
```
cp ~/workspace/IDE-Preferences/macros.xml ~/Library/Preferences/Rider2017.3/options/
```

#### Microsoft Visual Studio Code
These are JetBrains-style key mappings

```
cp ~/workspace/IDE-Preferences/keybindings.json ~/Library/Application\ Support/Code/User/
```

## 3. Restart the IDE

If you have a current IDE instance open you'll need to restart it

## 4. Select the keymap in your IDE
Preferences (⌘,) -> Keymap -> Select "Mac OSX 10.5 + Improved" from the Keymaps dropdown
