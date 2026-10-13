# The Darkest Pit

RPG tático gótico por turnos: formação em 4 posições, estresse e aflições, tocha que se apaga, itens, loja e três masmorras com chefes diferentes. Tudo em um único arquivo (`index.html`), sem bibliotecas nem imagens externas.

## Jogar localmente
Abra o `index.html` no navegador. Não precisa de servidor.

## Publicar no GitHub Pages (pelo site, sem comandos)
1. No GitHub, clique em **New repository**, dê um nome (ex.: `the-darkest-pit`) e marque **Public**.
2. Clique em **uploading an existing file** e envie `index.html`, `README.md` e `.nojekyll`.
3. Clique em **Commit changes**.
4. Vá em **Settings → Pages**. Em **Build and deployment**, escolha **Deploy from a branch**, branch **main**, pasta **/ (root)**, e salve.
5. Em 1 a 2 minutos o jogo estará em `https://SEU-USUARIO.github.io/the-darkest-pit/`.

## Publicar com git
```bash
git init && git add . && git commit -m "The Darkest Pit"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/the-darkest-pit.git
git push -u origin main
```
Depois ative o Pages como no passo 4 acima.

## Notas
- O progresso é salvo no `localStorage` do navegador de cada jogador (não é compartilhado entre aparelhos).
- O som só começa depois do primeiro toque na tela (regra dos navegadores).
- Para atualizar o jogo, substitua o `index.html` no repositório e faça um novo commit.
