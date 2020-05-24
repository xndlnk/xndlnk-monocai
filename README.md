# XndLnks Version of a Monokai Theme for IntelliJ

This is a dark high-contrast Monokai theme for IntelliJ 2019.1+. The theme is inspired by [Monokai](https://www.monokai.nl/)
and by [bmikailis Monocai Theme](https://github.com/bmikaili/intellij-monocai-theme).

## Preview

![](preview.png)

## How to adjust this theme to your preferences

- Clone this repo
- Look into [xndlnk_monokai.theme.json](resources/META-INF/xndlnk_monokai.theme.json)
  and [xndlnk_monokai.xml](resources/META-INF/xndlnk_monokai.xml) and change colors directly.
- Or make color adjustments in your IntelliJ instance via `Preferences...`
    - Export your color scheme via `Editor / Color Scheme` to an `.icls` file
    - Open that `.icls` file and copy XML entries to `xndlnk_monokai.xml`
- Deploy your changes as a plugin:
    - From the main menu invoke `Build / Prepare Plugin Module ... For Deployment`
    - Goto `Preferences / Plugins / xndlnk-monokai / Uninstall` and restart IntelliJ
    - Goto `Preferences / Plugins / Install plugin from disk` and select `xndlnk-monokai.jar` file
    - Apply changes

## Color documentation

I could not find a good documentation of possible color keys for UI elements.

Some color references I found:
- [Customizing UI Theme](http://www.jetbrains.org/intellij/sdk/docs/reference_guide/ui_themes/themes_customize.html)
- [All keys from IntelliJ Platform and custom UI components](https://upsource.jetbrains.com/idea-ce/file/idea-ce-40e5005d02df57f58ac2d498867446c43d61101f/platform/platform-resources/src/themes/metadata/IntelliJPlatform.themeMetadata.json)
