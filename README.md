# Hi, I'm Gaurav Purohit 👋

**CSE undergrad at NIT Hamirpur (2024–2028)** · Systems programmer + full-stack developer · Competitive programmer

I like building things close to the metal (network protocols, RTOS kernels) as much as shipping full-stack products. Currently looking for **Software Engineering internships** and open-source mentorship opportunities.

📫 **Reach me:** [gauravpurohit985@gmail.com](mailto:gauravpurohit985@gmail.com) · [LinkedIn](https://linkedin.com/in/YOUR-HANDLE) · [LeetCode](https://leetcode.com/u/YOUR-HANDLE) · [Codeforces](https://codeforces.com/profile/YOUR-HANDLE)

---

## 🎓 Education

| Institution | Program | Duration | Score |
|---|---|---|---|
| National Institute of Technology, Hamirpur | B.Tech, Computer Science and Engineering | Aug 2024 – Jul 2028 | CGPA 9.24 / 10 |
| Doon Global School | Class XII / Class X | — | 95% / 95% |

---

## 🛠️ Tech Stack

**Languages:** C · C++ · Python · JavaScript
**Frontend:** React.js · Tailwind CSS · Bootstrap · Material UI
**Backend:** Node.js · Express.js
**Database:** MongoDB (Mongoose)
**Tools:** Git · Docker · Postman
**Core CS:** Operating Systems · Computer Networks · Computer Architecture · DBMS · Microprocessors (8085, 8086) · Digital Electronics · DSA · OOP

---

## 🚀 Projects

### 🔌 [Reliable UDP Protocol Stack (RUDP)](https://github.com/YOUR-USERNAME/RUDP)
`C11` `POSIX Sockets`

A reliable transport protocol library built from scratch in C over unreliable UDP.

- 3-way handshake (SYN / SYN-ACK / ACK) and graceful teardown (FIN / ACK)
- 16-byte packed binary header with big-endian byte order and a table-driven CRC32 checksum
- Selective Repeat sliding-window ARQ with out-of-order reassembly, `select()` I/O multiplexing, adaptive exponential backoff and 3-DupACK fast retransmit
- Custom impairment-simulator proxy (15% loss, 20–50 ms jitter, 5% duplicates), with multi-megabyte files transferred bit-exact and verified by SHA-256

### ⚙️ [Micro-RTOS](https://github.com/YOUR-USERNAME/Micro-RTOS)
`C` `Thumb-2 Assembly` `ARM Cortex-M3` `QEMU`

A bare-metal preemptive real-time kernel written from scratch, with no vendor HAL and no standard C runtime.

- Round-robin scheduler using 1000 Hz SysTick time-slicing, with context switching in PendSV across MSP/PSP stacks
- Atomic synchronization primitives built on `LDREX`/`STREX` with `DMB` barriers, plus cooperative yielding
- Custom BSP: linker scripts, vector table setup, memory-mapped UART driver
- 100% static TCB/stack allocation for deterministic execution and zero heap fragmentation

### 📈 [Vestra: Stock Trading Platform](https://github.com/YOUR-USERNAME/Vestra) · [Live Demo](https://YOUR-VESTRA-LINK)
`MongoDB` `Express` `React` `Node.js` `Chart.js`

A full-stack MERN app for tracking and trading holdings, positions and orders with live market data.

- Two independent front-ends: a marketing site and an interactive trading dashboard
- Live prices via the Finnhub API
- JWT + bcrypt authentication, data persisted in MongoDB, and portfolio trends visualized with Chart.js

### 🧠 [Reviora: Spaced-Repetition Revision App](https://github.com/YOUR-USERNAME/Reviora) · [Live Demo](https://YOUR-REVIORA-LINK)
`MongoDB` `Express` `React` `Node.js`

A full-stack MERN app that helps students retain what they learn through scheduled revisions.

- Custom revision-scheduling engine with user-configurable revision gaps
- JWT + bcrypt auth with protected routes for user-specific notes
- Reusable React custom hooks and a Context API state layer, with a REST API on Node/Express

---

## 🏆 Achievements

- 🥈 **First Runner-Up, HackSecure** (national-level hackathon): built an app that detects violations of sensitive mobile sensor data access (₹10,000)
- 🥈 **First Runner-Up, CodeArena** (CodeHurdles on Codeforces) (₹7,000)
- 🥉 **Second Runner-Up, LogicFrost** (E-Cell, NIT Hamirpur): solved all problems with 100% test cases passing (₹2,000)
- 📊 **Pupil** on Codeforces
- ✅ **500+ problems** solved across LeetCode, GeeksforGeeks and Codeforces

---

## 🤝 Leadership

**Secretary, CSEC Society, NIT Hamirpur**

---

## 🎯 Currently

- Preparing for **LFX Mentorship (Spring 2027)** and making open-source contributions
- Applying for **SWE internships**
- Always happy to talk about systems programming, networking, or competitive programming

---

⭐ If you like any of my projects, feel free to star the repo!
