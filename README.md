# Participantes

Felipe Jonathan Barros de Oliveira - 471752

Mario Cesar Freire Dias Filho - 472773


## Link para apresentação
[Video](https://youtu.be/0-HjJ-phw9M)

https://youtu.be/0-HjJ-phw9M


# *PIDSpoon [WIP]*
O PIDSpoon é um projeto de sistemas microprocessados que visa implementar um algoritmo de controle PID e de tratamento de sinais como a media movel para o desenvovimento de uma colher que possa ajudar a alimentação de pacientes com limitações motoras na mão.

## Motivação

Temos como motivação do desenvolvimento do PIDSpoon a reprodução de um modelo comercial de uma colher motorizada para alimentação de pessoas que possuem condições que dificultem a alimentação devido a movimentos irregulares dos braços ou mãos, condição muito comum em pacientes com sindrome de Parkinson.

## Componentes
O projeto utilizará os seguintes componentes:
* MPU6050
* STM32F103C8T6 
* 2 micro servo motores

Esquematico:

![Esquematico](https://i.imgur.com/4bEGhgM.jpg)
## Background

O algoritmo PID busca minimizar um erro a partir da ação em uma atuador agindo baseado em dados de um sensor, já a media movel busca reduzir ruidos e oscilações que possam atrapalhar a medição do valor real do sensor.

##Proposta inicial

Desenvolvimento de uma prova de conceito de uma colher para auxiliar a alimentação de pacientes de Mal De Parkinson utilizando um controlador PID e um acelerometro como sina de entrada.

## Alterações necessarias

Adaptação para entrada de dados do sensor para ser por meio de um sinal de audio, não possibilitando assim a sintonização do controlador PID.

## Fluxogramas

![Fluxograma 1](https://i.imgur.com/9Z6MAow.jpg)

![Fluxograma 2](https://i.imgur.com/EpABNp0.jpg)

![Fluxograma 3](https://i.imgur.com/nOADsRx.jpg)


## Resultados finais

* Implementação bem sucedida do filtro de media movel
* Implementação bem sucedida do controlador PID
* Comunicação bem sucedida entre STM32, Serial, Servomotor e sianal de entrada
* Uso bem sucedido de multiplos canais PWM e ADC

## Trabalhos Futuros

* Desenvolvimento de um modelo fisico para o projeto
* Substituição do sinal arbitrario de entrada pelo MPU6050

## Conclusão

Desse modo, temos que o projeto foi realizado com sucesso dentro das limitações apresentadas, mostrando todos os pontos apresentados na proposta de projeto, porem sem um modelo fisico que permita melhor visualização.


