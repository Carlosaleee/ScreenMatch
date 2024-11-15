
# ScreenMatch

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

ScreenMatch é uma aplicação Java voltada para a busca e gestão de informações sobre filmes e séries, permitindo que usuários explorem e obtenham dados sobre produções cinematográficas.

## Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Funcionalidades](#funcionalidades)
- [Instalação](#instalação)
- [Como Usar](#como-usar)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Sobre o Projeto

ScreenMatch foi desenvolvido como parte de um estudo em Java, com foco em entender e aplicar conceitos como manipulação de APIs, orientação a objetos, e desenvolvimento de aplicações desktop. O projeto também integra boas práticas de desenvolvimento, como modularização e tratamento de exceções.

## Funcionalidades

- Busca de filmes e séries por título.
- Exibição de detalhes, como sinopse, ano de lançamento, classificação, e duração.
- Listagem e filtro de produções favoritas.
- Integração com uma API de informações de filmes (OMDb API ou similar).

## Instalação

Para rodar este projeto localmente, siga as instruções abaixo:

1. Clone o repositório:
   ```bash
   git clone https://github.com/Carlosaleee/ScreenMatch.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd ScreenMatch
   ```
3. Configure a chave da API de filmes (exemplo: OMDb API) no arquivo de configuração ou diretamente na classe de conexão:
   ```java
   // Exemplo de configuração da chave de API
   private static final String API_KEY = "SUA_CHAVE_API";
   ```
4. Compile e rode o projeto:
   - Se estiver usando uma IDE como Eclipse ou IntelliJ, basta abrir o projeto e executar.
   - Para compilar manualmente, use:
     ```bash
     javac -d bin src/*.java
     java -cp bin Main
     ```

## Como Usar

1. Inicie a aplicação.
2. No menu principal, use a opção de busca para pesquisar filmes ou séries pelo título.
3. Explore as informações dos resultados e adicione favoritos.
4. Acesse a lista de favoritos para ver os filmes e séries salvos.

## Tecnologias Utilizadas

- **Java** - Linguagem de programação principal.
- **OMDb API** - Para informações de filmes (necessita de chave de API).
- **JDBC** - Para integração com bancos de dados, caso o projeto salve informações localmente.
- **JavaFX/Swing** - Interface gráfica (se aplicável).

## Contribuição

Contribuições são bem-vindas! Para contribuir, siga os passos abaixo:

1. Fork o repositório.
2. Crie uma branch para sua feature:
   ```bash
   git checkout -b minha-feature
   ```
3. Commit suas mudanças:
   ```bash
   git commit -m "Adicionei minha nova feature"
   ```
4. Faça o push da branch:
   ```bash
   git push origin minha-feature
   ```
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

---

Feito com ❤️ por Carlos Alexandre.
```

Esse arquivo `README.md` cobre as principais informações sobre o projeto, incluindo o propósito, instruções de instalação e execução, além de diretrizes para contribuições. Ele ajuda a documentar o projeto de forma clara e acessível, facilitando o entendimento para outros desenvolvedores.
