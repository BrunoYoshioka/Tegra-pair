# Tegra Pair

O Desafio
----------
Crie uma solução para sorteio de desenvolvedores para realizar pair programming.

###### Para entender sobre pair programming, acesse: https://www.youtube.com/watch?v=vgkahOzFH2Q&t=23s

Os requisitos são:

* Cadastrar desenvolvedores com nome e nível de experiência (estagiário, junior, pleno, sênior)
* Realizar o sorteio de dois desenvolvedores
* O primeiro desenvolvedor sorteado será o *driver*
* O segundo desenvolvedor sorteado será o *navigator*
* O nível do desenvolvedor *navigator* dependerá do nível do desenvolvedor *driver*, de acordo com as regras de sorteio

### Regras do Sorteio



###### Sorteio do Driver
| Nível de Experiência | Probabilidade de Sorteio |
|------------------------|------------------------|
|Sênior|10%|
|Pleno|10%|
|Junior|40%|
|Estagiário|40%|


###### Pares para Driver Estagiário
* Senior 40%
* Pleno 40%
* Junior 20%

###### Pares para Driver Junior
* Senior 75%
* Pleno 15%
* Junior 5%
* Estagiário 5%

###### Pares para Driver Pleno
* Senior 20%
* Pleno 10%
* Junior 30%
* Estagiário 40%

###### Pares para Driver Senior
* Senior 5%
* Pleno 15%
* Junior 60%
* Estagiário 20%

#### Restriçoes
* A solução deve gerar uma dupla por vez  

* A solução não deve permitir que estagiários realizem pair programming com estagiários  

* A solução não deve permitir que os desenvolvedores sorteados na rodada anterior sejam sorteados novamente  


#### Observações:
Desenvolvimento Web dessa solução

[![](https://s23.postimg.org/lvfz9brkb/Screen_Shot_2016_12_14_at_10_46_12_PM.png)](https://s23.postimg.org/lvfz9brkb/Screen_Shot_2016_12_14_at_10_46_12_PM.png)


## Instruções de execução

Basta clicar duas vezes no index.html ;)

## Informação importante

O arquivo index.php é utilizado apenas pelo heroku, como explicado no link abaixo.
[http://blog.teamtreehouse.com/deploy-static-site-heroku](http://blog.teamtreehouse.com/deploy-static-site-heroku)
