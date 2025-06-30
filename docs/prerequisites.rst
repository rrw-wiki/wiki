Prerequisites
=============

Before you begin working on a Roblox revival, you'll need a few essential tools and dependencies. This page covers the software, utilities, and environments that are commonly used throughout this wiki and the revival development process.

These are grouped by purpose, with a recommended tool listed first, followed by useful alternatives.

Hex Editors
-----------

Hex editors are used to modify and inspect binary files, which is a key part of patching Roblox clients.

- **Recommended**: `HxD <https://mh-nexus.de/en/hxd/>`_
- **Alternative (web-based)**: `HexEd.it <https://hexed.it/>`_
- **Alternative (cross-platform)**: `ImHex <https://github.com/WerWolv/ImHex>`_

Debuggers and Disassemblers
----------------------------

These tools are used for certain patches to the client, as well as general reverse engineering tasks.

- **Recommended**: `x64dbg / x32dbg <https://x64dbg.com/>`_ (used in examples throughout this wiki)
- **Alternative**: `IDA Free <https://hex-rays.com/ida-free/>`_
- **Alternative**: `Ghidra <https://ghidra-sre.org/>`_
- **Alternative**: `Cutter (built on Radare2) <https://cutter.re/>`_

IDEs and Compilers
-------------------

Throughout this wiki we will be showing various examples in different IDEs. We recommend using one of the following if you don't already have a preferred development environment.

- **Recommended IDE**: `Visual Studio Code <https://code.visualstudio.com/>`_
- **Alternative (C/C++)**: `Microsoft Visual Studio <https://visualstudio.microsoft.com/>`_

Client-Related Tools
--------------------

These tools (or their alternatives) are required for patching Roblox clients, signing assets, and setting up functional backends.

- **Auto-Patching Tool**: `roblox-auto-patcher <https://github.com/worships/roblox-auto-patcher>`_  
  Automatically applies common binary patches to Roblox clients.

- **Signing Certificate Generator (required)**: `rbxsign <https://github.com/worships/rbxsign>`_  
  Used to generate signing certificates for CoreScripts and other backend assets. Also generates the public key used by the client.

- **Alternative to rbxsign**: `Roblox-KeyGenerator-Decompiled <https://github.com/worships/Roblox-KeyGenerator-Decompiled>`_

Programming Languages
----------------------

Your choice of programming language is up to you. These are some of the most commonly used languages in public revival projects and examples referenced in this wiki.

- `PHP <https://www.php.net/>`_
- `Python <https://www.python.org/>`_
- `Node.js <https://nodejs.org/>`_
- `Bun <https://bun.sh/>`_ (**recommended alternative to Node.js**)
- `C# <https://learn.microsoft.com/en-us/dotnet/csharp/>`_
- `Go <https://go.dev/>`_
- `Rust <https://www.rust-lang.org/>`_ (*required for some tools by worships*)
- `C++ <https://isocpp.org/>`_

Other Useful Tools
-------------------

These aren't required, but may be useful depending on what you're doing.

- `Wireshark <https://www.wireshark.org/>`_ – for network packet capture and analysis
- `Process Hacker <https://sourceforge.net/projects/processhacker/>`_ – advanced process/task manager
- `Insomnia <https://insomnia.rest/>`_ – for API testing and debugging
- `Git <https://git-scm.com/>`_ – version control system
- `Microsoft Visual C++ Redistributables <https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170>`_ – required for some programs

Next Steps
----------

Make sure you're comfortable using at least some of these tools, especially a hex editor, debugger, and IDE. These will come up frequently in later sections, especially when patching clients or inspecting API behavior.