# State of Haskell editor/IDE support

This chart describes the support level of each Haskell editor/IDE *plug-in combination*.

In most cases there is a main plug-in which acts as a base for the provided features.

Each known plug-in has an associated link and tooltip with its name.


## The chart (with a link to each plug-in)

| IDE | Syntax highlight | Code Completion | Error Reporting | Lint | Code Format | Goto Def | Find Usages | Stepwise Debugger | Doc. tooltips | Snippets | Hoogle | REPL Integration |
|:---:|:----------------:|:---------------:|:---------------:|:----:|:-----------:|:--------:|:-----------:|:-----------------:|:-------------:|:--------:|:------:|:----------------:|
| Atom<br>「[ide-haskell][atom06]&nbsp;<sup>[[gh]][atom06r]</sup>」 | [✔️][atom01] | [➕][atom02] | ➕ | ➕ | [❕][gen01] | ➕ | ❔ | [➕][atom03] | [➕][atom05] | [➕][atom01] | [➕][atom04] | ❕ |
| Emacs 「[Intero][emacs02]&nbsp;<sup>[[gh]][emacs02r]</sup>」 | [✔️][emacs01] | ➕² | ➕² | ➕² | [➕][gen01] | ➕² | ❔ | ❌ | ➕² | [➕][emacs04] | ❔ | ➕ |
| Intellij 「[HaskForce][inte01]&nbsp;<sup>[[gh]][inte01r]</sup>」 | ✔️² | ➕ | ➕ | ➕ | ➕ | ➕ | ➕ | ❌ | ❌ | ➕ | ❌ | ❌ |
| Intellij<br>「[intellij&#8209;haskell][inte02]&nbsp;<sup>[[gh]][inte02r]</sup>」| ✔️² | ➕ | ✔️ | ❕ | ❕ | ✔️ | ✔️ | ❌ | ❕ | ➕ | ❕ | ❔ |
| Leksah | ✔️¹ | ❔ | ❔ | ❔ | ❔ | ❔ | ❔ | ❔ | ❔ | ❔ | ❔ | ❔ |
| Vim      | ✔️¹ | ❕¹ | ❔ | [➕³][vim01] | [➕][gen01] | ❕¹ | ❔ | ❌ | [➕][vim02] | [➕][vim03] | ❔ | ❕ |
| VSCode 「[Haskelly][vsco01]&nbsp;<sup>[[gh]][vsco01r]</sup>」 | [✔️][vsco02] | ❔ | [❌][vsco07] | [➕][vsco03] | [➕][vsco04] | ➕² | ❔ | [❕][vsco05] | ➕² | [❕][vsco02] | ❔ | ❕ |
| VSCode 「[Haskero][vsco06]&nbsp;<sup>[[gl]][vsco06r]</sup>」  | [✔️][vsco02] | ➕² | ➕² | [➕][vsco03] | [➕][vsco04] | ➕² | ➕² | [❕][vsco05] | ➕² | [❕][vsco02] | ❔ | ❌ |
| Sublime 「[SublimeHaskell][subl01]&nbsp;<sup>[[gh]][subl01r]</sup>」 | ✔️² | ➕² | ❔ | ➕² | ❔ | ❕¹ | ❔ | ❌ | ➕² | ❔ | ❔ | ❕ |


## Meaning of each level

| Symbol | Support Level                         |
|:------:|:------------------------------------- |
| ❔      | Unknown, support is uncertain         |
| ❌     | Absent, you are on your own           |
| ❕     | Immature, only for early-adopters     |
| ➕     | Mature, suitable for most programmers |
| ✔️     | The best™ possible experience         |

Notes:

1. native support (probably minimal)
2. via main plug-in
3. this plug-in needs special config and/or system deps, refer to its documentation

## Features

* Syntax highlight 
* Code Completion
* Error Reporting
* Lint
* Code Format
* Goto Def
* Find Usages
* Stepwise Debugger
* Doc. tooltips
* Snippets - Predefined and customizable templates for pieces of code you write often. For example, if you write `case`, an editor might provide a completion like
  ```haskell
  case ___ of
    __ -> ___
  ```
* Hoogle
* REPL Integration - Be able to load/reload a file to e.g. ghci and provide interaction. Autocompletion and syntax highlighting are also welcomed.

[gen01]: https://github.com/chrisdone/hindent "hindent"

[atom01]: https://atom.io/packages/language-haskell "language-haskell"
[atom02]: https://atom.io/packages/autocomplete-haskell "ghc-mod via autocomplete-haskell"
[atom03]: https://atom.io/packages/haskell-debug "haskell-debug"
[atom04]: https://atom.io/packages/haskell-hoogle "haskell-hoogle"
[atom05]: https://atom.io/packages/haskell-ghc-mod "haskell-ghc-mod"
[atom06]: https://atom.io/packages/ide-haskell "ide-haskell"
[atom06r]: https://github.com/atom-haskell/ide-haskell "ide-haskell repo"

[emacs01]: http://haskell.github.io/haskell-mode/ "haskell-mode"
[emacs02]: https://commercialhaskell.github.io/intero/ "intero"
[emacs02r]: https://github.com/commercialhaskell/intero "intero repo"
[emacs04]: https://github.com/joaotavora/yasnippet "yasnippet"

[inte01]: https://plugins.jetbrains.com/plugin/7602-haskforce "HaskForce"
[inte01r]: https://github.com/carymrobbins/intellij-haskforce "HaskForce repo"
[inte02]: https://plugins.jetbrains.com/plugin/8258-intellij-haskell "intellij-haskell"
[inte02r]: https://github.com/rikvdkleij/intellij-haskell "intellij-haskell repo"

[vim01]: https://github.com/vim-syntastic/syntastic "syntastic"
[vim02]: https://github.com/bitc/vim-hdevtools "vim-hdevtools"
[vim03]: https://github.com/honza/vim-snippets "vim-snipmate default snippets"

[vsco01]: https://marketplace.visualstudio.com/items?itemName=UCL.haskelly "Haskelly"
[vsco01r]: https://github.com/haskelly-dev/Haskelly "Haskelly repo"
[vsco02]: https://marketplace.visualstudio.com/items?itemName=justusadam.language-haskell "Haskell Syntax Highlighting"
[vsco03]: https://marketplace.visualstudio.com/items?itemName=hoovercj.haskell-linter "haskell-linter"
[vsco04]: https://marketplace.visualstudio.com/items?itemName=monofon.hindent-format "hindent"
[vsco05]: https://marketplace.visualstudio.com/items?itemName=phoityne.phoityne-vscode "Phoityne"
[vsco06]: https://marketplace.visualstudio.com/items?itemName=Vans.haskero "Haskero"
[vsco06r]: https://gitlab.com/vannnns/haskero "Haskero repo"
[vsco07]: https://github.com/haskelly-dev/Haskelly/issues/29 "haskelly: issue #29"

[subl01]: https://packagecontrol.io/packages/SublimeHaskell "SublimeHaskell"
[subl01r]: https://github.com/SublimeHaskell/SublimeHaskell "SublimeHaskell repo"
