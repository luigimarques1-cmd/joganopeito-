# JOGA NO PEITO — Catálogo atualizado com novas URLs

Site estático em HTML, CSS e JavaScript, pronto para GitHub Pages e Vercel. Publique **todos os arquivos e a pasta `assets/` juntos**.

## Alterações aplicadas nesta versão

- **Banner principal preservado**, sem mudança na imagem ou no seu link.
- Atualizados os banners horizontais de Copa do Mundo, Brasileirão, La Liga, Premier League, Série A, Bundesliga, Ligue 1, Times da América, Resto do Mundo e NBA.
- Atualizada **somente a imagem** do banner de Fórmula 1 (1920 × 800 de referência). O link de catálogo anterior foi preservado.
- Adicionados os clubes **AL-NASSR** e **AL-HILAL**, com os links de escudo e catálogo enviados, **ao final** dos 12 clubes já existentes em Resto do Mundo (total 14).
- Configurada a seção **OUTRAS COLEÇÕES** com banner horizontal e oito imagens 1:1 com os links fornecidos: Kit Frio, Kit Frio Capuz, Corta Vento, Kit Treino, Baby Jersey, Bobojaco, Manga Longa e Shorts.
- Mantida a ordenação dos 23 clubes do Campeonato Brasileiro: Flamengo, Vasco, Fluminense, Botafogo; Corinthians, Palmeiras, São Paulo, Santos; depois os demais.
- Atualizados **apenas os links dos catálogos** de **RETRÔ**, **KIT INFANTIL**, **FEMININAS** e **JOGADOR**; imagens, formato circular, posição e design dessas coleções foram mantidos. Os demais catálogos e escudos existentes, WhatsApp e Instagram permanecem sem alteração.
- A segunda seção nova **continua configurada, mas oculta do site** enquanto seu nome, banner e itens não são informados (para não mostrar escudos de exemplo como se fossem reais). É ativada quando for preenchida: procure `"secao-extra-02"` e altere `"ativo": false` para `true` em `configuracao.js`.

## Links ainda pendentes

Veja `PENDENCIAS_PARA_FINALIZAR.txt` para copiar e preencher. Atualmente:

1. Nova seção 01 / **OUTRAS COLEÇÕES**: fornecidos oito itens; faltam quatro caso deseje completar os 12 previstos.
2. Nova seção 02: faltam nome, banner e os 12 conjuntos de imagem + catálogo.
3. Catálogo da Fórmula 1: **só é pendência se você quiser trocá-lo**; o atual continua válido na configuração.

## Onde alterar as URLs

Edite `configuracao.js`. Os banners das ligas usam `bannerDesktop`; a imagem da Fórmula 1 usa `bannerFormula1.imagem`; as bolinhas usam `nome`, `imagem` e `link`. Imagens horizontais têm referência **1080 × 608 px**; as bolinhas são **quadradas 1:1**.

## Publicar no GitHub/Vercel

Descompacte o arquivo ZIP e substitua os arquivos existentes no repositório (sem criar uma pasta extra acima do `index.html`). Faça commit; se a Vercel estiver conectada ao repositório, ela fará o deploy conforme sua configuração.
