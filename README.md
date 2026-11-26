# Tio do Pavê

Site de uma loja de pavês feito com HTML e CSS. O visitante vê os produtos, monta o carrinho e preenche um formulário de entrega.

## Páginas

- `index.html`: página inicial
- `produtos.html`: lista de produtos com preço e botão de compra
- `carrinho.html`: itens escolhidos, resumo do pedido e formulário

## Estrutura

```
index.html
produtos.html
carrinho.html
css/
  style.css        estilos gerais
  carrinho.css     estilos do carrinho
  formulario.css   estilos do formulário
fonts/
  Super Chips.ttf  fonte dos títulos
```

## Como rodar

Abra o `index.html` no navegador. Não precisa instalar nada.

## Visual

- **Fonte dos títulos:** Super Chips
- **Cores:** vermelho `#9e2a2b`, bege `#e9d8a6`, amarelo `#fff3b0`, laranja `#e09f3e`, azul-esverdeado `#335c67`

## Carrinho

Aumenta e diminui a quantidade, remove itens e recalcula o total sozinho. O frete é fixo e fica na constante `FRETE` do script em `carrinho.html`.

## Limitações

- O formulário ainda não envia os dados para lugar nenhum.
- Os produtos do carrinho são exemplos fixos.