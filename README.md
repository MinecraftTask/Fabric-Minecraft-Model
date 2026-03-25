Fabric Mod Template

A clean and structured **Fabric mod template** for Minecraft, built for development, testing, and scalable mod architecture.

Overview

This repository provides a solid starting point for creating Minecraft mods using the **Fabric mod loader**. It is designed to be simple enough for learning and flexible enough for real projects.

Features

- Fabric-based Minecraft mod setup
- Clean and maintainable project structure
- Ready for custom gameplay features
- Easy to expand with commands, items, blocks, events, and mixins
- Suitable for both learning and production-ready mod development

Project Structure

```bash
src/
 └── main/
      ├── java/
      │    └── your/package/mod/
      │         ├── ModMain.java
      │         ├── item/
      │         ├── block/
      │         ├── event/
      │         ├── util/
      │         └── mixin/
      │
      └── resources/
           ├── fabric.mod.json
           ├── modid.mixins.json
           └── assets/
                └── modid/
