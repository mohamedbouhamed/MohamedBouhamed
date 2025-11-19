<h1 align="center" >Welcome all !</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/mohamedbouhamed">
  <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" >
  </a>
<a href="https://huggingface.co/MohamedBouhamed">
  <img src="https://img.shields.io/badge/HuggingFace-FC9803?style=for-the-badge&logo=huggingface&logoColor=white" />
</a>

  </a>
</p>

<h2 align="center" > My main skills </h2>
<p align="center">
  <img src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/SWIFT-FA7343?style=for-the-badge&logo=swift&logoColor=white" />

</p>

<h2 align="center" >Who am I ? 🧑‍💻 </h2>
<p align="center">
I'm a 23 yo computer science student at Paris-Saclay University 👨‍🎓 With a strong experienc ML, LLMs and Software Engineering</p>

<p align="center">
I am currently a Machine Learning Engineer intern at Ekimetrics, developing end-to-end ML pipelines in Python and transforming a RAG architecture with LangChain into an agentic OpenAI SDK system for iterative self-correction and multi-step operations.
Previously, I worked as a Software Engineer at EDF, building an Angular frontend for real-time and predictive visualization of nuclear plant availability, integrating complex datasets from EDF’s public APIs with a focus on user-centric design.
</p>


<h2 align="center" > What do I like ? 😎 </h2>
<p align="center">
I'm passionate about many things but my favorite things at the moment are LLMs and Software Development. Let's have a look at a couple of projects I participated in !
</p>

<!-- 
Kernel dev
-->

<h2 align="center" > aarch64 (ARMv8) (micro)kernel development 0️⃣1️⃣ </h2>

<p align="center" > 💻 Language : <code>C</code> <code>ARMv8 assembly</code> <code>C++</code> </p> 
<p align="center" > 🛠️ Features : GIC, MMU, Timers, UART, Virtual addressing, Userspace process scheduling, Dynqmic memory allocation  </p> 
<p align="center">
As a big fan of the ARM architecutre, I decided to dive deep into ARM development by undertaking the development of a kernel in C / C++ languages. The kernel runs kernel mode at EL1 and user mode at EL0. It leverages virtual memory mapping and dynamic memory allocation to offer userspace features. Since I'm really interested in microkernel, this could evolve to one of them in the future. WIP.
The project is available there :  <a href="https://github.com/raphfaur/foxOS.git">foxOS</a>

</p>



<h2 align="center" > Rust x86 kernel development 0️⃣1️⃣ </h2>

<p align="center" > 💻 Language : <code>Rust</code> <code>x86 Assembly</code> </p> 
<p align="center" > 🛠️ Features : MBR, ext4 fs, PIC, I/O APIC, BIOS </p> 
<p align="center">
With a friend <a href="https://github.com/sleiderr">@sleiderr</a>, we wanted to learn how do a computer boot. I personnaly began by writing an x86 ASM bootloader and then we decided to try to do it in Rust. We first collaborated to write our own bootloaders and then decided to work together on a common project : we decided to found <a href="https://github.com/frozenpeach-dev">frozenpeach</a> to develop common projects.
</p>
<ul list-style-type="none" align="center">
  <a href = "https://github.com/raphfaur/bootloader" > The first bootloader </a> <br/>
  <a href = "https://github.com/frozenpeach-dev/bootloader" > The common bootloader </a>
</ul>


<!-- VHDL CPU 
-->
<h2 align="center" > VHDL custom RISC CPU implementation 🎛️ </h2> 
<p align="center" > 💻 Language : <code>VHDL</code></p> 
<p align="center" > 🛠️ Features : register file, ALU,  </p> 

<ul list-style-type="none" align="center">
  <a href = "https://github.com/raphfaur/cpu" > VHDL CPU for MAX-10 FPGA  </a>
  <p>
  I designed a RISC inspired CPU in VHDL. The CPU is pipelined and has its own simple assembly language that supports looops, comparisons and more.  
  The project runs on MAX 10 FPGA hardware.
  </p>
</ul>



<!-- Haskell compiler
-->

<h2 align="center" > Imperative language interpreter and LLVM IR compiler ⚙️ </h2> 
<p align="center" > 💻 Language : <code>Haskell</code></p> 
<p align="center" > 🛠️ Features : LLVM IR compiler, interpreter, runtime exceptions</p> 

<ul list-style-type="none" align="center">
  <p>
  I'm super interested in how compilers and interpreter work, so I decided to build my own language and its own interpreter / compiler from scratch. I went with Haskell to build a monadic interpreter and a combinator parser. The compiler compiles to LLVM IR, allowing multi target compilation. The project is available there : <a href = "https://github.com/raphfaur/foxC.git" > foxC </a>
  </p>
</ul>


<!-- Apple silicon GPU accelerated ML Library
-->

<h2 align="center" > Apple silicon GPU accelerated ML Library </h2> 
<p align="center" > 💻 Language : <code>C++</code> <code>Metal</code> <code>Python</code></p> 

<ul list-style-type="none" align="center">
  <p>
    <a href = "https://github.com/raphfaur/metal_ml.git" > GPU accelerated ML framework </a> <br/>
    Passionate about low-level stuff as well as ML, I started developping some ML algorithms in C++ using metal-cpp to leverage Apple silicon GPU acceleration. Using compute shaders, I implemented a GPU accelerated map and a clustering algorithm. The map implmeentation outperforms unordered_map by 1300% on insert time for huge maps.
  </p>
  <p>
    I'm also developing the python bindings for this ML framework, using C python bindings, and especially the buffer protocol.
  </p>
