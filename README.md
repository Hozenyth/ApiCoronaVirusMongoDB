
<h1>Api usando banco de dados em nuvem MongoDB Atlas</h1>
 
 Esse projeto foi feito através do Visual Studio .NET 5.0. Referência do projeto: <a href="https://github.com/gabrielfbarros/dotnet-mongo"> 
      Curso Digital Innovation One
 </a>
 O mongoDB é um banco de dados não relacional (NoSQL) ele é utilizado pra registro de documento onde as tabelas são chamadas de coleção e a coluna de atributos. Nesse projeto foi utilizado o MongoDB Atlas onde os dados são armazenados em nuvem podendo assim ser acessado de qualquer lugar onde se tenha uma conexão com a internet.
 
 <h2>PASSO A PASSO DO CADASTRO AO MONGODB ATLAS.</h2>
 
  •	Criar um cluster. No caso foi criado um banco na opção gratuito. <br>
   <img src="MongoDB1.png">
  
  •	Criar um usuário em Network Acess com nome e senha ler e escrever no banco. <br>
  <img src="MongoDB2.png">
  
  •	Adicionar um IP no caso foi usado permitir acesso de qualquer lugar. <br>
   <img src="MongoDB3.png">
  • Ir em Clusters e conectar ao cluster criado. Escolher um método Connect Your Aplication, selecionar o driver C# NET e a versão. Copiar o link de acesso. OBS.: No programa no arquivo appsettings.json o link de acesso deve ser substituido  com o password e o MyFirstDatabase. <br>
  
   <img src="MongoDB4.png"> <br>
    <img src="MongoDB5.png">
  
 
