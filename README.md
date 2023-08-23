# Biomechanical Features of Orthopedic Patients

Este projeto utiliza um classificador de árvore de decisão para analisar e classificar características biomecânicas de pacientes ortopédicos.

## Requisitos

- Python 3.x
- pandas
- scikit-learn
- numpy

## Como Usar

1. **Preparar os Dados**: Certifique-se de ter o arquivo CSV contendo os dados dos pacientes ortopédicos. O arquivo deve estar no caminho especificado no código (`/content/column_2C_weka.csv`).
2. **Verificar Valores Faltantes e Tipagem**: O código começa verificando valores faltantes e a tipagem dos dados.
3. **Preparar Variáveis de Entrada e Saída**: O código separa os dados em preditores (X) e alvo (y), e codifica a variável alvo.
4. **Descobrir os Melhores Parâmetros**: Utiliza o Grid Search para encontrar os melhores parâmetros para o classificador de árvore de decisão.
5. **Treinar e Avaliar o Modelo**: Utiliza validação cruzada para treinar e avaliar o modelo de árvore de decisão.

## Código

O código principal está contido no arquivo `Biomechanical features of orthopedic patients.ipynb`. Você pode executá-lo em um ambiente Jupyter Notebook ou Google Colab.

## Resultados

O código imprimirá os melhores parâmetros encontrados pelo Grid Search, bem como a acurácia do modelo.

## Contribuições

Contribuições e feedback são bem-vindos!
