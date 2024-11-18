# Projeto-ALFA-
Este é um projeto dedicado a matéria de Mobile e Programação Web II

1. Configuração de Desenvolvimento Documentado Ferramentas e Tecnologias
Frontend : HTML, CSS, JavaScript
Backend : API RESTful (Node.js)
Banco de Dandos: MySQL

API Fetch : Utilização da API Fetch para comunicação sincronizada entre o frontend e o backend.
Armazenamento : localStoragepara armazenar informações de autenticação do usuário.
Configuração de Desenvolvimento
Requisitos :
Editor de Código/IDE : Visual Studio Code, Sublime Text ou qualquer editor de texto que suporte HTML/CSS/JavaScript.
Servidor Local : Servidor Node.js (ou uma alternativa) para rodar ou backend localmente.
Navegador Moderno : Recomendado para suporte à API Fetch e outros recursos modernos do JavaScript.
Configuração do Projeto :

Clonar o repositório do projeto :
bater
Copiar código
git clone <URL do repositório>
cd <diretório do projeto>
Configuração do Backend do Servidor :
-se de que o servidor está rodando na porta adequada (exemplo: localhost:3000).
Iniciar o Servidor :
Inicie o backend do servidor com o comando:
bater
Copiar código
npm start


Caso utilize outra estrutura, substituição pelo comando de proteção.
Executar o Frontend :
Abra o arquivo index.htmlno navegador ou configure um servidor local de desenvolvimento para hospedar o frontend.

2. Definir Cronograma de Versões em 5 Sprints
Sprint 1 (Semana 1) : 
Implementar a estrutura básica do projeto e arquivos principais.
Configurar o localStoragearmazenamento do tipo de usuário.

Sprint 2 (Semana 2) :
Tela inicial, 
Dashboard e Controle de Permissões
Desenvolver uma interface do dashboard e uma lógica de exibição de opções com base no tipo de usuário.
Integrar a verificação localStorageao carregar o dashboard.

Sprint 3 (Semana 3) : Funcionalidade da Reserva
Implemente a funcionalidade de envio de dados de reserva ao servidor usando uma API Fetch.
Exibir confirmações de reserva e logar as informações no console.

Sprint 4 (Semana 4) : Cadastro de Equipamentos
Desenvolver uma interface de cadastro de equipamentos e preparar a comunicação com o backend.
Interrompa o envio padrão do formulário e configure uma estrutura para envio de dados.
Testes de usabilidade e coleta de feedback.

Sprint 5 (Semana 5) : Relatórios e Preparação para Lançamento
Implementar a funcionalidade de busca de relatórios e exibição dinâmica de resultados.
Finalizar a documentação do projeto.
Realizar testes de integração e corrigir bugs.

Lançar a versão 1.0 com a documentação e guias de uso.
4. Definir Backlog Geral
Funcionalidades Principais :
*Login : Implementar envio de dados ao endpoint /logine tratamento de resposta.
Dashboard : Carregar o tipo de usuário localStoragee ocultar/exibir menus.
*Reserva : Envio de dados de formulário de reserva ao endpoint /reservascom confirmação.
Cadastro de Equipamentos : Implementar formulário e enviar dados ao servidor.
*Relatórios : Crie busca por dados e tipo de relatório e exibição de resultados na tela.

Interface do usuário :
Crie estilos CSS para garantir que as telas sejam responsivas.
Melhorar a usabilidade dos formulários e feedbacks de validação.
Armazenamento e Autenticação :
Configure o armazenamento não localStoragepara tipos de usuários.
Implementar lógica de controle de permissões no frontend.
Controle de Acesso :
Implemente o controle de acesso visual no dashboard.js.
Adicionar validação de permissões no backend (etapa futura para segurança).
Melhorias Futuras :
Implemente uma página de perfil do usuário.
Adicionar funcionalidades de logout e redefinição de senha.
Crie registros de atividades para rastrear o uso das funcionalidades.

SPRING 02 
Tela inicial, com telas seguintes
Dashboard e Controle de Permissões
Desenvolver uma interface do dashboard e uma lógica de exibição de opções com base no tipo de usuário.
Integrar a verificação localStorageao carregar o dashboard.

TELA INICIAL 
No inicio temos a tela de login que te leva a um login como professor tem acessor a resevas e pedido de algum equipamento, o login do funcionario permite ele editar e adicionar equipamentos,
os relatorios que aparecemn sao os dias e os equipamentos solicitados.

![login](https://github.com/user-attachments/assets/4a047ba6-7f2f-4f37-91b4-f40753f64251)

INICIAL

![image](https://github.com/user-attachments/assets/67236a8a-b409-4b44-906a-9f0794008590)

RESERVA 

![image](https://github.com/user-attachments/assets/1a65d1aa-13ca-47c5-ade8-de9c7d3b6a9b)

BANCO DE DADOS DA RESERVA

![image](https://github.com/user-attachments/assets/4a615f4e-ab57-470e-976d-a113e522223c)

CADASTRO DE EQUIPAMENTOS 

![image](https://github.com/user-attachments/assets/a27a8e9b-8bb8-4953-a8b5-a09ec1f407aa)

BANCO DE DADOS EQUIPAMENTOS 

![image](https://github.com/user-attachments/assets/291daea6-fb32-48b3-bf0d-114f4dd8611c)

RELATÓRIOS

![image](https://github.com/user-attachments/assets/b5b0569a-18f6-4ab6-8a75-eeaa9c0a58d2)

