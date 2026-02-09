# Hi there, I'm andogensi

I specialize in **Low-level Programming**, **System Programming**, and **Security Research**.
My passion lies in understanding software internals at the binary level and building high-performance tools.
（ソフトウェアの深層理解と、低レイヤー技術を用いた高パフォーマンスなアプリケーション開発を専門としています）

大学1年・情報学部所属。
普段はセキュリティ保護の観点からPrivateリポジトリを中心に活動していますが、**解析技術（Reverse Engineering）**から**GUI/Webアプリケーション開発**まで、"動くもの"を作り上げる実践的な開発を行っています。

<p align="left">
  <a href="https://github.com/andogensi">
    <img height="20" src="https://komarev.com/ghpvc/?username=Keichan15" />
  </a>
  <a href="https://github.com/andogensi">
    <img height="20" src="https://img.shields.io/github/followers/Keichan15?label=follow&logo=github&style=flat" />
  </a>
</p>

---

### Tech Stack
**Core & Low-Level**
<br>
<img src="https://skillicons.dev/icons?theme=dark&perline=8&i=cpp,c,cs,kotlin,linux,kali" />

**Analysis & Tools**
<br>
`IDA` `Ghidra` `Win32 API` `x86/x64 Assembly` `CUDA` `DirectX`

**Application & Web**
<br>
<img src="https://skillicons.dev/icons?theme=dark&perline=8&i=python,pytorch,js,ts,flask,qt,flutter" />

---

### Project Highlights

####  Core System & Graphics Engineering (C++ / DirectX 11)
**Runtime Overlay & Process Extension Framework**
* **Overview:** Designed a lightweight internal rendering engine for DirectX 11 applications.
* **DirectX 11アプリケーション向けの、軽量な内部オーバーレイおよびランタイム拡張エンジンの開発。**
* **Key Technologies:**
    * **Graphics Pipeline:** Custom rendering pipeline hooking via **Kiero**, implementing UI with **ImGui/ImFX**.
    * **Architecture:** Implemented **EnTT (ECS)** for high-performance component management, optimizing memory layout.
    * **Low-Level Control:** API detouring using **MinHook** and robust signature scanning with **libhat** for version-independent compatibility.
    * **Modern C++:** Built with **C++17/20**, focusing on compile-time optimization and type safety.

#### System & Security Research
**Process Instrumentation Tool** (C#, WPF, .NET)
* Advanced launcher for UWP applications with **DLL Injection** capabilities.
* Features memory management and hardware monitoring using **LibreHardwareMonitor**.
* UWPプロセスへのインジェクション、メモリ最適化・ハードウェア監視機能を統合したランチャー開発。

####  High-Performance Computing (CUDA / C++)
**V10Inference - Scratch-built AI Inference Engine**
* **Overview:** Developed a lightweight neural network inference engine from scratch, executing ONNX models on NVIDIA GPUs without relying on high-level frameworks like TensorRT.
* **ONNXモデルを解析し、自作のCUDAカーネルを用いて推論を行う軽量エンジンの開発。**
* **Key Technologies & Implementation:**
    * **Custom CUDA Kernels:** Implemented **Convolution (Conv2D)**, **MaxPooling**, and **Softmax** kernels from scratch to optimize parallel execution on GPU.
    * **Low-Level Memory Management:** Manually managed Host-Device memory transfers (`cudaMalloc`, `cudaMemcpy`) to minimize latency and optimize bandwidth usage.
    * **ONNX Integration:** Built a custom parser to extract tensor data and network topology directly from **ONNX Protocol Buffers**, enabling interoperability with standard trained models.
    * **Pipeline Architecture:** Designed a layer-by-layer execution pipeline supporting multi-channel convolution and fully connected layers for MNIST-scale tasks

**Binary Protection & Analysis** (C++)
* **Obfuscation Research:** Developed a custom XOR/Substitution cipher library for **intellectual property protection**.
* **Anti-Analysis Techniques:** Research on mitigating static analysis by tools like IDA/Ghidra.
* **Reverse Engineering:** Reconstructing function signatures in stripped binaries and implementing assembly-level hooks.
* 静的解析耐性を持つ軽量難読化ライブラリの開発および、バイナリ保護技術の研究。

#### 🛠️ Developer Experience (DX) & Tools
**CppLiveTuner** (C++17 / Header-only Library)
* **Overview:** A cross-platform, header-only library enabling real-time parameter tuning in C++ applications without recompilation.
* **再ビルド待ち時間をゼロにする、C++開発者向けのライブチューニングライブラリ（STBスタイル）。**
* **Key Technologies & Implementation:**
    * **Native OS Integration:** Implemented event-driven file monitoring using specific OS APIs (**ReadDirectoryChangesW** for Win, **inotify** for Linux, **FSEvents** for macOS) to achieve ~1ms latency with near-zero CPU usage.
    * **Thread Safety for Games:** Designed a synchronization mechanism where callbacks execute on the main thread, ensuring safety for graphics APIs (DirectX/OpenGL) updates.
    * **API Design:** Adopts **STB-style** single-header architecture for easy integration, supporting dependency injection for unit testing.

####  Product & Utility Development
**StemStudio** (Python, C++)
* **Overview:** AI-based music separation tool combining **PyTorch** with a **C++ backend** for performance critical sections.
* **Technology:** Accelerated signal processing using C++ to overcome Python's GIL limitations.
* 音源分離AIを用いたデスクトップアプリ。ボトルネックとなる処理をC++で記述し高速化を実現。

**Attendance Reminder** (Chrome Extension / JavaScript)
* **Problem Solving:** Automated attendance tracking helper for students to prevent missed registrations.
* **Impact:** Published on Chrome Web Store to support student life.
* 学生の課題（出席登録漏れ）を解決するChrome拡張機能。GitHub Publicにて公開中。

**RAG-based Doc Search API** (Python, LangChain)
* Developed a Retrieval-Augmented Generation system using **ChromaDB** and **Gemini/GPT-4**.
* Implemented optimized chunking strategies for handling large PDF datasets.


---

### GitHub Stats
<p align="center">
  <img height="160" src="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=andogensi&theme=gruvbox" />
  <img height="160" src="http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=andogensi&theme=gruvbox" />
</p>
<p align="center">
  <img height="160" src="http://github-profile-summary-cards.vercel.app/api/cards/stats?username=andogensi&theme=gruvbox" />
  <img height="160" src="http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=andogensi&theme=gruvbox&utcOffset=9" />
</p>
