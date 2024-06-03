# Aleatórios

### O dia do vinho

Uma das situações mais engraçadas que já presenciei/criei. Trabalhei em uma empresa X, que oferecia um sistema SAAS de loja virtual. Várias empresas, inclusive grandes empresas, utilizavam esse sistema.

Essa empresa tinha um diferencial de ser muito próximo dos clientes contratantes da plataforma.

Certo dia, precisei fazer uma alteração para um cliente que vendia vinhos. Foi necessário utilizar uma estrutura condicional na API para solucionar o problema (ou criar mais um) para esse cliente. Era algo mais ou menos assim:

```php
if ($storeId = 123) {
...
}

```

Subi a alteração para a produção. Foi no “confia” mesmo.

> "Minha loja está aparecendo vinhos", ligou um cliente que tinha uma loja de roupas.


Vários clientes relatando a mesma coisa: todas as lojas vendendo vinhos. Não que seja ruim, mas também não é bom.

Qual o problema do código apresentado acima? O sinal de `=` quebrando as pernas.

Um descuido por pressa ou falta de atenção fez com que eu subisse esse pequeno bug, fazendo todas as lojas comercializarem vinho. Lojas de roupas vendendo vinho, lojas de lingerie vendendo vinho, lojas de skate vendendo vinho…

Esse dia na empresa foi chamado de `"Dia do Vinho"`. Acho que até hoje esse dia deve estar marcado como história na empresa.


