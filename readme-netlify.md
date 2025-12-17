# Quiz App Reconquista - Deploy na Netlify

## 📋 Instruções de Deploy

### Opção 1: Drag & Drop (Mais Fácil)
1. Acesse https://app.netlify.com/drop
2. Arraste a pasta `netlify-deploy` para a área de upload
3. Pronto! Seu site estará online em segundos

### Opção 2: Git (Recomendado)
1. Faça upload deste arquivo para seu repositório GitHub
2. Conecte o repositório na Netlify
3. Configure o build command: `echo 'Deploy pronto!'`
4. Configure o publish directory: `.`
5. Deploy automático!

### Opção 3: CLI
```bash
npm install -g netlify-cli
netlify deploy --prod --dir=.
```

## 📁 Estrutura de Arquivos
- `index.html` - Página principal do quiz
- `imagem/` - Todas as imagens do projeto
- `netlify.toml` - Configuração da Netlify

## ✅ Checklist Antes de Deploy
- [x] Todas as imagens estão em `imagem/`
- [x] Link de checkout está configurado
- [x] Vídeo Vimeo está funcionando
- [x] Todos os botões CTA redirecionam para checkout

## 🔗 Links Importantes
- Checkout: https://lastlink.com/p/CD995B711/checkout-payment
- Documentação Netlify: https://docs.netlify.com/

## 💡 Dicas
- O arquivo `netlify.toml` configura redirecionamentos automáticos
- Todas as rotas internas funcionam automaticamente
- Cache é otimizado automaticamente pela Netlify

Boa sorte com seu deploy! 🚀
