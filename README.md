# Notas em aberto

Blog pessoal de pehprado baseado no tema Tale, com interface em português.

## Publicar no GitHub Pages

1. Crie um repositório público chamado `pehprado.github.io` na conta `pehprado`. Se ele já existir, confira seu conteúdo antes de enviar estes arquivos.
2. Envie os arquivos deste projeto para a raiz da branch `master`, incluindo as pastas cujos nomes começam com `_`.
3. Em Settings → Pages, selecione Deploy from a branch, branch `master` e pasta `/ (root)`, e salve.
4. Aguarde o build do GitHub Pages. O endereço esperado é https://pehprado.github.io/.

## Escrever uma nota

Copie `_drafts/minha-primeira-nota.md` para `_posts/AAAA-MM-DD-titulo-da-nota.md`, usando a data da publicação. Edite título, descrição, tags e texto. Crie a pasta `_posts` ao publicar sua primeira nota. Cada commit na branch publicada atualiza o blog.

O modelo está em rascunhos e não aparece no site publicado. A página Sobre contém uma sugestão de texto para você revisar.

## Rodar localmente

Com Ruby e Bundler compatíveis com a gem github-pages instalados:

```sh
bundle install
bundle exec jekyll serve --drafts
```

Abra http://127.0.0.1:4000. Para conferir a versão de produção, use `bundle exec jekyll build` sem `--drafts`.

## Créditos

Tema original: https://github.com/chesterhow/tale. A licença MIT original está preservada em LICENSE.
