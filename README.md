**Support chart (with links to plug-ins)**

| IDE | Syntax highlight | Code Completion | Lint | Code Format | Goto Def | Find Usages | Stepwise Debugger | Doc. tooltips | Snippets | Hoogle |
|:---:|:----------------:|:---------------:|:----:|:-----------:|:--------:|:-----------:|:--------:|:-------------:|:--------:|:------:|
| Atom<br>「[ide-haskell][atom06]」 | [🚀][atom01] | [🚗][atom02] | 🚗 | [🚲][gen01] | 🚗 | … | [🚗][atom03] | [🚗][atom05] | [🚗][atom01] | [🚗][atom04] |
| Emacs 「[Intero][emacs02]」 | [🚀][emacs01] | 🚗² | 🚗² | [🚗][gen01] | 🚗² | … | 🚶 | 🚗² | [🚗³][emacs04] | … |
| Intellij 「[HaskForce][inte01]」 | 🚀² | … | … | … | … | … | 🚶 | … | … | … |
| Intellij<br>「[intellij-haskell][inte02]」| 🚀² | … | … | … | … | … | 🚶 | … | … | … |
| Leksah | 🚀¹ | … | … | … | … | … | … | … | … | … |
| Vim      | 🚀¹ | 🚲¹ | [🚗][vim01] | [🚗][gen01] | 🚲¹ | … | 🚶 | [🚗][vim02] | [🚗][vim03] | … |
| VSCode 「[Haskelly][vsco01]」 | [🚀][vsco02] | … | [🚗][vsco03] | [🚗][vsco04] | 🚗² | … | [🚲][vsco05] | 🚗² | [🚲][vsco02] | … |
| VSCode 「[Haskero][vsco01]」  | [🚀][vsco02] | 🚗² | [🚗][vsco03] | [🚗][vsco04] | 🚗² | 🚗² | [🚲][vsco05] | 🚗² | [🚲][vsco02] | … |
| Sublime 「[SublimeHaskell][subl01]」 | 🚀² | 🚗² | 🚗² | … | 🚲¹ | … | 🚶 | 🚗² | … | … |


| Symbol | Support Level                         |
|:------:|:------------------------------------- |
| …      | Unknown, support is uncertain         |
| 🚶     | Absent, you are on your own           |
| 🚲     | Inmature, only for early-adopters     |
| 🚗     | Mature, suitable for most programmers |
| 🚀     | The best™ possible experience         |


Notes:

1. native support (probably minimal)
2. via main plug-in
3. more emacs snippets [here][emacs03], via haskell-snippets

[gen01]: https://github.com/chrisdone/hindent "hindent"

[atom01]: https://atom.io/packages/language-haskell "language-haskell"
[atom02]: https://atom.io/packages/autocomplete-haskell "ghc-mod via autocomplete-haskell"
[atom03]: https://atom.io/packages/haskell-debug "haskell-debug"
[atom04]: https://atom.io/packages/haskell-hoogle "haskell-hoogle"
[atom05]: https://atom.io/packages/haskell-ghc-mod "haskell-ghc-mod"
[atom06]: https://github.com/atom-haskell/ide-haskell "ide-haskell"

[emacs01]: http://haskell.github.io/haskell-mode/ "haskell-mode"
[emacs02]: https://commercialhaskell.github.io/intero/ "intero"
[emacs03]: https://github.com/haskell/haskell-snippets "haskell-snippets"
[emacs04]: https://github.com/joaotavora/yasnippet "yasnippet"

[inte01]: https://github.com/carymrobbins/intellij-haskforce "HaskForce"
[inte02]: https://github.com/rikvdkleij/intellij-haskell "intellij-haskell"

[vim01]: https://github.com/vim-syntastic/syntastic "syntastic"
[vim02]: https://github.com/bitc/vim-hdevtools "vim-hdevtools"
[vim03]: https://github.com/honza/vim-snippets "vim-snipmate default snippets"

[vsco01]: https://marketplace.visualstudio.com/items?itemName=UCL.haskelly "Haskelly"
[vsco02]: https://marketplace.visualstudio.com/items?itemName=justusadam.language-haskell "Haskell Syntax Highlighting"
[vsco03]: https://marketplace.visualstudio.com/items?itemName=hoovercj.haskell-linter "haskell-linter"
[vsco04]: https://marketplace.visualstudio.com/items?itemName=monofon.hindent-format "hindent"
[vsco05]: https://marketplace.visualstudio.com/items?itemName=phoityne.phoityne-vscode "Phoityne"
[vsco06]: https://marketplace.visualstudio.com/items?itemName=Vans.haskero "Haskero"

[subl01]: https://github.com/SublimeHaskell/SublimeHaskell "SublimeHaskell"
