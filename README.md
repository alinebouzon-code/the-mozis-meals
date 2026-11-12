# The Mozis Meals — GitHub Pages

Este projeto hospeda o site The Mozis Meals gratuitamente no GitHub Pages.

## Publicação inicial

1. No GitHub, crie um repositório **público** chamado `the-mozis-meals` com a branch `main`.
2. Envie os arquivos e pastas deste pacote ao repositório, preservando a estrutura: `index.html`, `.nojekyll` e `.github/workflows/deploy.yml`.
3. Abra **Settings → Pages → Build and deployment → Source: GitHub Actions**.
4. Abra a aba **Actions** e acompanhe a execução **Publicar The Mozis Meals no GitHub Pages**. Se necessário, clique em **Run workflow**.
5. O endereço normalmente será `https://SEU-USUARIO.github.io/the-mozis-meals/`. O link exato aparecerá em **Settings → Pages**.

## Alterações automáticas

Quando quiser atualizar o site, substitua `index.html` pela nova versão e envie a alteração por **Commit changes** no GitHub ou **Commit → Push** no GitHub Desktop. A publicação será disparada automaticamente a cada push para `main`, mantendo o mesmo endereço público.

## Atenção às receitas personalizadas

As receitas, alterações e listas salvas no navegador atualmente usam `localStorage`. Essas informações não são sincronizadas entre aparelhos pelo GitHub Pages. Utilize Exportar/Importar receitas como backup. Um banco de dados ou serviço de sincronização seria necessário para compartilhar dados automaticamente.

## Direitos de imagem e internet

Algumas fotos são carregadas de sites externos. Verifique o direito de utilização/publicação antes de tornar público um site que as exibe; o fato de haver um link público não garante licença de republicação. Imagens e fontes externas podem exigir acesso à internet.
