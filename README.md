# hugo-git-pages-starter
Starter pack for a Hugo Blog on GitHub Pages

See the full guide for using this repo [here](https://commitconfirmed.github.io/posts/hugo-github-pages-starter/)

https://commitconfirmed.github.io/posts/hugo-github-pages-starter/

Try it out in codespaces

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/commitconfirmed/hugo-git-pages-starter?quickstart=1&devcontainer_path=.devcontainer%2Fdevcontainer.json)


## TLDR

- Create a GitHub account
- Create a new public repo called **username**.github.io replacing username your GitHub username 
- Clone this repo into your repo
- Update the `~/site/hugo.toml` file with your own personal details
- Update the `~/site/content/about/index.md` file with your own personal details
- See the `~/site/content/posts/` directory for an example blog bost. 
  - Create a new folder and `index.md` file to make your own blog post
- Update your repos Settings/Pages to deploy using Github Actions and create a workflow using the provided `~/.github/workflows/hugo.yml` file 
  - See the Hugo [Documentation](https://gohugo.io/host-and-deploy/host-on-github-pages/) for detailed instructions
- Commit some changes and push to Main and your blog should now be available at https://username.github.io
- (Optional) Apply any [Extras](https://commitconfirmed.github.io/posts/hugo-github-pages-starter/#extras)

Supports Local, Docker Compose or GitHub Codespaces development.