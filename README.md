# Participantes

Felipe Jonathan Barros de Oliveira - 471752

Leo Vitor Nascimento Ribeiro - 473079

## Link para a apresentação:

https://youtu.be/dtgXIBNPakQ

# *Smart Pot*
O Smart Pot é um projeto de sistemas microprocessados que visa implementar um sistema de rega automática de plantas de pequeno porte. O Smart Pot é um vaso que possui acoplado um pequeno reservatório de água e sensores de umidade que controlam a porcentagem de água no solo para o crescimento da planta sem interferência humana.

## Motivação

O projeto foi idealizado para atender as necessidades de pessoas que não possuem o tempo necessário para manter pequenas plantas em bom estado. O produto visa facilitar o trato das plantas permitindo que permaneçam saudáveis sem interferência humana.

## Componentes
O projeto utilizará os seguintes componentes:
* BluePill STM32F103C6
* Sensor De Umidade De Solo (https://www.filipeflop.com/produto/sensor-de-umidade-do-solo-higrometro/)
* Sensor de Nível de água (https://www.eletrogate.com/modulo-sensor-de-chuva-nivel-de-agua/)


Esquematico:

![Esquematico](https://github.com/FelipeJBarros/smart-pot/blob/main/src/Esquemático.png)

## Proposta inicial

Desenvolvimento de uma prova de conceito de um vaso autômato que ajuda a manter saudável plantas de pequeno porte. O produto conta com um sensor de umidade usado para controlar o nível de água no solo e um sensor de nível de água usado para informar ao usuário quando é necessário reabastecer o repositório.

## Alterações necessarias

Devido a natureza excepcional da disciplina de sistemas microprocessados, o desenvolvimento da prova de conceito foi realizado em ambiente simulado (Proteus) e assim surgiu a principal limitação do projeto, que é, alguns dos módulos necessário para confecção estão indisponíveis ou apresentam mau funcionamento no ambiente virtual supracitado.

Tendo isso em vista, tomamos a liberdade de simular os dados de entrada do sistema a partir de potenciômetros simples.

## Fluxogramas

![Fluxograma 1](https://github.com/FelipeJBarros/smart-pot/blob/main/src/fluxo01.png)

![Fluxograma 2](https://github.com/FelipeJBarros/smart-pot/blob/main/src/fluxo02.png)

## Resultados finais

* Implementação bem sucedida do sistema de controle e notificação visual de nível de água.
* Implementação bem sucedida do acionamento do sistema de liberação de água.
* Comunicação bem sucedida entre STM32, Serial, componentes e sinais de entrada.
* Uso bem sucedido de multiplos canais ADC.

## Trabalhos Futuros

* Desenvolvimento de um modelo fisico para o projeto.
* Substituição dos módulos simulados por módulos reais.
* Adição do sistema de acionamento da torneira via rele.

## Conclusão

Desse modo, temos que o projeto foi realizado com sucesso dentro das limitações apresentadas, mostrando todos os pontos apresentados na proposta de projeto, porem sem um modelo fisico que permita melhor visualização.


