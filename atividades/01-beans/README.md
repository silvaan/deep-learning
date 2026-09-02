# Atividade: Classificação de Grãos

## Dataset

Para esta tarefa, utilizaremos uma versão adaptada do Dry Bean Dataset, disponível no arquivo `data/beans_train.csv`. O conjunto é composto por amostras de diferentes tipos de feijões secos, descritas por atributos morfológicos extraídos a partir de imagens, como área, perímetro, compacidade, excentricidade e fatores de forma. Essas características capturam propriedades geométricas relevantes dos grãos, permitindo distinguir classes com base em padrões estruturais no espaço de atributos.

As amostras estão organizadas em sete classes distintas de feijões: Seker, Barbunya, Bombay, Cali, Dermason, Horoz e Sira. As classes não estão balanceadas, e os atributos estão em escalas bastante diferentes entre si.

O arquivo `data/beans_test.csv` contém as mesmas colunas, sem a coluna `Class`, e é utilizado na competição descrita em `competicao.md`.

## O que será avaliado

Serão considerados os seguintes aspectos:

* **Implementação:** Coerência entre o problema proposto e o método de classificação adotado, bem como a correta aplicação do algoritmo.
* **Estabilidade:** Controle do comportamento do processo de treinamento, assegurando convergência consistente e reduzindo variações indesejadas ao longo da otimização.
* **Regularização:** Capacidade de mitigar o sobreajuste por meio de estratégias adequadas ao modelo e aos dados.
* **Análise de Desempenho:** Interpretação dos resultados com base em métricas apropriadas de avaliação, considerando o desbalanceamento entre as classes.

## Entrega

A atividade deve ser entregue obrigatoriamente em formato de **Jupyter Notebook (.ipynb)**. O arquivo deve estar devidamente organizado e comentado, justificando as decisões tomadas para garantir a estabilidade e a capacidade de generalização do modelo.
