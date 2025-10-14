
###
git checkout main
git pull origin main
git checkout casa
git merge main
###

###
Depois de trabalhar:

git add .
git commit -m "Alterações feitas em casa"
git checkout main
git merge casa
git push origin main casa
###


1. pensar o problema.
2. dividir em partes menores. 
3. modelar os dados.  
4. transformar em algoritmos simples usando pseudocódigo e diagramas conceituais.

1) Entenda o problema — requisitos essenciais

Antes de codar, pergunte-se:

O que o usuário precisa fazer? (ver produtos, buscar/ordenar, adicionar ao carrinho, finalizar compra)

Quais dados preciso representar? (produtos, carrinho, pedido, cliente)

Quais restrições existem? (estoque, validação de campos, persistência local)

Quais operações são essenciais? (renderizar lista, filtrar, ordenar, adicionar, alterar quantidade, calcular total, persistir)

