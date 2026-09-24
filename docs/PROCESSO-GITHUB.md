# Processo de desenvolvimento no GitHub

## Repositório

Crie um repositório privado com **Use this template** e adicione o professor como colaborador. Não use fork.

As issues do repositório `Racass/checkpoint-csharpracass-expensehub` são o backlog central e permanecerão abertas.

## Uma feature por fluxo

Para cada issue:

1. sincronize sua branch `main`;
2. crie uma branch curta, como `i07-approve-reject`;
3. faça commits coesos;
4. envie a branch;
5. abra uma pull request no seu repositório;
6. cite a issue como `Racass/checkpoint-csharpracass-expensehub#7`;
7. aguarde o pipeline;
8. faça auto-revisão;
9. corrija os problemas;
10. faça merge.

Não use palavras de fechamento automático (`Closes`, `Fixes` ou `Resolves`) para referenciar o backlog central.

## Pull request

Inclua:

- issue implementada;
- resumo técnico;
- decisões e concessões;
- como validar;
- evidências relevantes;
- impactos em segurança e autorização;
- uso de IA relacionado;
- checklist concluído.

Modelo de checklist:

```text
- [ ] Critérios de aceite atendidos
- [ ] Casos negativos validados
- [ ] Autorização revisada
- [ ] Testes unitários adicionados ou atualizados
- [ ] Build sem erros
- [ ] Pipeline analisado
- [ ] Documentação atualizada
- [ ] AI-USAGE.md atualizado
```

## Commits

Commits devem registrar evolução real e ter mensagens objetivas, por exemplo:

```text
feat(expenses): enforce draft ownership on updates
test(expenses): cover invalid approval transitions
docs: document SQLite setup
```

Quantidade de commits não representa produtividade. Commits artificiais, vazios, divididos sem motivo ou feitos por outra pessoa não geram crédito.

## Entrega final

Entregue o SHA exato do commit final da `main`. Mudanças posteriores não fazem parte da correção, salvo autorização do professor.

Antes de enviar:

```shell
dotnet restore ./sources/ExpenseHub.slnx
dotnet build ./sources/ExpenseHub.slnx
dotnet test ./sources/ExpenseHub.slnx
```

Confirme também que o workflow `code-quality` terminou e que o professor continua com acesso.
