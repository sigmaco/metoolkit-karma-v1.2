# MathEngine Karma (Physics Engine) v1.2 (2003)
MathEngine Physics Suite branded as "Karma" v1.2 (2003) – Precompiled SDK

This repository provides a partial **precompiled Software Development Kit for Karma 1.2**, the physics simulation engine originally developed by **MathEngine** and widely used in early 2000s real-time applications and game engines.

Karma (sometimes branded simply as **MathEngine Karma**) offered rigid-body dynamics, collision detection, constraints, and tools for integrating advanced physics into 3D applications—well known for its use in several commercial titles of that era.

This suite made its way into early **Unreal Engine** versions, and has been later acquired by **Criterion Software**, consequently requalified as **RenderWare Physics**.

## Why This Repository Exists

The original MathEngine tools and distributions are no longer widely available.  
This repository provides a preservated version of the **precompiled SDK for Karma 1.2** to support:

- Game preservation & reverse engineering research  
- Legacy toolchain maintenance  
- Hobbyist experimentation with early 2000s physics systems


## 📦 What's Included

- **Karma 1.2 Runtime Libraries**  
  Prebuilt binaries ready to link against legacy engines or tools.
- **Header Files**  
  C/C++ headers for the Karma API.
- **Sample Code**  
  Minimal examples demonstrating initialization, body creation, and basic simulations.
- **Documentation (HTML/PDF)**  
  API reference and integration notes from the original 2003 release.

## 🗂 Folder Structure

/bin
Precompiled Karma 1.2 dynamic/static libraries
/include
Header files for engine modules
/samples
Small projects demonstrating core engine features
/docs
API reference and technical documentation


## Requirements

- Compatible **C/C++ toolchain** (MSVC-era compilers recommended)
- Typically requires a legacy Windows environment
- Optional: A 3D engine or framework capable of integrating Newtonian physics modules

## Getting Started

1. Add the `include/` directory to your project’s header search paths.  
2. Link your project with the libraries in `bin/`.  
3. Review the examples in `samples/`.  
4. Consult `docs/` for API details and integration guidelines.

## Contribution

This repository is one of some internal distros owned by the SIGMA Technology Group, it is an archival resource for developers working with legacy Karma-based projects. 

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated. For details, see the "[Contributing Guidelines][contribute-guide]".

You can also contribute or address to any doubt or difficult although by join the SIGMA's gathering point on Discord.

[![SIGMA Discord Server](https://discord.com/api/guilds/349379672351571969/widget.png?style=banner2)](https://sigmaco.org/discord)

The SIGMA thanks [all the contributors][contributors] by their individual and collective involvements in the development of this project.

[![all-contributors](https://contrib.rocks/image?repo=sigmaco/afx&columns=16)][contributors]
