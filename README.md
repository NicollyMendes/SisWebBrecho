# 📦 SisWebBrecho – Sistema de Gerenciamento de Brechó (Isabella Calçados)
Este é um sistema web desenvolvido como Progressive Web App (PWA) para o gerenciamento de estoque, cadastro de clientes e vendas de um brechó de pequeno porte, chamado Isabella Calçados. O projeto foi criado como evolução de uma versão desktop anterior, migrando para uma solução web moderna e acessível.

## 🚀 Tecnologias Utilizadas
Frontend: React

Backend: Django (REST API)

Banco de Dados: SQLite

Versionamento: GitHub

Design: Figma (protótipos)

Comunicação: Discord e WhatsApp

## 📋 Funcionalidades Principais
✅ Cadastro de clientes (com validação de CPF)
✅ Cadastro de produtos (com ajuste dinâmico de tamanho conforme categoria)
✅ Realização de vendas, atualizando automaticamente o estoque
✅ Visualização de clientes, produtos e vendas
✅ Regras de negócio para garantir integridade dos dados e consistência nas operações
✅ Interface intuitiva, adaptada para usuários com pouca experiência técnica

## 🎨 Interface do Usuário
A interface foi projetada com foco em simplicidade, clareza e objetividade. O sistema conta com telas para:

Cadastro e visualização de clientes

Cadastro e visualização de produtos

Registro e histórico de vendas

## 🛠️ Estrutura em Camadas
Frontend (React):
Exibição de dados, formulários e interação com a usuária (Isabella), utilizando chamadas à API para persistência e recuperação de dados.

Backend (Django):
Processamento de dados, validações, regras de negócio e comunicação com o banco de dados.

Persistência (SQLite):
Armazenamento estruturado das informações de clientes, produtos e vendas, com integridade referencial.

## 🧩 Diagrama de Componentes
Frontend: React PWA\

Backend: Django REST API\

Banco de Dados: SQLite

## ⚙️ Instalação e Execução
Clone o repositório:

bash
Copiar
Editar
git clone <https://github.com/NicollyMendes/SisWebBrecho>
cd SisWebBrecho
Instale as dependências do frontend e backend:

bash
Copiar
Editar
# Backend
cd backend
pip install -r requirements.txt

# Frontend
cd ../frontend
npm install
Execute o backend:

bash
Copiar
Editar
cd backend
python manage.py runserver 8080
Execute o frontend:

bash
Copiar
Editar
cd ../frontend
npm start
Acesse o sistema:
Abra o navegador e vá para http://localhost:3000

## 🏗️ Metodologia de Desenvolvimento
Scrum: Ciclos curtos (sprints), reuniões diárias (daily), revisões e retrospectivas ao final de cada sprint.

Artefatos: Product Backlog, Sprint Backlog e Incremento.

## 🤝 Equipe
Nome	Função
João Pedro Faccio	Product Owner / Scrum Master
Nicolly Mendes	FullStack / Análise de Requisitos
Artur Xavier	Frontend / Interface e Interação
João Paulo Kaezer	QA / Testes e Estrutura Técnica
Thiago Caleb	Análise de Negócios
Isabella	Cliente / Usuária Final / Feedback

## 📃 Licença
Este projeto foi desenvolvido como parte do curso de Engenharia de Software do Centro Universitário de Várzea Grande e está disponível para fins educacionais e de pesquisa.
