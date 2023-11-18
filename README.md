# Enquete Web

![image](https://github.com/htadmg/EnqueteWeb/assets/124289385/06b768ca-38f0-417d-9a0f-e4fffd0f6a2c)

## Descrição do Projeto
Este projeto consiste em um curso de criação de uma aplicação web para realização de enquetes. O exemplo apresentado inclui uma aplicação simples usando ASP.NET Core para criar uma enquete sobre a disposição das pessoas para fazer uma viagem sem volta para Marte. A aplicação permite que os usuários respondam à enquete, visualize os resultados parciais e retorna ao início.

## Tecnologias Utilizadas
- **Linguagem de Programação:** C#
- **Framework:** ASP.NET Core
- **Bibliotecas e Ferramentas Utilizadas:**
    - Microsoft.AspNetCore.Mvc
    - Bootstrap 5
    - HTML/CSS
    - Razor (para a renderização de páginas)
  
## Estrutura do Projeto
- **Models:**
    - `Resposta.cs`: Define o modelo para as respostas à enquete, incluindo validações para os campos Nome, Email e Resposta (Sim/Não).
    - `Repositorio.cs`: Simula um repositório de dados, armazenando e fornecendo respostas de exemplo para a enquete.

- **Controllers:**
    - `HomeController.cs`: Controlador principal que gerencia as rotas e a lógica da aplicação, incluindo métodos para renderizar a página inicial, responder à enquete, exibir resultados parciais, entre outros.

- **Views:**
    - `Index.cshtml`: Página inicial da enquete, permitindo que os usuários respondam ou vejam os resultados parciais.
    - `Responder.cshtml`: Página para responder à enquete, onde os usuários preenchem seus nomes, e-mails e selecionam sua resposta (Sim/Não).
    - `Resultado.cshtml`: Página que exibe os resultados parciais da enquete.
    - `Obrigado.cshtml`: Página de agradecimento exibida após o usuário responder à enquete.

## Execução do Projeto
Para executar este projeto:
1. Certifique-se de ter o ambiente de desenvolvimento ASP.NET Core configurado.
2. Clone o repositório e abra o projeto em sua IDE preferida.
3. Execute a aplicação, verifique se todas as dependências estão instaladas.
4. Acesse a aplicação por meio do navegador web e interaja com as diferentes funcionalidades oferecidas pela enquete.

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para propor melhorias, reportar problemas ou enviar solicitações de novos recursos.

## Autor
Este projeto foi desenvolvido por [Agata Domingues Farias](https://www.linkedin.com/in/agatadominguesfarias/) como parte de um estudo prático.
## Observações
- Este readme serve como documentação básica para o curso e não abrange todos os detalhes do desenvolvimento web com ASP.NET Core.
- Para uma compreensão mais aprofundada sobre o desenvolvimento de aplicações web com ASP.NET Core, recomenda-se consultar a documentação oficial e outros recursos educacionais.
