# plataforma-de-orientacao


Plataforma de Orientação Acadêmica
Este projeto consiste em uma interface web interativa para orientação acadêmica, voltada para estudantes universitários. A aplicação oferece um canal automatizado de atendimento por meio da integração com o Botpress, permitindo o acesso rápido a informações sobre procedimentos acadêmicos como trancamento, matrícula, solicitações de documentos e regulamentos.

Objetivo
Prover uma ferramenta de autoatendimento que facilite o acesso a informações acadêmicas institucionais, reduzindo a demanda direta sobre a equipe da secretaria e otimizando a comunicação com os alunos.

Tecnologias Utilizadas
Vite – Empacotador de módulos utilizado para desenvolvimento rápido e moderno (versão recomendada: ^4.0.0)

React – Biblioteca JavaScript para construção da interface do usuário (versão detectada: 18.3.1)

Botpress Webchat v3 – Widget de chatbot para comunicação com agentes automatizados

Google Analytics (gtag.js) – Utilizado para rastreamento de interações e simulação de novos usuários via client_id

CSS customizado – Aplicado com base em variáveis CSS modernas e classes utilitárias

Estrutura do Projeto
bash
Copy
Edit
chatbot-pronto-vite/
├── index.html           # Entrada principal da aplicação (contém os scripts do Botpress e Google Analytics)
├── index.js             # Script principal empacotado (React + lógica de montagem do chatbot)
├── index.css            # Estilização com Tailwind ou similar
├── /assets              # (Gerado pelo Vite) Recursos empacotados
Requisitos para Execução
Node.js: versão 18.x ou superior

Gerenciador de pacotes: npm ou yarn

Ambiente local recomendado: Vite + React + navegador compatível

Instruções para Instalação e Execução Local
Caso o projeto original com arquivos de desenvolvimento (como package.json) esteja disponível:

bash
Copy
Edit
# Instalar dependências
npm install

# Rodar servidor de desenvolvimento
npm run dev

# Acesse a aplicação em
http://localhost:5173
Caso tenha apenas os arquivos empacotados (como neste repositório), hospede os arquivos em um servidor local com suporte a HTML estático (ex: Live Server ou Vite Preview).

Funcionalidades
Renderização instantânea do chatbot ao carregar a página

Medição de interações com o chatbot via Google Analytics

Interface responsiva, centralizada e compatível com dispositivos móveis

Código modular e preparado para integração com backends externos

Observações
O sistema foi desenvolvido com fins acadêmicos e pode ser adaptado para uso institucional.

A versão atual não contém backend; a lógica de conversa é toda gerenciada pelo Botpress externo.

O rastreamento de usuários é simulado forçando um novo client_id a cada reload.
