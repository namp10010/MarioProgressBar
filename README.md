# MarioProgressBar

The Mario progress bar for IntelliJ IDEA and other JetBrains IDEs.

[![Version](https://img.shields.io/jetbrains/plugin/v/14708-mario-progress-bar)](https://plugins.jetbrains.com/plugin/14708-mario-progress-bar/versions)
[![Rating](https://img.shields.io/jetbrains/plugin/r/rating/14708-mario-progress-bar)](https://plugins.jetbrains.com/plugin/14708-mario-progress-bar/reviews)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/14708-mario-progress-bar)](https://plugins.jetbrains.com/plugin/14708-mario-progress-bar)

![MarioDeterminateBar](https://i.imgur.com/3ry0GOy.gif)

![MarioIndeterminateBar](https://i.imgur.com/fdUDmZI.gif)


This is the [Mario Progress Bar](https://plugins.jetbrains.com/plugin/14708-mario-progress-bar/versions) for [JetBrains IntelliJ IDEA](https://www.jetbrains.com/idea/) based on the Nyan Progress Bar by Dmitry Batkovitch. It display Mario with some bricks for the basic bar and a Koopa Shell for the indeterminate one.


## Contributing

Contributions are very welcome on this project! Please see our [contributing guidelines](CONTRIBUTING.md) and [code of conduct](CODE_OF_CONDUCT.md) to get started.

## Acknowledgements

### Sprites
* All sprites belong to Nintendo. Find them on [Spriters-Resource](https://www.spriters-resource.com/)

### Code

* The code for the progress bar was adapted from [Nyan Progess Bar](https://github.com/batya239/NyanProgressBar).
* This plugin is of course heavily dependent on JetBrains' IntelliJ SDK  

### Misc

* Gif editing done with [Gimp](https://www.gimp.org/)
* This readme is inspired by the [Kagof intellij-pokemon-progress](https://github.com/kagof/intellij-pokemon-progress/blob/master/README.md)
* The Pokémon Company, for creating Pokémon

[![Buy Me a Coffee](https://img.buymeacoffee.com/api/?url=aHR0cHM6Ly9pbWcuYnV5bWVhY29mZmVlLmNvbS9hcGkvP3VybD1hSFIwY0hNNkx5OWpaRzR1WW5WNWJXVmhZMjltWm1WbExtTnZiUzkxY0d4dllXUnpMM0J5YjJacGJHVmZjR2xqZEhWeVpYTXZNakF5TVM4d015ODBZekkwT0RnNE1XWmxOVE5pWmprM1lUa3pOV1kxWm1NNFlqRXpPV1EyTWk1d2JtYz0mc2l6ZT0zMDAmbmFtZT1raWtpbWFuamFybw==&creator=kikimanjaro&is_creating=creating%20mobile%20apps%20and%20plugins&design_code=1&design_color=%23ff813f&slug=kikimanjaro)](https://www.buymeacoffee.com/kikimanjaro)

### Plugin template

![Build](https://github.com/namp10010/gotestgen/workflows/Build/badge.svg)
[![Version](https://img.shields.io/jetbrains/plugin/v/PLUGIN_ID.svg)](https://plugins.jetbrains.com/plugin/PLUGIN_ID)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/PLUGIN_ID.svg)](https://plugins.jetbrains.com/plugin/PLUGIN_ID)

## Template ToDo list
- [x] Create a new [IntelliJ Platform Plugin Template][template] project.
- [ ] Get familiar with the [template documentation][template].
- [ ] Verify the [pluginGroup](/gradle.properties), [plugin ID](/src/main/resources/META-INF/plugin.xml) and [sources package](/src/main/kotlin).
- [ ] Review the [Legal Agreements](https://plugins.jetbrains.com/docs/marketplace/legal-agreements.html).
- [ ] [Publish a plugin manually](https://plugins.jetbrains.com/docs/intellij/publishing-plugin.html?from=IJPluginTemplate) for the first time.
- [ ] Set the Plugin ID in the above README badges.
- [ ] Set the [Deployment Token](https://plugins.jetbrains.com/docs/marketplace/plugin-upload.html).
- [ ] Click the <kbd>Watch</kbd> button on the top of the [IntelliJ Platform Plugin Template][template] to be notified about releases containing new features and fixes.

<!-- Plugin description -->
This Fancy IntelliJ Platform Plugin is going to be your implementation of the brilliant ideas that you have.

This specific section is a source for the [plugin.xml](/src/main/resources/META-INF/plugin.xml) file which will be extracted by the [Gradle](/build.gradle.kts) during the build process.

To keep everything working, do not remove `<!-- ... -->` sections.
<!-- Plugin description end -->

## Installation

- Using IDE built-in plugin system:

  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>Marketplace</kbd> > <kbd>Search for "gotestgen"</kbd> >
  <kbd>Install Plugin</kbd>

- Manually:

  Download the [latest release](https://github.com/namp10010/gotestgen/releases/latest) and install it manually using
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>


---
Plugin based on the [IntelliJ Platform Plugin Template][template].

[template]: https://github.com/JetBrains/intellij-platform-plugin-template
