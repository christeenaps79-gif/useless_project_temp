# [rock-lockdown] 🪨🔐

## Basic Details

### Team Name: cipher

### Team Members

* **Team Lead:** Krishnapriya N — College of Engineering Adoor
* **Member 2:** Christeena PS — College of Engineering Adoor

---

## Project Description

**Rock Lockdown** is a ridiculously over-engineered digital vault protected by a series of increasingly chaotic security challenges.

Instead of simply entering a password, users must survive riddles, fill-in-the-blanks, CAPTCHA challenges, a real camera scan, mathematical problems, timing challenges, memory tests, patterns and trivia to prove they deserve access. 🪨🔐

---

## The Problem (that doesn't exist)

We discovered a serious security crisis:

**What if someone tries to access a vault without proving that they are sufficiently qualified to press buttons?**

Traditional passwords seemed far too reasonable, so we decided to solve the completely unnecessary problem of **unnecessarily complicated vault security**.

---

## The Solution (that nobody asked for)

We created **Rock Lockdown** — a vault guarded by an emotionally judgmental rock.

Users have to pass multiple security locks, each testing a different ability such as logic, memory, observation, mathematics, reaction time and general knowledge.

Wrong answers trigger dramatic security warnings, funny insults and a temporary red-alert interface.

Because apparently, getting one question wrong deserves a full security incident. 💀

---

# Technical Details

## Technologies/Components Used

### For Software:

**Languages used**

* HTML5
* CSS3
* JavaScript

**Frameworks**

* None / Vanilla JavaScript

**Libraries**

* Three.js
* Three.js Postprocessing / Effect Composer

**Tools**

* Visual Studio Code
* Git & GitHub
* Web Browser
* Web Camera API
* Web Speech API

### For Hardware:

* No external hardware required
* Uses the computer's built-in webcam for the camera verification challenge

---

# Implementation

## For Software

Rock Lockdown is implemented as a browser-based interactive application.

The application begins with a cinematic particle-based introduction and then moves into the vault interface.

The user progresses through multiple security locks:

1. **Riddle Lock** — Solve a randomly selected riddle.
2. **Fill-in-the-Blank Lock** — Complete a technology-related statement.
3. **CAPTCHA Lock** — Identify the correct rock symbols.
4. **Camera Verification** — Access the user's webcam and perform a visual scanning sequence.
5. **Math Lock** — Solve a randomly generated mathematical problem.
6. **Timing Lock** — Stop a timer as close as possible to the target time.
7. **Rearrangement Lock** — Rearrange words into the correct sentence.
8. **Pattern Lock** — Identify the next value in a sequence.
9. **Memory Lock** — Memorize and reproduce a sequence.
10. **Trivia Lock** — Answer a general-knowledge question.

After completing the locks, the user enters their details and receives a generated **Vault Zero clearance certificate**.