</ul>

<!-- Various algorithms
-->

<h2 align="center" > Multithreaded compression algorithm </h2> 
<p align="center" > 💻 Language : <code>C++</code>
<p align="center" > 🛠️ Features : Huffman compression, Huffman decompression, multi threaded compression </p> 

<ul list-style-type="none" align="center">
  <p>
    <a href = "https://github.com/raphfaur/compressor.git" > Huffman compression algorithm </a> <br/>
    To learn more about multithreading and concurrency in C++, I implemented a multithreaded compression algorithm in C++. Originally designed single threaded, the parallelized implementation led to a x20 speedup in compression time.
  </p>
</ul>



<!-- 
Debugger
-->

<h2 align="center" > Embedded debugger and test framework ✔️ </h2> 
<p align="center" > 💻 Language : <code>Rust</code> <code>x86 Assembly</code> </p> 
<p align="center" > 🛠️ Features : gdb, rust-gdb, qemu, ld linker</p> 

<ul list-style-type="none" align="center">
  <p>
    <a href = "https://github.com/frozenpeach-dev/debugger" > An embedded Rust test framework </a> <br/>
    In order to debug and run test in our embedded Rust bootloader, we needed a custom test framework that could start a Qemu instance and automatically analyse execution flow.
    I also developped procedural macro to easily integrate tests in the main project. Not in production yet.
  </p>
</ul>


<!-- 
Compiler
-->

<h2 align="center" > Compiler theory training course 📚 </h2> 
<p align="center" > 💻 Language : <code>C</code></p> 

<ul list-style-type="none" align="center">
  <p>
    <a href = "https://github.com/raphfaur/compiler" > My compiler theory exercises </a> <br/>
    I'm currently interested in compiler and interpreter theory and I started training with the well-known book "Modern Compiler Implementation in C" by ANDREW W. APPEL. This repository is where I code the exercices given by the author.
  </p>
</ul>

<!-- 
Network dev
-->

<h2 align="center" > Low-level network development 🔌 </h2> 
<p align="center" > 💻 Language : <code>Rust</code> <code>C++</code> <code>C</code> </p> 
<p align="center" > 🛠️ Features : DHCP, loadbalancing</p> 
<p align="center">
As I said before, I used to be a network architect and administrator and I had to deal with networking issues. I'm thus interested in networking development. 
</p>
<ul list-style-type="none" align="center">
  <p>
    <a href = "https://github.com/frozenpeach-dev/dhcp" > A Rust DHCP </a> <br/>
    With <a href="https://github.com/frozenpeach-dev">frozenpeach</a> and <a href="https://github.com/sleiderr">@sleiderr</a> again we started the development of a Rust DHCP. I mainly worked on a <strong>high speed database</strong> with both hot and cold storage allowing fast and afe access to DHCP Leases.
  </p>

  <p>
    <a href = "https://github.com/raphfaur/loadbalancer" > A C++ Loadbalancer </a> <br>
  I worked a lot with HAProxy, that's why I started developing a loadbalancer in C++
  </p>
</ul>

<!-- 
Python ML and Cyber
-->

<h2 align="center" > ML 📈 and Cybersecurity 🔒</h2> 
<p align="center" > 
  💻 Language : <code>Python</code>  
</p> 
<p align="center" > 🛠️ Features : Neural networks, audio procesing</p> 
<p align="center">
I'm also interested in cybersecurity and machine learning.
</p>
<ul list-style-type="none" align="center">
  <p>
    <a href = "https://github.com/raphfaur/keyboard-eavesdropping" > Keyboard eavesdropping</a> <br/>
    I managed to reproduce a keayboard eavesdropping using neural networks, whitout using any library.
  </p>
</ul>

<!-- 
Web dev
-->

<h2 align="center" > Full stack development 🌐 </h2> 
<p align="center" > 💻 Language : <code>React</code> <code>ExpressJS</code></p> 
<p align="center">
As an administrator of an Internet Provider, I had to fix and improve wesites for our clients. In this context I learned backend and frontend development.
</p>
<ul list-style-type="none" align="center">
  <p>
    <a href = "https://github.com/raphfaur/frozencloud" > Photo cloud </a> <br/>
    As an easy example of what I can produce, I developped in a few days a authenticated photo cloud in React and Express.
  </p>
</ul>

<hr>

<h2 align="center">Tools & Libraries I'm familiar with</h2>
<p align="center">
  <!-- Python / ML -->
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-7B68EE?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Google%20ADK-4285F4?style=for-the-badge&logo=google&logoColor=white" />
</p>

<p align="center">
  <!-- Data / Dev / Web -->
  <img src="https://img.shields.io/badge/Databricks-FC5000?style=for-the-badge&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure%20DevOps-0078D7?style=for-the-badge&logo=azure-devops&logoColor=white" />
  <img src="https://img.shields.io/badge/Visual%20Studio-5C2D91?style=for-the-badge&logo=visual-studio&logoColor=white" />
  <img src="https://img.shields.io/badge/Xcode-007ACC?style=for-the-badge&logo=Xcode&logoColor=white" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
</p>






