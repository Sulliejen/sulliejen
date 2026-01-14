<!-- 🌸 Sakura Animated Header -->
<div align="center">

<svg width="100%" height="180" viewBox="0 0 1200 180" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="sakuraGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#FFD1DC"/>
      <stop offset="50%" stop-color="#FFB7C5"/>
      <stop offset="100%" stop-color="#FADADD"/>
    </linearGradient>
  </defs>

  <rect width="1200" height="180" fill="#0d1117"/>

  <!-- Falling petals -->
  <g fill="#FFB7C5" opacity="0.8">
    <circle cx="200" cy="-10" r="4">
      <animateTransform attributeName="transform" type="translate"
        from="0 0" to="100 220" dur="12s" repeatCount="indefinite"/>
    </circle>
    <circle cx="600" cy="-20" r="3">
      <animateTransform attributeName="transform" type="translate"
        from="0 0" to="-80 240" dur="14s" repeatCount="indefinite"/>
    </circle>
    <circle cx="950" cy="-15" r="5">
      <animateTransform attributeName="transform" type="translate"
        from="0 0" to="60 230" dur="16s" repeatCount="indefinite"/>
    </circle>
  </g>

  <text x="50%" y="50%" text-anchor="middle" fill="url(#sakuraGrad)"
        font-size="34" font-family="Fira Code, monospace" font-weight="600">
    System Programming · Security · Linux
  </text>
</svg>

</div>

---

<div align="center">
  
  ![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=25&pause=1000&color=00D9FF&center=true&vCenter=true&width=435&lines=System+Programming+Enthusiast;Security+expert;Linux+Power+User)
  
</div>

---

## 🚀 About Me

```python
class SullieJen:
    def __init__(self):
        self.name = "SullieJen"
        self.role = "Student"
        self.MBTI = "INTP"
        self.languages = ["Python", "C", "C++", "SQL", "HTML"]
        self.systems = ["Linux"]
        self.interests = [
            "System-level Security",
            "White Hat Hacking",
            "Low-level Programming",
            "Secure Web Architecture",
            "Database Design with Integrity"
        ]

    def philosophy(self):
        return "Understanding how systems break is the first step to securing them."

me = SullieJen()
print(me.philosophy())
