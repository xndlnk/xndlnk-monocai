# Xndlnks Version of a Monokai Theme for IntelliJ

This is a dark high-contrast Monokai theme for IntelliJ 2019.1+.

Inspirations:
- [Monokai](https://www.monokai.nl/)
- [bmikaili](https://github.com/bmikaili/intellij-monocai-theme)

## Preview

![](preview.png)

## Adjusting this theme to your needs

Some colors are defined in [xndlnk_monokai.theme.json](resources/META-INF/xndlnk_monokai.theme.json) and some other colors are defined in [xndlnk_monokai.xml](resources/META-INF/xndlnk_monokai.xml). IntelliJ is missing a clear documentation about the UI elements and their colors.

Reference: [Customizing UI Theme](http://www.jetbrains.org/intellij/sdk/docs/reference_guide/ui_themes/themes_customize.html).

### How to install

Goto `Preferences / Plugins / Install plugin from disk` and select `xndlnk-monokai.jar` file

### How to change colors

1. Modify the json or xml file.
2. Make color adjustments in your IntelliJ instance via `Preferences...`
3. Export your color scheme via `Editor / Color Scheme` to an `.icls` file
4. Open that `.icls` file and copy XML entries to `xndlnk_monokai.xml`

### How to deploy your changes

1. From the main menu invoke `Build / Prepare Plugin Module ... For Deployment`
2. Goto `Preferences / Plugins / xndlnk-monokai / Uninstall` and restart IntelliJ
3. Goto `Preferences / Plugins / Install plugin from disk` and select `xndlnk-monokai.jar` file
4. Apply changes
