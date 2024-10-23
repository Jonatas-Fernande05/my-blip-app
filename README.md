# Aplicação Web de Exibição de Contatos e Conversas - Blip Chatbot
## Este projeto é uma aplicação web que exibe contatos e conversas de um chatbot utilizando a API do Blip. O objetivo é fornecer uma interface simples e intuitiva para gerenciar as interações entre o bot e os usuários. A aplicação permite ao usuário visualizar uma lista de contatos e acessar conversas específicas, tudo de maneira paginada e organizada.

## Funcionalidades Principais
### Autenticação com API Key:

O usuário deve inserir uma chave de API do Blip para autenticar a aplicação.
A chave de API é validada e armazenada de forma segura para uso posterior em outras requisições.
Listagem de Contatos:

Após o login, o usuário é redirecionado para a página principal, onde uma lista de contatos é exibida.
A listagem é paginada, permitindo ao usuário visualizar um número configurável de contatos por página.
Cada contato exibido pode ser selecionado para visualizar as conversas correspondentes.
Exibição de Conversas:

Ao selecionar um contato, o usuário é redirecionado para uma página que exibe a conversa completa com esse contato.
Todas as mensagens trocadas com o contato são exibidas sem paginação, permitindo uma visão clara e contínua das interações.
Tecnologias Utilizadas
A aplicação foi construída utilizando tecnologias modernas e eficientes para proporcionar uma boa experiência de desenvolvimento e usabilidade:

## Frontend:

Svelte: Framework JavaScript leve e reativo para construção de interfaces de usuário.
TypeScript: Superset do JavaScript que adiciona tipagem estática ao código.
Tailwind CSS: Framework CSS utilitário para estilização rápida e customizável.

## Backend:

Node.js: Plataforma para construção de aplicações backend em JavaScript.
Express.js: Framework web minimalista para Node.js, utilizado para gerenciar as rotas e a lógica da aplicação.
Firebase Admin SDK: Para autenticação e gerenciamento de dados via Firebase.
Como Rodar o Projeto
Pré-requisitos
Node.js (versão >= 14)
npm ou yarn
Conta no Blip para obter a API Key.
Conta no Firebase para autenticação personalizada.
