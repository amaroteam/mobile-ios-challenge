# AMARO iOS challenge
In this exercise, the proposed challenge is to create a catalogue app that displays [AMARO](https://amaro.com/)'s all-time *best-sellers*.

## A few guidelines
* The app must read product data from [this mocked products API](http://www.mocky.io/v2/59b6a65a0f0000e90471257d).
* All products from the resource must be displayed.
* You may use any third-party libraries as you see fit.
* In case you need any help, feel free to search for reference materials on Google or ask your friends, but do not ask them to work on the challenge for you, which is obviously unethical behaviour.

## Basic requirements
For each product item, the following information should be displayed:
* Image
* Name
* Price
* Promotion status (on sale or not)
* Promotional price (if available)
* Available sizes
* The user should be able to add products to the cart
* The user should be able to open the cart, and see each added product
* You must use Swift as the main language

## Additional requirements
* If you had no problems until here, why not make the user capable of removing a product, and editing the quantities of each product in the cart?
* Don't forget to show the total payment amount on the cart!
* Was it easy until now? What about adding a filter to show only the items that are on sale (`on_sale`)?
* Some products lack a complete size grid (sizes are out of stock). Display only the sizes that are in stock.
* We all enjoy clean, comprehensible and testable code, don't we? This is a major plus, so refactor your code if necessary and add unit tests where possible.

## Examination criteria
* The code will be examined according to following main criterias: semantics, structure and legibility.
* Organization and comments of the *git* commit history will be considered.
* We're looking for an experienced Swift developer who also knows how to build a beautiful UI, so this is your opportunity to show us your knowledge in both areas.

-------------------------------

# AMARO iOS challenge
O objetivo do desafio é construir um app de catálogo para alguns dos *best-sellers* da história da [AMARO](https://amaro.com/).

## Algumas regras
* O app deve consumir o serviço [products service](http://www.mocky.io/v2/59b6a65a0f0000e90471257d) como uma API Rest.
* Todos os produtos carregados do serviço devem ser exibidos no catálogo.
* É permitido utilizar quaisquer bibliotecas que você desejar.
* Se você estiver com dúvidas, busque por referências no Google, ou pergunte para amigos. Mas não peça para eles resolverem o desafio para você.

## Requisitos
Para cada item de produto, as seguintes informações devem estar presentes no catálogo:
* Imagem
* Nome
* Preço
* Status de promoção
* Preço promocional (se houver)
* Tamanhos disponíveis
* Deve ser possível adicionar produtos ao carrinho do usuário.
* Deve ser possível verificar quantos e quais produtos do carrinho.
* Utilizar Swift como linguagem principal.

## Diferenciais
* Foi moleza? Então permita que os usuários interajam com o carrinho removendo produtos e alterando a quantidade de itens.
* Ah! Não se esqueça de mostrar o valor total do carrinho.
* Achou o teste até aqui fácil? Que tal adicionar um filtro para mostrar só os produtos em promoção (`on_sale`)?
* Alguns produtos não tem sua grade completa (todos os tamanhos disponíveis). Mostre somente os tamanhos em estoque.
* Todos gostamos de código limpo e testável, certo? Então esse é um grande diferencial.

## Critérios de avaliação
* O código será avaliado considerando: semântica, estruturação, legibilidade, tamanho, entre outros fatores.
* O histórico do *git* também será avaliado.
* Estamos buscando um desenvolvedor iOS que saiba montar um *layout*  bonito e que também saiba programar em Swift, por isso aproveite a oportunidade para nos mostrar que você tem conhecimento nas duas áreas.
