# State of Haskell editor/IDE support

This chart describes the support level of each Haskell editor/IDE *plug-in combination*.

In most cases there is a main plug-in which act as a base for the provided features.

Each known plug-in have an associated link and tooltip with its name.


## The chart (with a link to each plug-in)

| IDE | Syntax highlight | Code Completion | Error Reporting | Lint | Code Format | Goto Def | Find Usages | Stepwise Debugger | Doc. tooltips | Snippets | Hoogle |
|:---:|:----------------:|:---------------:|:---------------:|:----:|:-----------:|:--------:|:-----------:|:--------:|:-------------:|:--------:|:------:|
| Atom<br>「[ide-haskell][atom06]」 | [🚀][atom01] | [🚗][atom02] | 🚗 | 🚗 | [🚲][gen01] | 🚗 | … | [🚗][atom03] | [🚗][atom05] | [🚗][atom01] | [🚗][atom04] |
| Emacs 「[Intero][emacs02]」 | [🚀][emacs01] | 🚗² | 🚗² | 🚗² | [🚗][gen01] | 🚗² | … | 🚶 | 🚗² | [🚗][emacs04] | … |
| Intellij 「[HaskForce][inte01]」 | 🚀² | … | … | … | … | … | … | 🚶 | … | … | … |
| Intellij<br>「[intellij-haskell][inte02]」| 🚀² | … | … | … | … | … | … | 🚶 | … | … | … |
| Leksah | 🚀¹ | … | … | … | … | … | … | … | … | … | … |
| Vim      | 🚀¹ | 🚲¹ | … | [🚗³][vim01] | [🚗][gen01] | 🚲¹ | … | 🚶 | [🚗][vim02] | [🚗][vim03] | … |
| VSCode 「[Haskelly][vsco01]」 | [🚀][vsco02] | … | [🚶][vsco07] | [🚗][vsco03] | [🚗][vsco04] | 🚗² | … | [🚲][vsco05] | 🚗² | [🚲][vsco02] | … |
| VSCode 「[Haskero][vsco06]」  | [🚀][vsco02] | 🚗² | 🚗² | [🚗][vsco03] | [🚗][vsco04] | 🚗² | 🚗² | [🚲][vsco05] | 🚗² | [🚲][vsco02] | … |
| Sublime 「[SublimeHaskell][subl01]」 | 🚀² | 🚗² | … | 🚗² | … | 🚲¹ | … | 🚶 | 🚗² | … | … |


## Meaning of each level

| Symbol | Support Level                         |
|:------:|:------------------------------------- |
| …      | Unknown, support is uncertain         |
| 🚶     | Absent, you are on your own           |
| 🚲     | Immature, only for early-adopters     |
| 🚗     | Mature, suitable for most programmers |
| 🚀     | The best™ possible experience         |


Notes:

1. native support (probably minimal)
2. via main plug-in
3. this plug-in needs special config and/or system deps, refer to its documentation

[gen01]: https://github.com/chrisdone/hindent "hindent"

[atom01]: https://atom.io/packages/language-haskell "language-haskell"
[atom02]: https://atom.io/packages/autocomplete-haskell "ghc-mod via autocomplete-haskell"
[atom03]: https://atom.io/packages/haskell-debug "haskell-debug"
[atom04]: https://atom.io/packages/haskell-hoogle "haskell-hoogle"
[atom05]: https://atom.io/packages/haskell-ghc-mod "haskell-ghc-mod"
[atom06]: https://github.com/atom-haskell/ide-haskell "ide-haskell"

[emacs01]: http://haskell.github.io/haskell-mode/ "haskell-mode"
[emacs02]: https://commercialhaskell.github.io/intero/ "intero"
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
[vsco07]: https://github.com/haskelly-dev/Haskelly/issues/29 "haskelly: issue #29"

[subl01]: https://github.com/SublimeHaskell/SublimeHaskell "SublimeHaskell"
