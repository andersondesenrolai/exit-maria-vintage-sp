# Maria × EXIT — São Paulo

Apresentação estática da proposta de conteúdo pré-evento para Maria, cobrindo os eventos da EXIT em São Paulo. Cada evento tem seu próprio acordo/permuta, copy dos vídeos e roteiro técnico, acessíveis por um seletor de eventos no topo.

## Eventos cobertos

- **Vintage Culture** — 18/09 · Komplexo Tempo · 4 PMT pista · 2 vídeos (Ingresse, cupom EXIT)
- **Piknic Electronik (Deep Dish)** — 20/09 · Varanda Estaiada · 5 PMT pista · 2 vídeos (agtoday, cupom EXIT)

## Publicação

- Produção: https://exit-maria-vintage-sp.vercel.app (URL atual — projeto Vercel ainda com o nome antigo)
- Projeto Vercel: `exit-maria-vintage-sp` (time `andersonmassuzaki`) — **rename pendente** para `exit-maria-sp`
- Repositório: https://github.com/andersondesenrolai/exit-maria-vintage-sp
- Deploy inicial: 04/08/2026 — `dpl_45YNZyvFHzkiooeHR44ojLdFySwX`

## Estrutura

- `index.html`: proposta completa e responsiva, com seletor de eventos e três seções por evento (acordo, copy, roteiro).
- `assets/logos/`: logotipo EXIT usado no cabeçalho.
- `assets/design-system/fonts/`: fontes locais do design system.
- `vercel.json`: configuração de URLs limpas.

## Pendências

- **Rename do projeto Vercel** de `exit-maria-vintage-sp` para `exit-maria-sp` (dashboard ou API — não é feito só renomeando a pasta local). A URL de produção muda junto.
- **Rename do repositório GitHub** (opcional, depende de acesso de escrita).
- Confirmar cupom e link finais do Piknic (agtoday) antes de publicar os vídeos.
- Push pendente: a credencial da sessão (`andersonmassuzaki`) não tem escrita em `andersondesenrolai/exit-maria-vintage-sp`. Reautenticar e rodar `git push -u origin main`.
