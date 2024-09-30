# Atividade

## Instruções

1) Escolha um dataset pronto adequado para classificação binária, evitando datasets "toy" como `Iris` ou `Pima Indians Diabetes`. Certifique-se de selecionar um dataset que ofereça desafios reais em termos de volume e complexidade.

2) Em seguida, explore o dataset escolhido e explique suas características principais, como o número de amostras, features, e a tarefa de classificação que ele representa.

3) Desenvolva um modelo sequencial em Keras com uma única camada Dense, utilizando uma unidade com a função de ativação sigmoid. Compile o modelo utilizando o otimizador adam, a função de perda binary_crossentropy, e a métrica accuracy. Inclua também a métrica F1 para uma avaliação mais completa, e explique brevemente a função de cada um desses componentes no treinamento.

4) Treine o modelo por 50 épocas com um batch size de 10. Após o treinamento, utilize o modelo para prever os rótulos do conjunto de teste e calcule tanto a acurácia quanto a métrica F1. Interprete os resultados, discutindo o desempenho do modelo e possíveis melhorias.

5) Entregue o link do caderno `.ipynb` em um repositório GitHub.
