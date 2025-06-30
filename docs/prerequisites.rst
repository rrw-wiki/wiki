Prerequisites
=============

Before you begin working on a Roblox revival, you'll need a few essential tools and dependencies. This page covers the software, utilities, and environments that are commonly used throughout this wiki and the revival development process.

These are grouped by purpose, with a recommended tool listed first, followed by useful alternatives.

Hex Editors
-----------

Hex editors are used to modify and inspect binary files, which is a key part of patching Roblox clients.

- **Recommended**: [HxD](https://mh-nexus.de/en/hxd/)
- **Alternative (web-based)**: [HexEd.it](https://hexed.it/)
- **Alternative (cross-platform)**: [ImHex](https://github.com/WerWolv/ImHex)

Debuggers & Disassemblers
--------------------------

These tools are used for certain patches to the client, as well as general reverse engineering tasks.

- **Recommended**: [x64dbg / x32dbg](https://x64dbg.com/) — used in examples throughout this wiki
- **Alternative**: [IDA Free](https://hex-rays.com/ida-free/)
- **Alternative**: [Ghidra](https://ghidra-sre.org/)
- **Alternative**: [Cutter (built on Radare2)](https://cutter.re/)

IDEs & Compilers
----------------

Throughout this wiki we will be showing various examples in different IDEs, we recommend using these if you do not have one already. Otherwise its up to you:

- **Recommended IDE**: [Visual Studio Code](https://code.visualstudio.com/)
- **Alternative (C/C++)**: [Microsoft Visual Studio](https://visualstudio.microsoft.com/)

Client-Related Tools
--------------------

These tools (or its possible alternatives) are required tools for patching Roblox clients, signing assets, etc.

- **Auto-Patching Tool**: [`roblox-auto-patcher`](https://github.com/worships/roblox-auto-patcher)  
  Automatically applies common binary patches to Roblox clients.

- **Signing Certificate Generator (Required)**: [`rbxsign`](https://github.com/worships/rbxsign)  
  Used for generating the signing certificate needed to sign CoreGuis and other assets in the backend, as well as the public key used by the clients.

- **Alternative to rbxsign**: [`Roblox-KeyGenerator-Decompiled`](https://github.com/worships/Roblox-KeyGenerator-Decompiled)

Programming Languages
----------------------

Your choice of programming language is up to you, these are some of the most commonly used languages from public revival projects and examples in this wiki:

- [PHP](https://www.php.net/)
- [Python](https://www.python.org/)
- [Node.js](https://nodejs.org/)
- [Bun](https://bun.sh/) (***recommended alternative to Node.js***)
- [C#](https://learn.microsoft.com/en-us/dotnet/csharp/)
- [Go](https://go.dev/)
- [Rust](https://www.rust-lang.org/) (*required if building certain rust tools by "worships"*)
- [C++](https://isocpp.org/)

Other Useful Tools
-------------------

These aren't required, but may be useful depending on what you're doing:

- [Wireshark](https://www.wireshark.org/) — for network packet capture and analysis
- [ProcessHacker](https://sourceforge.net/projects/processhacker/) - advanced process/task manager
- [Insomnia](https://insomnia.rest/) — for API testing and debugging
- [Git](https://git-scm.com/) — version control system
- [Microsoft Visual C++ Redistributables](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170) - required for some programs

Next Steps
-----------

Make sure you're comfortable using at least some of these tools, especially a hex editor, debugger, and IDE. These will come up frequently in later sections, especially when patching clients or inspecting API behavior.