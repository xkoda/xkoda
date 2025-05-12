![Typing](https://readme-typing-svg.demolab.com/?lines=Hi+there!+I'm+Sithija;Self-taught+Python+Learner;Loves+AI+%7C+Bots+%7C+Clean+Code&center=true&width=500&height=30)

<h1 align="center">Hi there, I'm Sithija Sankalpa (xkoda/) 👋</h1>

<p align="center">
  <em>Self-taught Developer | Python & AI Enthusiast | Building the Future from My Phone</em>
</p>

---

### 🔥 About Me
- Passionate about **clean code, automation**, and **AI**.
- 📱 Learning Python, building bots, and experimenting with AI tools — _all from a phone!_
- ✨ Believer in: _"Discipline and curiosity can take you far — even with just a phone."_

---

### 🛠️ Skills & Tools
![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![AI](https://img.shields.io/badge/AI-FF6F00?logo=OpenAI&logoColor=white)

---

### 🎯 2025 Goals
- 🤖 Build an **AI-powered chatbot**.
- 🌍 Contribute to **open-source projects**.
- 🌐 Learn **web development** (HTML/CSS/JS).

---

### 🚧 Projects
_Work in progress — stay tuned!_

- **Solea AI**: My AI experiments and blog → [soleaai.blogspot.com](https://soleaai.blogspot.com)

---

### 📊 GitHub Stats
![Sithija's GitHub Stats](https://github-readme-stats.vercel.app/api?username=xkoda&show_icons=true&theme=radical)

---

### 📬 Let's Connect!
- [![Email Me](https://img.shields.io/badge/-Contact-blue?style=for-the-badge&logo=gmail)](mailto:sankalpakoda@gmail.com)
- **Twitter/X:** [@xkoda](https://twitter.com/xkoda)
"""
Twitter/X Profile Card for GitHub README
"""
from datetime import datetime

class TwitterCard:
    def __init__(self):
        self.username = "xsithij"
        self.display_name = "Sithija Sankalpa (xkoda)"
        self.bio = "AI Developer | Python Specialist | Tech Blogger"
        self.current_year = datetime.now().year
        self.stats = {
            'tweets': '500+',
            'topics': ['AI', 'Python', 'Open Source'],
            'engagement': 'Active Daily'
        }
    
    def generate_card(self):
        return f"""
<div align="center">
  
### 🚀 Twitter/X Profile

<a href="https://x.com/{self.username}">
  <img src="https://img.shields.io/badge/Twitter-{self.username}-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"/>
</a>

**{self.display_name}**  
*"{self.bio}"*

```python
# {self.current_year} Twitter Activity
tweets = {self.stats['tweets']}  # Tech/AI focused
topics = {self.stats['topics']}
engagement = "{self.stats['engagement']}"
---

> _"Turning ideas into code — one tap at a time."_