## Postgres Commands
```bash
alias pg-start='sudo service postgresql start'
alias pg-run='sudo -u postgres psql'
alias pg-stop='sudo service postgresql stop'
alias pg-status='sudo service postgresql status'
```

## More ls
```bash
alias ll='ls -alhF'
alias la='ls -A'
alias l='ls -CF'
```

## Add an "alert" alias for long running commands.  Use like so:
## sleep 10; alert
```bash
alias alert='notify-send --urgency=low -i "$([ $? = 0 ] && echo terminal || echo error)" "$(history|tail -n1|sed -e '\''s/^\s*[0-9]\+\s*//;s/[;&|]\s*alert$//'\'')"'
```

## Git Commands
```bash
alias gs='git status'
alias gaa='git add -A'
# Git Commit Message function (allows use of backticks for inline code in commit messages)
gcm() {
  git commit -m "$@"
}
alias gp='git push'
alias gpl='git pull'
alias gd='git diff'
alias gds='git diff --staged'
alias gb='git branch'
```

## System Updates
```bash
alias supgrade='sudo apt update && sudo apt upgrade'
```

## Python
```bash
alias python='python3'
```
