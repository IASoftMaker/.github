# IASoftMaker

Desenvolvemos sistemas sob medida para empresas que precisam de soluções digitais eficientes e escaláveis. Cada projeto é construído com atenção às necessidades reais do cliente, do planejamento à entrega.

---

## Como trabalhamos

Valorizamos código limpo, processos bem definidos e comunicação clara. Nossos repositórios seguem padrões que garantem qualidade e rastreabilidade em cada entrega.

---

## Convenções de Commits

Todas as mensagens de commit devem seguir o padrão **Conventional Commits**:

```
<tipo>(<escopo opcional>): <descrição curta>
```

### Tipos

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

### Exemplos

```bash
feat(auth): adiciona login com Google
fix(pagamento): corrige erro 500 na finalização do pedido
docs: atualiza instruções de instalação no README
chore: atualiza dependências para versões mais recentes
refactor(usuario): extrai lógica de validação para service
test(api): adiciona testes de integração na rota de produtos
```

### Regras

- Use o **imperativo** na descrição: "adiciona", "corrige", "atualiza"
- Descrição em **letras minúsculas**
- Sem ponto final
- Máximo de **72 caracteres** na primeira linha

---

## Estratégia de Branches

| Branch | Finalidade |
|---|---|
| `main` | Produção — sempre estável |
| `feature/nome` | Novas funcionalidades |
| `fix/nome` | Correções de bugs |
| `hotfix/nome` | Correções urgentes em produção |
| `chore/nome` | Manutenção, dependências, configs |

> Nenhum commit vai direto para a `main`. Todo código entra via Pull Request.

---

## Segurança

- Nunca commite arquivos `.env` ou credenciais
- Todo repositório deve ter um `.env.example` com as variáveis necessárias
- Em caso de vazamento acidental, revogue as credenciais imediatamente

---
