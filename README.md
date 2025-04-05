# docs
# Padrões de Desenvolvimento

Este documento descreve os padrões adotados pelo projeto para organização e padronização dos fluxos de trabalho com Git.

---

## Padrão de Branches

As branches devem seguir a estrutura:
<tipo>/<nome-descritivo>-<id-da-issue>

### Tipos válidos:

- feature/ – Para novas funcionalidades
- fix/ – Para correções de bugs
- hotfix/ – Para correções urgentes em produção
- refactor/ – Para refatorações sem mudança de comportamento
- test/ – Para adição ou manutenção de testes
- docs/ – Para documentações do repositório

### Exemplos:

- feature/criar-pagina-de-login-102
- bugfix/corrigir-cor-do-botao-de-login-87
- hotfix/corrigir-rota-sem-autenticacao-112

> Sempre use um nome descritivo e o ID da issue relacionada no final da branch.


---

## Padrão de Commits — Conventional Commits

Utilizamos o padrão **[Conventional Commits](https://www.conventionalcommits.org/)** para garantir clareza e rastreabilidade no histórico do repositório.

### Estrutura do commit: 
<tipo>: <mensagem curta>

#### Tipos aceitos:

| Tipo        | Descrição                                      |
|-------------|-----------------------------------------------|
| feat      | Nova funcionalidade                            |
| fix       | Correção de bug                                |
| docs      | Alterações na documentação                     |
| style     | Ajustes de formatação (espaços, vírgulas...)   |
| refactor  | Refatoração de código sem mudança de lógica    |
| test      | Criação ou modificação de testes               |
| chore     | Tarefas de build, configs, ou dependências     |

### Exemplos:

```bash
feat: adicionar validação de campos obrigatórios
fix: corrigir retorno 500 ao criar usuário
docs: atualizar instruções de contribuição
style: remover espaçamento desnecessário
refactor: simplificar lógica de autenticação
test: adicionar testes para criação de usuário
chore: ajustar configuração do GitHub Actions
=======
