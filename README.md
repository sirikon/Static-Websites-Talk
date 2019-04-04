# Static Websites Talk

## Create a static website with Hugo

```bash
hugo new site mysite
cd mysite
git init
git submodule add https://github.com/budparr/gohugo-theme-ananke.git themes/ananke
echo 'theme = "ananke"' >> config.toml
hugo new posts/my-first-post.md
```

## Run the web locally

```bash
hugo server -D
```
