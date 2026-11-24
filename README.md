# Puzzle League Recomp

Experimental native development builds of Pokémon Puzzle League for Windows x64 and Linux x86_64. Supply your own supported USA ROM. No ROM or game artwork is included.

**[Download the installer and builds](https://github.com/brandongillespie17-jpg/puzzle-league-recomp/releases/tag/v0.1.1-preview.20261124)**

| Platform | Getting started |
| --- | --- |
| Windows 10/11 x64 | Use the **Windows Setup EXE** for shortcuts and guided dependency setup. A portable ZIP is also available. |
| Linux x86_64, glibc 2.44+ | Extract the Linux archive and open **Play.sh**. **Setup.sh** offers missing dependencies on supported current Arch/CachyOS systems. |

Use **Choose ROM** in the launcher, then **Play**. The launcher remembers the file location. A compatible graphics driver is required. Windows setup offers missing Python/Tk and Microsoft runtimes using official vendor downloads and visible installer dialogs; it does not accept vendor terms for you. Linux setup uses the distribution package manager and does not upgrade the operating system.

**Start Online** opens the private lobby. Online play needs a separate relay; these downloads do not provide a hosted service. Each player needs their own ROM and compatible build.

Windows gameplay has been tested under Wine, with actual Windows-PC testing still pending. The Linux build targets current CachyOS and is not portable to older distributions. Read the release notes and included platform guides for requirements and test limitations.

The explicitly named **PuzzleLeagueRecomp-Source** release archive contains the complete project snapshot, pinned dependency sources, patches, installer recipes and license notices. GitHub's automatically generated “Source code” archives contain only this distribution repository's README. Consult the per-file and upstream notices for license terms. A full rebuild from the assembled source archive has not been repeated. **SHA256SUMS.txt** records download checksums.
