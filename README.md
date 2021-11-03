### Hi there 👋 , I'm Jeonguk Hur





***
[![John's GitHub stats](https://github-readme-stats.vercel.app/api?username=johnjeongukhur&show_icons=true&theme=cobalt)](https://github.com/johnjeongukhur/github-readme-stats)

<!--START_SECTION:waka-->
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ 1d2b7d89-babd-45fd-a0a5-5b308f57a7b3 }}
          GH_TOKEN: ${{ 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 }}
<!--END_SECTION:waka-->
