<div style="text-align: center;"> <img src="https://static-00.iconduck.com/assets.00/aws-icon-1024x1024-runl182z.png" alt="drawing" width="150" style="border-radius:50%; display: block; margin-left: auto; margin-right: auto;"/> </div>

# Desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas"

>Desafio proposto pelo bootcamp da plataforma DIO, com o objetivo de desenvolver um modelo de previsão de estoque utilizando o SageMaker Canvas e documentar o processo em um repositório no GitHub.

## Etapas do desenvolvimento

### Primeira etapa 

Criação inicial de um modelo customizável de análise preditiva, concomitantemente ao upload de um dataset robusto com 1000 amostras de produtos com preço promocional e renovação de estoque.

### Segunda etapa

Definição da coluna de destino (estoque) e configuração do modelo, atribuindo a coluna de ID do produto, além da adesão às sugestões (replace) das alterações sugeridas na própria plataforma. Após isso, iniciei o treinamento do modelo com o quick build.  

### Terceira etapa

Análise dos resultados:
- `avG.wql: 0.60` - Média ponderada da qualidade da previsão. Quanto mais próximo de 1, melhor.
- `MAPE: 0.148` - Erro médio absoluto percentual. Quanto menor, melhor previsão.   
- `WAPE: 0.100` - Erro médio absoluto ponderado. Idem.
- `RMSE: 5.765` - Raiz do erro quadrático médio. Quanto menor, melhor ajuste do modelo.
- `MASE: 0.301` - Erro médio absoluto estacionarizado. Valores abaixo de 1 indicam previsões melhores do que uma média móvel simples.

Estes valores indicam um bom ajuste inicial do modelo ao dataset.

### Quarta etapa

Predição das variáveis de preços e sua correspondência para com os estoques em pauta para a previsão, além do reconhecimento da enorme capacidade da ferramenta em prever de forma dinâmica e simples dos dados configurados.

## Conclusão

Ferramentas de código aberto e acessíveis como o SageMaker Canvas são extremamente importantes para o desenvolvimento e aprimoramento de modelos de aprendizado de máquina. Isso permite que pessoas de diferentes áreas apliquem técnicas de Data Science e contribuam para o avanço do conhecimento.
