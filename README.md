import os

readme = """# 👋 Hi, I'm Gesa

💻 Computer Science student passionate about backend development, data science, and cybersecurity.

---

## 🚀 Skills

- 🟢 C++ (Beginner)
- 🐍 Python (Intermediate)
- 🗄️ MySQL
- 🌐 Node.js (learning)
- 🧠 SQL & Databases (learning)

---

## 🎯 Interests

- Backend Development
- Data Science
- Cybersecurity
- Database Systems

---

## 📚 Currently Learning

- SQL
- Node.js
- Python for Data Science

---

## 📫 Contact

- Email: gesasega00@gmail.com
- GitHub: https://github.com/Gesa-111

⭐ Keep learning, keep building!
"""

# write README
with open("README.md", "w") as f:
    f.write(readme)

print("README updated")

# git commands
os.system("git add README.md")
os.system('git commit -m "update README via python"')
os.system("git push origin main")

print("Pushed to GitHub 🚀")
