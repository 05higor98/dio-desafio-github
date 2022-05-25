# Introdução ao Git e ao GitHub

## Gerando cave SSH

- ssh-keygen -t ed25519 -C "email"
- Criar uma senha
- cd /caminho da pasta criada/
- -ls
- -cat id_es25519.pub
- Copiar a chave gerada, ir para o GitHub, clicar em "New SSH", colocar título e a chave gerada
- eval $(ssh-agent -s)
- agent pid
- ssh-add id_25519
- digiar senha
