# **BookStore - Gerência de Configuração**

Bem-vindo ao repositório do sistema **BookStore**, uma plataforma de troca e venda de livros. Este repositório implementa uma estrutura organizada para facilitar a gerência de configuração do projeto, garantindo controle, rastreabilidade e documentação clara de todas as mudanças.

---

## **Estrutura do Repositório**

Abaixo está a estrutura principal do repositório, com uma breve descrição de cada diretório e arquivo:

```plaintext
.
├── Audits/               # Relatórios de auditoria do sistema
├── Changes/              # Changelog com o histórico de mudanças
├── Docs/                 # Documentação técnica e funcional do projeto
├── Releases/             # Histórico de releases e notas de versão
├── Scripts/              # Scripts de automação e testes
├── Src/                  # Código-fonte do sistema
└── README.md             # Documento explicativo do repositório
```

---

### **1. Audits**
- Contém os relatórios de auditoria realizados durante o ciclo de desenvolvimento.
- **Exemplo de Conteúdo:**
  - `Relatorio_de_Auditoria_de_Outubro.md`: Registro das mudanças identificadas e planejadas no mês de outubro.
  - Auditorias incluem análise de problemas e propostas de melhorias.

---

### **2. Changes**
- Histórico de mudanças no projeto, documentado em um arquivo `CHANGELOG.md`.
- **Exemplo de Conteúdo:**
  - Registro de novas funcionalidades, melhorias e correções de bugs.
  - Segue o formato de versionamento semântico (major, minor, patch).

---

### **3. Config**
- Diretório responsável por armazenar arquivos de configuração essenciais para o funcionamento do sistema.
- **Exemplo de Conteúdo:**
  - `.env`: Variáveis de ambiente (não versionadas).
  - `config.json`: Configurações gerais do sistema.
  - `docker-compose.yml`: Configurações para contêineres Docker.
  - `README_CONFIG.md`: Documentação sobre como configurar o ambiente.

---

### **4. Docs**
- Diretório dedicado à documentação técnica e funcional do projeto.
- **Exemplo de Conteúdo:**
  - `Arquitetura.md`: Diagramas e explicações sobre a arquitetura do sistema.
  - `Plano_de_Gerenciamento_do_Projeto.md`: Detalhes sobre prazos, recursos e gerenciamento do projeto.
  - `Testes.md`: Planejamento e relatórios de execução de testes.

---

### **5. Releases**
- Contém as notas de release para cada versão do sistema.
- **Exemplo de Conteúdo:**
  - `release-1.0.0.md`: Detalhes da primeira versão estável, incluindo funcionalidades, melhorias e correções.
  - Histórico de versões para referência e rastreamento.

---

### **6. Scripts**
- Scripts automatizados e testes utilizados no desenvolvimento do sistema.
- **Exemplo de Conteúdo:**
  - `adicionarLivros.spec.cy.js`: Teste automatizado para a funcionalidade de adição de livros.
  - `login.spec.cy.js`: Teste automatizado para o fluxo de login.
  - Scripts de automação para configurar o ambiente (`setup.sh`).

---

### **7. Src**
- Diretório principal contendo o código-fonte do sistema.
- Estrutura organizada em módulos para fácil manutenção e escalabilidade.

---

## **Gerência de Configuração**

A gerência de configuração do projeto é estruturada para garantir controle, rastreabilidade e documentação completa. Abaixo, os principais elementos:

### **Controle de Versão**
- Utiliza **Git** para versionamento.
- Branches principais:
  - `main`: Branch principal com código estável.
  - `develop`: Branch de desenvolvimento.
  - Branches de feature: Criadas para implementar funcionalidades específicas (ex.: `feature/busca-livros`).

### **Versionamento Semântico**
- O projeto segue o esquema `MAJOR.MINOR.PATCH`:
  - **MAJOR:** Alterações incompatíveis com versões anteriores.
  - **MINOR:** Adições compatíveis com versões anteriores.
  - **PATCH:** Correções de bugs.

### **Automação**
- **Testes Automatizados:** Utiliza **Cypress** para garantir a qualidade do sistema.
- **Scripts de Configuração:** Scripts para configurar rapidamente o ambiente de desenvolvimento.

---

## **Como Contribuir**

1. Faça um fork do repositório.
2. Crie uma branch para sua funcionalidade:
   ```bash
   git checkout -b feature/sua-funcionalidade
   ```
3. Adicione suas mudanças e faça commits com mensagens descritivas:
   ```bash
   git commit -m "feat: implementar funcionalidade X"
   ```
4. Envie suas alterações:
   ```bash
   git push origin feature/sua-funcionalidade
   ```
5. Abra um Pull Request na branch `develop`.

---

## **Como Executar o Projeto**

### **Requisitos**
- Node.js
- MySQL
- Docker (opcional para execução com contêineres)

### **Configuração**
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-repositorio/bookstore.git
   cd bookstore
   ```

2. Configure o ambiente:
   - Renomeie o arquivo `example.env` para `.env` e preencha as variáveis de ambiente.

3. Instale as dependências:
   ```bash
   npm install
   ```

4. Execute o projeto:
   ```bash
   npm start
   ```

---

## **Testes Automatizados**

### **Execução**
1. Instale o Cypress:
   ```bash
   npm install cypress --save-dev
   ```

2. Execute os testes:
   ```bash
   npx cypress open
   ```

3. Arquivos de testes disponíveis em `Scripts/`.

---

## **Contatos**
- **Gerente do Projeto:** Carlos Uchôa  
- **Equipe de Desenvolvimento:**
  - Bruna Miranda (Frontend)
  - Julia Farias (Banco de Dados)
  - Wellython Sá (Backend)

---
