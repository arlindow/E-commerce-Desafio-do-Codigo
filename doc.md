## Criar e trocar de branch ao mesmo tempo ## 
git checkout -b nome-da-branch

## Atualize a main com as mudanças do curso: ## 
# Quando estiver no curso
git checkout main
git merge curso

# git remote add origin https://github.com/arlindow/E-commerce-Desafio-do-Codigo

# git push --set-upstream origin curso

## Vá para a branch principal e atualize-a
git checkout main
git pull origin main

## Vá para a sua branch casa
git checkout casa

# Atualize a branch casa com as novidades da main
git merge main

### Quando chegar em casa: ### 

git checkout main
git pull origin main
git checkout casa
git merge main


Depois de trabalhar:

git add .
git commit -m "Alterações feitas em casa"
git checkout main
git merge casa
git push origin main casa



1. pensar o problema.
2. dividir em partes menores. 
3. modelar os dados.  
4. transformar em algoritmos simples usando pseudocódigo e diagramas conceituais.

1) Entenda o problema — requisitos essenciais

Antes de codar, pergunte-se:

# O que o usuário precisa fazer? (ver produtos, buscar/ordenar, adicionar ao carrinho, finalizar compra)

# Quais dados preciso representar? (produtos, carrinho, pedido, cliente)

# Quais restrições existem? (estoque, validação de campos, persistência local)

# Quais operações são essenciais? (renderizar lista, filtrar, ordenar, adicionar, alterar quantidade, calcular total, persistir)

