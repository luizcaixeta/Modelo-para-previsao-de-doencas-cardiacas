## ❤ Modelo para previsão de doenças cardíacas

Neste projeto, utilizamos um conjunto de dados do Kaggle com dados médicos de pacientes homens e mulheres. O objetivo desse projeto é desenvolver um modelo de classificação para determinar se, de acordo com os dados médicos de um paciente ele é classificado como 1 (portador de doença cardíaca) ou 0 (sem doença cardíaca).

As informações médicas dos pacientes utilizadas foram:

+ age: idade do paciente (anos)
+ sex: sexo do paciente (M: masculino, F: feminino)
+ ChestPainType: tipo de dor no peito (TA: Angina Típica, ATA: Angina Atípica, NAP: Dor Não Anginal, ASY: Assintomático)
+ RestingBP: pressão arterial em repouso (mm Hg)
+ Cholesterol: colesterol sérico (mm/dl)
+ FastingBS: glicemia em jejum (1: se FastingBS > 120 mg/dl, 0: caso contrário)
+ RestingECG: resultados do eletrocardiograma em repouso (Normal: Normal, ST: presença de anormalidade na onda ST-T (inversões da onda T e/ou elevação ou depressão do segmento ST > 0,05 mV), LVH: indica hipertrofia ventricular esquerda provável ou definitiva pelos critérios de Estes)
+ MaxHR: frequência cardíaca máxima alcançada (valor numérico entre 60 e 202)
+ ExerciseAngina: angina induzida por exercício (Y: Sim, N: Não)
+ Oldpeak: oldpeak = ST (valor numérico medido em depressão)
+ ST_Slope: inclinação do segmento ST no pico do exercício (Up: ascendente, Flat: plano, Down: descendente)
+ HeartDisease: classe de saída (1: doença cardíaca, 0: Normal)

Para compreender o comportamento dos dados e ajustar melhor o modelo, foi realizada uma análise exploratória dos dados (EDA) para entender quais dados realmente são relevantes e também compreender o status de saúde dos pacientes estudados.

## 🚀 Como Executar o Projeto, utilizar o modelo e visualizar a EDA:

1. Clone o repositório utilizando o comando:
   
```git clone https://github.com/yourusername/Modelo-para-previsao-de-doencas-cardiacas.git```

2. Instale as dependências:

Certifique-se de que o Python está instalado na sua máquina. Execute o seguinte comando para instalar as bibliotecas necessárias:

```pip install -r requirements.txt``` 

3. Arquivos necessários:

Verifique se o seguinte arquivo está no diretório do projeto (já incluído no repositório):

+ heart.csv

4. Execute a análise e a previsão:

   ```python main.py```

## 🛠️  Tecnologias Usadas

+ Python
+ Pandas, NumPy (Manipulação de dados)
+ Scikit-learn (Modelagem preditiva)
+ Matplotlib, Seaborn (Visualização de dados)
