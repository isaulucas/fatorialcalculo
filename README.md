# fatorialcalculo

01. Desenvolva uma aplicação que deve estar empacotada em um arquivo jar que ao ser invocado deve ser passado um valor inteiro como argumento, calcular o fatorial do número passado e apresente o resultado na tela. (1 pt)

Exemplo:
   $ java -jar app.jar 5
   120
   
   $ java -jar app.jar 8
   40320    

02. Faça uma nova versão da aplicação anterior de forma que utilize um banco de dados para armazenar os fatoriais parciais calculados de forma a evitar novos cálculos. (2pt)

Exemplo:
   5! = 5 x 4 x 3 x 2 x 1 = 120
   6! = 6 x 5! = 6 x 120 = 720
   4! = 4 x 3 x 2 x 1 = 24
   
Quando é solicitado para calcular 5! deve-se inserir no banco de dados o fatorial de 1, 2, 3, 4 e 5. De forma que ao ser solicitado o fatorial de 6 seja possível consultar os fatorial parciais já solicitados. Desta forma o cálculo dos fatoriais se torna mais eficiente ao se utilizar um valor já armazenado em tabela.
   
No banco de dados, a tabela deve conter duas colunas: numero e fatorial. Número corresponde ao inteiro cujo fatorial está na coluna fatorial.

A aplicação deve ser capaz de calcular fotoriais de grandes números, utilize o tipo de dado BigInteger

Trabalho desenvolvido por: Isaú Lucas e Liza Magalhães
