No terminal, estando na raiz do repositório e com os ficheiros já salvos:

# adiciona tudo que mudou (novos, modificados, removidos)
git add .            # ou `git add -A`

# cria um commit com uma mensagem descritiva
git commit -m "Minha mensagem de commit"

# envia a branch actual para o remoto (origin/main por exemplo)
git push -u origin main

# se as alterações forem apenas em ficheiros já rastreados, dá para combinar add+commit em:
git commit -am "mensagem"   # atalho: adiciona+commita modificações
git push

# 1. marca tudo que mudou (novos, modificados ou removidos)
git add .            # ou `git add -A`

# 2. cria um commit com uma mensagem descritiva
git commit -m "Minha mensagem de commit"

# 3. envia para o repositório remoto (substitua `main` se usar outra branch)
git push -u origin main

# — alternativa para modificações em arquivos já versionados:
git commit -am "mensagem"   # combina add + commit
git push