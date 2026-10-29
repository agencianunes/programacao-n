# programacao-n

Casca de uma pagina que mostra a programacao de mensagens de WhatsApp de um lancamento:
o que ja foi pro ar, o que esta na fila e o que ainda nao foi programado, com o texto de
cada mensagem renderizado como bolha de WhatsApp.

**Nao ha dado nem credencial neste repositorio.** O conteudo vem de uma API com token, e o
token viaja na URL da pagina (`?k=`), nao no codigo. Abrir o endereco sem token nao mostra
nada.

Por que GitHub Pages: bucket do Supabase e Edge Function entregam HTML como `text/plain`
(protecao anti-XSS), e o deploy em Cloudflare Pages esta travado por token expirado. Aqui o
HTML e servido como HTML.

Co-Authored-By: Claude Opus 5 <noreply@anthropic.com>
