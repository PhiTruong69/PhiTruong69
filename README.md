# Hi, I'm Trường.
## 🌐Socials
[![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?logo=Facebook&logoColor=white)](https://facebook.com/phi.truong.069) [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/truo_gcon) 

# 💻Tech Stack
![C](https://img.shields.io/badge/c-%2300599C.svg?style=flat&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=flat&logo=c%2B%2B&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) ![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?style=flat&logo=latex&logoColor=white) ![R](https://img.shields.io/badge/r-%23276DC3.svg?style=flat&logo=r&logoColor=white)
# 📊GitHub Stats :
![](https://github-readme-stats.vercel.app/api?username=PhiTruong69&theme=material-palenight&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=PhiTruong69&theme=material-palenight&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=PhiTruong69&theme=material-palenight&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---
[![](https://visitcount.itsvg.in/api?id=PhiTruong69&icon=0&color=0)](https://visitcount.itsvg.in)
      - name: Checkout main branch
        uses: actions/checkout@v4
        with:
          ref: main
      - name: Update README.md
        run: |
          sed -i '/<!-- breakout-start -->/,/<!-- breakout-end -->/c\<!-- breakout-start -->\n<p align="center">\n  <img src="https://raw.githubusercontent.com/${{ github.repository }}/github-breakout/images/breakout-light.svg#gh-light-mode-only" alt="Breakout Game"/>\n  <img src="https://raw.githubusercontent.com/${{ github.repository }}/github-breakout/images/breakout-dark.svg#gh-dark-mode-only" alt="Breakout Game"/>\n</p>\n<!-- breakout-end -->' README.md
          git add README.md
          git commit -m "chore: update README with latest breakout game" || echo "No changes"
          git push origin main

<p align="center">
  <sub><em>Built with <a href="https://github.com/cyprieng/github-breakout">cyprieng/github-breakout</a></em></sub>
</p>

