# TextMate Language Grammar for DASM-16

This is the language grammar to get nice syntax highlighting for Notch's DCPU-16's assembler in Textmate and Sublime Text. It should work on Textmate although I haven't tested it myself.


## Installation

For Sublime Text:
* Open the package folder  -- `Preferences->Browse Packages`, or using the command menu for extra kudos).
* Then copy to the folder User the file dasm.tmLanguage.
* Set the syntax highlight to DCPU-16 or restart sublime text to see the changes.

Remember that it only applies the highlight if the file extension is .dasm or .dasm16.

## Screenshots

Here's how Notch's example code looks like in Monokai, [Railscats](http://railscasts.com/about) and [Tomorrow Night](https://github.com/ChrisKempson/Tomorrow-Theme) themes with the language grammar.



## Caveats
The language grammar is only intended for simple highlight. Some tags may still need some tweaks to adjust colours, but after that monster regex for the labels I need to rest a bit. :p