<p align="center">
  <img width="152" alt="image" src="https://github.com/user-attachments/assets/c811324a-c760-470e-a7d9-a4bde9757915">
</p>


<p align="center">
    <a href="https://rq-isp.vercel.app/"><img src="https://img.shields.io/badge/Aplicação%20Web-Online-brightgreen" alt="Aplicação Web"></a>
    <a href="https://rq-isp.vercel.app/"><img src="https://img.shields.io/badge/Documentação-Disponível-blue" alt="Documentação"></a>
    <img src="https://img.shields.io/badge/Versão-1.0.0-purple" alt="Versão">
    <img src="https://img.shields.io/badge/Licença-MIT-green" alt="Licença">
</p>

## 📜 Descrição

Falhas e defeitos em software podem resultar em erros, levando a interrupções indesejadas e custos adicionais na área de desenvolvimento de software. A inspeção de software desempenha um papel fundamental ao permitir uma revisão rigorosa, identificando e corrigindo falhas antes que causem problemas, melhorando, assim, a qualidade do software e evitando consequências negativas. O objetivo deste trabalho é propor uma ferramenta para apoiar o processo de inspeção, visando aumentar a precisão e eficiência das inspeções.

## 🛠️ Metodologia

A metodologia adota práticas como:
- Planejamento
- Elicitação e refinamento de requisitos
- Design de interface gráfica
- Desenvolvimento de software

A abordagem metodológica aplicada permitiu o desenvolvimento do produto mínimo viável do RQ_ISP. Trabalhos futuros envolvem o aprimoramento da ferramenta, com ênfase na criação e gerenciamento de listas de verificação, além da adição de novas funcionalidades sugeridas por usuários.

## 📁 Estrutura dos Repositórios

- `client`: Frontend da aplicação.
- `server`: Backend da aplicação.

## 🚀 Primeiros Passos

### 📋 Pré-requisitos

- Node.js
- npm

### 🛠️ Instalação



1. Clone o repositório do client-side:
    ```sh
    git clone https://github.com/RQISP-Tool/client-side
    cd RQ_ISP
    ```

2. Instale as dependências do client-side:
    ```sh
    npm install
    ```

3. Clone o repositório do servidor:
    ```sh
    git clone https://github.com/RQISP-Tool/server
    cd RQ_ISP
    ``

4. Instale as dependências do servidor:
    ```sh
    npm install
    ```

### 🔧 Configuração de Variáveis de Ambiente

Crie um arquivo `.env` no diretório `server` com o seguinte conteúdo:
```plaintext
TOKEN_SECRET_KEY=your_token_secret_key
DATABASE_URL=your_database_url
S3_BUCKET=your_s3_bucket
AWS_ACCESS_KEY_ID=your_aws_access_key_id
AWS_SECRET_ACCESS_KEY=your_aws_secret_access_key
PORT=8000
```

Crie um arquivo `.env` no diretório `client-side` com a variável `VITE_BASE_URL`:
```plaintext
VITE_BASE_URL=your_base_url
```

**Certifique-se de manter as variáveis de ambiente seguras e não expô-las publicamente.**

### 📚 Uso

#### Cliente

Para iniciar o cliente, use os seguintes comandos:

1. Desenvolvimento:
    ```sh
    cd client
    npm run dev
    ```

2. Pré-visualização da build:
    ```sh
    cd client
    npm run preview
    ```

#### Servidor

Para iniciar o servidor, use os seguintes comandos:

1. Desenvolvimento:
    ```sh
    cd server
    npm run dev
    ```

2. Build:
    ```sh
    cd server
    npm run build
    ```


Acesse a aplicação em `http://localhost:3000`

## 📄 Licença

Este projeto é licenciado sob a Licença MIT.

## 🔮 Trabalhos Futuros

Melhorias futuras incluem:
- Aprimorar a ferramenta com um gerenciamento mais abrangente de listas de verificação.
- Adicionar novas funcionalidades baseadas no feedback dos usuários.
