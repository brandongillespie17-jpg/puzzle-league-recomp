# Puzzle League Recomp

Experimental native Linux and Windows builds of Pokémon Puzzle League for Nintendo 64. Supply your own supported USA ROM. No ROM, game artwork or saved progress is included in the downloads.

[Download the development preview](https://github.com/brandongillespie17-jpg/puzzle-league-recomp/releases/tag/v0.1.0-preview.20261124)

| Platform | Start playing | Requirements |
| --- | --- | --- |
| Windows 10/11 x64 | Extract the complete ZIP, then open **Play.cmd** | Python 3.11+ with Tk; compatible Vulkan driver. Tested under Wine; actual Windows-PC testing remains pending. |
| Linux x86_64 | Extract the complete archive, then open **Play.sh** | glibc **2.44+**, Python 3.11+ with Tk, and the system dependencies in README-LINUX.md. Built on CachyOS; not a portable build for older Linux releases. |

Both packages include a ROM picker, normal offline play and a separate **Start Online** launcher. Offline play needs no account or server. Private online lobbies require a separately operated relay; no hosted internet service is included.

Local Linux/Windows-under-Wine testing completed 1,200 active gameplay updates through an original round result and into a rematch, with matching observed state and inputs. Wider game-mode, hardware and internet testing is still needed.

The release's **Source** archive contains the project, pinned dependency sources, patches, license notices and build instructions. Consult those per-file and upstream notices for license terms. Full rebuilding from that source archive has not been repeated. **SHA256SUMS.txt** records download checksums.
