<!-- Zero-Downtime Header + Animated Typing SVG -->
<div align="center">
  <h1>👋 Hey there, I'm Aditya Kumar</h1>
  <p>
    <b>Incoming SDE @ Eternal (June 2027)</b> • 
    <b>B.Tech CSE @ IIT Gandhinagar '27</b> • 
    <b>Ex-Financial Quant Intern @ Futures First</b>
  </p>

  <a href="https://github.com/Aditya-Kumar-IITGN">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=3000&pause=1000&color=7AA2F7&center=true&vCenter=true&width=780&height=45&lines=Incoming+SDE+%40+Eternal+(Joining+June+2027);B.Tech+Computer+Science+%26+Engineering+%40+IIT+Gandhinagar+(CPI%3A+8.01);Ex-Financial+Quant+Intern+%40+Futures+First+(May+'26+%E2%80%93+Jul+'26);Codeforces+Expert+(1723)+%7C+CodeChef+4-Star+(1849)+%7C+1000%2B+Problems;Kernel-Bypass+Networking+(AF_XDP)+%7C+ANN+Vector+Search+%7C+Sharded+Systems" width="780" height="45" alt="Typing SVG" />
  </a>
</div>

<br/>

<!-- Social, Coding & Portfolio Badges -->
<div align="center">
  <a href="https://aditya-kumar-iitgn.github.io/personal-portfolio/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-Website-00C7B7?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/aditya-iitgn" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-aditya--iitgn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:aditya.kumar@iitgn.ac.in">
    <img src="https://img.shields.io/badge/Email-aditya.kumar%40iitgn.ac.in-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://codeforces.com/profile/JaspurKHURD" target="_blank">
    <img src="https://img.shields.io/badge/Codeforces-Expert_(1723)-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces" />
  </a>
  <a href="https://www.codechef.com/users/decode186" target="_blank">
    <img src="https://img.shields.io/badge/CodeChef-4★_(1849)-5B4638?style=for-the-badge&logo=codechef&logoColor=white" alt="CodeChef" />
  </a>
  <a href="https://leetcode.com/u/adityakumarbhanu15062003/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" />
  </a>
</div>

---

### ⚡ About Me

