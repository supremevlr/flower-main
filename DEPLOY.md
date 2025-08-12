# Como Deployar o Site Flower-Main

## Opção 1: GitHub Pages (Gratuito)

1. Faça push do código para um repositório GitHub
2. Vá em Settings > Pages
3. Selecione a branch `gh-pages` como source
4. O site será publicado automaticamente em: `https://seuusuario.github.io/flower-main`

## Opção 2: Netlify (Gratuito)

1. Conecte sua conta GitHub ao Netlify
2. Selecione o repositório `flower-main`
3. Deploy automático será feito a cada push
4. URL personalizada disponível

## Opção 3: Vercel (Gratuito)

1. Conecte sua conta GitHub ao Vercel
2. Importe o projeto `flower-main`
3. Deploy automático será feito a cada push
4. URL personalizada disponível

## Desenvolvimento Local

```bash
# Instalar dependências
npm install

# Executar servidor local
npm start

# Ou usar live-server para desenvolvimento
npm run dev
```

## Estrutura do Projeto

- `index.html` - Página principal
- `flower.html` - Página da animação
- `src/css/` - Estilos CSS
- `src/img/` - Imagens
- `main.js` - JavaScript da animação
