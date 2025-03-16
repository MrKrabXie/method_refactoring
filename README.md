
# Method Refactoring Plugin Description
![Build](https://github.com/MrKrabXie/method_refactoring/workflows/Build/badge.svg)
[![Version](https://img.shields.io/jetbrains/plugin/v/MARKETPLACE_ID.svg)](https://plugins.jetbrains.com/plugin/MARKETPLACE_ID)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/MARKETPLACE_ID.svg)](https://plugins.jetbrains.com/plugin/MARKETPLACE_ID)

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
## Plugin Overview
JavaRefactorPlugin is a powerful plugin designed specifically for IntelliJ IDEA, aiming to assist developers in efficiently refactoring Java code. It provides a rich set of practical functions that can significantly improve code quality, maintainability, and readability. Whether for small projects or large enterprise-level applications, this plugin offers high value for code optimization.

## Core Features
1. **Code Structure Optimization**  
   Automatically identifies and optimizes redundant structures in Java code, such as splitting overly long methods into smaller ones, adjusting class inheritance relationships, and modifying member variable access permissions to make the code structure clearer and more compliant with best practices.

2. **Code Simplification & Cleanup**  
   Removes unused code blocks, variables, and import statements. Simplifies complex conditional and loop structures to reduce code redundancy and enhance code simplicity.

3. **Refactoring Suggestions**  
   Provides intelligent refactoring recommendations based on in-depth code analysis. For example, when renaming a method, it automatically highlights all call sites to help developers make informed decisions and reduce refactoring risks.

4. **Pattern Recognition & Application**  
   Identifies common design pattern scenarios and offers one-click transformation capabilities. Convert code into Singleton, Factory, or other patterns to improve code design and scalability.

## Open Source License
This plugin is distributed under the Apache License 2.0, which allows:
- Free use for both commercial and non-commercial purposes
- Redistribution in original or modified forms
- Creation of derivative works

Key requirements:
1. Maintain all copyright and license notices
2. Clearly document any modifications made



## Template ToDo list
- [x] Create a new [IntelliJ Platform Plugin Template][template] project.
- [X] Get familiar with the [template documentation][template].
- [X] Adjust the [pluginGroup](./gradle.properties) and [pluginName](./gradle.properties), as well as the [id](./src/main/resources/META-INF/plugin.xml) and [sources package](./src/main/kotlin).
- [X] Adjust the plugin description in `README` (see [Tips][docs:plugin-description])
- [X] Review the [Legal Agreements](https://plugins.jetbrains.com/docs/marketplace/legal-agreements.html?from=IJPluginTemplate).
- [ ] [Publish a plugin manually](https://plugins.jetbrains.com/docs/intellij/publishing-plugin.html?from=IJPluginTemplate) for the first time.
- [ ] Set the `MARKETPLACE_ID` in the above README badges. You can obtain it once the plugin is published to JetBrains Marketplace.
- [ ] Set the [Plugin Signing](https://plugins.jetbrains.com/docs/intellij/plugin-signing.html?from=IJPluginTemplate) related [secrets](https://github.com/JetBrains/intellij-platform-plugin-template#environment-variables).
- [ ] Set the [Deployment Token](https://plugins.jetbrains.com/docs/marketplace/plugin-upload.html?from=IJPluginTemplate).
- [ ] Click the <kbd>Watch</kbd> button on the top of the [IntelliJ Platform Plugin Template][template] to be notified about releases containing new features and fixes.

<!-- Plugin description -->
This Fancy IntelliJ Platform Plugin is going to be your implementation of the brilliant ideas that you have.

This specific section is a source for the [plugin.xml](/src/main/resources/META-INF/plugin.xml) file which will be extracted by the [Gradle](/build.gradle.kts) during the build process.

To keep everything working, do not remove `<!-- ... -->` sections. 
<!-- Plugin description end -->

## Installation

- Using the IDE built-in plugin system:
  
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>Marketplace</kbd> > <kbd>Search for "method_refactoring"</kbd> >
  <kbd>Install</kbd>
  
- Using JetBrains Marketplace:

  Go to [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/MARKETPLACE_ID) and install it by clicking the <kbd>Install to ...</kbd> button in case your IDE is running.

  You can also download the [latest release](https://plugins.jetbrains.com/plugin/MARKETPLACE_ID/versions) from JetBrains Marketplace and install it manually using
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>

- Manually:

  Download the [latest release](https://github.com/MrKrabXie/method_refactoring/releases/latest) and install it manually using
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>


---
Plugin based on the [IntelliJ Platform Plugin Template][template].

[template]: https://github.com/JetBrains/intellij-platform-plugin-template
[docs:plugin-description]: https://plugins.jetbrains.com/docs/intellij/plugin-user-experience.html#plugin-description-and-presentation
