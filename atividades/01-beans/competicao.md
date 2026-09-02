# Competição: Classificação de Grãos

Nesta atividade, será realizada uma competição de classificação, na qual o objetivo é desenvolver um modelo capaz de predizer corretamente as classes dos grãos a partir de seus atributos.

Serão utilizados dois arquivos: **data/beans_train.csv**, contendo os dados de treinamento com rótulos (o mesmo da *Atividade da Unidade I*), e **data/beans_test.csv**, contendo apenas os atributos, sem as classes correspondentes. O modelo deverá ser treinado com base no conjunto de treinamento e utilizado para inferir as classes do conjunto de teste.

O entregável deverá consistir exclusivamente em um arquivo no formato **.csv**, contendo as *strings* das classes preditas para cada amostra do conjunto de teste. O arquivo deve seguir exatamente a mesma ordem das amostras em **beans_test.csv**, possuir uma única coluna chamada **Class** e conter 2.723 linhas além do cabeçalho. As classes devem ser escritas em caixa alta, exatamente como aparecem no arquivo de treinamento. Por exemplo:

```
Class
SEKER
BARBUNYA
SEKER
DERMASON
...
```

Não serão aceitos notebooks, links, arquivos compactados ou quaisquer outros formatos externos. A avaliação será baseada na acurácia das predições realizadas no conjunto de teste. O primeiro lugar receberá **1,0 ponto extra**, e o segundo lugar receberá **0,5 ponto extra**.
