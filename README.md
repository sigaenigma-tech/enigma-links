# ENIGMA // CONNECT

Página estática de links oficiais da ENIGMA.

## Publicar gratuitamente na Vercel
1. Crie um repositório novo no GitHub.
2. Envie `index.html` e `vercel.json`.
3. Na Vercel, crie um novo projeto importando esse repositório.
4. Framework Preset: **Other**.
5. Build Command: deixe vazio.
6. Output Directory: deixe vazio.
7. Deploy.

## Logo e tipografia
O layout já está com a estética definida. O símbolo no topo é apenas um placeholder geométrico para evitar alterar/recriar a logo oficial. Quando tiver o arquivo oficial da logo disponível na pasta do projeto, substitua o bloco `.mark` por uma imagem, por exemplo:

```html
<div class="mark"><img src="logo-enigma.svg" alt="ENIGMA"></div>
```

Para usar Besan exatamente, adicione o arquivo da fonte ao seu projeto (caso tenha licença/arquivo próprio) e uma regra `@font-face` no CSS. Não inclua nem redistribua arquivos de fonte sem a licença adequada.
