<!--
  ██████╗  ██████╗ ██╗  ██╗███████╗███████╗
  ██╔══██╗██╔═══██╗╚██╗██╔╝██╔════╝██╔════╝
  ██████╔╝██║   ██║ ╚███╔╝ █████╗  █████╗
  ██╔══██╗██║   ██║ ██╔██╗ ██╔══╝  ██╔══╝
  ██║  ██║╚██████╔╝██╔╝ ██╗███████╗███████╗
  ╚═╝  ╚═╝ ╚═════╝ ╚═╝  ╚═╝╚══════╝╚══════╝

  you opened the source. good instinct.
  now go break something — legally, and in a VM.
-->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00E5FF,50:7C4DFF,100:0B0620&height=190&section=header&text=R0x7e&fontSize=68&fontColor=FFFFFF&fontAlignY=36&desc=GAME%20SECURITY%20%C2%B7%20FAIR%20PLAY%20%26%20DEFENSE&descAlignY=60&descSize=15&animation=twinkling" alt="R0x7e" />

<a href="https://github.com/R0x7e">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2800&pause=900&color=00E5FF&center=true&vCenter=true&width=800&lines=game+security+engineer+%28level+1%29;keeping+the+game+fair%2C+one+sample+at+a+time;trojan+analysis+%26+anti-cheat+research;fair+play+%2B+security+defense;class+of+2025+%C2%B7+computer+science;still+learning.+always+will+be." alt="typing" />
</a>

<br/>

<img src="https://img.shields.io/badge/CLASS-Game_Security_Engineer-00E5FF?style=for-the-badge&labelColor=0D1117" alt="class" />
<img src="https://img.shields.io/badge/LEVEL-01_%C2%B7_Rookie-7C4DFF?style=for-the-badge&labelColor=0D1117" alt="level" />
<img src="https://img.shields.io/badge/DIRECTION-Fair_Play_%26_Defense-FF4D6D?style=for-the-badge&labelColor=0D1117" alt="direction" />

</div>

<br/>

```text
┌───────────────────────────────────────────────┐
│                ◇ PLAYER CARD ◇                │
├───────────────────────────────────────────────┤
│ IGN       R0x7e                               │
│ CLASS     Game Security Engineer              │
│ LEVEL     01  -  rookie, still grinding       │
│ ORIGIN    B.Eng. Computer Science, Jun 2025   │
│ FOCUS     Trojan analysis  /  Anti-Cheat      │
│ DIRECTION Fair play  &  security defense      │
│ STATUS    reading binaries instead of playing │
└───────────────────────────────────────────────┘
```

---

## `$ whoami`

> Game security engineer — **level 1**, still grinding.

**Computer Science**, class of **June 2025**. No grand career story yet: I'm at the stage
where I've finally figured out what I want to spend my time on — **keeping games fair**,
and **defending the players who just want a clean match**.

The direction I care about is **fair play and security defense**, not offense for its own sake.
So these days I spend more time reading binaries than playing them: taking trojans apart,
watching how cheats talk to their servers, and poking at the assumptions game clients make
that they really shouldn't.

Not an expert. Just stubborn, curious, and taking notes in public.
Weird sample, nasty cheat, or a writeup I should read — I'm listening.

---

## `$ cat /quests/active.log`

| 🦠 **Trojan & Malware Analysis** | 🛡️ **Anti-Cheat / Cheat Research** | 🎯 **Fair Play & Defense** |
| :--- | :--- | :--- |
| Static triage first, always. PE headers, sections, imports, entropy, strings — then unpacking and rebuilding what the sample actually *does*.<br/><br/>**Rule #1: never run a sample outside an isolated VM.** Ever. | How cheats actually get in: memory reads/writes, DLL injection, hooking, driver-level games — and what all of it looks like from the detection side.<br/><br/>Still on the reading-heavy end of this curve. | The goal behind the technique: a match where **skill is the only variable**. Client-side authority, unsigned data, plaintext protocols — the boring-but-fatal stuff a motivated player will eventually notice. |

---

## `$ ls ~/arsenal`

<p align="center">
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/x86--64_ASM-6E4AFF?style=for-the-badge" alt="Assembly" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/IDA_Pro-0D1117?style=for-the-badge&logoColor=00E5FF" alt="IDA Pro" />
  <img src="https://img.shields.io/badge/Ghidra-0D1117?style=for-the-badge&logoColor=00E5FF" alt="Ghidra" />
  <img src="https://img.shields.io/badge/x64dbg-0D1117?style=for-the-badge&logoColor=00E5FF" alt="x64dbg" />
  <img src="https://img.shields.io/badge/WinDbg-0D1117?style=for-the-badge&logoColor=00E5FF" alt="WinDbg" />
  <img src="https://img.shields.io/badge/Frida-0D1117?style=for-the-badge&logoColor=00E5FF" alt="Frida" />
  <img src="https://img.shields.io/badge/PE--bear-0D1117?style=for-the-badge&logoColor=00E5FF" alt="PE-bear" />
  <img src="https://img.shields.io/badge/Wireshark-0D1117?style=for-the-badge&logoColor=00E5FF" alt="Wireshark" />
</p>

---

## `$ ls ~/projects --sort=chaos`

| Project | What it is |
| :--- | :--- |
| **[LearnMaliciouCode](https://github.com/R0x7e/LearnMaliciouCode)** · `C++` | My malware lab notebook — hand-written samples and notes covering the classic malicious code patterns, one technique at a time. |
| **[SimplePacker](https://github.com/R0x7e/SimplePacker)** · `C++` | A minimal PE packer. Built purely to understand what packers do to a binary — from the packer's side of the table. |
| **[SearchCodeCaving](https://github.com/R0x7e/SearchCodeCaving)** · `C++` | Scanner for code caves in PE files. Started as an excuse to learn PE layout, accidentally became a small tool. |
| **[Argus](https://github.com/R0x7e/Argus)** · `Python` | AI-driven multi-agent system for SRC vulnerability hunting. My most-starred repo, and the reason I read so many stack traces. |
| **[JavaCodeAudit](https://github.com/R0x7e/JavaCodeAudit)** · `Java` | Code audit notes and practice targets — where I learned that reading code is a skill of its own. |

---

## `$ git log --stat`

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=R0x7e&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&rank_icon=github&bg_color=0D1117&title_color=00E5FF&icon_color=7C4DFF&text_color=C9D1D9" alt="stats" />
  <img height="165" src="https://streak-stats.demolab.com?user=R0x7e&hide_border=true&background=0D1117&stroke=1F2937&ring=00E5FF&fire=7C4DFF&currStreakLabel=00E5FF&currStreakNum=FFFFFF&sideNums=C9D1D9&sideLabels=8B949E&dates=8B949E" alt="streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=R0x7e&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=00E5FF&text_color=C9D1D9" alt="top langs" />
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=R0x7e&bg_color=0D1117&color=00E5FF&line=7C4DFF&point=FFFFFF&area=true&hide_border=true" alt="activity" />
</p>

---

<div align="center">

<i>"Know the cheat before the cheat knows the game."</i>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=R0x7e&color=00E5FF&style=for-the-badge&label=VISITORS" alt="visitors" />

<br/><br/>

<sub>This profile is a living document. Expect it to change as I learn.</sub>

</div>
