# Teste GitHub CLI

Este é um repositório de teste criado para demonstrar as capacidades do GitHub CLI.

## Funcionalidades Testadas

- [x] Criação de repositório
- [x] Clone automático
- [x] Adição de arquivos
- [x] Criação de issues
- [ ] Criação de pull requests

## Mais Exemplos de Comandos

```bash
# Trabalhar com issues
gh issue create --title "Título" --body "Descrição"
gh issue list
gh issue view 1
gh issue close 1

# Trabalhar com pull requests
gh pr create --title "Título" --body "Descrição"
gh pr list
gh pr view 1
gh pr merge 1
```

## Comandos Utilizados

```bash
# Criar repositório
gh repo create teste-github-cli --public --description "Repositório de teste" --clone

# Listar repositórios
gh repo list

# Ver informações do repositório
gh repo view
```

## Data de Criação

Criado em: $(date)
