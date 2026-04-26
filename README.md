### Global zsh config

```bash
git init
echo "### Global zsh config" > README.md
git add -Av
eza
git commit -m "$(date)"
git status
gh repo create --public --source=. --remote=origin
git push -u origin main
git status
```
