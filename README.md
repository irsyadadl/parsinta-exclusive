## Parsinta Exclusive
Parsinta Exclusive is a color scheme, customized user interface theme and complete icon set for Visual Studio Code. It has been designed by the Irsyad A. Panjaitan.

## Apply theme

To apply theme, it's so simple. Just open your command palette and type "settings.json". Then you can add the theme like so

```json
{
    "workbench.colorTheme": "Parsinta Exclusive",
    // ...
}
```

If you care about the title bar style, please make sure you have the titleBarStyle to "custom" like so:
```json
{
    "workbench.colorTheme": "Parsinta Exclusive",
    "window.titleBarStyle": "custom"
    // ...
}

If you want, I have some recommended settings that you can use.

```bash
{
    "workbench.colorTheme": "Parsinta Exclusive",
    "editor.lightbulb.enabled": false,
    "editor.selectionHighlight": false,
    "editor.overviewRulerBorder": false,
    "editor.renderLineHighlight": "none",
    "editor.occurrencesHighlight": false,
    "problems.decorations.enabled": false,
    "editor.renderControlCharacters": false,
    "editor.hideCursorInOverviewRuler": true,
}
```

If you like more, please read on [Parsinta](https://parsinta.com/s/psnth).

## Contribute

I also opened the repo on [github](https://github.com/irsyadadl/parsinta-exclusive), so for those of you who want to make the theme more robust, or add support for other languages, you can directly make a pull request.
