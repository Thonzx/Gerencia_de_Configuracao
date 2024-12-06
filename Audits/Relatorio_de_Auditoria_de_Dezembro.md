# **Relatório de Auditoria - Execução de Testes do Sistema**

**Data da Auditoria:** 05/12/2024  
**Equipe Participante:**
- **Carlos Uchôa** (Gerente de Projeto)
- **Bruna Miranda** (Desenvolvedora Frontend)
- **Wellython Sá** (Desenvolvedor Backend)
- **Julia Farias** (Analista de Banco de Dados)

---

## **Objetivo da Auditoria**
Analisar os resultados da execução dos testes definidos previamente para verificar se as funcionalidades do sistema atendem aos requisitos estabelecidos.

---

## **Resumo dos Testes Executados**
Foram realizados os testes especificados no relatório anterior, com base nos arquivos listados:

1. **adicionarLivros.spec.cy.js**
   - **Resultados:** Todos os cenários de adição de livros foram validados com sucesso.
   - **Observação:** O sistema está exibindo mensagens claras para campos obrigatórios não preenchidos.

2. **busca.spec.cy.js**
   - **Resultados:** A busca retornou resultados adequados para todos os cenários testados.
   - **Observação:** A mensagem "Nenhum resultado encontrado" está sendo exibida corretamente para termos inexistentes.

3. **cadastroUsuario.spec.cy.js**
   - **Resultados:** O cadastro de usuário funcionou conforme o esperado.
   - **Observação:** Mensagens de erro para senhas diferentes e e-mails duplicados foram verificadas.

4. **comprarLivro.spec.cy.js**
   - **Resultados:** Cenários de compra de livro foram realizados com sucesso.
   - **Observação:** Nenhum problema foi identificado neste teste.

5. **editarDadosUsuario.spec.cy.js**
   - **Resultados:** A edição de dados do usuário está funcionando corretamente.
   - **Observação:** Mensagens de validação de senhas estão sendo exibidas conforme o esperado.

6. **editarLivros.spec.cy.js**
   - **Resultados:** A edição de livros ocorreu sem erros.
   - **Observação:** A troca de imagem do livro foi validada com sucesso.

7. **listagemFiltros.spec.cy.js**
   - **Resultados:** A listagem de livros e aplicação de filtros por categorias funcionaram como esperado.
   - **Observação:** Livros relacionados estão sendo exibidos corretamente na página de detalhes.

8. **login.spec.cy.js**
   - **Resultados:** O fluxo de login foi validado com sucesso para todos os cenários.
   - **Observação:** Mensagens de erro claras para credenciais inválidas e inexistentes foram confirmadas.

9. **notificacoesDestaques.spec.cy.js**
   - **Resultados:** As funcionalidades de notificações e destaque funcionaram conforme o esperado.
   - **Observação:** O destaque de livros está sendo refletido na tela principal corretamente.

10. **remocaoLivros.spec.cy.js**
    - **Resultados:** A remoção de livros ocorreu sem problemas.
    - **Observação:** Livros excluídos não aparecem mais na lista de "Meus Livros".

---

## **Resultados Consolidados**
- **Total de Testes Executados:** 10  
- **Testes Bem-Sucedidos:** 04 
- **Testes com Problemas:** 06

O sistema não atendeu a todos os requisitos testados sem falhas ou comportamentos inesperados.

---

## **Recomendações**
- Continuar executando testes após novas implementações para garantir a estabilidade do sistema.
- Priorizar a automação de testes para fluxos críticos, como login, cadastro e compra de livros.
- Atualizar o backlog de testes para incluir cenários futuros com base no feedback dos usuários.

---

## **Conclusão**
A auditoria confirmou que os testes planejados foram executados com sucesso e que o sistema está parcialmente funcional em relação às funcionalidades validadas. A equipe deve continuar utilizando o Cypress para garantir a qualidade contínua do sistema.

---

### **Responsáveis pela Aprovação**
- **Carlos Uchôa** (Gerente de Projeto)  
- **Bruna Miranda** (Desenvolvedora Frontend)  
- **Wellython Sá** (Desenvolvedor Backend)  
- **Julia Farias** (Analista de Banco de Dados)  
