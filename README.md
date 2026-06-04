# 🪐 ATLAS OS — Autonomous Android/Termux AI Operating Station

ATLAS OS is a highly optimized, asynchronous AI orchestration platform designed to run locally inside **Termux on Android devices**. It bridges lightweight local processing (Ollama, SQLite, FFmpeg) with ultra-fast cloud intelligence (Groq, Gemini), giving the user complete control over privacy, multimedia production, and scientific computing without heavy hardware requirements.

---

## 🚀 Key Features

* **Dual-Engine AI Routing**: Instant fallback to local Ollama (`llama3.2:1b`) if network connection drops, seamlessly switching between Groq (LPU speed) and Gemini.
* **4-Channel Live Web Audio Studio**: Direct integration with `pydub` and native `mpv` inside Termux, featuring real-time 3-band EQ, Panorama (L/R) mixing, reverb simulation, and multi-format export.
* **Asynchronous Research Router**: Deep-dive real-time web scraping utilizing Google CSE, BeautifulSoup4, and parallel RSS feed compilation without blocking the main event loop.
* **Scientific Computation Shield**: Built-in mathematical and physical execution layer using NumPy, SciPy, and SymPy for exact analytical solutions.
* **Edge-Safe Vault**: Local database synchronization through `aiosqlite` with rigid shell execution token verification.

---

## 📱 Hardware & Environment

* **OS**: Android (via Termux Environment)
* **Core**: Python 3.13+ / FastAPI / WebSockets
* **Skins/UI**: Responsive UI with multi-language engine (hr/en/de/fr/es) and real-time state synchronization.
* **Media Processor**: Native FFmpeg 8.1 binaries.
