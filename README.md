# Base16 Builder

Easily build color variations of Base16 with YAML scheme definitions and ERB templates.
See the [Base16](https://github.com/chriskempson/base16) repository for more information.
Requires Ruby 1.9 or greater.

## About the fork

It seems that original [repo](https://github.com/chriskempson/base16-builder) is no longer maintained.

There've been a lot of pull requests with fixes and enhancements that should have been merged so I decided to create a fork and merge them.

## Usage

Build all schemes:

    > ./base16


Build only the "default" theme:

    > ./base16 -s schemes/default.yml


Build only the terminal-app termplate:

    > ./base16 -t templates/terminal-app


Build a scheme stored on some webspace:

    > ./base16 https://awesome-schemes.com/my-scheme.yml


## Templates

* Ace
* Atom
* BBEdit (TextWrangler)
* Brackets
* Chrome DevTools (Web Inspector)
* Chrome Secure Shell
* CodeMirror
* ConEmu
* Console2
* Devtools-Author
* DrRacket
* Emacs
* Escape Code Shell Script (shell)
* Geany
* Gedit
* Gimp Palette
* Gnome Terminal
* Guake
* highlight.js
* Highlighting Kate
* HTML Preview (preview)
* IDEA
* IPython Notebook
* iTerm 2
* Konsole
* Mate Terminal
* MinTTY
* MultiMarkdown Composer 2 (mmdc2)
* Mou
* Notepad++
* OS X Terminal (terminal-app)
* Pantheon Terminal
* prettify.js
* Prism.js
* PuTTY
* Pygments
* Qt Creator
* Rainbow
* Rouge
* Sequel Pro
* Terminator
* Termite
* Textadept
* TextMate (Sublime Text)
* Vim
* Visual Studio
* Virtual Console (vconsole)
* Windows Command Prompt
* Xcode
* XFCE4 Terminal
* Xresources
* Zathura

## Maintainers

* [chriskempson](https://github.com/chriskempson) - HTML Preview, Vim, TextMate, iTerm 2, XFCE4 Terminal, Mou, Escape Code Shell Script, Gnome Terminal, BBEdit
* [jayferd](https://github.com/jayferd) - Rouge
* [neil477](https://github.com/neil477) - Emacs
* [joedynamite](https://github.com/joedynamite) - Xcode
* [robloach](https://github.com/robloach) - Geany
* [geoffstokes](https://github.com/geoffstokes) - Windows Command Prompt, MinTTY
* [idleberg](https://github.com/idleberg) - Ace, Atom, Brackets, Chrome DevTools, CodeMirror, Devtools-Author, Gedit, highlight.js, Notepad++, prettify.js, Pygments, Rainbow
* [rgieseke](https://github.com/rgieseke) - Textadept
* [oxplot](https://github.com/oxplot) - Mate Terminal
* [esn89](https://github.com/esn89) - Zathura PDF Reader
* [romainx](https://github.com/romainx) - MultiMarkdown Composer 2
* [moonpyk](https://github.com/moonpyk) - ConEmu
* [jprjr](https://github.com/jprjr) - ConnectBot, vx-connectbot
* [atelierbram](https://github.com/atelierbram) - Prism
* [bbrks](https://github.com/bbrks) - Sequel Pro
* [auduchinok](https://github.com/auduchinok) - maintaining

## License

Base16 Builder is released under the [MIT License](https://github.com/chriskempson/base16-builder/blob/master/LICENSE.md)
