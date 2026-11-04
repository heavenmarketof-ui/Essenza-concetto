# Essenza Concetto — Candle Marketing & Strategy

Primeira versão do site responsivo com Home, dez páginas de tratamentos e painel em /admin.

## Executar

```bash
npm install
npm run dev
```

## Habilitar o painel

1. Crie um projeto Supabase e execute `supabase/schema.sql`.
2. Configure `VITE_SUPABASE_URL` e `VITE_SUPABASE_ANON_KEY` no ambiente e no Cloudflare Pages.
3. Crie a conta da Talita no Supabase Authentication e insira o UUID em `public.site_admins` pelo SQL Editor.
4. O painel permite editar textos, fotos e serviços existentes, com upload no Storage.
5. Configure o WhatsApp com código do país no painel.

## Deploy

Cloudflare Pages: comando `npm run build`, diretório `dist`.

## Antes de publicar

Imagens externas são ilustrativas; substituir por fotos licenciadas ou próprias. Logo original isolado ainda não fornecido. Confirmar textos, procedimentos e habilitação profissional. Não há promessa de resultados. O painel depende da configuração do Supabase; o site tem conteúdo inicial sem ele.
