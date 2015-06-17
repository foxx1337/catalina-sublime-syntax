Sublime Text 3 catalina.out syntax highlighting
===============================================

Highlights `catalina.out` (actually `.out` files) as spewed out by [Tomcat](http://tomcat.apache.org/).

## Requirements :

- Sublime Text 3
- [AAAPackageDev](https://github.com/SublimeText/AAAPackageDev)

## Installation :

1. install (through Package Manager) AAAPackageDev
2. create a symbolic link `~/.config/sublime-text-3/Packages/User/catalina.YAML-tmLanguage` pointing to the supplied `catalina.YAML-tmLanguage`
3. open said symbolic link and build it (Ctrl-B); AAAPackageDev will ask what type of build to perform, just select `Convert To ... - Property List`

Everything should work now and _some_ syntax highlighting will appear in `catalina.out` files.
