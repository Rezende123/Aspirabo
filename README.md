# Aspirabô
Aspirabô é um projeto que tem o intuito de praticar conhecimentos em robótica, através do desenvolvimento de um robô pessoal que vai conter um aspirador e terá como função principal limpar a casa.

## Tecnologias
Será desenvolvido encima da plataforma Arduino. A prototipagem é feita através do Thinkercad: https://www.tinkercad.com/things/anO8rvLCC5Y

## Lógica da varredura
Será uma varredura simples, não contornará as bordas do ambiente, vai traçar seu caminho pelo meio, algo semelhante à técnica de aragem na agricultura. [Aqui o fluxograma](./Varredura.drawio.pdf).

Não foi possível obter os sensores laterais, por isso o sensor ultrassônico vai ser atrelado a um servo motor para fazer a varredura. [Aqui o fluxograma](./Varredura_Sem_IR_Lateral.drawio.pdf).
