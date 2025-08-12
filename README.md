# SimakLink Frontend - Phase Out

Este é o frontend do projeto SimakLink, uma aplicação web construída com Nuxt.js.

## Sobre o Projeto

Este diretório contém os arquivos estáticos já buildados da aplicação Nuxt.js, prontos para deploy no Azure Static Web Apps.

## Estrutura do Projeto

- `_nuxt/` - Arquivos buildados do Nuxt.js
- `*.html` - Páginas HTML estáticas
- `css/` - Arquivos CSS
- `fonts/` - Fontes da aplicação
- `images/` - Imagens e ícones
- `staticwebapp.config.json` - Configuração do Azure Static Web Apps

## Deploy

O projeto está configurado para deploy automático no Azure Static Web Apps através do GitHub Actions.

### Configurações do Deploy

- **App Location**: `/` (raiz do projeto)
- **Output Location**: `/` (arquivos já buildados)
- **Skip App Build**: `true` (arquivos já estão buildados)

## Configuração do Azure Static Web Apps

O arquivo `staticwebapp.config.json` define:
- Rotas para SPA (Single Page Application)
- Fallback para `index.html`
- Headers de segurança
- Configurações de cache

## Desenvolvimento

Para desenvolvimento local, você precisará do código fonte original do Nuxt.js. Este diretório contém apenas os arquivos de produção.
Ajustes no Workflow