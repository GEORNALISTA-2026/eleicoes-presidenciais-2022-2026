# Dashboard Presidencial 2022 × 2026 — publicação no GitHub Pages

## Estrutura obrigatória

```text
index.html
.nojekyll
presidente_detalhado_2022/
  index.json
  candidatos.json
  AC.jsonl ... ZZ.jsonl
presidente_detalhado_2026/
  index.json
  candidatos.json
  AC.jsonl ... ZZ.jsonl
```

Copie as pastas `presidente_detalhado_2022` e `presidente_detalhado_2026` completas, geradas anteriormente, para a raiz deste repositório. O HTML carrega automaticamente os índices e busca cada arquivo estadual `.jsonl` quando necessário.

## Ativar o GitHub Pages

No repositório, abra **Settings → Pages**. Em **Build and deployment**, escolha **Deploy from a branch**, selecione `main` e `/(root)`, e clique **Save**.

O site deverá ficar em `https://GEORNALISTA-2026.github.io/eleicoes-presidenciais-2022-2026/`.

Os dados e o site serão públicos. Não coloque arquivos pessoais ou dados privados neste repositório.
