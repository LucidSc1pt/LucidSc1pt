
<!-- ============================================ -->
<!--        LUCIDSC1PT - GITHUB PROFILE          -->
<!-- ============================================ -->

<div align="center">

<!-- Animated Header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C9FF,50:92FE9D,100:00C9FF&height=200&section=header&text=LucidSc1pt&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Code%20%E2%80%A2%20Create%20%E2%80%A2%20Conquer&descAlignY=60&descAlign=50" width="100%"/>

<!-- Typing Animation -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=00C9FF&center=true&vCenter=true&random=false&width=600&lines=Welcome+to+my+GitHub+Profile+%F0%9F%91%8B;Full-Stack+Developer+%F0%9F%92%BB;Open+Source+Enthusiast+%E2%9C%A8;Always+Learning+New+Things+%F0%9F%9A%80" alt="Typing SVG" />
</a>

<!-- Profile Views + Followers -->
<img src="https://komarev.com/ghpvc/?username=LucidSc1pt&label=Profile%20views&color=00C9FF&style=for-the-badge" alt="profile views" />
<img src="https://img.shields.io/github/followers/LucidSc1pt?label=Followers&style=for-the-badge&color=92FE9D&labelColor=000000" alt="followers" />

</div>

---

## 🌟 About Me

```yml
name: LucidSc1pt
location: Indonesia 🇮🇩
focus: Web Development, Automation, Open Source
motto: "Code with clarity, build with purpose."
hobbies:
  - Coding 💻
  - Learning 📚
  - Gaming 🎮
  - Coffee ☕
```

---

🛠️ Tech Stack

<div align="center">

💻 Languages

<img src="https://skillicons.dev/icons?i=js,java,html,css,lua,luau&theme=dark" />

⚙️ Frameworks & Libraries

<img src="https://skillicons.dev/icons?i=tailwind&theme=dark" />

🗄️ Databases & Tools

<img src="https://skillicons.dev/icons?i=git,github,vscode,supabase,firebase&theme=dark" />

</div>

---

📊 GitHub Statistics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=LucidSc1pt&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=00C9FF&icon_color=92FE9D&text_color=ffffff"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=LucidSc1pt&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00C9FF&text_color=ffffff"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=LucidSc1pt&theme=tokyonight&hide_border=true&background=0D1117&stroke=00C9FF&ring=92FE9D&fire=00C9FF&currStreakLabel=92FE9D" alt="GitHub Streak"/>

</div>

---

🏆 GitHub Trophies

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=LucidSc1pt&theme=tokyonight&no-frame=true&no-bg=true&margin-w=15&column=7" />
</div>

---

🐍 Contribution Snake

<div align="center">
<img src="https://raw.githubusercontent.com/LucidSc1pt/LucidSc1pt/output/github-contribution-grid-snake-dark.svg" alt="Snake Animation" width="100%"/>
</div>

---

📈 Contribution Graph

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=LucidSc1pt&theme=dark&bg_color=0D1117&color=00C9FF&line=92FE9D&point=FFFFFF&hide_border=true" width="100%"/>
</div>

---

🌐 Connect With Me

<div align="center">

<a href="https://github.com/LucidSc1pt" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

</div>

---

💭 Random Dev Quote

<div align="center">
<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" />
</div>

---

☕ Support Me

<div align="center">

<a href="https://saweria.co/username" target="_blank">
  <img src="https://img.shields.io/badge/Saweria-FFA500?style=for-the-badge&logo=buymeacoffee&logoColor=white" />
</a>
<a href="https://ko-fi.com/username" target="_blank">
  <img src="https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white" />
</a>

</div>

---

<div align="center">

<!-- Animated Footer -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C9FF,50:92FE9D,100:00C9FF&height=120&section=footer&animation=twinkling" width="100%"/>

✨ Thanks for visiting! ✨

⭐ Jika kamu suka project-project saya, jangan lupa kasih star ya! ⭐

</div>
```

---

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:
  push:
    branches:
      - main

jobs:
  generate:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - name: Generate Snake SVG
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: LucidSc1pt
          outputs: |
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

linkedin.com/in/username Link LinkedIn kamu
instagram.com/username Username Instagram kamu
email@example.com Email kamu
discord.com/users/username Discord ID kamu
saweria.co/username Link Saweria kamu
ko-fi.com/username Link Ko-fi kamu

---
