![GitHub](https://img.shields.io/github/license/roboticapratica/motorshield)
# Configuração do Motor Shield L293D no Arduino
![motor shield L293D](https://raw.githubusercontent.com/roboticapratica/motorshield/main/img/motorshield.jpg)

O motor shield L293D é uma placa que pode ser conectada ao arduino, permitindo controlar até 4 motores DC ou 2 motores de passo e 2 servos, sendo muito utilizado em projetos de robótica.
### Dados técnicos
- 2 chips L293D (Cada chip vem com 2 pontes H)
- Tensão de operação: 5V a 12V
- Tensão de saída: 4.5V a 36V
- Corrente de saída: 600mA por canal
- Controle de até 4 motores DC
Até 2 Motores de Passo (Unipolar ou Bipolar) com bobina unica, dupla ou passos interlaçados
- 4 Pontes H: 0,6A por Ponte (1,2A de pico) com proteção térmica e diodos de proteção contra retro-alimentação
- Resistores Pull Down mantem motores desativos durante a entrada de alimentação
- Botão de Reset Arduino disponível no topo da placa
- Terminais em bloco de 2 pinos e jumper para conexão de alimentação externa

## Diagrama elétrico
Esquema de ligação do Motor Shield L293D no Arduino para controlar:
- 4 motores de corrente contínua
- 1 micro servo
- 1 sensor ultrassônico HC-SR04
---
![diagrama motor shield L293D arduino](https://github.com/roboticapratica/motorshield/blob/main/diagrama%20el%C3%A9trico.jpg)
