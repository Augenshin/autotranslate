# Auto Translate

**An automated translation tool for Minecraft 26.2 Fabric mods.**

Auto Translate scans installed mods for language entries, translates missing text through configurable translation services, and generates a resource pack to apply the results in-game.

No manual language-file extraction or modification of original mod files is required. Configure your preferred translation provider, choose your target language, and let Auto Translate handle the workflow.

## Features

- **One-click batch translation** of installed mod language files.
- **Multiple translation providers**, including Google, Bing, DeepL, Baidu, Youdao, LibreTranslate, MyMemory, and OpenAI-compatible APIs.
- **Automatic resource pack generation** to apply translated language entries.
- **Optional automatic resource pack activation** and reload.
- **Configurable source and target languages**, with support for following the game's current language.
- **Translation caching and request controls**, including batch size, request interval, maximum text length, and cache limit.
- **Additional UI text rewriting** for supported hardcoded interface strings.
- **Meteor Client UI translation support.**
- **HTTP proxy configuration** and translation provider connection testing.
- **In-game configuration interface** for managing translation settings and tasks.

## Getting Started

1. Install Auto Translate in your Minecraft Fabric instance.
2. Open the mod's configuration screen.
3. Select a translation provider and configure its required credentials or endpoint.
4. Choose your source and target languages.
5. Start the translation task and wait for the resource pack to be generated.
6. Enable the generated resource pack if it is not activated automatically.

## Requirements

- Minecraft 26.2
- Fabric Loader 0.19.5+
- Java 25+
- Fabric API

Mod Menu and Cloth Config are optional. Meteor Client is optional and required only for its related compatibility features.

## Notes

Translation quality and availability depend on the selected provider, network connectivity, API limits, and service configuration. Some providers may require an API key or incur usage costs.

Auto Translate aims to make Minecraft mod localization easier by automating the process of translating language files and applying the results through resource packs.
