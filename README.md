<h1>Projeto de Consultas - Aplicativo de Gerenciamento de Consultas</h1>
<h2>Gustavo da Silva Dias RM550820</h2>
Este é um aplicativo simples de gerenciamento de consultas médicas, com funcionalidades para exibir, atualizar e persistir dados utilizando AsyncStorage. O app permite que o usuário visualize suas consultas salvas, atualize informações de consultas e mantenha os dados salvos mesmo após o fechamento do aplicativo.

Funcionalidades
Exibição das Consultas Salvas: A tela inicial exibe uma lista das consultas salvas, permitindo ao usuário visualizar rapidamente suas consultas agendadas.

Atualização da Lista de Consultas: O usuário pode adicionar novas consultas ou editar consultas já existentes diretamente na interface do aplicativo.

Persistência de Dados com AsyncStorage: Todas as consultas são salvas localmente utilizando o AsyncStorage, garantindo que os dados sejam mantidos mesmo quando o aplicativo for fechado.

Tecnologias Utilizadas
React Native: Framework para desenvolvimento de aplicativos móveis.

AsyncStorage: Utilizado para persistir dados localmente no dispositivo do usuário.

Como Rodar o Projeto
Pré-requisitos
Node.js instalado (versão 14 ou superior).

Yarn ou npm.

Expo (caso esteja utilizando Expo para o desenvolvimento).

Passos para Instalação
Clone o repositório do projeto:

bash
Copiar
Editar
git clone https://github.com/seuusuario/nome-do-repositorio.git
Navegue até o diretório do projeto:

bash
Copiar
Editar
cd nome-do-repositorio
Instale as dependências:

bash
Copiar
Editar
yarn install
# ou
npm install
Inicie o servidor de desenvolvimento:

bash
Copiar
Editar
yarn start
# ou
npm start
Abra o aplicativo no seu emulador ou dispositivo físico utilizando o Expo ou outra ferramenta de sua preferência.

Como Funciona
Na tela inicial, o usuário poderá ver a lista de consultas que foram salvas.

O usuário pode adicionar uma nova consulta clicando no botão de adicionar, preenchendo os campos de data, horário, nome do médico e outros detalhes importantes.

Consultas podem ser editadas ou removidas conforme necessário.

Todos os dados inseridos serão salvos no AsyncStorage, garantindo que não sejam perdidos ao fechar o aplicativo.
