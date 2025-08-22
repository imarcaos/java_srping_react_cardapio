# Java Spring - API Cardápio

Projeto para estudo do Java Spring, desenvolvendo uma API utilizando uma base de dados PostgreSQL.

Iniciado: 2025-08-22

## Ferramentas:

- OpenJDK 21
- IntelliJ
- PostgreSQL
- 


## Iniciando o projeto no site Spring Initializr
Nome do projeto: cardapio_java_spring_react
Iniciar um projeto no site [Spring Initializr](https://start.spring.io/).
![alt text](spring-initializr.png)


## Carregando o projeto para dentro do IntelliJ
- Download e descompactar na pasta onde irá ficar o nosso projeto.
- Importar o projeto para o IntelliJ File > Open > "buscar a pasta do projeto"

## Desenvolvendo o projeto
- No projeto Botão Direito (BT-DT) em cima src > main > java > com.example.cardapio_java_spring_react > "New Java Class" > Name: FoodController
- Dentro da Classe criada:
  - vamos alterar o caminho do package para "controller", parar o rato em cima do erro no caminho do package e clicar em more actions > "move to package".
  - Adicionar duas anotações: @RestController - para indicar que esta classe é um controlador e @RequestMapping para adicionar um endpoint "food"
  - Vamos criar um método para pegar todos os dados dentro da nossa Base de Dados (BD) "public void getAll()" e precisamos indicar para mapear o nosso método com a anotação "@GetMapping"
  - Agora precisamos conectar com a nossa BD, mas para isso precisamos adicionar mais algumas bibliotecas(dependências) na nossa aplicação o Postgress e o JPA.
    - Adicionar as duas dependências através do Spring Initializr, ir em Explore e copiar o código das dependências para o nosso arquivo "pom.xml"
  - Rodar a aplicar até aqui para ver se está tudo "ok".
  - 15:15

- Vídeo que segui para este estudo: [Aplicativo Fullstack Java Spring e React](https://www.youtube.com/watch?v=lUVureR5GqI)

## em desenvolvimento para estudo

