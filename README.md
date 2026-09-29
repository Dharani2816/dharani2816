<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0d1117&height=150&section=header&text=%3E_%20Dharani%20Kumar%20K%20S&fontSize=44&fontColor=00ff41&fontAlignY=40&desc=CSE%20%40%20Madras%20Institute%20of%20Technology%20%20%7C%20%20Full-Stack%20Developer%20%20%7C%20%20Systems%20%26%20Networking%20Enthusiast&descSize=15&descAlignY=72&descAlign=50" width="100%" alt="Dharani Kumar K S - CSE at Madras Institute of Technology - Full-Stack Developer, Systems and Networking Enthusiast" />

<a href="https://www.linkedin.com/in/dharani-kumar-ks/"><img src="https://img.shields.io/badge/LinkedIn-dharani--kumar--ks-00ff41?style=for-the-badge&logo=linkedin&logoColor=00ff41&labelColor=0d1117" alt="LinkedIn: dharani-kumar-ks" /></a>
<a href="https://github.com/Dharani2816?tab=repositories"><img src="https://img.shields.io/badge/Repositories-Dharani2816-ffb000?style=for-the-badge&logo=github&logoColor=ffb000&labelColor=0d1117" alt="GitHub repositories of Dharani2816" /></a>

</div>

### `$ whoami`

I'm a Computer Science Engineering student at **Madras Institute of Technology, Chennai**, building full-stack applications with **React, Node.js and Express** on top of MongoDB, MySQL and Redis. Lately I've been going below the application layer into **SDN, routing and operating systems**, and wiring ML and LLM APIs into the things I build. Most of my projects start with *"can I actually make this work?"*. I keep going until they run end-to-end.

### `$ cat education.txt`

**B.E. Computer Science and Engineering**
Madras Institute of Technology, Chennai · Expected graduation **2028**

### `$ ls ~/skills`

| | |
|---|---|
| **Languages** | C · C++ · Java · Python · JavaScript · HTML · CSS |
| **Frontend** | React · Vite · React Router · Tailwind CSS · Bootstrap · Chart.js |
| **Backend** | Node.js · Express · REST APIs · Socket.IO · JWT · FastAPI |
| **Databases** | MongoDB · MySQL · Redis · Firebase Firestore |
| **Systems & Networking** | SDN · OpenFlow 1.3 · Ryu · Mininet · Open vSwitch · Network routing |
| **AI / ML** | scikit-learn (Decision Tree) · Gemini / OpenAI / Groq APIs |

## `$ ls ~/projects --featured`

### NetShield-AI
**Self-healing SDN network with AI-assisted adaptive routing, an NFV firewall and anomaly detection**

`Python · Ryu · OpenFlow 1.3 · Mininet · scikit-learn · FastAPI · React`

