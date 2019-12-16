# Xndlnks Version of a Monocai Theme for IntelliJ

This is a dark high-contrast Monocai theme for IntelliJ.
It is inspired by [bmikaili](https://github.com/bmikaili/intellij-monocai-theme)
with some modifications and color fixes. This theme only works in IntelliJ 2019.1+.

## Preview

![](preview.png)

## Adjusting this theme to your needs

Some colors are defined in [xndlnk_monocai.theme.json](resources/META-INF/xndlnk_monocai.theme.json) and some other colors are defined in [xndlnk_monocai.xml](resources/META-INF/xndlnk_monocai.xml). IntelliJ is missing a clear documentation about the UI elements and their colors.

Reference: [Customizing UI Theme](http://www.jetbrains.org/intellij/sdk/docs/reference_guide/ui_themes/themes_customize.html).

### How to change colors

1. Modify the json or xml file.
2. Make color adjustments in your IntelliJ instance via `Preferences...`
3. Export your color scheme via `Editor / Color Scheme` to an `.icls` file
4. Open that `.icls` file and copy XML entries to `xndlnk_monocai.xml`

### How to deploy your changes

1. From the main menu invoke `Build / Prepare Plugin Module ... For Deployment`
2. Goto `Preferences / Plugins / Uninstall` and restart IntelliJ
3. Goto `Preferences / Plugins / Install plugin from disk` and select `xndlnk-monocai.jar` file
4. Apply changes
