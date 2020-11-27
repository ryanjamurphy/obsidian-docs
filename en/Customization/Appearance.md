### Base mode

Obsidian comes with two "Base Modes", light and dark. Dark is the default. We call it a "mode" rather than a "theme" because the base mode is the foundation that a custom theme works on top of.

You can change your base mode in Settings -> Appearance.

### Custom theme

You can enable the [[Custom CSS]] plugin to start customizing your Obsidian in greater detail.

As a great starting point, once you enable custom CSS, there are lots of community themes contributed by our amazing community that you can easily choose from.

Once you choose a community theme, you can still add your own tweaks to it by modifying the `obsidian.css` file.

### CSS Snippets

[0.9.18](https://forum.obsidian.md/t/obsidian-release-v0-9-18-insider-build/9063) introduced the ability to implement custom CSS snippets that can be toggled on and off in the Appearance settings. Use these in tandem with CSS themes to add additional modular customizations.

### CSS specification order
CSS is interpreted in the following order: app.css -> obsidian.css -> theme.css -> snippets.
