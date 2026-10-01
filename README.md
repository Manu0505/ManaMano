# Fundo ManaMano · site

Site institucional do Fundo ManaMano, projeto de extensão da UFRJ.
Identidade visual: LUPA. Publicado pela Vercel a cada alteração na branch `main`.

## Estrutura

- `index.html`: o site inteiro (estilos, conteúdo e animações).
- `assets/`: logo, ícones temáticos, formas, texturas e a mão "Deslizar", extraídos do Manual de Arte e Criação.

## Como atualizar o conteúdo

1. Abra `index.html` aqui no GitHub e clique no lápis (Edit).
2. Procure o bloco `const CONTEUDO = {`. Todo texto do site está nele.
3. Edite apenas o que está entre aspas. Não apague vírgulas, chaves ou colchetes.
4. Clique em **Commit changes**. Em cerca de um minuto a Vercel publica a nova versão.

## Empreendedoras, professores e relatos

- Cada item só aparece no site com `publicado: true`.
- Antes de publicar, confirme a autorização de uso de imagem e de nome assinada pela pessoa.
- Fotos vão para `assets/fotos/` e o caminho entra no campo `foto`, por exemplo
  `foto: { src: "assets/fotos/nome.png", alt: "Descrição da foto" }`.
- Com nenhum item publicado, a seção some do site e do menu.

## Modo prévia

`modoPrevia: false` é a versão pública. Mudar para `true` mostra os itens de exemplo com selo, útil apenas para revisão interna.

## Pendências

- Link da página do Facebook (`contato.facebook.url`).
- Nome correto da disciplina "Formação de Custos".
- Favicon provisório: o manual não prevê o símbolo sem o logotipo.
