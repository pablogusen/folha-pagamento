# folha-pagamento
Análise da Folha de Pagamento - ISSSPL/ALMT

## Estrutura do Projeto

- `github-pages/` - Diretório contendo os arquivos para publicação no GitHub Pages

## Publicação no GitHub Pages

O diretório `github-pages` contém uma página web estática para apresentação da análise de folha de pagamento. Para publicar essa análise, siga as instruções no arquivo [github-pages/README.md](github-pages/README.md).

### Método 1: Usando comandos Git (do diretório github-pages)

```bash
cd github-pages
git init
git add .
git commit -m "Publicar análise de folha"
git branch -M main
git remote add origin https://github.com/pablogusen/folha-pagamento.git
git push -u origin main
```

### Método 2: Usando GitHub Pages diretamente

1. Acesse as configurações do repositório no GitHub
2. Vá para Settings → Pages
3. Configure a publicação a partir da pasta `/github-pages`
4. Aguarde alguns minutos para a página ficar disponível

## Visualização Local

Para visualizar a análise localmente antes de publicar:

```bash
cd github-pages
python -m http.server 8000
```

Depois acesse `http://localhost:8000` no navegador.
