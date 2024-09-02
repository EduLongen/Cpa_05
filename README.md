# CPA

Bem-vindo a **CPA**! Este é um sistema educacional desenvolvido para ajudar estudantes a melhorar suas notas e acompanhar seu desempenho acadêmico.

## Tabela de Conteúdos

- [Descrição](#descrição)
- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)
- [Configuração](#configuração)
- [Execução](#execução)
- [Contribuindo](#contribuindo)

## Descrição

O projeto é dividido em dois componentes principais:
- **Backend**: Desenvolvido em Java Spring Boot.
- **Frontend**: Desenvolvido em React.

## Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas no seu ambiente de desenvolvimento:

- **Java JDK 11** ou superior
- **Maven**
- **Node.js** (recomendado: versão 14 ou superior)
- **Yarn** ou **npm**
- **Docker** e **Docker Compose**

## Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. Navegue até o diretório do backend:

   ```bash
   cd cpa-back
   ```

3. Instale as dependências do backend:

   ```bash
   mvn clean install
   ```

3. Configure o Docker para o backend:

   ```bash
   docker-compose up -d
   ```

4. Navegue até o diretório do frontend:

   ```bash
   cd ../cpa-front
   ```

5. Instale as dependências do frontend:

   ```bash
   yarn install
   # ou
   npm install
   ```

## Configuração

Copie o arquivo .env-example para .env no diretório cpa-back e configure as variáveis de ambiente necessárias:

   ```bash
   cp .env-example .env
   ```

Nota: Certifique-se de preencher corretamente as informações de conexão com o banco de dados e outras configurações.

# Execução

1. Execute o backend:

   ```bash
   cd cpa-back
   mvn spring-boot:run
   ```

2. Execute o frontend:

   ```bash
   cd ../cpa-front
   yarn start
   # ou
   npm start
   ```
O backend estará disponível na porta 8080 e o frontend na porta 3000.

## Contribuindo

Se você deseja contribuir para o projeto, siga estas etapas:

1. Fork o Repositório: Faça um fork deste repositório para sua conta GitHub.
2. Crie um Branch: Crie um branch para suas modificações.
3. Faça as Mudanças: Implemente suas mudanças e faça commits descritivos.
4. Envie um Pull Request: Envie um pull request para o branch principal do repositório original.
