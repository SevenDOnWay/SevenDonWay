# Hi, I'm Loc 👋

[![GitHub](https://img.shields.io/badge/GitHub-SevenDOnWay-181717?style=flat&logo=github)](https://github.com/SevenDOnWay)
[![Email](https://img.shields.io/badge/Email-ngodaloc2006%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:ngodaloc2006@gmail.com)
[![Location](https://img.shields.io/badge/Location-Ho_Chi_Minh_City%2C_Vietnam-blue?style=flat&logo=google-maps&logoColor=white)](#)

🎮 **Computer Science Student | Game Developer | Gameplay & Tools Engineer**


I focus on bridging clean software engineering with performant, responsive gameplay feel. In addition to client gameplay and multiplayer networking, I build developer pipelines and tools that empower creators and automate tedious workflows.

- 🎯 **Primary Focus:** Gameplay Programming · Unity Systems · Editor Tooling & Automation
- 🛠️ **Core Principles:** Modular Architecture · Data-Driven Systems · Zero-Overhead Optimization
- 🌱 **Currently Exploring:** Photon Fusion, Scalable Game Backend with ASP.NET Core & MongoDB, AI-driven Editor Workflows (MCP)
- 💬 **Languages:** Vietnamese (Native), English

---

## 🛠️ Tech Stack & Skills

### Game Engines & Tooling
![Unity](https://img.shields.io/badge/Unity_6-000000?style=for-the-badge&logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![Photon Fusion](https://img.shields.io/badge/Photon_Fusion-004480?style=for-the-badge&logo=photon&logoColor=white)
![Editor Scripting](https://img.shields.io/badge/Unity_Editor_Scripting-222222?style=for-the-badge&logo=unity&logoColor=white)
![UGUI / UI Toolkit](https://img.shields.io/badge/UGUI_%2F_UI_Toolkit-02569B?style=for-the-badge)

### Programming Languages
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript / Node](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)

### Backend & Data
![.NET](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)

### Tools & DevOps
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Model Context Protocol](https://img.shields.io/badge/MCP_Protocol-6E40C9?style=for-the-badge)

---

## 🚀 Featured Projects

### 🎨 [UIQualityLife — Unity 6 UI & Styling Pipeline Toolkit](https://github.com/SevenDOnWay/UIQualityLife)
> *A rapid UI preset manager, CSS-like styling system, and automated UI creation pipeline for Unity 6.*

- **Design Token & Styling Pipeline**: Translates CSS variables, Tailwind tokens, and web styling into native Unity theme palettes with auto-generated 8×8 dynamic swatch previews.
- **Stateful Animation Engine**: Built a zero-dependency Visual State Machine (`UIVisualState`) with Penner easing curves supporting hover, click bounce, focus, and ambient loops.
- **Dual-Mode IPC Editor Bridge**: Implemented a local HTTP bridge (`127.0.0.1:8765`) + asynchronous file queue allowing headless prefab generation without locking the editor.
- **AI & CLI Automation**: Ships with custom Node.js CLI commands and Model Context Protocol (MCP) tool integration, letting AI agents construct native Unity prefabs directly from specs or HTML/Tailwind snippets.

**Tech:** Unity 6 · C# Editor Scripting · Node.js · Model Context Protocol (MCP) · REST IPC · TextMeshPro · UGUI  
🔗 [View Repository](https://github.com/SevenDOnWay/UIQualityLife)

---

### 🃏 [Tiến Lên — Multiplayer Card Game](https://github.com/SevenDOnWay)
> *A networked multiplayer implementation of the classic Vietnamese Tiến Lên card game with authoritative session flow.*

- Built client-server game loop and state synchronization using **Photon Fusion**.
- Designed matchmaking, seat selection, turn managers, and card-dealing flows using **VContainer** dependency injection.
- Integrated an **ASP.NET Core** backend with **MongoDB** for secure player authentication, currency transactions, and profile persistence.

**Tech:** Unity · C# · Photon Fusion · VContainer · ASP.NET Core · MongoDB  
🔗 [View Repository](https://github.com/SevenDOnWay)

---

### 🧱 [Break Brick — Unity 2D Mobile Game](https://github.com/SevenDOnWay/Break-Brick)
> *A portrait-mode arcade brick breaker engineered around data-driven scalability and clean architecture.*

- Designed an extensible architecture using **ScriptableObjects** for brick types, modular power-ups, and level balancing.
- Implemented **Dependency Injection** and event-driven decoupled systems to eliminate tightly coupled singletons.
- Utilized high-performance **Object Pooling** for visual effects, projectiles, and particle systems under intense object counts.

**Tech:** Unity · C# · ScriptableObjects · Dependency Injection · Object Pooling  
🔗 [View Repository](https://github.com/SevenDOnWay/Break-Brick)


---

## 🧠 Core Engineering Principles

| Area | Focus |
|---|---|
| **Gameplay Architecture** | Designing modular, plug-and-play gameplay features using decoupled events, state machines, and data-driven configs. |
| **Tooling & DX** | Building custom inspector utilities, asset generation pipelines, and automation tools to speed up iteration times. |
| **Multiplayer Systems** | State synchronization, client prediction/lag compensation, lobby orchestration, and session sharding. |
| **Backend Integration** | Connecting clients to scalable cloud services for auth, telemetry, matchmaking, and player persistence. |

---

## 💭 The Dream Game Formula

```csharp
public struct GameFormula
{
    public const float Fun     = float.PositiveInfinity;
    public const int   Players = int.MaxValue;
    public const int   FPS     = 400+;
    public const int   Hackers = 0;
}
