# Organizando git e suas chaves ssh para trabalhos profissionais

Arquivo localizado na pasta HOME do seu usuário

ex.: /home/bcl-lab/.gitconfig

### .gitconfig
```
[user]
  email = "seu email pessoal"
  name = "seu nome"

[init]
  defaultBranch = main

[includeIf "gitdir:<caminho para a pasta de trabalho>"]
  path = <caminho e nome da sua chave ssh>
```

---

Arquivo localizado na sua pasta de trabalhos profissionais

Ex.: ~/Microsoft/.gitconfigForMicrosoft

### .gitconfigForMicrosoft

```
[user]
  name = "Nome do seu usuário"
  email = "email de trabalho"

[core]
  sshCommand = ssh -i ~/.ssh/<nome da sua chave ssh>
```

###
