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

