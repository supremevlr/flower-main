# Como Deployar o Site Flower-Main

## Op��o 1: GitHub Pages (Gratuito)

1. Fa�a push do c�digo para um reposit�rio GitHub
2. V� em Settings > Pages
3. Selecione a branch `gh-pages` como source
4. O site ser� publicado automaticamente em: `https://seuusuario.github.io/flower-main`

## Op��o 2: Netlify (Gratuito)

1. Conecte sua conta GitHub ao Netlify
2. Selecione o reposit�rio `flower-main`
3. Deploy autom�tico ser� feito a cada push
4. URL personalizada dispon�vel

## Op��o 3: Vercel (Gratuito)

1. Conecte sua conta GitHub ao Vercel
2. Importe o projeto `flower-main`
3. Deploy autom�tico ser� feito a cada push
4. URL personalizada dispon�vel

## Desenvolvimento Local

```bash
# Instalar depend�ncias
npm install

# Executar servidor local
npm start

# Ou usar live-server para desenvolvimento
npm run dev
```

## Estrutura do Projeto

- `index.html` - P�gina principal
- `flower.html` - P�gina da anima��o
- `src/css/` - Estilos CSS
- `src/img/` - Imagens
- `main.js` - JavaScript da anima��o
