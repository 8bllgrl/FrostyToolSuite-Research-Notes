---
layout: default
title: AI Summaries Index - Codebase Navigation
permalink: /ai-summaries/
---

# 🤖 AI Summaries Index: Frosty Tool Suite Codebase

Welcome to the AI-generated documentation hub. The codebase is organized here based on the primary logical projects within the Frosty Tool Suite for ease of developer navigation.

## 💻 1. Core Applications & Libraries

These links cover the main executable projects and the foundational libraries that provide common UI functionality.

| Project/Area | Source Directories | Summary Link |
| :--- | :--- | :--- |
| **Frosty Editor** | `FrostyEditor/` (`Commands/`, `Windows/`) | [Editor Core & Windows](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-editor) |
| **Frosty Mod Manager** | `FrostyModManager/` (`Compression/`, `Windows/`) | [Mod Manager Logic](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-mod-manager) |
| **Frosty Commands** | `FrostyCmd/` (`Program.cs`, `ProfileCreator.cs`) | [Command-Line Utilities](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-cmd) |
| **Frosty Controls** | `FrostyControls/` | [Custom UI Components](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-controls) |

---

## ⚙️ 2. FrostyPlugin (Shared Core API)

This is the central framework for asset editing, plugin registration, and resource handling.

| Sub-Area | Source Directories | Summary Link |
| :--- | :--- | :--- |
| **Asset Editor Controls** | `FrostyPlugin/Controls/`, `FrostyPlugin/Controls/Editors/` | [UI Elements & Type Editors](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-plugin/controls) |
| **Plugin System & Extensibility** | `FrostyPlugin/Attributes/`, `FrostyPlugin/Extensions/` | [Attributes & Extensions](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-plugin/extensions) |
| **Mod & Resource Structure** | `FrostyPlugin/Mod/`, `FrostyPlugin/IO/` | [Modding Data Types & IO](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-plugin/mod-structure) |
| **Managers & Utilities** | `FrostyPlugin/Managers/`, `FrostyPlugin/Utils/` | [Plugin Managers & Core Utilities](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-plugin/managers) |
| **Viewport & Rendering** | `FrostyPlugin/Viewport/`, `FrostyPlugin/Screens/` | [3D Viewport & Screen Logic](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-plugin/viewport) |

---

## 📚 3. FrostySdk (Low-Level Data Handling)

The SDK provides the low-level logic for interacting with game files, data structures, and profiles.

| Sub-Area | Source Directories | Summary Link |
| :--- | :--- | :--- |
| **Asset Management** | `FrostySdk/Managers/`, `FrostySdk/Managers/Loaders/` | [Asset/Resource/Key Management & Loaders](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-sdk/managers) |
| **I/O and Serialization** | `FrostySdk/IO/` (`CasReader.cs`, `EbxReader.cs`, `DbReader.cs`) | [Low-Level File I/O Logic](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-sdk/io) |
| **EBX Data Types** | `FrostySdk/Ebx/` (`PointerRef.cs`, `ResourceRef.cs`, `CString.cs`) | [Frostbite EBX Data Structures](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-sdk/ebx) |
| **Profiles & Game Keys** | `FrostySdk/Profiles/` (`BF1SDK.dll`, `AnthemSDK.dll`, etc.) | [Game Profiles and SDK DLLs](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-sdk/profiles) |
| **Hashing & Deobfuscation** | `FrostyHash/`, `FrostySdk/Deobfuscators/` | [Hashing and Game Obfuscation Logic](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-sdk/hashing) |

---

## 🔧 4. Mod Execution & Support

Logic for applying and running mods in-game.

| Sub-Area | Source Directories | Summary Link |
| :--- | :--- | :--- |
| **Mod Execution Actions** | `FrostyModSupport/Actions/` (`CasModExecutor.cs`, `FifaModExecutor.cs`) | [Game-Specific Mod Execution Logic](/FrostyToolSuite-Research-Notes/ai-summaries/mod-support/actions) |
| **Legacy Scripting** | `FrostyModSupport/` (`FrostyLegacyScripting.cs`) | [Legacy Mod Scripting Support](/FrostyToolSuite-Research-Notes/ai-summaries/mod-support/legacy) |

---

## 🔌 5. Individual Plugins

These are separate, specialized projects for specific game features or asset types. Each project below should have its own dedicated summary page.

| Plugin Project Name | Source Directory | Summary Link |
| :--- | :--- | :--- |
| **Animation Editor** | `Plugins/AnimationEditorPlugin/` | [Animation Editor Plugin](/FrostyToolSuite-Research-Notes/ai-summaries/plugins/animation-editor) |
| **MeshSet & Skeleton Editor** | `Plugins/MeshSetPlugin/` | [MeshSet and Skeleton Plugin](/FrostyToolSuite-Research-Notes/ai-summaries/plugins/meshset) |
| **Sound Editor** | `Plugins/SoundEditorPlugin/` | [Sound and Wave Editor Plugin](/FrostyToolSuite-Research-Notes/ai-summaries/plugins/sound-editor) |
| **Texture Editor** | `Plugins/TexturePlugin/` | [Texture Asset Plugin](/FrostyToolSuite-Research-Notes/ai-summaries/plugins/texture) |
| **Localization (Bioware/FS)** | `Plugins/BiowareLocalizationPlugin/`, `Plugins/FsLocalizationPlugin/` | [Localization Plugins](/FrostyToolSuite-Research-Notes/ai-summaries/plugins/localization) |
| **Lua & Scripting** | `Plugins/LuaPlugin/` | [Lua Editor and Runner Plugin](/FrostyToolSuite-Research-Notes/ai-summaries/plugins/lua) |
| **Object Variation** | `Plugins/ObjectVariationPlugin/` | [Object Variation Plugin](/FrostyToolSuite-Research-Notes/ai-summaries/plugins/object-variation) |
| **Bundle Editor** | `Plugins/BundleEditorPlugin/`, `Plugins/DelayLoadBundlePlugin/` | [Bundle & DelayLoad Plugins](/FrostyToolSuite-Research-Notes/ai-summaries/plugins/bundle) |
| **Fifa Legacy** | `Plugins/Fifa/` (All sub-plugins) | [Fifa Legacy Tools](/FrostyToolSuite-Research-Notes/ai-summaries/plugins/fifa-legacy) |
| **Type Explorer** | `Plugins/TypeExplorerPlugin/` | [Type Explorer Plugin](/FrostyToolSuite-Research-Notes/ai-summaries/plugins/type-explorer) |
| **All Other Plugins** | *(e.g., `SvgImagePlugin/`, `EbxToXmlPlugin/`, etc.)* | [Miscellaneous Plugins Index](/FrostyToolSuite-Research-Notes/ai-summaries/plugins/misc) |