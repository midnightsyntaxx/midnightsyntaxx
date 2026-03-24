# Hi there, I'm Midnight 👋

Seorang pelajar tingkat akhir yang berdedikasi untuk menjadi Software Engineer. Saya memiliki ketertarikan mendalam pada Computer Science dan saat ini fokus membangun fondasi kuat dalam pengembangan perangkat lunak serta logika pemrograman.

---

### 🚀 Tentang Saya
- 🎓 Sedang menempuh pendidikan di bangku SMA (Lulus April 2026).
- 💻 Sedang aktif mempelajari **HTML, CSS, JavaScript, dan Python**.
- 🏆 Memiliki sertifikasi dasar **JavaScript** dan **Front-End Development** dari Dicoding.
- ⚡ Selain coding, saya juga aktif dalam kegiatan fisik seperti **Taekwondo** dan **Marathon**.

---

### 🛠️ Tech Stack & Tools
<p align="left">
  <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python" />
  <img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</p>

---

  ### 📊 GitHub Stats & Contributions
<p align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=midnightsyntaxx&show_icons=true&theme=tokyonight" alt="GitHub Stats" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=midnightsyntaxx&layout=compact&theme=tokyonight" alt="Top Langs" />
  </p>
  <p align="center">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=midnightsyntaxx&theme=tokyonight" alt="GitHub Streak" />
  </p>
 </p>

---

### 📫 Mari Terhubung!
- **LinkedIn:** [linkedin.com/in/fauzanfirdaus](https://linkedin.com/in/YOUR_LINKEDIN_URL)
- **Instagram:** [@your_username](https://instagram.com/YOUR_INSTAGRAM_URL)
- **Email:** fauzan@example.com

---
*"Terus belajar dan konsisten adalah kunci."*


- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:           A preset of color, one of [github, github-dark, github-light]
    #  - color_snake:       Color of the snake
    #  - color_dots:        Coma separated list of dots color.
    #                       The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                       Exactly 5 colors are expected.
    #  - color_background:  Color of the background (for gif only)
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9&color_background=#aaaaaa