A Ryu OpenFlow controller running over a Mininet topology of 6 switches with 4 candidate paths between hosts. It detects link failures, reroutes traffic automatically, and picks paths using live link metrics. Team project with [Nithishwaran S](https://github.com/NithishwaranSenthilkumar).

**Highlights**
- **Adaptive routing:** a Decision Tree model classifies network state as `NORMAL`, `CONGESTED` or `DEGRADED` from 5 live metrics. The state selects BFS or cost-weighted Dijkstra, whose cost mixes delay, utilization and packet loss. The model is trained on a documented synthetic dataset.
- **Self-healing:** link failures are detected through OpenFlow port-status events. Stale flows are flushed and traffic is rerouted onto an alternate path, verified live with `pingall` staying at 0% loss.
- **Security:** an in-controller NFV firewall installs OpenFlow drop rules. Threshold-based anomaly detection auto-blocks misbehaving sources, and TCP connection tracking follows flow state.
- **Multipath and dashboard:** a 5-tuple hash spreads TCP/UDP flows across healthy paths. A FastAPI REST API and React dashboard show topology, routing decisions and alerts.
- **Under development:** end-to-end performance and recovery-time benchmarks are not yet measured.

[`[GitHub]`](https://github.com/Dharani2816/Self-Healing-SDN-Network---NetShieldAI)

### Chatrr
**Real-time full-stack chat platform**

`React · Node.js · Express · Socket.IO · MongoDB · Redis · JWT · Gemini`

Multi-room chat with JWT authentication, instant messaging over Socket.IO, and an in-room AI assistant.

**Highlights**
- **Live rooms:** create or join rooms by ID, with online presence, typing indicators, timestamps and join/leave notices.
- **Redis:** holds room state, a per-room cache of the last 50 messages, and a rate limiter for messages and bot queries. MongoDB stores users, rooms and message history.
- **`@ChatrrBot`:** answers in-room questions through Google Gemini, using recent chat history as context.
- **Sessions:** bcrypt password hashing, and each account can be logged in from only one tab at a time.

[`[GitHub]`](https://github.com/Dharani2816/Chattr-Chat-App)

### Carbon Footprint Calculator
**Full-stack carbon tracking app with AI-generated reduction plans**

`React · Tailwind CSS · Chart.js · Node.js · Express · MongoDB · JWT`

A multi-step calculator covering home energy, transport and diet, with a personal dashboard for tracking emissions over time.

**Highlights**
- **Dashboard:** Chart.js visualizations, calculation history, and benchmarking against Indian and global averages.
- **What-if simulator:** estimates how reductions in electricity, travel and other habits would change your footprint.
- **AI insights:** tries Groq, then OpenAI, then Gemini, and falls back to rule-based tips if all AI providers fail.
- **Accounts:** JWT-secured login with MongoDB persistence, plus a GitHub Actions workflow that deploys the server to Azure.

[`[GitHub]`](https://github.com/Dharani2816/Carbon-footprint-calculator)

### `$ ls ~/projects --other`

- **[GitHub Dev Explorer](https://github.com/Dharani2816/GitHub-Dev-Explorer):** browses developer profiles, followers and repo counts from the GitHub REST API. `React · React Router · Bootstrap`
- **[CricketStat](https://github.com/Dharani2816/cricketstat):** match stats dashboard and history on a DAO/service layer. `Java · JDBC · MySQL`
- **[Student Ranking Portal](https://github.com/Dharani2816/Java-Based-Student-Ranking-Portal):** marks processing, grading and a sorted rank list. `Java · OOP`
- **[GPA Calculator](https://github.com/Dharani2816/Gpa-Calculator):** single-page GPA calculator. `React · Vite` [`[Live Demo]`](https://gpa-calculator-blond.vercel.app)

### `$ cat exploring.md`

```text
[>] Data Structures & Algorithms in C++
[>] Operating system internals: xv6 on RISC-V
[>] Computer networks, SDN and adaptive routing
[>] ML and LLM integration in real applications
[>] System design: caching, rate limiting, service layering
```

### `$ ./leetcode --stats`

250+ problems solved in C++ and auto-synced with LeetHub to [`Dharani2816/Leetcode`](https://github.com/Dharani2816/Leetcode), covering arrays, two pointers, sliding window, trees, DFS/BFS, union-find, backtracking and dynamic programming.

### `$ git log --stat`

<div align="center">
<img height="150" src="https://github-readme-stats.hackclub.dev/api?username=Dharani2816&show_icons=true&hide_rank=true&bg_color=0d1117&title_color=ffb000&text_color=00ff41&icon_color=00ff41&border_color=00ff41" alt="GitHub stats for Dharani2816" />
<img height="150" src="https://github-readme-stats.hackclub.dev/api/top-langs/?username=Dharani2816&layout=compact&langs_count=6&bg_color=0d1117&title_color=ffb000&text_color=00ff41&border_color=00ff41" alt="Most used languages of Dharani2816" />
</div>

### `$ cat contact.txt`

`linkedin ->` [linkedin.com/in/dharani-kumar-ks](https://www.linkedin.com/in/dharani-kumar-ks/)<br>
`github   ->` [github.com/Dharani2816](https://github.com/Dharani2816)

<div align="center">
<sub><code>$ echo "Thanks for stopping by" &amp;&amp; exit</code></sub>
</div>
