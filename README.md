# Night Owl 🌌

[![Version](https://vsmarketplacebadge.apphb.com/version/sdras.night-owl.svg)](https://aka.ms/nightowl)
[![Downloads](https://img.shields.io/vscode-marketplace/d/sdras.night-owl.svg)](https://aka.ms/nightowl)

A VS Code theme for the night owls out there. Works well in the daytime, too, but this theme is fine-tuned for those of us who like to code late into the night. Color choices have taken into consideration what is accessible to people with colorblindness and in low-light circumstances. Decisions were also based on meaningful contrast for reading comprehension and for optimal razzle dazzle. ✨

About this theme, and some of the considerations made while creating it (as well as _how_ to create it should you want to make your own): [https://css-tricks.com/creating-a-vs-code-theme/](https://css-tricks.com/creating-a-vs-code-theme/)

![Preview](preview.png)

# Installation

1.  Install [Visual Studio Code](https://code.visualstudio.com/)
2.  Launch Visual Studio Code
3.  Choose **Extensions** from menu
4.  Search for `night-owl-vscode-theme`
5.  Click **Install** to install it
6.  Click **Reload** to reload the Code
7.  From the menu bar click: Code > Preferences > Color Theme > **Night Owl**

## Disable Italics

If you wish to disable italics, there is now a no-italic theme available. You will have access to both, select **Night Owl No Italics** as your color theme.

## Other versions of this Theme

The community is awesome and has ported this theme over to other environments

- Hyper: [https://github.com/pbomb/hyper-night-owl](https://github.com/pbomb/hyper-night-owl)
- iTerm2
  1.  [https://github.com/nickcernis/iterm2-night-owl](https://github.com/nickcernis/iterm2-night-owl)
  2.  [https://github.com/jsit/night-owl-iterm2-theme](https://github.com/jsit/night-owl-iterm2-theme)
  3.  [https://github.com/florianeckerstorfer/night-owl-itermcolors](https://github.com/florianeckerstorfer/night-owl-itermcolors)
  4.  [https://github.com/andrewfluck/night-owl-iterm2](https://github.com/andrewfluck/night-owl-iterm2)
- Atom: [https://atom.io/themes/night-owl-vs-code-syntax](https://atom.io/themes/night-owl-vs-code-syntax)
- Jetbrains: [https://github.com/xdrop/night-owl-jetbrains](https://github.com/xdrop/night-owl-jetbrains)
- Emacs: [https://github.com/aaronjensen/night-owl-emacs](https://github.com/aaronjensen/night-owl-emacs)
- Vim [https://github.com/Khaledgarbaya/night-owl-vim-theme](https://github.com/Khaledgarbaya/night-owl-vim-theme)
- Pygments [https://github.com/liamdawson/nightowl-pygments-style](https://github.com/liamdawson/nightowl-pygments-style)

## Separate the Editor from the Sidebar

This theme uses contrast sparingly so that when it's applied, it's more meaningful. This can help reduce noise and improve your ability to scan. However, some of the decisions may not work for everyone. One such decision that some disagree on is whether or not to have a separation between the editor and sidebar, and the amount of contrast. If you wish for this to have more visual signifigance, please paste this into your user settings preferences. These are my recommendations for these settings but you can use whatever colors you wish. ☺️

```
"workbench.colorCustomizations": {
  "activityBar.background": "#000C1D",
  "activityBar.border": "#102a44",
  "sideBar.background": "#001122",
  "sideBar.border": "#102a44",
  "sideBar.foreground": "#8BADC1"
},
```

## Preferences shown in the preview

The font in the preview image is Dank Mono, [available here](https://dank.sh/). Editor settings to activate font ligatures:

```
"editor.fontFamily": "Dank Mono",
"editor.fontLigatures": true,
```

The preview image is using [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer), a really cool extension that highlights matching brackets. This can help reduce unwanted errors.

I use this setting:

```
"bracketPairColorizer.forceIterationColorCycle": true,
```

![Bracket](bracket.png)

## Misc

This is my first foray into creating a theme, so if you see something amiss, please feel free to [file an issue](https://github.com/sdras/night-owl-vscode-theme/issues)! I'm sure there are things I missed.

Any relevant changes for each version are documented in the changelog. Please update and check the changelog before filing any issues, as they may have already been taken care of.

This palette was inspired in part by Material Palenight [Theme](https://marketplace.visualstudio.com/items?itemName=whizkydee.material-palenight-theme), and the accessibility idea was inspired in part by Solarized [Themes](http://ethanschoonover.com/solarized)
