# mythemely
Very basic gnome theme changing script that can be aliased with a keyboard shortcut, someone asked for it so here it is.

This simple script changes theme from light to dark based on the first few lines, you can input your desired gtk or shell theme for both light and dark. It also changes the background into a randomly chosen image from a the directory `$HOME/Pictures/Lights` for light and `$HOME/Pictures/Darks` for dark mode.



Instructions:
- Copy or download `mythemely` file from master branch, into `/usr/bin` directory.
- Make it executable, `chmod +x /usr/bin/mythemely`
- Make sure to make two folders `Lights` and `Darks` inside `Pictures` directory, if this feature is not wanted go ahead and comment the lines `27, 29, 42, 44`.
- You can now use the command `mythemely -l` for light and `mythemely -d` for dark.
- For better use, add a custom shortcut using gnome settings -> devices -> keyboard. 
  Mine are `Alt+Super+L` for `mythemely -l`, and `Alt+Super+D` for `mythemely -d`.


That's it, simplified AF.
