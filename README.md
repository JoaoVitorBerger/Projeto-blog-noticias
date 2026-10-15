# 📰 Blog de Notícias

Aplicação web desenvolvida por João Vitor Berger e Vinícius Fernandes, com o objetivo de centralizar notícias do mercado financeiro e notícias internacionais em uma única interface.

O projeto integra duas APIs externas: uma voltada ao mercado financeiro e outra do **The New York Times (NYT)**. As notícias são obtidas por meio de requisições HTTP e exibidas na interface durante o carregamento da aplicação.

## 🛠️ Tecnologias utilizadas

- **JavaScript** — lógica da aplicação e consumo de APIs.
- **React** — desenvolvimento da interface por meio de componentes.
- **Tailwind CSS** — estilização da interface.
- **Vite** — ambiente de desenvolvimento e ferramenta de build.
- **Postman** — testes e validação dos endpoints das APIs.

## ⚙️ Instalação e execução

**Pré-requisitos:** Node.js e Git instalados.

1. Clone o repositório:

   ```bash
   git clone https://github.com/JoaoVitorBerger/projetoBlog.git
   ```

2. Entre no diretório do projeto:

   ```bash
   cd projetoBlog
   ```

3. Acesse a pasta da aplicação React:

   ```bash
   cd Blog
   ```

4. Instale as dependências:

   ```bash
   npm install
   ```

5. Inicie o servidor de desenvolvimento:

   ```bash
   npm run dev
   ```

6. Acesse no navegador o endereço local exibido pelo Vite no terminal.

## 🔌 Integração com APIs

A aplicação utiliza duas fontes externas de notícias:

- **API de mercado financeiro:** obtenção de notícias relacionadas ao setor financeiro.
- **API do The New York Times:** obtenção de notícias publicadas pelo jornal.

Os dados são carregados dinamicamente por meio de requisições às APIs, permitindo a atualização das notícias ao recarregar a página.

## 👥 Colaboração

Projeto desenvolvido em colaboração por **João Vitor Berger e Vinícius Fernandes**, com foco no aprendizado de React, consumo de APIs REST e desenvolvimento de interfaces web.
