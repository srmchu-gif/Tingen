# Arquivos de Tingen

Jogo de investigação para Android ambientado no mundo de *Lord of the Mysteries*. Projeto de fã, gratuito e offline.

**Baixar:** https://srmchu-gif.github.io/Tingen/

## Como publicar (para o dono do repositório)

Os arquivos do site (`index.html`, `assets/`, `_headers`, `.nojekyll`) ficam na raiz do repositório, ao lado do APK.

**GitHub Pages:** Settings → Pages → Source: *Deploy from a branch* → Branch `main`, pasta `/ (root)` → Save. Em um ou dois minutos o site abre em `https://srmchu-gif.github.io/Tingen/`.

**Cloudflare Pages (opcional):** Workers & Pages → Create → Pages → Connect to Git → escolha este repositório → Framework: *None*, Build command: vazio, Output directory: `/`. O Cloudflare aceita arquivos de até 25 MiB; o APK atual tem 24,5 MiB. Se um APK futuro passar disso, use o GitHub Pages ou anexe o APK numa Release.

**Versão nova:** suba o APK novo e troque no `index.html` o nome do arquivo (dois links), a versão, o tamanho e o SHA-256 (`certutil -hashfile release\ArquivosDeTingen-X.Y.Z.apk SHA256`). Pode apagar o APK antigo do repositório.
