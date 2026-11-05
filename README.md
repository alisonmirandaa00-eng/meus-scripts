# Meus Scripts SQL

Repositório central para armazenar e versionar scripts SQL e consultas de banco de dados.

## Estrutura

Todos os scripts ficam concentrados na pasta [`scripts/`](./scripts) para facilitar a busca e manutenção:

```text
meus-scripts/
├── scripts/
│   └── _template.sql    # Modelo base para novos scripts
├── .gitignore
└── README.md
```

## Boas Práticas

- **Nomes descritivos**: use nomes claros em minúsculas separados por `_` (ex.: `relatorio_vendas_mensal.sql`, `ajuste_estoque.sql`).
- **Cabeçalho**: inclua um breve comentário no topo do arquivo informando o objetivo do script e o banco de dados alvo.
- **Segurança**: nunca salve senhas, tokens, strings de conexão ou dumps de dados reais (`.bak`, `.dmp`, `.csv` com dados sensíveis) neste repositório.

## Como salvar novos scripts no Git

```powershell
git add .
git commit -m "Adiciona script de consulta X"
git push
```
