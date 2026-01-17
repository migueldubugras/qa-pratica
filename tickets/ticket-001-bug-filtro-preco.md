# Título do problema
Ao aplicar o filtro de preço na Amazon Brasil definindo valor mínimo de R$50 e máximo de R$100, alguns produtos exibidos na lista de resultados ultrapassam o valor máximo configurado no filtro.

## Descrição


## Passos para reproduzir
1.Acessar https://www.amazon.com.br
2.Pesquisar por “mouse gamer”
3.Na barra lateral esquerda, aplicar o filtro de preço:
-Mínimo: R$50
-Máximo: R$100
4.Rolar a página de resultados
5.Observar que produtos acima de R$100 continuam sendo exibidos

## Resultado atual
Produtos acima do limite máximo de R$100 aparecem entre os resultados, como um mouse exibido por R$101,06.

## Resultado esperado
Somente produtos com preço dentro da faixa selecionada (R$50 a R$100) deveriam aparecer na lista de resultados.

## Impacto
Esse comportamento pode confundir o usuário e reduzir a confiança na utilização dos filtros durante a busca por produtos.

## Classificação
- Tipo: Bug funcional
- Severidade: Média
- Prioridade: Média

## Ambiente
- Navegador: Chrome 142
- Sistema: Windows 11
- Resolução: 1920×1080
- Login: Não
