This is a major mode for GDScript. It's incomplete but I need this so it'll be as complete as I can make it soon. 

As of right now it has basic syntax highlighting and a mostly working cycling indentation function.

## Installation
```lisp
(add-to-list 'load-path "~/path/to/gdscript-mode.el/")
(load "gdscript-mode.el")
(require 'gdscript-mode)
```

## Customization
Use spaces instead of tabs. This defaults to whatever you have it set to. The editor defaults to tabs and I haven't found a way to change it so if you use spaces setting this to true might be useful.
```lisp
(setq gdscript-tabs-mode t)
```

Set indentation width. Again I couldn't find how to change this in the default editor and I use 2 for everything. 
```lisp
(setq gdscript-tab-width 4)
```

The script is set to open with any .gdscript file within Emacs.
