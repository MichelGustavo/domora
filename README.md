# Domora

E-commerce demonstrativo de camisas e pendrives com músicas de reggae em Vue 3, Vite e Lucide. Interface em português, responsiva, com catálogo, busca por nome, filtros por categoria, ordenação por preço, detalhes dos produtos, favoritos e sacola com quantidades. Favoritos e sacola são persistidos no localStorage.

## Executar

Requer Node.js 20.19+ ou 22.12+ e npm.

```bash
cd domora
npm install
npm run dev
```

Abra a URL exibida pelo Vite, normalmente http://localhost:5173.

## Produção

```bash
npm run build
npm run preview
```

O build estático fica em `dist/`.

## Personalização

- `src/App.vue`: produtos, preços, conteúdo e comportamento da loja.
- `src/style.css`: estrutura e layout responsivo.
- `src/reggae.css`: identidade reggae inspirada nas referências de design, com preto, verde, amarelo e vermelho, tipografia de cartaz e padrões geométricos.
- `public/images/`: ilustrações SVG locais dos produtos, composição do banner e padrões originais.

## Escopo

Projeto de frontend com dados ilustrativos. Checkout e inscrição na newsletter são demonstrações locais; não realizam pagamentos, pedidos reais nem enviam dados. Para uso comercial, integrar backend, estoque, autenticação, gateway de pagamento, frete e serviço de e-mail. As artes conceituais de produtos, o banner e os padrões usam SVG local. As fontes do Google Fonts dependem de conexão à internet e possuem fontes alternativas.
