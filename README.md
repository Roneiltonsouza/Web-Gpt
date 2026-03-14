# Web GPT - Sistema de Autenticação Segura

Este projeto utiliza um sistema de **ID Único de 10 dígitos** com validação direta em API (NetBase/Firebase) para garantir que apenas usuários cadastrados acessem o sistema.

## Funcionalidades
* **Geração de ID Único:** Criação de conta via ativação na nuvem.
* **Trava de Segurança:** O sistema valida o ID no servidor antes de conceder acesso.
* **LED de Estado:** Indicador visual de ativação (somente após sucesso no banco).
* **Persistência:** Sincronização de dados via API.

## Como usar
1. Abra o `index.html`.
2. Clique no LED para gerar e registrar um novo ID de 10 dígitos no servidor.
3. O LED ficará verde apenas após a confirmação do banco de dados.
4. Para logar em outros dispositivos, basta digitar o seu ID de 10 dígitos no campo de login e clicar em "LOGIN VALIDAÇÃO".

## Tecnologias
* HTML5 / CSS3 / JavaScript
* PeerJS para comunicação P2P
* API NetBase/Firebase para persistência de dados
