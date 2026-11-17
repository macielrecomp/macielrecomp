<div align="center">

# Maciel Recomp

### Static recompilation of 1990s arcade games into native C++

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=E0301E&center=true&vCenter=true&width=820&lines=Arcade+programs+recompiled+into+native+C%2B%2B;TMS34010+%C2%B7+ADSP-2105+%C2%B7+6809+%E2%86%92+C%2B%2B17;No+emulator+at+runtime%3A+built+from+your+own+ROM;Direct3D+12+%C2%B7+CRT+filters+%C2%B7+VRR)](https://github.com/macielrecomp)

[![Ko-fi](https://img.shields.io/badge/Support_on_Ko--fi-FF5E5B?style=for-the-badge&logo=kofi&logoColor=white)](https://ko-fi.com/macielrecomp)

</div>

---

I build **static recompilers**: tools that read the program of an arcade board and
turn it into C++ that runs natively on a PC. The board's hardware (video, sound DSP,
CMOS, inputs) is modelled by hand in C++; the game's own code is generated, never
written by hand. Fidelity first: same rules, timing, voices and effects as the cabinet.

## 🕹️ Featured project

### [TriUnit Recomp](https://github.com/macielrecomp/triunit-recomp)

Static recompilation, done locally from the user's ROM, of TMS34010 arcade boards
(T-Unit and Wolf Unit).

- Visual setup app: verify your ROM files, build, and play, without typing commands
- Native C++17 executables built on your own machine; no game files distributed
- Arcade Original and Remastered editions: CRT presets, ScaleFX, CAS, SMAA, VRR
- Remastered extras such as floor blood that stays for the whole fight

## 🔧 What I work with

**Recompiled hardware**

![TMS34010](https://img.shields.io/badge/TMS34010-GSP-B71C1C?style=for-the-badge)
![ADSP-2105](https://img.shields.io/badge/ADSP--2105-DCS_sound-6A1B9A?style=for-the-badge)
![6809](https://img.shields.io/badge/Motorola-6809-1565C0?style=for-the-badge)
![YM2151](https://img.shields.io/badge/YM2151-FM-2E7D32?style=for-the-badge)
![OKI ADPCM](https://img.shields.io/badge/OKI-ADPCM-EF6C00?style=for-the-badge)

**Languages and tools**

![C++](https://img.shields.io/badge/C++17-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![MSYS2](https://img.shields.io/badge/MSYS2_MinGW--w64-0E7AC0?style=for-the-badge&logo=msys2&logoColor=white)
![Direct3D 12](https://img.shields.io/badge/Direct3D_12-0078D4?style=for-the-badge)
![HLSL](https://img.shields.io/badge/HLSL-5E35B1?style=for-the-badge)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

## 🧠 How I approach a recomp

- **Generators, not hand ports**: decoders and emitters turn the ROM into C++; coverage grows through the generator
- **Hardware semantics by hand**: CPU, DMA, DSP and timing modelled from the chip, checked against reference runs
- **Differential verification**: generated paths compared with the original, digests pinned for every output
- **Legal by design**: only tools are published; the game is generated on the user's machine from their own ROM

## 📊 GitHub stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=macielrecomp&show_icons=true&theme=dark&hide_border=true" />
<img height="165" src="https://streak-stats.demolab.com/?user=macielrecomp&theme=dark&hide_border=true" />

</div>

## 🤝 Support and contact

[![Ko-fi](https://img.shields.io/badge/Ko--fi-FF5E5B?style=for-the-badge&logo=kofi&logoColor=white)](https://ko-fi.com/macielrecomp)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/macielrecomp)

Questions and bug reports: open an issue in the project. Security or rights notices: use the private report in the project's **Security** tab.

<div align="center">

<sub>Independent projects. Game names and marks belong to their owners; no game files are distributed.</sub>

</div>
