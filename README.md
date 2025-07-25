# Calculadora Financeira em JavaScript (VanillaJS) e Bootstrap

Agora você pode controlar seus lucros e gastos apenas pelo seu computador com a calculadora financeira em JavaScript desenvolvida por mim.

1. Instalação
2. Configurando Categorias
3. Como adicionar dados financeiros
4. Como excluir um dado errado
5. Como foi programado a calculadora em JavaScript


- - - 

# 1. Instalação

Apenas faça um gitclone em sua máquina local ou baixe o arquivo index.html e execute.

# 2. Configurando Categorias

As categorias são incrementadas a cada vez que você preenche alguma sem selecionar uma já existente, se não, o dado é populado na selecionada.

# 3. Como adicionar dados financeiros

Basta preencher os campos de input e textarea com o nome, valor, se foi lucro ou despesa, o motivo e apertar em salvar. O dado será visivel apenas no intervalo de data selecionado para filtro.

# 4. Como excluir um dado errado

Use o filtro de busca para encontrar o dado e aperte na lixeira, isso fará com que o mesmo seja excluído.

# 5. Como foi programado a calculadora em JavaScript

A calculadora armazena os dados em JSON e na LocalStorage do navegador. Por isso, caso você exclua os dados armazenados no navegador você também irá perder os dados da suas despesas e lucros da calculadora.