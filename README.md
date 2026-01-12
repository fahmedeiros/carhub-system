🚗 CarHub

Conectando tecnologia, estilo e performance

CarHub é um sistema de gestão para auto center e lojas de som e acessórios automotivos, desenvolvido para centralizar agendamentos, serviços, produtos, clientes e ordens de serviço em uma única plataforma moderna e eficiente.

📌 Visão Geral

O CarHub foi projetado para atender empresas que trabalham com:

🔊 Som automotivo

🛞 Suspensão

🎥 Câmeras de ré e sensores

🪟 Insulfilm e PPF

💡 Iluminação automotiva (LEDs, faróis, etc.)

🔧 Acessórios automotivos em geral

O sistema atua como um hub central, conectando tecnologia, estética e performance do veículo.

🚀 Funcionalidades
🔐 Autenticação

Login seguro

Controle de permissões por usuário

Perfis administrativos e operacionais

👤 Clientes

Cadastro completo de clientes

Histórico de serviços realizados

Veículos vinculados ao cliente

🚘 Veículos

Cadastro detalhado do veículo

Informações técnicas e observações

Histórico de modificações e serviços

🧾 Ordens de Serviço

Abertura e gerenciamento de OS

Serviços e produtos vinculados

Status da OS (aberta, em andamento, finalizada)

Observações técnicas

📦 Produtos

Cadastro de produtos e acessórios

Controle de estoque

Categorias personalizadas

🛠️ Serviços

Cadastro de serviços

Valores e tempo estimado

Associação com ordens de serviço

📊 Relatórios (em desenvolvimento)

Serviços mais realizados

Faturamento por período

Produtos mais vendidos

🧱 Arquitetura

Backend: PHP

Framework: Mini3

Frontend: AdminLTE

Padrão: MVC (Model-View-Controller)

Banco de Dados: MySQL / MariaDB

📂 Estrutura do Projeto
carhub-system/
├── app/
│   ├── Controllers/
│   ├── Models/
│   ├── Views/
│
├── core/
│   ├── Controller.php
│   ├── Model.php
│
├── public/
│   ├── assets/
│   ├── index.php
│
├── vendor/
├── config.php
├── .htaccess
└── README.md

⚙️ Requisitos

PHP >= 7.4

MySQL ou MariaDB

Apache com mod_rewrite habilitado

Composer (opcional)

🛠️ Instalação

Clone o repositório:

git clone https://github.com/seu-usuario/carhub-system.git


Configure o banco de dados em config.php

Crie o banco de dados:

CREATE DATABASE carhub CHARACTER SET utf8mb4 COLLATE utf8mb4_general_ci;


Configure o virtual host ou use o diretório /public como raiz

Acesse no navegador:

http://localhost/carhub

🔐 Segurança

Senhas criptografadas

Proteção contra acesso não autorizado

Validação de dados no backend

🎨 Interface

Layout moderno baseado no AdminLTE

Design responsivo

Foco em usabilidade e produtividade

🗺️ Roadmap

 Dashboard com métricas

 Controle financeiro

 Integração com WhatsApp

 Upload de imagens nas OS

 API REST

 Versão mobile

🤝 Contribuição

Contribuições são bem-vindas!

Fork o projeto

Crie sua branch (feature/nova-funcionalidade)

Commit suas alterações

Push para a branch

Abra um Pull Request

📄 Licença

Este projeto está sob a licença MIT.
Consulte o arquivo LICENSE para mais informações.

👨‍💻 Autor

Fabrício de Medeiros
Projeto desenvolvido para gestão de auto center e lojas automotivas.

⭐ Considerações Finais

O CarHub nasceu para ser o ponto central da gestão automotiva, unindo tecnologia, organização e performance em um único sistema.
