### .gitconfig

[user]
  email = "seu email pessoal"
  name = "seu nome"

[init]
  defaultBranch = main

[includeIf "gitdir:<caminho para a pasta de trabalho>"]
  path = <caminho e nome da sua chave ssh>
  
### .gitconfigForJob

[user]
  name = "Nome do seu usuário"
  email = "email de trabalho"

[core]
  sshCommand = ssh -i ~/.ssh/<nome da sua chave ssh>