- # projeto-crud-simple
+ 
+ Crud simples desenvolvido para teste
+ 
+ ## O que utilizei para desenvolver:
+ 
+ - Node.js
+ - Express
+ - JSON (para retornar os dados);
+ - Insomnia (para testar a API);
+
+ ## Testando a Aplicação no Insomnia: 
+
+ Rota             | HTTP         | Descrição          |
+ ---------------- |------------- |------------------- |
+ /projects        |  GET         | Selecionar Todos   | 
+ /projects/:id    |  GET         | Selecionar por Id  |
+ /projects/       |  POST        | Criar Id           |
+ /projects/:id    |  PUT         | Alterar Id         |
+ /projects/:id    |  DELETE      | Excluir por Id     |
+
+ ## Executar a API localmente
+ 
+ Iniciar => Clone o repositório do projeto na sua máquina e instale as dependências. 
+ É necessário que o **Node.Js** já tenha sido instalado.
+ Inicie o terminal na pasta do projeto
+ Na mesma tela do terminal, basta iniciar o index para o projeto ser executado localmente. 
+ 
+ node src/index.js
+ 
+ No Insomnia abra a página da aplicação em 'http://localhost:3333/projects. Dessa forma a aplicação será executada de maneira local na sua máquina. 
+ 
+ 

