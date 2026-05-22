<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:00D9FF&height=200&section=header&text=Ayush%20Narayan&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Builder.%20Breaker.%20Debugger%20of%20cursed%20bugs.&descAlignY=60&descSize=18" />

</div>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ayush%20Narayan-0A2540?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/)
[![Email](https://img.shields.io/badge/Email-ayushnarayan%40gmail.com-00D9FF?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ayushnarayan@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-120%2B%20Solved-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/)
[![BMSCE](https://img.shields.io/badge/BMSCE-BTech%20ISE-0A2540?style=for-the-badge&logo=academia&logoColor=white)](https://www.bmsce.ac.in/)
[![Hackathon](https://img.shields.io/badge/Phase%20Shift%202024-Winner-00D9FF?style=for-the-badge&logoColor=white)]()

</div>

---

## 🧠 About Me

```python
class AyushNarayan:
    def __init__(self):
        self.name          = "Ayush Narayan"
        self.location      = "Bengaluru, India"
        self.education     = "BTech ISE @ BMS College of Engineering (2023–2027)"
        self.current_work  = [
                               "FRPS-2025 Funded Research @ BMSCE (Rs. 4.5L Grant)",
                               "Industry Collaboration — Modelicon Infotech LLP"
                             ]
        self.building      = [
                               "AI-Powered ERP Assistant (LLM + RAG)",
                               "Motion-Controlled Cursor via Phone Gyroscope",
                               "Full-Stack Travel Platform with FastAPI + MongoDB"
                             ]
        self.interests     = [
                               "Systems Engineering", "Real-Time Applications",
                               "NLP Pipelines", "Competitive Programming",
                               "Full-Stack Development"
                             ]
        self.fun_fact      = "I made a laptop cursor move using phone gravity. Yes, really."

    def say_hi(self):
        print("Ship fast. Learn faster. Build things that actually work.")
```

---

## 🏆 Highlights & Achievements

<div align="center">

| Achievement | Details |
|---|---|
| 🏆 **Hackathon Winner** | Phase Shift 2024 @ BMSCE — Led solution design & rapid prototyping in 24-hr sprint |
| 🔬 **Funded Researcher** | VTU FRPS-2025 Grant · Rs. 4.5L · Industry collab with Modelicon Infotech LLP |
| 🧩 **Competitive Programmer** | 120+ problems on LeetCode — Arrays, Trees, Graphs, DP, O(n²)→O(n log n) |
| 🌐 **Web Coordinator** | Junior Coordinator, Information & Web Team — Phase Shift 2024, BMSCE |
| ⚡ **IEEE Participant** | Hands-on AI, IoT & Software Engineering workshops |
| 🚀 **Hackathon Regular** | Active on Devfolio, Unstop, HackerEarth, MLH |

</div>

---

## 🚀 Featured Projects

<details>
<summary><b>🤖 AI-Powered Academic ERP Assistant</b> — <i>FRPS-2025 Funded, Ongoing</i></summary>
<br>

Conversational AI backend grounding an LLM assistant with live institutional ERP data.

- RAG pipeline reducing hallucination by grounding responses with structured ERP records
- Secure API integration between the LLM assistant and campus ERP system
- Modular backend services for query parsing, auth handling, and ERP request routing
- Targeting campus-wide deployment, peer-reviewed publication, and patent filing

**Stack:** Python · LLM APIs · RAG · REST APIs · Modelicon Infotech LLP

</details>

<details>
<summary><b>🖱️ Mouse Controller</b> — <i>Real-Time Motion Mouse</i> · <a href="https://mouse-controller-nine.vercel.app/">Live Demo ↗</a></summary>
<br>

Control your laptop cursor by tilting your phone — like pointing a TV remote at your screen.

- WebSocket-based real-time communication with ultra-low latency
- DeviceOrientation API capturing gyroscope Alpha/Beta/Gamma axes from phone
- Python + FastAPI + pyautogui backend translating motion into cursor movement
- QR-code device pairing, HTTPS/WSS security, live telemetry dashboard
- Framer Motion UI with sensitivity slider, click buttons, and tracking toggle

**Stack:** Next.js · React · Python · FastAPI · WebSockets · pyautogui · Tailwind CSS

</details>

<details>
<summary><b>🇮🇳 India Explorer</b> — <i>Full-Stack Travel Platform</i> · <a href="https://india-explorer-peach.vercel.app">Live Demo ↗</a></summary>
<br>

Immersive full-stack travel discovery platform for exploring India's cultural and tourism landscape.

- FastAPI backend with REST endpoints for states, destinations, categories, and search
- MongoDB Atlas document architecture with async Motor/PyMongo integration
- Framer Motion animations, Tailwind responsive layouts, Axios API communication
- Cloud deployment: Vercel (frontend) + Render (backend) + MongoDB Atlas (DB)

**Stack:** React · FastAPI · MongoDB Atlas · Tailwind CSS · Framer Motion · Vercel · Render

</details>

<details>
<summary><b>📄 Automated Resume Analyzer</b> — <i>NLP Classification Pipeline</i></summary>
<br>

End-to-end supervised NLP pipeline for binary resume classification.

- TF-IDF vectorization (max_features=5000) capturing high-signal lexical features
- Gensim tokenization + NLTK stopword removal + normalization + noise reduction
- L2-regularized Logistic Regression and LinearSVC trained on stratified splits
- Evaluated with Accuracy, Precision, Recall, F1, and confusion matrices; real-time inference workflow

**Stack:** Python · scikit-learn · TF-IDF · NLTK · Gensim · Logistic Regression · LinearSVC

</details>

<details>
<summary><b>🌐 Congestion Detection System</b> — <i>Network Systems & ML</i></summary>
<br>

Real-time network performance monitoring with ML-based congestion state prediction.

- ICMP / UDP / TCP RTT measurement pipeline + iPerf3 throughput analysis
- Feature engineering: mean RTT, standard deviation, signal elevation
- SVM-based congestion classifier with CSV logging and matplotlib graph output
- Supports single-laptop and two-laptop demo configurations

**Stack:** Python · scikit-learn · SVM · iPerf3 · matplotlib · NumPy · pandas

</details>

<details>
<summary><b>💸 Expense Tracker</b> — <i>Full-Stack Web App</i></summary>
<br>

Real-time expense management with Firebase backend and React frontend.

- Firebase Auth + Firestore CRUD with optimistic UI updates for instant responsiveness
- Category-based filtering, input validation, and React Hooks state management
- Modular reusable component architecture with date-wise sorted transaction history
- Real-time balance sync across sessions via Firestore live listeners

**Stack:** React · Firebase · Firestore · React Hooks

</details>

---

## 🛠️ Skills & Technologies

### 🤖 AI / ML & NLP

![RAG](https://img.shields.io/badge/RAG-00D9FF?style=for-the-badge&logoColor=white)
![LLM APIs](https://img.shields.io/badge/LLM%20APIs-0A2540?style=for-the-badge&logoColor=white)
![Prompt Engineering](https://img.shields.io/badge/Prompt%20Engineering-00D9FF?style=for-the-badge&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-154F5B?style=for-the-badge&logo=python&logoColor=white)
![Gensim](https://img.shields.io/badge/Gensim-0A2540?style=for-the-badge&logo=python&logoColor=white)

**Capabilities:** TF-IDF Pipelines · RAG Architecture · Hallucination Mitigation · NLP Preprocessing · Supervised Classification · Model Evaluation · Confusion Matrices · Real-Time Inference

---

### 💻 Languages

![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Bash](https://img.shields.io/badge/bash-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)

---

### 🌐 Web & Full-Stack

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Node.js](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer%20Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)

---

### 🗄️ Databases & Storage

![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Firestore](https://img.shields.io/badge/Firestore-FF6F00?style=for-the-badge&logo=firebase&logoColor=white)

**Also:** NoSQL Schema Design · SQL Query Optimization · REST API Design · WebSockets · API Gateway Patterns

---

### ⚙️ Backend, Systems & DevOps

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)

**Also:** Shell Scripting · CI/CD Basics · Microservices · OAuth · Middleware Design · HTTPS/WSS · Production Debugging

---

### 🔬 CS Fundamentals & Analytics

- **DSA:** 120+ problems on LeetCode — Arrays, Linked Lists, Trees, Graphs, Dynamic Programming; complexity optimizations O(n²) → O(n log n)
- **Core:** OOP · System Design · DBMS · Operating Systems · Computer Networks · Distributed Systems Concepts
- **Data:** NumPy · Pandas · Matplotlib · TF-IDF · Diagnostic artifacts (confusion matrices, metric charts)
- **Networks:** RTT profiling · ICMP/UDP/TCP measurement · Throughput analysis · Congestion modeling

---

### 🧰 Tools & Platforms

![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Netlify](https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=#00C7B7)

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=marvelayush&theme=dark&hide_border=true&include_all_commits=true&count_private=true&bg_color=0D1117&title_color=00D9FF&text_color=c8d8e8&icon_color=00D9FF"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=marvelayush&theme=dark&hide_border=true&layout=compact&bg_color=0D1117&title_color=00D9FF&text_color=c8d8e8"/>

</div>

<div align="center">

<img src="https://nirzak-streak-stats.vercel.app/?user=marvelayush&theme=dark&hide_border=true&background=0D1117&ring=00D9FF&fire=00D9FF&currStreakLabel=00D9FF"/>

</div>

---

## 🏆 GitHub Trophies

<div align="center">

![](https://github-profile-trophy.vercel.app/?username=marvelayush&theme=tokyonight&no-frame=true&no-bg=false&margin-w=6&column=7)

</div>

---

<div align="center">

*"Ship fast. Learn faster. Build things that actually work."*

[![](https://visitcount.itsvg.in/api?id=marvelayush&icon=6&color=6)](https://visitcount.itsvg.in)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00D9FF,100:0D1117&height=100&section=footer" />

</div>