- 🎓 **Education:** Final-Year Undergraduate pursuing **B.Tech. in Computer Science & Engineering** at **IIT Gandhinagar** (2022–2027, **CPI: 8.01**).
- 🚀 **Upcoming Role:** Incoming **Software Development Engineer (SDE) @ Eternal** (Joining **June 2027**).
- 📈 **Quant Experience:** Former **Financial Quant Intern @ Futures First** (Gurgaon, May '26 – Jul '26), building custom backtesting engines and statistical alpha pipelines.
- 💻 **Competitive Programming:** **Expert (1723)** on [Codeforces (`JaspurKHURD`)](https://codeforces.com/profile/JaspurKHURD) & **4-Star (1849)** on [CodeChef (`decode186`)](https://www.codechef.com/users/decode186) with **1000+ problems solved** across platforms.
- 🏀 **Beyond Code:** **Captain of the IIT Gandhinagar Basketball Team** (4th place at Inter-IIT Sports Meet; 2-time District Khelmahakumbh Champion).

---

### 💼 Experience

#### 📈 **Financial Quant Intern** — **Futures First** *(Gurgaon, India)*
`May 18, 2026 – July 10, 2026`
- **Custom Backtesting Engine:** Engineered a zero-dependency backtesting framework from scratch supporting **6+ strategy variants** via decoupled signal, execution, and P&L modules with configurable parameters and per-turn transaction cost modeling.
- **Statistical & Numerical Modeling:** Implemented **6+ quantitative algorithms** (rolling z-scores, Ornstein-Uhlenbeck half-life, PCA, regression, Granger-causality) over multi-million-row datasets, optimized via vectorized `NumPy` and `pandas` operations.
- **Alpha & Regime Validation:** Automated event-analysis and validation workflows across **19 policy-event windows** and parameter/regime grids, lifting strategy **Sharpe Ratio from 0.24 to 0.77**.

#### 👨‍🏫 **Teaching Assistant — ES 113: Data-Centric Computing** — **IIT Gandhinagar**
`Jan 2025 – Apr 2025` | *Advisor: Prof. Balagopal Komarath*
- Mentored **400+ students** through live coding sessions and debugging clinics, collaborating with faculty to design and refine programming assignments.

#### 🚀 **Incoming Software Development Engineer (SDE)** — **Eternal**
`Starting June 2027`

---

### 🚀 Featured Engineering & Research Projects

| Project & Repository Link | Tech Stack | Architecture & Quantitative Impact |
| :--- | :--- | :--- |
| ⚡ **[DNS Resolver using AF_XDP Kernel Bypass](https://github.com/Aditya-Kumar-IITGN/AF_XDP_DNS)**<br/>*(CS331 Course Project, IITGN • Aug '26 – Sep '26)*<br/><br/>[![Repo](https://img.shields.io/badge/GitHub-AF__XDP__DNS-181717?style=flat-square&logo=github)](https://github.com/Aditya-Kumar-IITGN/AF_XDP_DNS) | `C` `eBPF / XDP` `AF_XDP` `Linux` `Multithreading` | • Bypassed the Linux kernel network stack via an **eBPF/XDP** program intercepting DNS (`UDP/53`) at the NIC driver, delivering packets zero-copy into a **16 MB UMEM** via `BPF_MAP_TYPE_XSKMAP`.<br/>• Built an iterative DNS resolver in C querying all **13 root servers** (A, CNAME, NS-referral, glue records) backed by a thread-safe LRU cache and **10-thread worker pool**.<br/>• Achieved **35–43% lower latency** (`848 ms` vs. `1,476 ms`) and **2–3x faster cache-hit responses** over traditional socket servers across **10M real-world queries** (`dnsperf`). |
| 🔍 **[Comparative Study of HNSW Tuning Strategies for ANN Search](https://github.com/Aditya-Kumar-IITGN/HNSW-Hyperparameter-Optimization-Framework)**<br/>*(Prof. Anirban Dasgupta, IITGN • Jan '26 – Apr '26)*<br/><br/>[![Repo](https://img.shields.io/badge/GitHub-HNSW--Optimization-181717?style=flat-square&logo=github)](https://github.com/Aditya-Kumar-IITGN/HNSW-Hyperparameter-Optimization-Framework) | `Python` `hnswlib` `Optuna` `FAISS` `SIFT-1M` | • Engineered a benchmarking framework evaluating **5 hyperparameter tuning strategies** for HNSW approximate nearest-neighbor (ANN) search, achieving **1.0000 Recall@10** on $20\text{K} \times 128\text{-D}$ vectors.<br/>• Reduced index build time by **~4.7x** (Bayesian TPE) and trimmed memory footprint by **~26%** (Multi-Objective Pareto) at **<0.01% recall loss** on **SIFT-1M** (~50K vectors, 1,500 queries). |
| 🛡️ **[GateGuard — Sharded Campus Gate Management Platform](https://github.com/Aditya-Kumar-IITGN/GateGuard-IITGN)**<br/>*(Prof. Yogesh Meena, IITGN • Jan '26 – Apr '26)*<br/><br/>[![Repo](https://img.shields.io/badge/GitHub-GateGuard--IITGN-181717?style=flat-square&logo=github)](https://github.com/Aditya-Kumar-IITGN/GateGuard-IITGN) | `React 18` `Vite` `Node/Express` `PostgreSQL` `Docker` `B+ Tree` | • Built a full-stack access-control platform with **JWT access/refresh rotation**, token-blacklisted server logout, and **RBAC** across Guard, Admin, and SuperAdmin tiers.<br/>• Implemented **hash sharding (`memberid % 3`)** across **3 Dockerized PostgreSQL nodes** with an $O(1)$ shard router, backed by a custom **order-4 $B^+$ tree storage engine** with **WAL-based crash recovery**. |

---

### 🛠️ Technical Skills

<div align="center">

**Programming Languages**
<br/>
<p align="center">
  <img src="https://skillicons.dev/icons?i=py,cpp,c,js,postgres,matlab&theme=dark" alt="Languages" />
  <br/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MATLAB-0076A8?style=flat-square" />
  <img src="https://img.shields.io/badge/Verilog_%2F_SystemVerilog-Hardware_Description-4EAA25?style=flat-square" />
</p>

**Systems, Frameworks, Data Science & Tools**
<br/>
<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,linux,git,github,pytorch,react,vite,express,nodejs&theme=dark" alt="Frameworks & Tools" />
  <br/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/FAISS_%26_hnswlib-Vector_Search-00A67E?style=flat-square" />
  <img src="https://img.shields.io/badge/Optuna-Bayesian_Optimization-1A73E8?style=flat-square" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/eBPF_%2F_AF__XDP-Kernel_Bypass-FCC624?style=flat-square&logo=linux&logoColor=black" />
</p>

**Core Coursework:** `Data Structures & Algorithms` • `Machine Learning` • `Financial Modeling & Engineering` • `Probability & Statistics` • `Object-Oriented Programming` • `Computer Networks`

</div>

---

### 🏆 Achievements & Positions of Responsibility

- ⚔️ **Competitive Programming:** Achieved **Expert rating (1723)** on [Codeforces](https://codeforces.com/profile/JaspurKHURD) and **4-Star (1849)** on [CodeChef](https://www.codechef.com/users/decode186) with **1,000+ algorithmic problems solved** across platforms.
- 🏅 **Best Undergraduate Research Poster:** Awarded at **IIT Gandhinagar** for quantitative research analyzing campus energy consumption.
- 📜 **Dean's List Awardee:** Recognized at **IIT Gandhinagar** for academic excellence (**CPI 8.5+** in Semester 2, AY 2022–23).
- 🏀 **Captain, IIT Gandhinagar Basketball Team** *(Jun '25 – Present)*: Led the institute squad to a **4th-place finish at the Inter-IIT Sports Meet**; **2-time District-level Khelmahakumbh Champion** and represented Gandhinagar District at the State Championship.
- 🎨 **Design Team Member, BlithChron** *(Oct '22 – Jul '23)*: Coordinated flagship cultural events (*Streetbeat*, *Panache*) and designed visual branding for IIT Gandhinagar's annual cultural festival.

---

### 🎓 Academic Background

| Degree / Examination | Institution | Duration / Year | Score / CPI |
| :--- | :--- | :--- | :--- |
| **B.Tech. in Computer Science & Engineering** | **Indian Institute of Technology (IIT) Gandhinagar** | `2022 – 2027` | **8.01 CPI** |
| **Class XII (PCM)** | **Kendriya Vidyalaya (KV) Kashipur** | `2021` | **95.6%** |
| **Class X** | **Kendriya Vidyalaya (KV) Kashipur** | `2019` | **93.4%** |

---

### 📊 Coding Profiles & GitHub Telemetry

<!-- Row 1: Full-Width Profile Summary & Contribution Area Graph -->
<div align="center">
  <img width="98%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Aditya-Kumar-IITGN&theme=tokyonight" alt="GitHub Profile Details & Activity Graph" />
</div>

<!-- Row 2: Stats, Streak & Language Breakdown -->
<div align="center">
  <img height="175" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Aditya-Kumar-IITGN&theme=tokyonight" alt="Aditya's GitHub Stats" />
  <img height="175" src="https://streak-stats.demolab.com?user=Aditya-Kumar-IITGN&theme=tokyonight&hide_border=true&background=1a1b27" alt="Aditya's GitHub Streak" />
  <img height="175" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Aditya-Kumar-IITGN&theme=tokyonight" alt="Top Languages" />
</div>

<!-- Row 3: Live LeetCode Card -->
<div align="center">
  <a href="https://leetcode.com/u/adityakumarbhanu15062003/">
    <img height="185" src="https://leetcard.jacoblin.cool/adityakumarbhanu15062003?theme=tokyonight&font=Fira%20Code&ext=heatmap" alt="LeetCode Stats" />
  </a>
</div>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=Aditya-Kumar-IITGN&label=Profile%20Views&color=7aa2f7&style=flat-square" alt="Profile Views" />
  <br/>
  <sub>⚡ Aditya Kumar • Computer Science & Engineering @ IIT Gandhinagar</sub>
</div>
