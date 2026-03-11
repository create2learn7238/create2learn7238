<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=35&pause=1000&color=6C63FF&center=true&vCenter=true&random=false&width=600&height=70&lines=%F0%9F%91%8B+Hey%2C+I'm+Dixit+Patel;Backend+Developer+%F0%9F%9A%80;Python+%7C+Java+%7C+DSA+%F0%9F%92%BB;Building+%7C+Learning+%7C+Growing+%F0%9F%8C%B1" alt="Typing SVG" />
</h1>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=create2learn7238&label=Profile%20Views&color=6C63FF&style=for-the-badge" alt="Profile Views" />
  <img src="https://img.shields.io/github/followers/create2learn7238?label=Followers&style=for-the-badge&color=6C63FF" alt="Followers" />
  <img src="https://img.shields.io/github/stars/create2learn7238?label=Stars&style=for-the-badge&color=6C63FF" alt="Stars" />
</p>

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="1000">
</div>

<br/>

<!-- ABOUT ME SECTION -->
<img align="right" alt="Coding" width="400" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif">

## 🧑‍💻 About Me

```yaml
name: Dixit Patel
role: Backend Developer
location: India 🇮🇳
currently_learning: Data Structures & Algorithms
passion: Building scalable backend systems
motto: "Create to Learn, Learn to Create"
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: create2learn7238
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
