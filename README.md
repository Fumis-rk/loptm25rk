# Ranking FTMSP 2025

Este é o site oficial do **Ranking 2025 da Federação de Tênis de Mesa do Estado de São Paulo (FTMSP)**.

## 🚀 Como atualizar o ranking

1. Abra o repositório no GitHub.
2. Substitua o arquivo `ranking.csv` pelo novo CSV oficial atualizado.
3. Confirme o commit.
4. O Netlify fará o deploy automático.

⚠️ Importante: **não altere o nome do arquivo** (`ranking.csv`).  
O site depende dele para carregar os dados.

## 🎨 Cores do site

- Vermelho oficial: `#c62828`
- Preto/Cinza: `#424242`
- Branco/Cinza claro: `#f5f5f5`

## 📂 Estrutura dos arquivos

- `index.html` → Página principal (carrega React, Tailwind e Papaparse via CDN).
- `ranking.csv` → Arquivo com os dados do ranking oficial.
- `README.md` → Este guia.
- `_headers` → Configuração para não cachear o CSV no Netlify.

---

FTMSP © 2025 - Federação de Tênis de Mesa do Estado de São Paulo
