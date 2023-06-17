# Projeto: Varredor De Preços (Selenium)
Projeto básico utilizando a biblioteca Selenium para coleta de dados.

Nesse projeto, utilizei a biblioteca Selenium para coletar dados e salvá-los num arquivo .CSV, para que posteriormente fossem colocados em planilha .xlsx para consulta.

Nesse caso, a tarefa era entrar em 3 sites diferentes:
[Eatveg](https://sitepreco1.netlify.app/),
[FreshShop](https://sitepreco2.netlify.app/) e
[Ogani](https://sitepreco3.netlify.app/)
e consultar neles o valor de um produto em específico (abacate). Após a coleta dos valores de abacate em cada um dos sites, transforma os valores num arquivo .CSV para que sejam visualizados em uma planilha.

## Como utilizar:

1. Baixe e execute o arquivo
2. Após executar o arquivo, ele realizará a varredura nos sites descritos e irá criar um arquivo .csv com os dados coletados
3. Com o arquivo .csv já baixado, abra o excel, vá em novo arquivo
4. Com o arquivo em branco aberto, selecione a aba dados, e na opção "obter dados externos" selecione "de texto" 
![Captura de Tela (99)](https://github.com/Lucas-Lobao/Projeto-SeleniumVarredorDePrecos/assets/107892354/c1930de0-f81f-4280-bed0-d334e17e79fb)
5. Em seguida, será aberto o assistente de importação de texto do Excel. Na primeira etapa selecione "delimitado" e clique em "avançar".
6. Na segunda etapa, desmarque todas as opções e deixe somente a opção "vírgula" marcada ![Captura de Tela (102)](https://github.com/Lucas-Lobao/Projeto-SeleniumVarredorDePrecos/assets/107892354/7f037de2-8f36-4f26-bcfe-4f01d56ca80c)
7. Na terceira e última etapa, selecione "texto" e clique em "concluir" 
![Captura de Tela (101)](https://github.com/Lucas-Lobao/Projeto-SeleniumVarredorDePrecos/assets/107892354/f161f488-154d-4637-96a2-1367d7b3dbfd)
8. A seguir, aparecerá a janela "importar dados" e basta clicar em "ok"
9. Este deverá ser o resultado, caso contrário, você formatou a importação de dados de forma incorreta. ![Captura de Tela (103)](https://github.com/Lucas-Lobao/Projeto-SeleniumVarredorDePrecos/assets/107892354/1c1a5733-3e1c-462f-ad6e-0c794a4d158d)
