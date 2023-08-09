@@ -55,9 +55,9 @@ Available as github action. It can automatically generate a new image each day.
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9

    env:
      # a github token is required to fetch the contribution calendar from github API
      GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  env:
    # a github token is required to fetch the contribution calendar from github API
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

[example with cron job](https://github.com/Platane/Platane/blob/master/.github/workflows/main.yml#L25-L33)
