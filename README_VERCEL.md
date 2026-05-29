# Publicar no Vercel

Use esta pasta para publicar a dashboard como site.

## O que o Vercel resolve

- Os botoes funcionam online.
- O time acessa por um link.
- Nao depende do preview do SharePoint.

## Limite importante

O Vercel nao edita automaticamente a planilha do SharePoint.

Fluxo recomendado:

1. A planilha oficial continua no SharePoint.
2. O time abre o link da dashboard no Vercel.
3. Clica em `Importar planilha`.
4. Seleciona `Cronograma de campanhas para GANTT.xlsx`.
5. Confere o Gantt.
6. Exporta CSV ou Asana CSV se precisar.

O botao `Salvar` salva no navegador da pessoa. Ele nao substitui a planilha oficial.

## Como publicar sozinha

Opcao mais simples:

1. Crie uma conta em https://vercel.com.
2. Crie um projeto novo.
3. Envie esta pasta `VERCEL_ROADMAP_AUDACES`.
4. Confirme que o arquivo principal e `index.html`.
5. Publique.
6. Compartilhe o link gerado com o time.

Opcao via terminal:

```text
npm i -g vercel
cd VERCEL_ROADMAP_AUDACES
vercel
vercel --prod
```

## O que mandar para o time

Mande o link do Vercel e diga:

```text
Abram o link da dashboard, cliquem em Importar planilha e selecionem o arquivo Cronograma de campanhas para GANTT.xlsx atualizado no SharePoint.
```
