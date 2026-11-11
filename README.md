# Quanto falta pra passar

Calculadora de boletim em uma página só. Mostra quanto cada disciplina precisa tirar no 3º trimestre pra fechar com a média mínima.

## O que faz

- 17 disciplinas, 3 trimestres, média mínima 6 (configurável).
- Cada trimestre pode ser **Fechada** (uma nota) ou **Parcial** (notas dos trabalhos). No modo Parcial a nota estimada é a soma dos trabalhos corrigidos ÷ número de trabalhos.
- Número de trabalhos ajustável por disciplina.
- Resumo do que falta no 3º trimestre, com a nota necessária, a média dos trabalhos restantes e os casos fora do alcance.
- Exporta o resumo em imagem PNG.
- Funciona no celular, com tema claro e escuro.

## Como o cálculo funciona

A média final é (1º + 2º + 3º trimestre) ÷ 3. Pra fechar com média 6, a soma dos três precisa chegar a 18. A nota necessária no 3º trimestre é 18 menos a soma do 1º e do 2º. Se passa da nota máxima, a disciplina aparece como fora do alcance.

## Como usar

Abra o `index.html` no navegador. Não precisa instalar nada nem ter servidor.

Pra publicar com GitHub Pages: no repositório, vá em **Settings → Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.

## Onde as notas ficam salvas

No navegador de quem usa (`localStorage`), por aparelho. Limpar os dados do site apaga as notas. Nada é enviado pra servidor.
