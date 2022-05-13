### Hi there 👋

<!--
**soopeach/soopeach** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:
-->
<!--START_SECTION:waka-->

name: Update gist with WakaTime stats
on:
  push:
    branches:
      - master
  schedule:
    - cron: "0 0 * * *"
jobs:
  update-gist:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@master
      - name: Update gist
        uses: matchai/waka-box@master
        env:
          GH_TOKEN: ${{ secrets.GH_TOKEN }}
          GIST_ID: ${{ secrets.GIST_ID }}
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          TIMEZONE: Asia/Seoul
<!--END_SECTION:waka-->

- 🔭 I’m currently working on ... 
- 🌱 I’m currently learning ... Android, Kotlin, Python
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ... hsjeon584@gmail.com
- 😄 Pronouns: ...
- ⚡ Fun fact: ...


[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fsoopeach&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)


[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=hsjeon01)](https://solved.ac/hsjeon01/)

![soopeach's github stats](https://github-readme-stats.vercel.app/api?username=soopeach&show_icons=true)
