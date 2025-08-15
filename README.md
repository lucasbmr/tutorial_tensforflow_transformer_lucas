# Tutorial TensorFlow Transformer para Tradução

Lucas Rego - G3

##  Resumo do Tutorial
O tutorial apresenta a construção de um modelo Transformer para tradução automática, baseado no artigo “Attention Is All You Need”. Utilizando os blocos de código oferecidos, percorremos desde o pré-processamento dos dados, tokenização, criação das camadas de atenção, até o treinamento e avaliação do modelo.  
O objetivo é implementar, passo a passo, um sistema de tradução capaz de mapear sentenças de um idioma para outro de forma eficiente.

## Aprendizados
Ao seguir o tutorial, aprendi sobre:
- **Transformer** — Entender como as camadas de *multi-head attention* e *feed-forward networks* se combinam para processar sequências.
- **Mecanismo de Atenção** — Compreender o papel da *self-attention* e como ela captura dependências no texto.
- **Positional Encoding** — Inserção de informações de posição nas sequências para que o modelo entenda a ordem das palavras.
- **Tokenização e Pré-processamento** — Preparação do dataset, segmentação em subpalavras e criação de batches.
- **Função de Perda com Máscara** — Uso de máscaras para ignorar tokens de preenchimento durante o cálculo da perda.
- **Treinamento no TensorFlow** — Configuração de train steps, métricas e avaliação.
- **Comparação CPU vs GPU** — Experiência prática na diferença de velocidade de processamento.

##  Pontos Positivos
  O tutorial é bem estruturado, com cada bloco de código acompanhado de explicações detalhadas. Ele permite entender o funcionamento interno do Transformer sem depender apenas de bibliotecas prontas. É interessante também que o código pode ser reutilizavel e a implementação pode servir de base para outros projetos de PLN. 

##  Pontos Negativos
  O treinamento completo pode ser bastante demorado, tornando a experiência cansativa. Eu também senti que algumas funções são extensas e me exigiram reler mais de uma vez para a compreensão.

##  Percepções sobre Desempenho
- **Treinamento com CPU** — Foi perceptivelmente mais lento, levando horas para concluir as épocas. O que seria ideal apenas para testes de código e não para treino real.
- **Treinamento com GPU** — Acelerou significativamente o processo, permitindo um ciclo de experimentação mais rápido e eficiente.
- **Experiência prática** — A diferença de performance clara onde com a GPU, o aprendizado é muito mais produtivo.

##  Conclusão
Seguir o tutorial foi muito bom para compreender na prática como funciona um modelo Transformer aplicado à tradução de idioma.  
O material é claro e a implementação detalhada permitem não apenas replicar o exemplo, mas também servir como base para projetos futuros.  
Meu aprendizado principal é a importância da atenção na modelagem de sequências e como a arquitetura Transformer revolucionou o campo do Processamento de Linguagem Natural.  
Apesar das dificuldades de execução e tempo de treino, especialmente sem GPU, o conteúdo foi muito bom e me ajudará bastante nesse módulo.
