## Hi, i am AiraaMel 


Business lover
Do everthing listening music, like 24 hours per day

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=AiraaMel&theme=rose)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=AiraaMel&layout=compact&theme=rose)

<div> 
 <a href="https://instagram.com/airaaxm" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
<a href="https://inteli-college.slack.com/team/U085DUGKQKZhttps" target="_blank"><img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white" target="_blank"></a>
<a href = "mailto: airamelbs@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>





    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: rafaballerini
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
