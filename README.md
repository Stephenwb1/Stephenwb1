# 🎓 Stephen Wend-Bell

**`Computer Engineering @ UC Santa Cruz`**

I'm a current student at University of California, Santa Cruz, pursuing my Bachelor's Degree in Computer Engineering with a minor in Computer Science. I'm interested in pursuing a career in software engineering or embedded systems.
Here on my github profile, I have organized many of my personal and school projects.

📬 Open to full-time SWE and embedded systems roles starting Summer/Fall 2026 — stephenwb360@gmail.com

---

### 🔧 Currently Working On
- **Autonomous Drone** — ESP32-based user-following drone with BLE mobile control (CSE123 Engineering Design Project)
- **Memory Allocator & Profiler Dashboard** — Custom malloc/free in C with a Java Spring Boot API and React dashboard

---

### 🧰 Languages and Tools

<img align="left" alt="C" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/c/c-original.svg" />
<img align="left" alt="C++" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/cplusplus/cplusplus-original.svg" />
<img align="left" alt="C#" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/csharp/csharp-original.svg" />
<img align="left" alt="Python" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-plain.svg" />
<img align="left" alt="Go" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/go/go-original.svg" />
<img align="left" alt="Java" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" />
<img align="left" alt="TypeScript" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" />
<img align="left" alt="JavaScript" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-plain.svg" />
<img align="left" alt="React" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" />
<img align="left" alt="HTML" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" />
<img align="left" alt="CSS" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" />
<img align="left" alt="PostgreSQL" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" />
<img align="left" alt="MongoDB" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongodb/mongodb-original-wordmark.svg" />
<img align="left" alt="Supabase" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/supabase/supabase-original.svg" />
<img align="left" alt="Git" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
<img align="left" alt="Linux" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" />
<br />

---
### 📊 GitHub Stats

<p align="left">
  <img height="165" src="https://awesome-github-stats.azurewebsites.net/user-stats/Stephenwb1?theme=radical&border=0" />
  <img height="165" src="https://streak-stats.demolab.com?user=Stephenwb1&theme=radical&hide_border=true" />
</p>

---

### Latest Projects

### [CodeCompass][codecompass_link]
*Open-source AI-assisted codebase comprehension and analysis tool*
* Built a full-stack application with Next.js and Tailwind, implementing file tree browsing, semantic search, and AI-generated code insights
* Integrated Supabase Auth for secure GitHub OAuth login, allowing users to safely connect and explore their repositories
* Implemented a Retrieval-Augmented Generation (RAG) pipeline to supply AI assistants with contextualized code summaries, enabling accurate queries on unfamiliar codebases
* Designed and built interactive UI tools for file viewing, semantic search results, and real-time AI analysis panels

### [Autonomous Drone][drone_link]
*ESP32-based user-following drone with BLE mobile control — Engineering Design Project (In Progress)*
* Developed low-level motor control firmware in C on an ESP32, managing PWM signals for brushless motor speed and directional control
* Implemented dual wireless communication modes — Bluetooth Low Energy (BLE) and WiFi SoftAP — for real-time drone command and telemetry
* Built a TypeScript mobile application for drone control, configuration, and live status monitoring over a Bluetooth connection
* Produced full system design documentation including PCB schematics, software architecture, and an OTA firmware update strategy

### [JobMe][JobMe_repo_link]
*A full-stack job application tracker and management platform built on the MERN stack*
* Developed RESTful APIs for seamless communication between the React frontend and Node.js/Express backend
* Implemented a secure user login system using JWT authentication and bcrypt password hashing
* Implemented Mongoose models to streamline interactions between the application and the MongoDB database
* Integrated form validation and error handling to ensure data integrity and improve user feedback

### [Minecraft HTN Planning][htn_link]
*An AI planning system using Hierarchical Task Networks to autonomously solve crafting and construction problems*
* Implemented a Hierarchical Task Network planner to autonomously decompose and solve multi-step crafting and construction problems in a Minecraft-inspired domain
* Automated translation of JSON crafting recipes into HTN operators and methods, eliminating manual rule encoding
* Enhanced planner performance with bidirectional task decomposition and real-time resource management
* Achieved planning solutions within 30 seconds under complex resource constraints, balancing computational efficiency and accuracy

### [Esp32 Bluetooth Mouse][mouse_link]
*A Bluetooth HID mouse built on an ESP32 using onboard IMU sensors for cursor control*
* Developed a Bluetooth HID mouse using an ESP32 and onboard ICM42670P sensor to control cursor movement
* Implemented real-time motion tracking with accelerometer and gyroscope data using the ESP-IDF toolchain
* Configured and debugged low-level I2C protocols to reliably retrieve real-time sensor data from onboard peripherals
* Debugged sensor input and system behavior using ESP logging and serial output, calibrating motion sensitivity for accurate and stable cursor control

### [Multithreaded HTTP Server][http_link]
*A high-throughput HTTP server in C built on a thread pool architecture with strict memory and concurrency guarantees*
* Performed load testing with 100+ simultaneous users to validate robustness and reliability under heavy concurrency
* Reduced memory usage by 80% by eliminating dynamic memory leaks and enforcing strict allocation discipline
* Integrated a thread-safe queue and reader-writer locks to ensure synchronized shared resource access and atomic request processing
* Optimized for throughput while maintaining coherent and durable request ordering under concurrent workloads

### [TCP Chat Application][tcp_link]
*A multi-user real-time chat application built on TCP sockets in Python*
* Built a multi-user chat application enabling real-time messaging over secure TCP connections using Python's socket API
* Implemented a client-server architecture handling concurrent connections and message routing between multiple users
* Deployed and tested within a Mininet virtual network environment, simulating real-world network topology and conditions
* Designed a lightweight messaging protocol ensuring reliable, ordered delivery of messages between connected clients



[http_link]: https://github.com/Stephenwb1/cse156asgn5
[main_link]: https://github.com/Stephenwb1
[mouse_link]: https://github.com/Stephenwb1/cse121_lab4
[tcp_link]: https://github.com/Stephenwb1/TCP-Chat-Application
[drone_link]: https://github.com/Stephenwb1/autonomous-drone
[JobMe_repo_link]: https://github.com/Stephenwb1/Application-Tracker
[codecompass_link]: https://github.com/vinngo/codecompass
[web_link]: https://stephenwb1.github.io/index.html
[htn_link]: https://github.com/Stephenwb1/Minecraft-HTN-Planning
