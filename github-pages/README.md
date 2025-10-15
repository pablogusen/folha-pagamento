# GitHub Pages - Análise de Folha de Pagamento

Este diretório contém os arquivos estáticos para publicação da análise de folha de pagamento no GitHub Pages.

## Estrutura

- `index.html` - Página principal da análise
- `styles.css` - Estilos CSS
- `script.js` - Funcionalidades JavaScript

## Como Publicar

Para publicar esta análise no GitHub Pages, execute os seguintes comandos:

```bash
cd github-pages
git init
git add .
git commit -m "Publicar análise de folha"
git branch -M main
git remote add origin https://github.com/pablogusen/folha-pagamento.git
git push -u origin main
```

Ou use o GitHub Pages diretamente do branch principal:

1. Vá para Settings → Pages no repositório GitHub
2. Selecione o branch desejado
3. Escolha a pasta `/github-pages` como source
4. Salve as configurações

## Personalização

Para personalizar a análise:

1. Edite os dados em `script.js`
2. Ajuste o layout em `index.html`
3. Modifique os estilos em `styles.css`

## Visualização Local

Para visualizar localmente, abra o arquivo `index.html` em um navegador web ou use um servidor HTTP local:

```bash
# Com Python
python -m http.server 8000

# Com Node.js (http-server)
npx http-server
```

Depois acesse `http://localhost:8000` no navegador.
