# Hi there, I'm andogensi

I specialize in **System Programming**, **High-Performance Computing**, and **Game/Graphics Engineering**.
My passion lies in understanding software internals at the binary level and building high-performance tools from scratch.
（ソフトウェアの深層理解と、低レイヤー技術を用いた高パフォーマンスなアプリケーション開発を専門としています）

大学1年・情報学部所属。
**C++ / DirectX / CUDA** を用いたコアシステムの開発を中心に、バイナリ解析技術からGUI/Webアプリケーションまで、"仕組み"を理解して"動くもの"を作り上げる実践的な開発を行っています。

<p align="left">
  <a href="https://github.com/andogensi">
    <img height="20" src="https://komarev.com/ghpvc/?username=Keichan15" />
  </a>
</p>

---

### Tech Stack
**Core & Low-Level**
<br>
<img src="https://skillicons.dev/icons?theme=dark&perline=8&i=cpp,c,cs,kotlin,rust" />
**Engineering & Analysis**
<br>
`DirectX 11` `CUDA` `Win32 API` `x86/x64 Assembly` `IDA` `Ghidra`

**Application & Web**
<br>
<img src="https://skillicons.dev/icons?theme=dark&perline=8&i=python,pytorch,js,ts,flask,qt,flutter" />

---

### Project Highlights

####  Graphics & Game Tool Engineering (C++ / DirectX 11)
**Runtime Overlay & Process Extension Framework**
* **Overview:** Designed a lightweight internal rendering engine and modding framework for DirectX 11 applications.
* **DirectX 11アプリケーション向けの、軽量な内部オーバーレイおよびランタイム拡張エンジンの開発。**
* **Key Technologies:**
    * **Graphics Pipeline:** Custom rendering pipeline hooking via **Kiero**, implementing UI with **ImGui/ImFX**.
    * **Architecture:** Implemented **EnTT (ECS)** for high-performance component management, optimizing memory layout.
    * **Low-Level Control:** Robust API hooking with **MinHook** and signature scanning with **libhat** for version-independent compatibility.
    * **Modern C++:** Built with **C++17/20**, focusing on compile-time optimization and type safety.

####  High-Performance Computing (CUDA / C++)
**V10Inference - Scratch-built AI Inference Engine** (Public)
* **Overview:** Developed a lightweight neural network inference engine from scratch, executing ONNX models on NVIDIA GPUs without relying on high-level frameworks like TensorRT.
* **ONNXモデルを解析し、自作のCUDAカーネルを用いて推論を行う軽量エンジンの開発。**
* **Key Technologies & Implementation:**
    * **Custom CUDA Kernels:** Implemented **Convolution (Conv2D)**, **MaxPooling**, and **Softmax** kernels manually to optimize parallel execution on GPU.
    * **Memory Optimization:** Managed Host-Device memory transfers (`cudaMalloc`, `cudaMemcpy`) to minimize latency.
    * **No Black Box:** Built a custom parser to extract tensor data directly from **ONNX Protocol Buffers**, strictly understanding the inference logic.

####  System Research & Security
**Binary Analysis & Protection Research** (C++ / C#)
* **Process Instrumentation:** Developed a UWP-compatible launcher with memory management and hardware monitoring (using LibreHardwareMonitor).
* **Security Mechanisms:** Research on software protection techniques, including custom obfuscation algorithms and static analysis mitigation.
* **Reverse Engineering:** Reconstructing function signatures in stripped binaries to understand internal logic.
* プロセス解析ツール開発および、ソフトウェア保護技術（難読化・解析耐性）の研究・実装。

#### 🛠️ Developer Experience (DX) & Tools
**CppLiveTuner** (C++17 / Header-only Library / Public)
* **Overview:** A cross-platform, header-only library enabling real-time parameter tuning in C++ applications without recompilation.
* **再ビルド待ち時間をゼロにする、C++開発者向けのライブチューニングライブラリ（STBスタイル）。**
* **Key Technologies:**
    * **Native OS Integration:** Utilized **ReadDirectoryChangesW** (Win) / **inotify** (Linux) for zero-latency file monitoring.
    * **Thread Safety:** Designed a synchronization mechanism for safe graphics API updates.

####  Product & Utility Development
**StemStudio** (Python, C++)
* **Overview:** AI-based music separation tool combining **PyTorch** with a **C++ backend** for performance-critical sections.
* **Impact:** Developed a hybrid architecture to overcome Python's GIL limitations for real-time processing.
* 音源分離AIを用いたデスクトップアプリ。ボトルネックとなる処理をC++で記述し高速化を実現。

**Attendance Reminder** (Chrome Extension / JavaScript)
* **Problem Solving:** Automated attendance tracking helper for students. Published on Chrome Web Store.
* **Impact:** Solved a real-world problem for university students, improving daily productivity.
* 学生の課題（出席登録漏れ）を解決するChrome拡張機能。ユーザー視点での課題解決を実践。


### GitHub Stats
<p align="center">
  <img height="160" src="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=andogensi&theme=gruvbox" />
  <img height="160" src="http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=andogensi&theme=gruvbox" />
</p>
<p align="center">
  <img height="160" src="http://github-profile-summary-cards.vercel.app/api/cards/stats?username=andogensi&theme=gruvbox" />
  <img height="160" src="http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=andogensi&theme=gruvbox&utcOffset=9" />
</p>
