# Comandos usando o git

### Configurando a identificação no Git

```bash
>> git config user.name "kethelynsantos"
>> git config user.email "kethelyngabrielly14@gmail.com"
```
---

### Salvando a primeira versão de um projeto

Depois de criar um repositório no github, executar os seguintes comandos ->

```bash
>> git init
>> git add .
>> git commit -m "commit"
>> git branch -M main
>> git remote add origin https://github.com/kethelynsantos/GitCommands.git
>> git push -u origin main
```
---

### Salvando uma nova versão
```bash
>> git status
>> git add .
>> git commit -m "update"
>> git push
```
---

### Clonando um repositório

Após copiar o link do repositório que deseja clonar, fazer ->
```bash
>> git clone codigocopiado
>> code .
```
---

### Criando uma Branch
```bash
>> Configure seu usuário
>> git checkout -b kethelyn
>> git checkout (mostra em qual branch você está)
>> git push origin kethelyn
```

### Plus

#### Se estiver na Bosch não esqueça de remover suas credenciais que ficaram salvas em:
```bash
>> "Gerenciador de Credenciais"
>> "Credenciais do Windows"
```
