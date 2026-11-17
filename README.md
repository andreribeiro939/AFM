# Fases AFm — Modelo 3D Interativo

Visualizador didático em português sobre as fases AFm, baseado nos conceitos da seção 6.1.1 de Taylor, *Cement Chemistry*.

## Publicação no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie o arquivo `index.html` para a raiz do repositório (o arquivo `.glb` é opcional e serve para baixar/inserir no PowerPoint; o visualizador HTML gera sua própria estrutura).
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/ (root)` e clique em **Save**.
6. O endereço normalmente será `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Controles

- Desktop: arrastar com mouse = girar; roda do mouse = zoom.
- Celular: um dedo = girar; dois dedos = aproximar/afastar.
- Botões: alterar fase AFm, vistas, rotação automática, reiniciar e tela cheia.
- Teclado: setas para girar, +/- para zoom, quando o visualizador está em foco.

## Observações

- O HTML carrega Three.js r128 via Cloudflare CDN; **é necessária uma conexão à internet** para carregar o motor 3D. No GitHub Pages funciona com acesso à rede.
- O arquivo GLB não precisa ser carregado pelo HTML, pois o modelo é gerado em JavaScript. Foi incluído para uso separado em softwares 3D e PowerPoint.
- O modelo representa princípios das fases AFm de modo **esquemático**; não utiliza coordenadas experimentais de um arquivo CIF e não deve ser usado para medidas cristalográficas.
