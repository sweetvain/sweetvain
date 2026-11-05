<div align="center">

# Hi, I'm Ely 👋

### Software engineering student at [42 Le Havre](https://42lehavre.fr)

Python · C · Algorithms · Concurrency · Applied AI (RAG & LLMs)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 👨‍💻 About me

I'm a student at **42**, where learning is project-based and peer-reviewed. I build things from scratch, from a C standard library to multithreaded simulations and local LLM pipelines, and I care about code that is **readable, typed, tested and linted**.

- 🎓 Studying at **42 Le Havre**, France
- 🔭 Currently exploring **Retrieval-Augmented Generation** and **constrained decoding** with small local language models
- 🧱 Solid foundations in **C** (memory, processes, threads) and modern **Python** (type hints, Pydantic, mypy, flake8)
- 🤝 Used to working in pairs and teams, with Git and code reviews
- 📫 Open to **internship and apprenticeship opportunities**

---

## 🚀 Featured projects

| Project | What it is | Stack |
| --- | --- | --- |
| [**RAG Against the Machine**](https://github.com/sweetvain/RAG-against-the-machine) | A Retrieval-Augmented Generation system that answers questions about the vLLM codebase. BM25 retrieval over ~28,000 chunks, a code-aware tokenizer, and grounded answers from a local `Qwen3-0.6B`. **Recall@5 of 84% on docs and 68.7% on code**, indexing in under a minute on CPU. | Python, bm25s, Transformers, PyTorch, Pydantic |
| [**Call Me Maybe**](https://github.com/sweetvain/Call_Me_Maybe) | A fully local **function-calling** engine. It turns natural-language requests into structured, valid function calls using **logit-based constrained decoding**, with out-of-scope request detection. | Python, Qwen3-0.6B, Pydantic, uv |
| [**Codexion**](https://github.com/sweetvain/Codexion) | A multithreaded variant of the Dining Philosophers problem. Per-resource **min-heaps** with **FIFO / EDF** scheduling, a watchdog thread, deadlock prevention and starvation control. | C, pthreads, mutexes, condition variables |
| [**Fly-In**](https://github.com/sweetvain/Fly-In) | A drone logistics simulator: **BFS** pathfinding on a graph with capacity limits, zone types and conflict-free turn-by-turn scheduling. | Python, graphs, mypy, flake8 |
| [**A-Maze-ing**](https://github.com/sweetvain/A-Maze-Ing) | A maze generator and solver (iterative **DFS**) with an interactive terminal UI and hexadecimal wall encoding. Built as a team of two. | Python |

### 🧪 Highlight: RAG Against the Machine

```text
data/raw ──> ingestion ──> BM25 index ──> retrieval ──> context ──> Qwen3-0.6B ──> grounded answer
                                              │
                                              └──> evaluation (recall@k)
```

- Two **chunking strategies** (Python by `def`/`class`/decorators, Markdown by headings), never exceeding the size limit
- Tokenizer that keeps identifiers whole **and** splits snake_case / camelCase
- Robust CLI: no tracebacks, clear errors, tested with `pytest`, checked with `flake8` and `mypy`

---

## 🧱 Core curriculum (C)

| Project | Topic |
| --- | --- |
| [libft](https://github.com/sweetvain/libft) | Re-implementation of the C standard library and linked-list utilities |
| [ft_printf](https://github.com/sweetvain/ft_printf) | Variadic functions and formatted output |
| [get_next_line](https://github.com/sweetvain/get_next_line) | File descriptors, buffers and static variables |
| [push_swap](https://github.com/sweetvain/push_swap) | Sorting algorithms and complexity optimization |
| [NetPractice](https://github.com/sweetvain/NetPractice) | TCP/IP, subnetting and network configuration |

## 🐍 Python track

Eleven progressive modules, from [Python_Module_00](https://github.com/sweetvain/Python_Module_00) to [Python_module_10](https://github.com/sweetvain/Python_module_10), building up a solid base in modern Python.

---

## 🛠️ Tech & tools

| | |
| --- | --- |
| **Languages** | Python, C, JavaScript, HTML/CSS |
| **AI / Data** | RAG, BM25, PyTorch, Hugging Face Transformers, constrained decoding, Pydantic |
| **Systems** | Linux, POSIX threads, Makefile |
| **Quality** | pytest, mypy, flake8, type hints, 42 Norm |
| **Workflow** | Git, GitHub, uv, pair programming, peer evaluation |

---

## 📊 GitHub stats

<div align="center">

[![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=sweetvain&layout=compact&hide_border=true)](https://github.com/sweetvain)

</div>

---

<div align="center">

⭐ Feel free to explore my repositories and reach out!

</div>
