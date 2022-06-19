# DadosTelecomunicacoes
Projeto com foco em limpeza e análise de dados de telecomunicações

Esse projeto tem como base o dataset: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

Obs: O projeto foi desenvolvido no ambiente do Jupyter Notebook.

### Problema de Negócio

Os dados serão usados para análise preditiva mas antes disso, precisamos analisar possíveis inconsistências. Realizaremos um trabalho de limpeza, daremos ênfase ao tratamento de valores ausentes, tratamento de outliers e ajustes nos tipos de dados.

# Carregando os pacotes

```
#Passo 1 - Carregando os pacotes

import math # funções matemáticas em python.
import sys, os # manipular o sistema.
import numpy as np # pacote para computação.
import pandas as pd # pacote para manipulação de dados.
```

```
#Adicionar o caminho para os módulos Python (Não obrigatório).

sys.path.append(os.path.abspath(os.path.join('modulos')))
from estrategia1 import *
from estrategia2 import *
from estrategia3 import *
```

```
# O pandas vai imprimir 100 colunas conforme o comando.
pd.set_option('display.max_columns',100)
```














