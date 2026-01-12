# 🚗 CarHub

![Mini MVC](https://img.shields.io/badge/Mini%204-MVC-green)
![PHP Version](https://img.shields.io/badge/PHP-8.3-blue)
![MariaDB](https://img.shields.io/badge/MariaDB-10.5-lightblue)
![AdminLTE 2](https://img.shields.io/badge/AdminLTE%204-Theme-blue)
![Composer](https://img.shields.io/badge/Composer-Package_Manager-orange)

**Conectando tecnologia, estilo e performance**

CarHub é um sistema de gestão para **auto center e lojas de som e acessórios automotivos**, desenvolvido para centralizar serviços, produtos, clientes e ordens de serviço em uma única plataforma moderna e eficiente.

![](public/capa_readme.png)

---

## 📌 Visão Geral

O CarHub foi projetado para atender empresas que trabalham com:

- 🔊 Som automotivo
- 🛞 Suspensão
- 🎥 Câmeras de ré e sensores
- 🪟 Insulfilm e PPF
- 💡 Iluminação automotiva (LEDs, faróis, etc.)
- 🔧 Acessórios automotivos em geral

O sistema atua como um **hub central**, conectando tecnologia, estética e performance do veículo.

---

## 🚀 Funcionalidades

### 🔐 Autenticação
- Login seguro
- Controle de permissões por usuário
- Perfis administrativos e operacionais

### 👤 Clientes
- Cadastro completo de clientes
- Histórico de serviços realizados
- Veículos vinculados ao cliente

### 🚘 Veículos
- Cadastro detalhado do veículo
- Informações técnicas e observações
- Histórico de modificações e serviços

### 🧾 Ordens de Serviço
- Abertura e gerenciamento de OS
- Serviços e produtos vinculados
- Status da OS (aberta, em andamento, finalizada)
- Observações técnicas

### 📦 Produtos
- Cadastro de produtos e acessórios
- Controle de estoque
- Categorias personalizadas

### 🛠️ Serviços
- Cadastro de serviços
- Valores e tempo estimado
- Associação com ordens de serviço

### 📊 Relatórios *(em desenvolvimento)*
- Serviços mais realizados
- Faturamento por período
- Produtos mais vendidos

---

## 🧱 Arquitetura

- **Backend:** PHP
- **Framework:** Mini3
- **Frontend:** AdminLTE
- **Padrão:** MVC (Model-View-Controller)
- **Banco de Dados:** MySQL / MariaDB

---

## 📂 Estrutura do Projeto

```text
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
```

---

## ⚙️ Requisitos

- PHP >= 8.3
- MySQL ou MariaDB >= 10.5
- Apache com mod_rewrite habilitado
- Composer

---

## 🛠️ Instalação

Siga os passos abaixo para instalar e configurar o projeto corretamente.

#### 🚀 1. Clonar o Repositório ou Baixar o ZIP  
Você pode **clonar** o repositório com o comando:

```sh
git clone git@github.com:fahmedeiros/carhub-system.git
```

Ou, se preferir, baixe o ZIP do repositório, extraia os arquivos e navegue até a pasta do projeto.

#### 📦 2. Instalar as Dependências
Dentro da pasta do projeto, execute o comando para instalar as dependências usando o Composer:

```sh
composer install
```

### ⚙️ 3. Configurar o Projeto

1. Crie um arquivo chamado `config.php`.
2. Copie o conteúdo do arquivo `config.example.php` e cole no novo arquivo `config.php`.
3. Abra o arquivo `config.php` e edite as configurações do banco de dados conforme necessário, ajustando os seguintes parâmetros:

```php
define('DB_TYPE', 'mysql'); // Tipo do banco de dados
define('DB_HOST', 'localhost'); // Endereço do servidor do banco de dados
define('DB_NAME', 'carhub'); // Nome da base de dados
define('DB_USER', 'root'); // Usuário do banco de dados
define('DB_PASS', ''); // Senha do banco de dados
define('DB_CHARSET', 'utf8'); // Charset para a conexão
```

**As configurações das variáveis acima são baseadas nos bancos de dados de exemplo e em um servidor local.**

---

## 🔐 Segurança

- Senhas criptografadas
- Proteção contra acesso não autorizado
- Validação de dados no backend

---

## 🎨 Interface

- Layout moderno baseado no AdminLTE
- Design responsivo
- Foco em usabilidade e produtividade

---

## 🗺️ Roadmap

- Dashboard com métricas
- Controle financeiro
- Integração com WhatsApp
- Upload de imagens nas OS
- API REST
- Versão mobile

## 🤝 Contribuição

Quer contribuir com o projeto? Siga estas diretrizes:

1. **Crie um Fork** deste repositório.
2. **Crie uma nova branch** para sua funcionalidade ou correção:
   ```sh
   git checkout -b feature/minha-feature
   ```
3. **Realize as alterações** necessárias e faça commit:
   ```sh
   git commit -m "Adiciona nova funcionalidade X"
   ```
4. **Envie suas modificações** para seu fork:
   ```sh
   git push origin feature/minha-feature
   ```
5. **Abra um Pull Request** e aguarde a revisão.

Agradecemos sua contribuição! 🚀

---

## 📄 Licença

Este projeto está sob a licença **MIT**.
Consulte o arquivo LICENSE para mais informações.

---

## 👨‍💻 Autor

**Fabrício de Medeiros**  
Projeto desenvolvido para gestão de auto center e lojas automotivas.

---

## ⭐ Considerações Finais

O **CarHub** nasceu para ser o ponto central da gestão automotiva, unindo tecnologia, organização e performance em um único sistema.