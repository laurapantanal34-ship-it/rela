# ExBack Accelerator - Instruções de Uso

## 📋 Sobre o Projeto

Este é o projeto **ExBack Accelerator**, um quiz interativo desenvolvido para ajudar pessoas a reconquistar seus relacionamentos. O projeto está completamente funcional e pronto para uso.

## 🚀 Como Executar o Projeto

### Pré-requisitos

- Node.js (versão 22 ou superior)
- pnpm (gerenciador de pacotes)

### Instalação

1. **Instalar as dependências:**
```bash
pnpm install
```

### Executar em Desenvolvimento

2. **Iniciar o servidor de desenvolvimento:**
```bash
pnpm dev
```

O projeto estará disponível em: `http://localhost:3000`

### Build para Produção

3. **Criar build de produção:**
```bash
pnpm build
```

4. **Executar em produção:**
```bash
pnpm start
```

## 📁 Estrutura do Projeto

```
quiz-app-reconquista/
├── client/                 # Código do frontend React
│   ├── src/
│   │   ├── components/    # Componentes UI reutilizáveis
│   │   ├── contexts/      # Contextos React (Theme)
│   │   ├── hooks/         # Hooks customizados
│   │   ├── lib/           # Utilitários
│   │   ├── pages/         # Páginas da aplicação
│   │   ├── app.tsx        # Componente principal
│   │   ├── main.tsx       # Entry point
│   │   └── index.css      # Estilos globais
│   └── public/
│       └── imagem/        # Assets de imagens
├── server/                # Servidor Express
│   └── index.ts           # Configuração do servidor
├── shared/                # Código compartilhado
├── imagem/                # Imagens do projeto
├── index.html             # HTML principal
├── package.json           # Dependências
└── vite.config.ts         # Configuração Vite
```

## 🛠️ Tecnologias Utilizadas

- **Frontend**: React 18.3.1 + TypeScript
- **Build Tool**: Vite 7.1.9
- **Styling**: TailwindCSS 4.1.14
- **UI Components**: Radix UI (componentes acessíveis)
- **Routing**: Wouter 3.7.1 (roteamento leve)
- **Backend**: Express 4.21.2
- **Package Manager**: pnpm 10.4.1

## ✨ Funcionalidades

### Quiz Interativo
- Sistema de perguntas com múltipla escolha
- Barra de progresso visual
- Navegação entre perguntas (avançar/voltar)
- Animações suaves entre transições
- Design responsivo para mobile

### Interface
- Tema claro otimizado
- Componentes UI profissionais (Radix UI)
- Ícones com Lucide React
- Tipografia Inter para melhor legibilidade

### Páginas
- **Home**: Página inicial com apresentação e CTA
- **Quiz**: Sistema de perguntas interativas
- **404**: Página de erro personalizada

## 🎨 Personalização

### Alterar Cores
Edite o arquivo `client/src/index.css` para modificar a paleta de cores do tema.

### Adicionar Novas Perguntas
As perguntas do quiz estão no arquivo `index.html`. Procure pela seção de perguntas e adicione novas seguindo o padrão existente.

### Modificar Componentes
Todos os componentes UI estão em `client/src/components/ui/` e podem ser personalizados conforme necessário.

## 📦 Scripts Disponíveis

- `pnpm dev` - Inicia servidor de desenvolvimento
- `pnpm build` - Cria build de produção
- `pnpm start` - Executa servidor de produção
- `pnpm preview` - Preview do build de produção
- `pnpm check` - Verifica erros TypeScript
- `pnpm format` - Formata código com Prettier

## 🌐 Deploy

O projeto está configurado para deploy no Netlify. Os arquivos de configuração incluem:

- `netlify.toml` - Configurações do Netlify
- `_redirects` - Regras de redirecionamento para SPA

Para fazer deploy em outros serviços, execute `pnpm build` e faça upload da pasta `dist/`.

## 📝 Notas Importantes

1. O projeto usa **pnpm** como gerenciador de pacotes. Certifique-se de tê-lo instalado.
2. Todas as imagens estão na pasta `imagem/` e são referenciadas no HTML principal.
3. O servidor Express serve os arquivos estáticos em produção.
4. O projeto suporta hot-reload durante o desenvolvimento.

## 🔧 Solução de Problemas

### Porta 3000 ocupada
Se a porta 3000 estiver em uso, o Vite automaticamente tentará a próxima porta disponível.

### Erros de instalação
Certifique-se de estar usando Node.js 22+ e execute:
```bash
pnpm install --force
```

### Build falhando
Limpe o cache e reconstrua:
```bash
rm -rf dist node_modules
pnpm install
pnpm build
```

## 📄 Licença

MIT License - Criado via Lunaris.online

---

**Projeto 100% funcional e pronto para uso!** ✅
