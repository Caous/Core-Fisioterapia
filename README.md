# Core Reabilitação & Performance — Consultoria de Presença Digital e SEO

Página de consultoria de SEO e presença digital desenvolvida pela **InnovaSfera Tecnologia** para a clínica **Core Reabilitação & Performance**, localizada no Portal do Morumbi, São Paulo.

---

## Sobre o Projeto

Documento interativo em HTML standalone que apresenta uma análise técnica completa do posicionamento digital da clínica no Google, incluindo:

- Diagnóstico do posicionamento atual (5ª posição na região)
- Análise técnica com 4 pilares: Performance, Acessibilidade, Best Practices e SEO
- Pontos positivos e críticos do cenário atual
- Comparação entre situação atual e situação ideal
- Estratégia de palavras-chave por categoria
- Resumo estratégico e próximos passos

---

## Tecnologias

- HTML5 + CSS3 (inline, sem dependências de build)
- JavaScript vanilla (accordion, animações, IntersectionObserver)
- [Font Awesome 6](https://fontawesome.com/) — ícones
- [Google Fonts — Inter](https://fonts.google.com/specimen/Inter) — tipografia

---

## Estrutura

```
.
├── index.html        # Página principal (deploy-ready)
├── logo-large.svg    # Logo InnovaSfera (watermark de fundo)
├── vercel.json       # Configuração de deploy no Vercel
└── README.md
```

---

## Deploy

O projeto está configurado para deploy direto no **Vercel**.

O `vercel.json` redireciona qualquer rota para o `index.html`:

```json
{
  "rewrites": [
    { "source": "/(.*)", "destination": "/index.html" }
  ]
}
```

Para publicar via CLI:

```bash
vercel --prod
```

---

## Contato — InnovaSfera Tecnologia

| Canal | Link |
|---|---|
| Site | [www.innovasfera.com.br](https://www.innovasfera.com.br/) |
| WhatsApp | [(11) 94261-6650](https://wa.me/5511942616650) |
| Instagram | [@innovasfera](https://www.instagram.com/innovasfera/) |
| LinkedIn | [InnovaSfera](https://www.linkedin.com/company/innova-sfera/about/?viewAsMember=true) |
