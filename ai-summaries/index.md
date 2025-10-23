---
layout: default
title: AI Summaries Index - Codebase Navigation
permalink: /ai-summaries/
---

# 🤖 AI Summaries Index: Frosty Tool Suite Codebase

Welcome to the AI-generated documentation hub. The codebase is organized here based on the primary logical projects within the Frosty Tool Suite for ease of developer navigation.

> **Note:** The links below assume you will create files with the corresponding names (e.g., `frosty-editor.md`, `frosty-sdk/managers.md`) within the `_ai-summaries/` directory.

## 💻 1. Core Applications

These are the main executable projects that users and developers interact with.

| Project Name | Source Code Directory | Description | Summary Link |
| :--- | :--- | :--- | :--- |
| **Frosty Editor** | `FrostyEditor/` | The primary GUI for asset viewing and modification. | [Frosty Editor Core](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-editor) |
| **Frosty Mod Manager** | `FrostyModManager/` | The separate application for compiling, installing, and managing mods. | [Mod Manager Core](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-mod-manager) |
| **Frosty Cmd** | `FrostyCmd/` | Command-line utilities for hashing, database dumping, and other background tasks. | [FrostyCmd Utilities](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-cmd) |

## 🧩 2. Foundational Libraries

These libraries contain the core logic, data structures, and APIs shared across the applications and plugins.

### 📚 Frosty Sdk (`FrostySdk/`)
The foundation of the toolset, containing low-level game-specific data, profiles, and file-handling logic.

* **[SDK Overview](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-sdk/):** High-level summary and structure of the SDK project.
* **[Managers](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-sdk/managers):** Asset loading, file system, resource, and key management (`AssetManager.cs`, `FileSystemManager.cs`).
* **[Input/Output (IO)](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-sdk/io):** Readers and Writers for core file formats like EBX, CAS, and CAT (`EbxReader.cs`, `CasReader.cs`).
* **[EBX Types](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-sdk/ebx):** Core data types and references used in the Frostbite engine's EBX assets (`PointerRef.cs`, `ResourceRef.cs`).

### ⚙️ Frosty Plugin (`FrostyPlugin/`)
The shared core library for common functionality, UI components, and the plugin registration system.

* **[Plugin Overview](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-plugin/):** High-level summary and the core plugin registration mechanism.
* **[UI Controls & Editors](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-plugin/controls):** Base classes for asset editors, property grids, and UI components (`FrostyAssetEditor.cs`, `FrostyPropertyGrid.cs`).
* **[Mod Structure](/FrostyToolSuite-Research-Notes/ai-summaries/frosty-plugin/mod-structure):** Defines the structure of a loaded mod and its resources (`EbxResource.cs`, `IFrostyMod.cs`).

## 🔌 3. Plugins

The directory containing extension projects that add support for specific game features or specialized editing capabilities.

* **[All Plugins Index](/FrostyToolSuite-Research-Notes/ai-summaries/plugins/):** A master list and overview of the various plugins available, from Texture to Animation Editors.