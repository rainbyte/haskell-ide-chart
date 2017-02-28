**Support chart (with links to plug-ins)**

| IDE | Syntax highlight | Code Completion | Lint | Code Format | Goto Def | Find Usages | Debugger | Doc. tooltips | Snippets | Hoogle |
|:---:|:----------------:|:---------------:|:----:|:-----------:|:--------:|:-----------:|:--------:|:-------------:|:--------:|:------:|
| Atom     | [🌑][atom01] | [🌓][atom02] | 🌓 | [🌕][gen01] | 🌓 | … | [🌓][atom03] | … | … | [🌓][atom04] |
| Emacs 「[Intero][emacs02]」 | [🌑][emacs01] | 🌓² | 🌓² | [🌓][gen01] | 🌓² | … | … | 🌓² | … | … |
| Intellij | 🌑 | … | … | … | … | … | … | … | … | … |
| Vim      | 🌑¹ | 🌕¹ | [🌓][vim01] | [🌓][gen01] | 🌕¹ | … | … | [🌓][vim02] | … | … |
| VSCode 「[Haskelly][vsco01]」 | [🌑][vsco02] | … | [🌓][vsco03] | [🌓][vsco04] | 🌓² | … | [🌕][vsco05] | 🌓² | … | … |
| VSCode 「[Haskero][vsco01]」  | [🌑][vsco02] | 🌓² | [🌓][vsco03] | [🌓][vsco04] | 🌓² | 🌓² | [🌕][vsco05] | 🌓² | … | … |
| Sublime 「[SublimeHaskell][subl01]」 | 🌑² | 🌓² | 🌓² | … | 🌕¹ | … | … | 🌓² | … | … |


| Symbol | Support Level                         |
|:------:|:------------------------------------- |
| …      | Unknown, support is uncertain         |
| 🌕     | Immature, only for early-adopters     |
| 🌓     | Mature, suitable for most programmers |
| 🌑     | The best™ experience                  |


Notes:

1. native support (probably minimal)
2. via main plug-in

[gen01]: https://github.com/chrisdone/hindent "hindent"

[atom01]: https://atom.io/packages/language-haskell "language-haskell"
[atom02]: https://atom.io/packages/autocomplete-haskell "ghc-mod via autocomplete-haskell"
[atom03]: https://atom.io/packages/haskell-debug "haskell-debug"
[atom04]: https://atom.io/packages/haskell-hoogle "haskell-hoogle"

[emacs01]: http://haskell.github.io/haskell-mode/ "haskell-mode"
[emacs02]: https://commercialhaskell.github.io/intero/ "intero"

[vim01]: https://github.com/vim-syntastic/syntastic "syntastic"
[vim02]: https://github.com/bitc/vim-hdevtools "vim-hdevtools"

[vsco01]: https://marketplace.visualstudio.com/items?itemName=UCL.haskelly "Haskelly"
[vsco02]: https://marketplace.visualstudio.com/items?itemName=justusadam.language-haskell "Haskell Syntax Highlighting"
[vsco03]: https://marketplace.visualstudio.com/items?itemName=hoovercj.haskell-linter "haskell-linter"
[vsco04]: https://marketplace.visualstudio.com/items?itemName=monofon.hindent-format "hindent"
[vsco05]: https://marketplace.visualstudio.com/items?itemName=phoityne.phoityne-vscode "Phoityne"
[vsco06]: https://marketplace.visualstudio.com/items?itemName=Vans.haskero "Haskero"

[subl01]: https://github.com/SublimeHaskell/SublimeHaskell "SublimeHaskell"