The interface also includes dynamic feedback, speech responses from the Guardian, animated particles and temporary visual changes when incorrect answers are submitted.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/christeenaps79-gif/rock-lockdown.git
```

Navigate to the project folder:

```bash
cd rock-lockdown
```

Open the project in Visual Studio Code:

```bash
code .
```

---

## Run

Run the project using a local development server.

For example:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

> A local server is recommended because the camera verification feature requires browser permission and a secure/local environment.

---

# Project Documentation

## For Software

# Screenshots

<img width="1920" height="1020" alt="Screenshot 2026-09-12 163652" src="https://github.com/user-attachments/assets/e7816bf2-c243-452a-bf4a-1d6958c7ecec" />





<img width="1920" height="1020" alt="Screenshot 2026-09-12 163706" src="https://github.com/user-attachments/assets/7c5aa947-a172-47c9-a273-0d6ce0944a05" />


<img width="1920" height="1020" alt="Screenshot 2026-09-12 163745" src="https://github.com/user-attachments/assets/ade80e9b-8339-4524-a1e4-f93e41f20cfc" />

<img width="1920" height="1020" alt="Screenshot 2026-09-12 164159" src="https://github.com/user-attachments/assets/08b29e43-45df-4569-8df6-1a9804cbffee" />

<img width="1920" height="1020" alt="Screenshot 2026-09-12 164302" src="https://github.com/user-attachments/assets/455d51dc-4277-45c5-944d-3556168f34e4" />


# Diagrams

                    ┌─────────────────────┐
                    │     VAULT ZERO      │
                    │    INTRO / START    │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │    ENTER THE VAULT  │
                    └──────────┬──────────┘
                               │
                               ▼
              ┌─────────────────────────────────┐
              │        SECURITY LOCKS           │
              └───────────────┬─────────────────┘
                              │
        ┌─────────────────────┼─────────────────────┐
        ▼                     ▼                     ▼
 ┌──────────────┐      ┌──────────────┐      ┌──────────────┐
 │  LOCK 1      │      │  LOCK 2      │      │  LOCK 3      │
 │    RIDDLE    │ ───► │ FILL BLANK   │ ───► │   CAPTCHA    │
 └──────────────┘      └──────────────┘      └──────┬───────┘
                                                    │
                                                    ▼
                                             ┌──────────────┐
                                             │   LOCK 4     │
                                             │ CAMERA SCAN  │
                                             └──────┬───────┘
                                                    │
                                                    ▼
                                             ┌──────────────┐
                                             │   LOCK 5     │
                                             │     MATH     │
                                             └──────┬───────┘
                                                    │
                                                    ▼
                                             ┌──────────────┐
                                             │   LOCK 6     │
                                             │    TIMER     │
                                             └──────┬───────┘
                                                    │
                                                    ▼
                                             ┌──────────────┐
                                             │   LOCK 7     │
                                             │  REARRANGE   │
                                             └──────┬───────┘
                                                    │
                                                    ▼
                                             ┌──────────────┐
                                             │   LOCK 8     │
                                             │   PATTERN    │
                                             └──────┬───────┘
                                                    │
                                                    ▼
                                             ┌──────────────┐
                                             │   LOCK 9     │
                                             │    MEMORY    │
                                             └──────┬───────┘
                                                    │
                                                    ▼
                                             ┌──────────────┐
                                             │   LOCK 10    │
                                             │    TRIVIA    │
                                             └──────┬───────┘
                                                    │
                              ┌─────────────────────┴─────────────────────┐
                              │                                           │
                           WRONG                                      CORRECT
                              │                                           │
                              ▼                                           ▼
                   ┌──────────────────┐                         ┌──────────────────┐
                   │ FUNNY WARNING /  │                         │  ACCESS GRANTED  │
                   │ GUARDIAN REACTS  │                         │  THE ROCK APPROVES│
                   └────────┬─────────┘                         └────────┬─────────┘
                            │                                            │
                            └──────► TRY AGAIN ◄─────────────────────────┘
                                                                         │
                                                                         ▼
                                                               ┌──────────────────┐
                                                               │   USER PROFILE   │
                                                               │ Name / Class /   │
                                                               │ Hobbies / Talent │
                                                               └────────┬─────────┘
                                                                        │
                                                                        ▼
                                                               ┌──────────────────┐
                                                               │ VAULT CLEARANCE  │
                                                               │   CERTIFICATE    │
                                                               └──────────────────┘

# Project Demo

## Video





https://github.com/user-attachments/assets/e684aa5c-88cb-44e6-a02b-030b1fa96797


---

## Additional Demos

https://rock-lockdown.vercel.app/  
https://github.com/christeenaps79-gif/rock-lockdown.git
---

# Team Contributions

* **Krishnapriya N:**  Challenge content, testing, debugging, interface improvements, documentation and presentation support.

* **Christeena PS:** Project concept, UI/UX design, security challenge design, frontend development and overall project integration.

---

## Final Note

**Rock Lockdown exists because normal passwords were apparently not dramatic enough.**

If you make it through all the locks:

**THE ROCK APPROVES. 🪨🔥**

---

Made with ❤️ at TinkerHub Useless Projects

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000\&link=https%3A%2F%2Fwww.tinkerhub.org%2F)

![Static Badge](https://img.shields.io/badge/UselessProjects--26-26?link=https%3A%2F%2Ftinkerhub.org%2Fevents%2F1M8ORET9A1%2Fuseless-projects-3.0)


