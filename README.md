<img align="right" src="https://visitor-badge.laobi.icu/badge?page_id=Mahnoor-Muhammad-Naeem.Mahnoor-Muhammad-Naeem" />

<h1 align="center">
    <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=500&height=70&duration=4000&lines=Hi+There!+👋;+I'm+Mahnoor+Naeem!;+I'm+Frontend+Developer!;" />
</h1>

<h3 align="center">A passionate frontend developer from Pakistan</h3>

<br/>

<div align="center">
 
 🔭 I’m currently working on **a IF**
 
 🌱 I’m currently learning **React.js, Docker, AWS**

💬 Ask me about **Node.js, JS, React.js... or anything [here](https://github.com/Mahnoor-Muhammad-Naeem)**

⚡ Fun fact **Game of Thrones Night's Watch cloaks are made from Ikea rugs**

 </div>
 
<div align="center"> 
  <a href="mailto:mahnoormuhammadnaeem99@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=red" />
  </a>
  <a href="https://www.linkedin.com/in/mahnoor-muhammad-naeem-06592b2a9/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank" />
  </a>
  <a href="https://www.instagram.com/digital_creator1230/" target="_blank">
     <img src="https://img.shields.io/badge/Instagram-FF5722?style=for-the-badge&logo=todoist&logoColor=white" target="_blank" /> <!-- sqlite, safari, google-chrome are other good icon options -->
  </a>
</div>

 <hr/>
 
<h2 align="center">⚒️ Languages-Frameworks-Tools ⚒️</h2>
<br/>
<div align="center">
    <img src="https://skillicons.dev/icons?i=react,bootstrap,mui,html,css,vscode,github,figma,tailwind,git,r" />
    <img src="https://skillicons.dev/icons?i=nodejs,python,javascript,typescript,express,firebase,mongodb,c,java,nextjs,mysql,flask" /><br>
</div>

<br/>
<hr/>

<div align="center">
  <h2>🐍 My Contributions 🐍</h2>
  <br>
  <img alt="snake eating my contributions" src="https://raw.githubusercontent.com/Mahnoor-Muhammad-Naeem/Mahnoor-Muhammad-Naeem/output/github-contribution-grid-snake.svg" />
  
  <br/><br/><br/>
</div>

<hr/>

<h2 align="center">⚡ Stats ⚡</h2>
<br>
<div align=center>
  <img width=390 src="https://github-readme-streak-stats-Mahnoor-Muhammad-Naeem.vercel.app/?user=Mahnoor-Muhammad-Naeem&count_private=true&theme=react&border_radius=10" alt="streak stats"/>
  <img width=390 src="https://github-readme-stats-Mahnoor-Muhammad-Naeem.vercel.app/api?username=Mahnoor-Muhammad-Naeem&count_private=true&show_icons=true&theme=react&rank_icon=github&border_radius=10" alt="readme stats" />
  <br/>
  <img width=325 align="center" src="https://github-readme-stats-Mahnoor-Muhammad-Naeem.vercel.app/api/top-langs/?username=Mahnoor-Muhammad-Naeem&hide=HTML&langs_count=8&layout=compact&theme=react&border_radius=10&size_weight=0.5&count_weight=0.5&exclude_repo=github-readme-stats" alt="top langs" />
</div>

<br/><br/>

<hr/>

<br/>

<div align="center">
<a href='https://ko-fi.com/V7V4RAK9C' target='_blank'><img height='64' style='border:0px;height:64px;' src='https://storage.ko-fi.com/cdn/kofi1.png?v=3' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>
</div>

<br/>



![snake gif](https://github.com/Mahnoor-Muhammad-Naeem/Mahnoor-Muhammad-Naeem/blob/output/github-contribution-grid-snake.gif)




# snk

[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/platane/platane/main.yml?label=action&style=flat-square)](https://github.com/Platane/Platane/actions/workflows/main.yml)
[![GitHub release](https://img.shields.io/github/release/platane/snk.svg?style=flat-square)](https://github.com/platane/snk/releases/latest)
[![GitHub marketplace](https://img.shields.io/badge/marketplace-snake-blue?logo=github&style=flat-square)](https://github.com/marketplace/actions/generate-snake-game-from-github-contribution-grid)
![type definitions](https://img.shields.io/npm/types/typescript?style=flat-square)
![code style](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)

Generates a snake game from a github user contributions graph

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="github contribution grid snake animation"
    src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg"
  />
</picture>

Pull a github user's contribution graph.
Make it a snake Game, generate a snake path where the cells get eaten in an orderly fashion.

Generate a [gif](https://github.com/Platane/snk/raw/output/github-contribution-grid-snake.gif) or [svg](https://github.com/Platane/snk/raw/output/github-contribution-grid-snake.svg) image.

Available as github action. It can automatically generate a new image each day. Which makes for great [github profile readme](https://docs.github.com/en/free-pro-team@latest/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme)

## Usage

**github action**

```yaml
- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
```

[example with cron job](https://github.com/Platane/Platane/blob/master/.github/workflows/main.yml#L26-L33)

If you are only interested in generating a svg, consider using this faster action: `uses: Platane/snk/svg-only@v3`

**dark mode**

For **dark mode** support on github, use this [special syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#specifying-the-theme-an-image-is-shown-to) in your readme.

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="github-snake.svg" />
  <img alt="github-snake" src="github-snake.svg" />
</picture>
```

**interactive demo**

<a href="https://platane.github.io/snk">
  <img height="300px" src="https://user-images.githubusercontent.com/1659820/121798244-7c86d700-cc25-11eb-8c1c-b8e65556ac0d.gif" ></img>
</a>

[platane.github.io/snk](https://platane.github.io/snk)

**local**

```
npm install

npm run dev:demo
```

## Implementation

[solver algorithm](./packages/solver/README.md)
