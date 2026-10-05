<!-- ═══════════════ 顶部横幅 ═══════════════ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b5fa5,100:41CD52&height=180&section=header&text=Kunpeng%20Xie&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=C%2B%2B%20%7C%20Systems%20%7C%20Distributed%20Training%20%7C%20Qt%20%26%20Audio-Video&descAlignY=58&descSize=16" width="100%" alt="header"/>

<!-- ═══════════════ 身份徽章 ═══════════════ -->
<a href="https://www.nwpu.edu.cn/"><img src="https://img.shields.io/badge/Northwestern%20Polytechnical%20University-985%20%7C%20Double%20First--Class-0b5fa5?style=flat-square&logo=academia&logoColor=white" alt="NPU"/></a>
<img src="https://komarev.com/ghpvc/?username=u1s1xv&style=flat-square&color=0b5fa5&label=Profile%20views" alt="views"/>

<br/><br/>

<!-- ═══════════════ 技术栈图标 ═══════════════ -->
<img src="https://skillicons.dev/icons?i=cpp,c,python,qt,linux,cmake,git,pytorch,cuda,mysql,sqlite,js,html,css&perline=7" alt="tech stack"/>

</div>

---

<!-- ═══════════════ 个人简介 ═══════════════ -->

### 👋 About Me

- 🎓 **西北工业大学**（985 / 双一流）计算机学院 · 数据科学与大数据技术
- 💻 主要写 **C++**：Linux 系统编程、网络编程、多线程与并发
- 🔬 毕业设计做 **分布式训练** 的检查点优化（DeepSpeed + CUDA 多卡）
- 🖥️ 在学 **Qt 客户端与音视频开发**（FFmpeg / RTSP）
- 📌 正在找 **C++ 后端 / Qt 客户端 / 音视频** 方向的工作，随时可入职

<sub>💡 更喜欢简洁的话，也可以用这一行版：</sub>

<sub><code>C++ / Linux systems · Distributed training · Qt & audio-video | NPU CS · Open to work</code></sub>

---

<!-- ═══════════════ 重点项目 ═══════════════ -->

## 🔬 Featured Project

<div align="center">

### LowDiff — Efficient Frequent Checkpointing for Distributed Training

<a href="https://github.com/u1s1xv/LowDiff-for-Graduation-project">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=u1s1xv&repo=LowDiff-for-Graduation-project&theme=default&hide_border=true" alt="LowDiff"/>
</a>

</div>

A frequent-checkpointing framework that **reuses compressed gradients as differential checkpoints** to cut checkpoint cost, with batched gradient write optimization and dynamic tuning of checkpoint frequency and batch size.

**My contribution** — extended it with fault-tolerance & observability modules:

| Module | What it does |
|---|---|
| **Fault / SDC injection** | Injects pipeline faults and silent data corruption to validate recovery paths |
| **Pipeline recovery** | Rebuilds pipeline stages after mid-training failure and resumes |
| **Smart checkpoint manager** | Tiered full/differential retention with fallback interval & history rebuild on restart |
| **Optimizer anomaly detection** | Detects abnormal optimizer states during training |

<blockquote>
🎯 <b>Result:</b> checkpointing frequency up to <b>once per iteration</b> with <b>&lt; 3.1% runtime overhead</b><br/>
📊 Evaluated on CIFAR-10/100 · ImageNet · WikiText-103 · SQuAD · baselines: CheckFreq / Gemini / DC
</blockquote>

<p>
<img src="https://img.shields.io/badge/PyTorch-2.6-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/DeepSpeed-0.16-0078D4?style=flat-square"/>
<img src="https://img.shields.io/badge/CUDA-12.4-76B900?style=flat-square&logo=nvidia&logoColor=white"/>
<img src="https://img.shields.io/badge/NCCL-multi--GPU-76B900?style=flat-square"/>
<img src="https://img.shields.io/badge/OpenMPI-4.0.5-CB2E44?style=flat-square"/>
</p>

---

<!-- ═══════════════ 其他项目 ═══════════════ -->

## 🛠 Selected Projects

<table>
<tr>
<td width="50%" valign="top">

### 🎮 星弈五子棋 · GomokuServer
<a href="https://github.com/u1s1xv/GomokuServer">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=u1s1xv&repo=GomokuServer&theme=default&hide_border=true" alt="GomokuServer"/>
</a>

A C++ **HTTP service framework** with an online Gomoku app built on it. Focus is the **application layer** — HTTP/1.1 parsing, regex dynamic routing, session management, pluggable middleware chain (CORS), OpenSSL HTTPS.

</td>
<td width="50%" valign="top">

### ☁️ 异步日志系统 + 云存储
<a href="https://github.com/u1s1xv/AsynLogSystem-CloudStorage">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=u1s1xv&repo=AsynLogSystem-CloudStorage&theme=default&hide_border=true" alt="AsynLogSystem"/>
</a>

C++ cloud storage + self-built **asynchronous logging library**. **Double buffering** with condition variables so logging never blocks business threads; rolling files, remote backup, two-tier storage over libevent HTTP.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🌳 KinWeave · 家谱关系图
<a href="https://github.com/u1s1xv/kinweave">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=u1s1xv&repo=kinweave&theme=default&hide_border=true" alt="kinweave"/>
</a>

An **Android app** visualizing family relationships as an interactive graph — draggable nodes, four tree layouts, position locking, gender coloring, multiple independent graphs.

</td>
<td width="50%" valign="top">

### 📊 GitHub Stats
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=u1s1xv&layout=compact&theme=default&hide_border=true&langs_count=6" alt="top langs"/>

<img src="https://github-readme-stats.vercel.app/api?username=u1s1xv&show_icons=true&theme=default&hide_border=true&count_private=true&include_all_commits=true" alt="stats"/>

</td>
</tr>
</table>

---

<!-- ═══════════════ 技能表 ═══════════════ -->

## 🧰 Tech Stack

| Area | Tools |
|---|---|
| **Languages** | C · C++ (11/14/17) · Python · JavaScript · SQL |
| **Systems & Network** | Linux · Socket · epoll · TCP/IP · libevent · muduo · multithreading · CMake · Makefile |
| **Distributed Training** | PyTorch · DeepSpeed · CUDA · NCCL · OpenMPI · pipeline parallelism · gradient compression · checkpointing |
| **Client & Media** | Qt Widgets · QThread · QTcpSocket · SQLite · OpenCV · FFmpeg · RTSP |
| **AI Engineering** | LLM API integration · SSE streaming · RAG basics · ReportLab |

---

<!-- ═══════════════ 联系方式 ═══════════════ -->

## 📫 Contact

<div align="center">

<a href="mailto:2573520746@qq.com"><img src="https://img.shields.io/badge/Email-2573520746%40qq.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="email"/></a>
<a href="https://github.com/u1s1xv"><img src="https://img.shields.io/badge/GitHub-u1s1xv-181717?style=for-the-badge&logo=github&logoColor=white" alt="github"/></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:41CD52,100:0b5fa5&height=100&section=footer" width="100%" alt="footer"/>

</div>
