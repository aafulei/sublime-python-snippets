# My Python Snippets for Sublime Text

The real purpose is to override and thus remove the unnecessary built-in snippets.

## Install

### macOS

```
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages
[ -d "Python" ] && mv Python Python.old && echo "Move directory Python ===> Python.old"
git clone http://github.com/aafulei/sublime-python-snippets.git Python
```
