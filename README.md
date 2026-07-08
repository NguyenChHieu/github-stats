# GitHub Stats (NguyenChHieu)

Concise GitHub stats cards for my profile, generated automatically with GitHub Actions.

<img src="./generated/overview.svg#gh-dark-mode-only" />
<img src="./generated/languages.svg#gh-dark-mode-only" />
<img src="./generated/overview.svg#gh-light-mode-only" />
<img src="./generated/languages.svg#gh-light-mode-only" />

## Quick setup

1. Add a repository secret named `ACCESS_TOKEN` (PAT with `read:user` and `repo`).
2. Run the **Generate Stats Images** workflow from the Actions tab.
3. Use images from `/generated` in your profile README.

## Embed in profile README

```md
![](https://raw.githubusercontent.com/NguyenChHieu/github-stats/master/generated/overview.svg#gh-dark-mode-only)
![](https://raw.githubusercontent.com/NguyenChHieu/github-stats/master/generated/overview.svg#gh-light-mode-only)
![](https://raw.githubusercontent.com/NguyenChHieu/github-stats/master/generated/languages.svg#gh-dark-mode-only)
![](https://raw.githubusercontent.com/NguyenChHieu/github-stats/master/generated/languages.svg#gh-light-mode-only)
```

## Credits

Forked from [jstrieb/github-stats](https://github.com/jstrieb/github-stats).
