# My Python Snippets for Sublime Text

The real purpose is to override and thus remove the unnecessary built-in snippets.

## Install

### macOS

```sh
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages
[ -d "Python" ] && mv Python Python.old && echo "Move directory Python ===> Python.old"
git clone http://github.com/aafulei/sublime-python-snippets.git Python
```

### Windows

```bat
cd %APPDATA%\Sublime Text 3\Packages
if exist Python (move /Y Python Python.old) && (echo "Move directory Python ===> Python.old")
git clone http://github.com/aafulei/sublime-cpp-snippets.git Python
```
