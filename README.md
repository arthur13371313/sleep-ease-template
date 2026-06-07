# 🌙 RestaBem — Template de Landing Page de Sono

Landing page **original**, responsiva e pronta para converter, ideal para produtos de sono, bem-estar, meditação, cursos e infoprodutos. Arquivo único em HTML/CSS/JS puro — **sem build, sem dependências, sem framework**.

![status](https://img.shields.io/badge/status-pronto%20para%20vender-8b7cf6)
![license](https://img.shields.io/badge/licen%C3%A7a-comercial-5ad1c8)

## ✨ O que está incluído

- ✅ Hero com chamada de ação e prova social
- ✅ Seção de benefícios (6 cards)
- ✅ Passo a passo "como funciona"
- ✅ Depoimentos
- ✅ Tabela de planos/preços (3 colunas)
- ✅ FAQ com acordeão
- ✅ CTA final + rodapé
- ✅ Animações de scroll, FAQ interativo, 100% responsivo
- ✅ Tema configurável por variáveis CSS (troca de cores em segundos)

## 🚀 Como usar

1. Abra o arquivo `index.html` em qualquer navegador — pronto, já funciona.
2. Edite os textos diretamente no HTML.
3. Para hospedar de graça: arraste a pasta para o [Netlify Drop](https://app.netlify.com/drop), ou use GitHub Pages / Vercel.

## 🎨 Como personalizar

### Cores
No topo do `<style>`, edite as variáveis em `:root`:

```css
:root {
  --accent:   #8b7cf6;  /* cor principal */
  --accent-2: #5ad1c8;  /* cor secundária */
  --bg:       #0e1530;  /* fundo */
}
```

### Nome / marca
Troque "RestaBem" no header, footer e `<title>`.

### Conectar o checkout
No final do `<script>`, descomente e ajuste:

```js
window.location.href = 'https://seu-checkout.com/' + plano;
```

Funciona com Hotmart, Kiwify, Stripe, Eduzz, Cakto, etc.

## 📦 Estrutura

```
sleep-ease-template/
├── index.html      # a landing page completa
├── README.md       # este arquivo
├── LICENSE.md      # termos de licença comercial
└── assets/         # coloque aqui suas imagens
```

## 💰 Pode revender?

Sim. Este template é **original** (nenhum conteúdo copiado de terceiros) e pode ser usado, modificado e vendido conforme a `LICENSE.md`.

---

Feito para vender. Bom negócio! 🚀
