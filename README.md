<h1 align="center">Imersao de Dados 2021 - Alura</h1>

Nessa semana de imersão, iremos analisar dados de uma tabela que trás informações sobre células que foram expostas a modificações genéticas através de experimentação com novos fármacos. Na tabela a baixo podemos analiasar o tipo de tratamento que cada célula obteve, o tempo que levou para que a droga fizesse o efeito esperado sobre a célula, a quantidade de dosagem aplicada na célula, a droga utilizada e a porcetagem de RNA's afetados em cada gene de DNA alterado pelos experimentos.

## Dados Experimentos

~~~python
import pandas as pd

url_dados = 'https://github.com/alura-cursos/imersaodados3/blob/main/dados/dados_experimentos.zip?raw=true'

dados = pd.read_csv(url_dados, compression = 'zip')
print(dados)
~~~
<p align="center">
  <img src="/img/tabela.png">
</p>
