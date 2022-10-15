# Celeste Dialog Highlighter

A [Visual Studio Code](https://code.visualstudio.com/) extension that provides basic syntax highlighting for [Celeste](http://www.celestegame.com/) Language Dialog documents.

## Configuration
 
This extension's language is called "Celeste Dialog Document", but targets `.txt` files. __You may need to manually switch to this language whenever you create a file, or if Visual Studio Code doesn't detect it automatically.__ There are multiple ways to do this:
- When you create a new file, Visual Studio Code should let you know that you can manually set the desired language.
- The currently selected language is displayed at the bottom right of the window. For `.txt` files, it's usually something like "Plain Text", but it varies depending on the extension of the file. Clicking on it will allow you to change the file's language regardless of its extension.
- Use the command palette (brought with `Ctrl+Shift+P`) and search for the "Change Language Mode" setting. This brings a dropdown menu from which you can look for the Celeste Dialog Document language.
- You can configure Visual Studio to always associate a `.txt` file with the Celeste Dialog Document language within the scope of your project, or globally.
    * To do so, open up the Preferences Settings tab (through File > Preferences > Settings, or with `Ctrl+,`).
    * Look for the "file association" option. You can choose whether you edit this setting globally or for this workspace only, by clicking on the corresponding tab below the search bar.
    * Then, add an entry to associate `.txt` files with the Celeste Dialog Document language. The key should be `*.txt`, and the value should be `celeste-dialog`. If your workspace is a the root directory of a mod, you can specifically target Dialog files only, by setting the key as `Dialog/*.txt`.

## Known Issues

If you find a bug, or have a suggestion, please consider opening an issue. Alternatively, we can chat on discord; message me at `catapillie#1927`, or you can find me in the [Mt. Celeste Climbing Association Discord server](https://discord.gg/celeste).
