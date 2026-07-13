# Atlas dos Mangás

Landing page de vendas do **Atlas dos Mangás** — coleção de 6 Guias Mangá (Bioquímica, Cálculo, Eletricidade, Biologia Molecular, Microprocessadores e Universo), cada um com +200 páginas, mais 3 bônus de desenho.

Página estática, em arquivo único, com estética manga/otaku (preto/vermelho/amarelo, halftone, speed lines), 100% responsiva.

## Estrutura
- `index.html` — a página completa (HTML + CSS + JS inline)
- `assets/` — imagens otimizadas em WebP (capa do hero responsiva + capas dos guias e bônus)

## Rodar localmente
```bash
python -m http.server 8791
# abra http://localhost:8791/index.html
```

## Deploy
Site estático — pode ser publicado direto na Vercel, Netlify ou GitHub Pages apontando para a raiz do projeto.
