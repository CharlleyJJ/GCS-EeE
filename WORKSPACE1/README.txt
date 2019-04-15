---------------------------------------------
ESTUDOS DE PACOTES E DEPENDÊNCIAS
---------------------------------------------
Ferramentas : Eclipse , Spring tool suite 4 .
---------------------------------------------

Criação de  exemplo do uso de pacotes e dependências fazendo uso de Spring Boot + Maven +IDE eclipse .
Linguagem JAVA.

( não há o uso de nenhum banco de dados)

1- Baixe e instale o arquivo Spring Tools 4 Eclipse  https://download.springsource.com/release/STS4/4.2.0.RELEASE/dist/e4.11/spring-tool-suite-4-4.2.0.RELEASE-e4.11.0-win32.win32.x86_64.zip
( qualquer problema com o arquivo ir para o site https://spring.io/tools )

2- Crie o próprio projeto no site do Spring Tools ---> https://start.spring.io/  
(Aqui vc seleciona os pacotes de dependencias e baixa eles diretamente em seu projeto , NOTA: "Selecionar apenas dependências para o pacote WEB.")

3- O arquivo gerado do Projeto criado com as dependências deverá estar dentro da pasta do projeto criado ao inicializar o Spring Tools Suite 4.

Como segue a Figura 1 : (estará na pasta do projeto )

4- Basta clicar na pasta e navegar até os 2 controladores criados ( PessoaController e ProdutoController), compilar e executar eles . 

é possível acessar os resultados diretamente no navegar local pelas portar 8080 , exemplo : http://localhost8080/api/pessoa ou http://localhost8080/api/produto .

Também foi feito um teste fazendo um uso da aplicação POSTMAN (Tanto o app quanto a extensão no próprio navegador funciona).


