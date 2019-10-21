# Aliases

a - git add .
co - git commit -m ...
s - git status
c - git checkout
p - git pull
su - git submodule update
clone - git clone
r - git reset --hard
clean - r - git reset --hard
i - npm install
po - git pull origin

initRepo - args - repo + branch - 1. git clone $1 && git checkout $2 && npm install && npm run build:debug && code . 