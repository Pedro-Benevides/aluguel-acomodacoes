# Airbnb-clone
Projeto de desenvolvimento web para a matéria de Linguagem de Programação III do 4º semestre do período letivo de 2022.1 da Universidade do Estado da Bahia (UNEB).
Autores: Pedro Victor Santana Benevides e Rafael R C Cruz.

# Tecnologias
Desenvolvido em php 8.1 mais banco de dados MySQL, utilizando o MySQL Workbench 8.0 CE e xampp para conexão com servidores.

# Build da Aplicação
1. Coloque os arquivos do projeto em um subdirétorio no xampp htdocs folder
2. Inicialize o servidor MySQL pelo painel de controle do xampp
3. Crie uma conexão com o banco de dados no MySQL Workbench
4. Utilize o script de build presente em database/migrations para criar as tabelas do sistema
5. Crie o arquivo env.php, a partir do env.example.php, com as credenciais da conexão criada

<h2 id="variaveis-ambiente">Variáveis de Ambiente</h2>

|Variável|Descrição|Valor Padrão|
|--------|---------|------------|
|DB_DATABASE|Nome da conexão no banco de dados|airbnb-clone|
|DB_HOSTNAME|Endereço do servidor do banco||
|DB_PORT|Porta de acesso ao servidor||
|DB_USER|Usuário de acesso||
|DB_PASSWORD|Senha de acesso||

7. Inicialize o servidor Apache, também pelo xampp
