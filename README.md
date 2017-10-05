# ide-themes

Beautiful themes for your IDE, so you can enjoy coding like a sweet 🍹 on a ⛱

## Coding fonts

We Love Menlo, and for some IDEs where you cannot configure line height there is Meslo to help you pick the right spacing.

Downloads:

* [Menlo](http://www.cufonfonts.com/en/font/13494/menlo)
* [Meslo](https://github.com/andreberg/Meslo-Font)

## XCode

Dark is nice and we replicated great JetBrains Darcula theme.

To install:

* Clone the repo
* Copy `Darcula.xccolortheme` to `~/Library/Developer/Xcode/UserData/FontAndColorThemes`

## Visual Studio Code

VSCode comes with a lot of cool themese out of the box, but to get the Darcula theme, simply [download it through the VSC Marketplace.](https://marketplace.visualstudio.com/items?itemName=rokoroku.vscode-theme-darcula)

To change fonts in VSCode, open your user settings (typically via `⌘,` on MacOS) and update:

```
  "editor.fontFamily": "Menlo, Monaco, 'Courier New', monospace",
```

You can also configure font size and line height here.

To cycle between themes fast you can use `⌘K ⌘T` which comes with a live preview of each theme you select. You can also manually assign a theme:

```
"workbench.colorTheme": "Darcula Extended",
```

Note: If you are comming to VSCode from Sublime Text, then you might be happy to learn that Monokai and Monokai dimmed are available by default.
