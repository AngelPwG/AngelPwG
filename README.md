<div align="center">

```
╔═══════════════════════════════════════════════════════════╗
║  SYSTEMS ENGINEER  ·  BACKEND ARCHITECT  ·  RUST / JAVA  ║
╚═══════════════════════════════════════════════════════════╝
```

# Jose Angel Garcia Plascencia

**Building things from the ground up — bytes, pages, and trees.**

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&pause=1000&color=00FF9C&center=true&vCenter=true&width=500&lines=Database+engine+from+scratch;B%2B+Tree+%7C+Buffer+Pool+%7C+Disk+Manager;Rust+%7C+Java+%7C+Systems+%26+Backend)](https://git.io/typing-svg)

![](https://komarev.com/ghpvc/?username=AngelPwG&color=00ff9c&style=flat-square&label=PROFILE+VIEWS)

</div>

---

## ⚙️ What I'm Building

### 📝 [text-editor](https://github.com/AngelPwG/text-editor) &nbsp; <img src="https://skillicons.dev/icons?i=rust" width="20"/>
> *Built from scratch in Rust - with few external libraries for terminal control*

A terminal text editor built from first principles in Rust:

- **Gap Buffer** — O(1) local insertions and deletions, dynamic gap expansion
- **Raw Terminal** — termios raw mode, ANSI escape codes, manual cursor control
- **Mouse Support** — click-to-position via VT100 mouse protocol
- **Vim-like Modes** — Normal, Insert, Command (`:w`, `:q`, `:wq`)
```
keystroke → read_key() → process_mode() → GapBuffer → render()
                                               ↑
                                    [ gap_start | gap | gap_end ]
```

### 💾 [AngelDB](https://github.com/AngelPwG/AngelDB) &nbsp; <img src="https://skillicons.dev/icons?i=java" width="20"/>
> *No external libraries · Built from scratch*

A fully hand-rolled database engine with:

- **B+ Tree** — persisted over binary file, custom byte-level serialization
- **Buffer Pool** — FIFO/Write-Through eviction, 4KB page management
- **Disk Manager** — built on `RandomAccessFile`, raw I/O at the page level
- **REST API** — Spring Boot layer with Docker + Bind Mounts for deployment

```
CLI → Spring Boot → Buffer Pool → Disk Manager → .db binary file
                                       ↑
                              [ B+ Tree Index ]
```

### 🦀 [rust-data-structures](https://github.com/AngelPwG/rust-data-structures) &nbsp; <img src="https://skillicons.dev/icons?i=rust" width="20"/>
> *A personal library to practice Rust before diving deeper into systems projects*

Low-level data structure implementations — every split, borrow, and merge written by hand.

### 🎲 [RPG-Manager](https://github.com/AngelPwG/RPG-Manager) &nbsp; <img src="https://skillicons.dev/icons?i=java" width="20"/>

### 🔩 [c-data-structures](https://github.com/AngelPwG/c-data-structures) &nbsp; <img src="https://skillicons.dev/icons?i=c" width="20"/>

---

## 🛠️ Stack

![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)
![C](https://img.shields.io/badge/C-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-%236DB33F.svg?style=for-the-badge&logo=spring-boot&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-%23FCC624.svg?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com?user=AngelPwG&theme=dark&hide_border=true&ring=00FF9C&fire=00FF9C&currStreakLabel=00FF9C&background=0d1117&dates=ffffff)

</div>

---

## 🎯 Goals

- 🎓 Software Engineering · Class of 2027
- 🏢 Targeting backend/systems roles
- 🔩 Obsessed with what happens *below* the abstraction layer

