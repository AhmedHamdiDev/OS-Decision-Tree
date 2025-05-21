# OS Decision Tree

This decision tree helps recommend alternative operating systems to Windows based on user preferences and needs.

---

**1. Do you care about the privacy and control of your personal data?**

* **A) Yes, absolutely. Data privacy and control are very important to me.**
    * **A1. Are you willing to spend time writing an operating system from scratch?**
        * **A1.1) Yes**
            * **A1.1.1) Do you want to spend time compiling all your packages every single time you want to install something?**
                * **A1.1.1.1) Yes** $\rightarrow$ **Gentoo**
                * **A1.1.1.2) Somewhat** $\rightarrow$ **Arch Linux**
                * **A1.1.1.3) No**
                    * **A1.1.1.3.1) Are you a hacker?**
                        * **A1.1.1.3.1.1) Yes** $\rightarrow$ **BlackArch**
                        * **A1.1.1.3.1.2) Somewhat**
                            * **A1.1.1.3.1.2.1) Is your hardware 20 years old?**
                                * **A1.1.1.3.1.2.1.1) Yes** $\rightarrow$ **Kali Linux**
                                * **A1.1.1.3.1.2.1.2) No** $\rightarrow$ **Parrot OS**
                        * **A1.1.1.3.1.3) No** $\rightarrow$ **Linux From Scratch (LFS)**
        * **A1.2) No**
            * **A1.2.1) Do you value stability or bleeding edge technology?**
                * **A1.2.1.1) Yes (Stability)** $\rightarrow$ **Debian**
                * **A1.2.1.2) No (Bleeding Edge)**
                    * **A1.2.1.2.1) Do you want an extensive repository of software?**
                        * **A1.2.1.2.1.1) Yes**
                            * **A1.2.1.2.1.1.1) Do you want your system to break every single time you update it?**
                                * **A1.2.1.2.1.1.1.1) Yes** $\rightarrow$ **Manjaro**
                                * **A1.2.1.2.1.1.1.2) No** $\rightarrow$ **EndeavourOS**

* **B) Somewhat. I prefer more privacy, but it's not my top priority.**
    * **B1. Are you comfortable with the CLI (Command Line Interface)?**
        * **B1.1) Yes**
            * **B1.1.1) Are you a gamer?**
                * **B1.1.1.1) Yes**
                    * **B1.1.1.1.1) Which of these best describes your gaming needs and preferences?**
                        * **B1.1.1.1.1.1) I primarily play Steam games, and I want a console-like experience that boots directly into my game library.** $\rightarrow$ **SteamOS**
                        * **B1.1.1.1.1.2) I play a mix of Steam and non-Steam games (e.g., Epic Games, GOG, emulators), and I want a versatile desktop environment that's excellent for gaming and general use.** $\rightarrow$ **Pop!\_OS**
                        * **B1.1.1.1.1.3) I play a mix of Steam and non-Steam games, and I want a gaming-focused desktop that uses an immutable system for reliability and easy rollbacks.** $\rightarrow$ **Bazzite**
                * **B
