# Mapa-Múndi Interativo

Mapa estático em D3.js com 11 países destacados. Passe o mouse para ver o nome em inglês; clique em um destaque para aproximar e clique novamente ou no fundo branco para voltar à visão geral.

## Incorporar no SharePoint

Adicione a web part **Incorporar** (*Embed*) e cole:

```html
<iframe src="https://pedro-pauletti.github.io/mapa-mundi-embed/" width="100%" height="550" style="border:0; border-radius:12px; background:#ffffff;" title="Mapa-Múndi Interativo"></iframe>
```

Se o SharePoint bloquear o iframe, solicite que o administrador da coleção de sites adicione `pedro-pauletti.github.io` à lista de domínios permitidos em **HTML Field Security**.

O GitHub Pages publica a raiz (`/`) da branch `main`. D3.js, TopoJSON e os dados geográficos do World Atlas são carregados via CDN.
