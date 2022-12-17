## Olá, sou Alexsander Ferreira!
<div align="center">

  <a href="https://github.com/AlexsanderFrr">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=alexsanderfrr&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=alexsanderfrr&layout=compact&langs_count=7&theme=dracula"/>
</div>
  
  ##
 
<div> 
  name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Summary Cards
      - uses: actions/checkout@v2
      - uses: vn7n24fzkq/github-profile-summary-cards@release
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
        with:
          USERNAME: ${{ github.repository_owner }}

      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
</div>
