# notebooks/

Ordem numerada obrigatória. Cada notebook deve rodar de cima para baixo em ambiente limpo
(`Kernel → Restart & Run All`) sem erro — é isso que caracteriza reprodutibilidade.

| Arquivo | Escopo |
|---|---|
|[Uploading tech_challenge_grupo28_v3.py…]() | Analise Exploratoria de Dados|

## Regras

- **Antes do commit:** verifique que a numeração das células está em ordem crescente
  (`[1]`, `[2]`, `[3]`...). Células fora de ordem indicam execução caótica.
- Mantenha as saídas dos gráficos salvas no notebook — o avaliador precisa ver os
  resultados sem executar nada.
- Todo gráfico precisa de um parágrafo de interpretação em markdown logo abaixo.
  Gráfico solto, sem leitura, não comunica nada.
- A primeira célula de cada notebook define `RANDOM_STATE = 42` e os caminhos.
  Não mude o valor entre notebooks.
