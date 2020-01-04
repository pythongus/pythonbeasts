# Python Beasts
Um site dedicado à fina arte de programação em Python. Com desafios regulares para qualquer Pythonista. 
## Desafios
### 1. Jogo De Senha
Baseado num clássico jogo dos anos 80.

O objetivo do jogo é acertar uma combinação de cores e posições de quatro pinos. Por exemplo, se a senha (combinação secreta) for verde, amarelo, azul e vermelho, uma tentativa com as cores verde, azul, verde e amarelo, possui uma cor correta e posição correta (indicada por um pino preto) e duas cores corretas com posições erradas (indicadas por pinos brancos) 
  
  
Resultado | VeAmAzVo  
--- | ---  
PrBrBr | VeAzVeAm  

Cores erradas não recebem nenhuma avaliação. 

O jogador tem 10 chances de acertar a combinação correta. Como visto no exemplo, cores repetidas são permitidas.

A senha inicial deve ser gerada aleatoriamente, sendo revelada somente se ocorrer a combinação correta ou ao final das 10 tentativas. 
