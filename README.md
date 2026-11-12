# MSA — Análise de Sistemas de Medição

**Aprenda a avaliar sistemas de medição com exemplos em Python**

Material complementar do livro de **Ruan Carvalho Mayworm**.

[![Abrir no Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rcmayworm/msa-com-python/blob/main/msa_aplicacoes.ipynb)

[Ver o notebook no GitHub](https://github.com/rcmayworm/msa-com-python/blob/main/msa_aplicacoes.ipynb) · [Baixar o arquivo .ipynb](https://raw.githubusercontent.com/rcmayworm/msa-com-python/main/msa_aplicacoes.ipynb)

## Planilha Excel

[**Baixar a planilha Excel (.xlsx)**](https://raw.githubusercontent.com/rcmayworm/msa-com-python/main/msa_calculos.xlsx)

A planilha oferece uma alternativa para acompanhar os principais cálculos sem programar. Contém instruções, entradas destacadas em amarelo, fórmulas automáticas e gráficos editáveis, sem macros.

Inclui Gage R&R por médias e amplitudes e ANOVA, tendência e linearidade, estudo tipo 1, cartas de estabilidade e análise por atributos com kappa de Cohen e de Fleiss. Os exemplos de eixos e de resistência elétrica são selecionados na aba **GRR**. A crimpagem e as matrizes das tampas estão na aba **Atributos**.

Salve uma cópia antes de substituir os dados amarelos. Os tamanhos dos estudos são fixos nesta versão: Gage R&R de **10 peças × 3 avaliadores × 3 repetições**, linearidade com 60 ou 30 leituras, tipo 1 com 25 repetições e estabilidade com 24 subgrupos de cinco leituras. Não insira nem exclua linhas. Ajuste a faixa de comparação e mantenha uma única unidade por estudo. A faixa de 0,40 mΩ do exemplo elétrico é ilustrativa e não representa uma tolerância bilateral.

Esta versão foi recalculada no Microsoft Excel 16.0, comparada com os exemplos em Python e submetida a 119 verificações de resultados, troca de estudo, entradas ausentes e categorias inválidas. A compatibilidade com o Google Sheets ainda não foi validada.

## Como acompanhar o notebook

1. Abra o notebook pelo botão **Abrir no Google Colab**.
2. Entre com sua conta Google e salve uma cópia no Drive pelo menu **Arquivo**.
3. Conecte ao ambiente de execução e execute as **quatro células de preparação**, na ordem.
4. Execute as células do capítulo pelo botão de reprodução ou por **Shift+Enter**.
5. Ao alterar os dados, execute novamente o cálculo e a visualização.

O Colab oferece um ambiente Python pronto pelo navegador. O notebook é autocontido, com dados, funções e exemplos no mesmo arquivo. A execução é opcional para acompanhar o livro. O **Apêndice F** explica as principais chamadas, suas bibliotecas e as funções desenvolvidas para o material.

## Conteúdo da versão 1.0

Os 16 exemplos de cálculo e os seis gráficos acompanham os capítulos do livro. O material inclui fundamentos, planejamento, Gage R&R por médias e amplitudes e ANOVA, interpretação, tendência, linearidade, estudo tipo 1, estabilidade e atributos. Os estudos finais tratam da resistência elétrica a quatro fios e da inspeção visual da crimpagem.

Os dados são hipotéticos ou simulados e estão identificados como didáticos. As 26 células foram verificadas em um ambiente Python independente. O ambiente de verificação usou Python 3.13, NumPy 2.2.6, SciPy 1.15.3 e Matplotlib 3.10.9.

## Acesso pela edição impressa e versões

O endereço do GitHub impresso no livro leva a esta página:

**https://github.com/rcmayworm/msa-com-python**

Os QR codes do notebook e da planilha abrem diretamente os arquivos vigentes. A cada atualização, os arquivos `msa_aplicacoes.ipynb` e `msa_calculos.xlsx` são atualizados na raiz da branch `main`, com os mesmos endereços.

A [pasta da versão 1.0](https://github.com/rcmayworm/msa-com-python/tree/main/v1.0) guarda os arquivos publicados originalmente.
