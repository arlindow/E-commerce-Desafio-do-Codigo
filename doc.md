--------
Git 
curso: 
git status 
git add .
git commit -m "edit curso" 
git push origin curso:main

---------

1. pensar o problema.
2. dividir em partes menores. 
3. modelar os dados.  
4. transformar em algoritmos simples usando pseudocódigo e diagramas conceituais.

1) Entenda o problema — requisitos essenciais

Antes de codar, pergunte-se:

* O que o usuário precisa fazer? (ver produtos, buscar/ordenar, adicionar ao carrinho, finalizar compra)

* Quais dados preciso representar? (produtos, carrinho, pedido, cliente)

* *Quais restrições existem? (estoque, validação de campos, persistência local)

* *Quais operações são essenciais? (renderizar lista, filtrar, ordenar, adicionar, alterar quantidade, calcular total, persistir)

2) Divida em módulos lógicos (top-down)

Modelo de dados — como estruturar produtos, carrinho e pedido.

Armazenamento — onde guardar o estado (ex.: memória + localStorage).

Renderização — transformar estado em interface (DOM).

Interação / Eventos — ouvir cliques, inputs, formulários.

Regras de negócio — limitar por estoque, calcular totais, validações.

Persistência / Sincronização — salvar/recuperar o carrinho.

Checkout — validar dados do cliente e processar ordem (simulado).

3) Modelo de dados (ponto fundamental)

Pense nos dados como objetos simples:

Produto:

produto = {
  id: string,
  nome: string,
  preco: number,
  estoque: integer,
  imagem: string
}



