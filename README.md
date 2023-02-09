# Prereq
1. 
```sh
mkdir yourrepo
sudo i -g lerna
lerna init
.gitignore //edit or create
```

2. Create the server package
```sh
cd packages
mkdir server && cd "$_"
npm init --yes
npm i express
npm i --save-dev typescript ts-node
```

