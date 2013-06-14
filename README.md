IDE-Preferences
===============

Keymappings for RubyMine and IntelliJ IDEA

Ideally clone this repo.
Then symlink the files in your IDE preferences folder.
For example, using RubyMine ~> 5

```
cd ~/Library/Preferences/RubyMine50/keymaps
ln -sf ~/workspace/IDE-Preferences/IntelliJKeymap.xml
```

For IntelliJ 12

```
cd ~/Library/Preferences/IntelliJIdea12/keymaps
ln -sf ~/workspace/IDE-Preferences/IntelliJKeymap.xml
```

They are using the same format, so you can change configuration in one IDE and see it applied to the other one.
The Keymap is called "Mac OSX 10.5 + Improved" in your keymaps settings.
