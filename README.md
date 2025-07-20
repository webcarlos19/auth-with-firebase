# auth-with-firebase

Este projeto demonstra como implementar autenticação de usuários utilizando o Firebase Authentication em uma aplicação React/Next.js. Ele serve como exemplo prático de integração com um backend NoSQL (Firebase) e autenticação segura, ideal para mostrar habilidades em integração de serviços externos e manipulação de dados em tempo real.

## Funcionalidades

- **Login e autenticação de usuários** via Firebase Authentication.
- **Gerenciamento de estado do usuário** com Context API do React (

AuthContext

).
- **Integração com Firebase** usando configuração dinâmica via variáveis de ambiente.
- **Exemplo de uso de NoSQL** (Firebase Firestore pode ser facilmente integrado).
- **Carregamento dinâmico** enquanto o estado de autenticação é verificado.

## Estrutura

- 

src/context/AuthContext.js

: Contexto React para autenticação.
- 

src/firebase/config.js

: Inicialização do Firebase usando variáveis de ambiente.
- `.env`: Armazena as credenciais do Firebase (não incluídas no repositório público).

## Como usar

1. Configure suas credenciais do Firebase no arquivo `.env`.
2. Instale as dependências:
   ```sh
   npm install
   ```
3. Inicie o projeto:
   ```sh
   npm run dev
   ```

## Observações

- **Segurança:** As credenciais do Firebase devem ser mantidas apenas no `.env` e nunca expostas publicamente.
- **Extensível:** Pode ser facilmente adaptado para incluir Firestore, Storage, ou outros serviços do Firebase.