# scala-format
Atom package to format scala files with standard scalariform library.

##Usage
`cmd+ctrl+s` formats the current file in place using default Scalariform settings.  If the file does not have a .scala extension no action is done.  Also accessible from context (right click) menu and command palette.

## Installation
This package isn't on the APM registry yet so you'll have to clone the repo and load the package in [developer mode][dev-mode-package]

## About Scalariform
[Scalariform][scalariform] is the official code formatter for Scala.  It's the de facto formatter used by most tools, including [Scala IDE][scala-ide].

Current Scalariform version bundled with this package is `0.1.5-SNAPSHOT`

## Features
Some are in progress
- [x] Format scala file through menu / command palette
- [x] Format scala file through context menu
- [x] Format scala file through keybinding (`cmd+ctrl+s`)
- [ ] Format highlighted text selection (instead of entire file)
- [ ] Configure scalariform [preferences][prefs]

[dev-mode-package]: https://discuss.atom.io/t/load-developing-package/2554/11
[scalariform]: https://github.com/mdr/scalariform
[scala-ide]: http://scala-ide.org
[prefs]: https://github.com/mdr/scalariform#preferences
