# Convenções de Commits

Todas as mensagens de commit devem seguir o padrão **Conventional Commits**:

```
<tipo>(<escopo opcional>): <descrição curta>
```

---

## Tipos

| Tipo | Quando usar |
|---|---|
| `feat` | Nova funcionalidade |
| `fix` | Correção de bug |
| `docs` | Alterações em documentação |
| `style` | Formatação, espaçamento (sem mudança de lógica) |
| `refactor` | Refatoração sem mudança de comportamento |
| `test` | Adição ou correção de testes |
| `chore` | Dependências, configurações, CI |
| `perf` | Melhorias de performance |
| `revert` | Reversão de commit anterior |

---

## Exemplos

```bash
feat(auth): adiciona login com Google
fix(pagamento): corrige erro 500 na finalização do pedido
docs: atualiza instruções de instalação no README
chore: atualiza dependências para versões mais recentes
refactor(usuario): extrai lógica de validação para service
test(api): adiciona testes de integração na rota de produtos
```

---

## Regras

- Use o **imperativo** na descrição: "adiciona", "corrige", "atualiza"
- Descrição em **letras minúsculas**
- Sem ponto final
- Máximo de **72 caracteres** na primeira linha
