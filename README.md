# 🔐 Architecture 4001 – Intel Firmware Attack & Defense

![Course](https://img.shields.io/badge/OpenSecurityTraining2-Architecture%204001-darkred?style=flat-square&logo=intel)
![Status](https://img.shields.io/badge/Status-In%20Progress-blue?style=flat-square&logo=verizon)
![Type](https://img.shields.io/badge/Type-Learning%20Notes-orange?style=flat-square&logo=notion)
![Focus](https://img.shields.io/badge/Focus-Firmware%20Security-informational?style=flat-square&logo=linux)
![Maintainer](https://img.shields.io/badge/Maintainer-Thành%20Danh-blueviolet?style=flat-square&logo=github)

This repository contains structured notes, diagrams, checklists, extended resources, and the certificate of completion for the **Architecture 4001 – x86-64 Intel Firmware Attack & Defense** course.  
It is designed as a **community knowledge base** for both Red Team and Blue Team practitioners.

---

## 📚 Notes (Modules)

- 📄 [`01-uefi-basics.md`](./notes/01-uefi-basics.md) – UEFI boot fundamentals  
- 📄 [`02-spi-flash.md`](./notes/02-spi-flash.md) – SPI flash memory & firmware storage  
- 📄 [`03-intel-me.md`](./notes/03-intel-me.md) – Intel Management Engine  
- 📄 [`04-smm.md`](./notes/04-smm.md) – System Management Mode (SMM)  
- 📄 [`05-boot-guard-txt.md`](./notes/05-boot-guard-txt.md) – Boot Guard & Trusted Execution  
- 📄 [`06-hardening.md`](./notes/06-hardening.md) – Firmware security hardening  

---

## 📋 Checklists & Security Guides

- ✅ [`firmware-hardening.md`](./content/checklists/firmware-hardening.md) – Practical firmware hardening checklist  
- 🛡️ [`platform-security-controls.md`](./content/blue-team/platform-security-controls.md) – Blue Team perspective  
- 🎯 [`threat-modeling-only.md`](./content/red-team/threat-modeling-only.md) – Red Team threat modeling  

---

## 📂 Documentation

- 📑 [`syllabus.md`](./docs/syllabus.md) – Course syllabus overview  
- 🛠️ [`roadmap.md`](./docs/roadmap.md) – Suggested learning roadmap  
- 📖 [`glossary.md`](./docs/glossary.md) – Key terminology explained  
- 📚 [`references.md`](./docs/references.md) – Research papers & references  

---

## 📊 Extras

- 🕒 [`timeline.md`](./extras/timeline.md) – Evolution of firmware attacks & defenses  
- 📂 [`case-studies.md`](./extras/case-studies.md) – Real-world case studies  
- 📘 [`resources.md`](./extras/resources.md) – Extended learning resources  

---

## 📸 Screenshots

| Step                  | Screenshot |
|-----------------------|------------|
| 📘 Course – Part I    | ![](./screenshots/course-partone.png) |
| 📘 Course – Part II   | ![](./screenshots/course-parttow.png) |
| 💬 Discussions        | ![](./screenshots/discussions.png) |

---

## 🖼️ Diagrams

| Diagram | Preview |
|---------|---------|
| 🔧 UEFI Boot Flow | ![](./images/diagram-uefi-boot-flow.png) |

---

## 📜 Certificate

🎓 [`Architecture 4001 – Intel Firmware Attack & Defense`](./cert/Architecture%204001%20x86-64%20Intel%20Firmware%20Attack%20%26%20Defense.png)

---

## 📝 Reflections

> Personal takeaways after completing this course:

- **Strengths**: The course provides deep technical coverage from hardware architecture to firmware security mechanisms, especially SMM, Intel ME, and Boot Guard.  
- **Challenges**: The labs demand strong background knowledge in OS internals, assembly, and hardware. Without that, the learning curve feels steep.  
- **Practical Relevance**: Extremely useful for Red Teams analyzing firmware persistence and for Blue Teams implementing platform security controls.  
- **Most impressive part**: The LoJax rootkit case study — showing that firmware attacks are not just theory, but real-world threats.  
- **My own growth**: I became much more confident in reading firmware specifications, applying hardening checklists, and preparing for Red Team projects.  

---

## ✍️ Author

**Thành Danh** – Red Team Learner | Pentester & Security Researcher  

GitHub: [@ngvuthdanhh](https://github.com/ngvuthdanhh)  

Email: **ngvu.thdanh@gmail.com**

---

## 📄 License

This project is licensed under the terms of the **MIT License**.  
See [`LICENSE`](./LICENSE) for details.

© 2025 ngvuthdanhh. All rights reserved.
