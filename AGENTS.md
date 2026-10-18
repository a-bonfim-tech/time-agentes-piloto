# Regras do projeto

## Papéis
- Claude Code implementa; Codex revisa. Quem escreve não revisa.
- Nenhum agente faz merge, deploy ou push na main.

## Fluxo
- Toda tarefa começa por uma issue com critérios de aceitação.
- Trabalhe numa branch feat/issue-<n>; abra PR com `gh pr create`.
- Descreva no PR o que foi feito e como foi testado.

## Segurança
- Nunca leia, imprima ou commite .env, chaves ou tokens.
- Na dúvida sobre uma ação irreversível, pare e pergunte.
