# Comandos usando o git

### Configurando a identificação no Git

```
git config user.name "kethelynsantos"
git config user.email "kethelyngabrielly14@gmail.com"
```
---

### Salvando a primeira versão de um projeto

Depois de criar um repositório no github, executar os seguintes comandos ->

```
git init
git add .
git commit -m "commit"
git branch -M main
git remote add origin https://github.com/kethelynsantos/GitCommands.git
git push -u origin main
```
---

### Salvando uma nova versão
```
git status
git add .
git commit -m "update"
git push
```
---

### Clonando um repositório

Após copiar o link do repositório que deseja clonar, fazer ->
```
git clone codigocopiado
code .
```
