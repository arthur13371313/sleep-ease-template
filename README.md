# 🌙 Noite Sem Dor — Página de Vendas

Página de vendas (landing page) **original** para vender um **guia digital** que ajuda a aliviar as dores que atrapalham o sono: **cãibra na perna, dor nas costas e dores nas pernas**.

Arquivo único em HTML/CSS/JS puro — **sem build, sem dependências, sem framework**. Abre em qualquer navegador e hospeda de graça.

![status](https://img.shields.io/badge/status-pronto%20para%20vender-8b7cf6)

## ✨ Seções da página

- ✅ Hero com promessa clara e prova social
- ✅ "As dores" — conexão com o problema do cliente
- ✅ "O guia" — a solução e seus benefícios
- ✅ Como funciona (3 passos)
- ✅ O que vem no guia (conteúdo + bônus)
- ✅ Depoimentos
- ✅ Oferta com preço, ancoragem e garantia
- ✅ FAQ com acordeão
- ✅ CTA final + rodapé com aviso legal
- ✅ 100% responsivo, com animações de scroll

## 🚀 Como usar

1. Abra `index.html` no navegador — já funciona.
2. Edite os textos direto no HTML (preço, depoimentos, nome do guia).
3. Hospede de graça: arraste a pasta no [Netlify Drop](https://app.netlify.com/drop), ou use GitHub Pages / Vercel.

## 🎨 Personalizar

### Cores e marca
No topo do `<style>`, edite as variáveis em `:root` (`--accent`, `--bg`...). Troque "Noite Sem Dor" no header, footer e `<title>`.

### Preço e oferta
Procure a seção `<!-- OFERTA -->` no HTML e ajuste valores, parcelas e itens da lista.

### Conectar o checkout (Hotmart, Kiwify, Cakto, Stripe...)
No final do `<script>`, descomente e ajuste:

```js
window.location.href = 'https://seu-checkout.com/' + produto;
```

## ⚠️ Aviso legal

O rodapé já inclui um aviso de que o guia é informativo e **não substitui orientação médica**. Mantenha esse aviso — é importante para produtos ligados a saúde e evita problemas com plataformas de pagamento.

## 📦 Estrutura

```
sleep-ease-template/
├── index.html      # a página de vendas completa
├── README.md       # este arquivo
├── LICENSE.md       # termos de licença
└── assets/         # coloque aqui suas imagens (capa do guia, etc.)
```

---

Conteúdo 100% original. Bom negócio! 🚀
