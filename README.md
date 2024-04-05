# Projeto Arduino - Detecção de Luminosidade em Leds

Este é um projeto de arduino que foi construído com o intuito de receber a luminosidade, através de um LDR (Light Dependent Resistor) e sinalizar eventuais problemas através de LEDs e um buzzer.

## Funcionamento do Projeto

O projeto consiste em:

1. Captura de Luminosidade: O Arduino utiliza um LDR para capturar informações sobre a luminosidade do ambiente.

2. Sinalização Visual: O sistema utiliza três LEDs para indicar o estado da luminosidade:
- LED Verde: Indica que a luminosidade está dentro dos limites aceitáveis.
- LED Amarelo: Indica que a luminosidade está em níveis de alerta e ativará o buzzer.
- LED Vermelho: Indica que há algum problema com a luminosidade.

3. Sinalização Sonora: Quando a luminosidade está em nível de alerta, um buzzer é ativado por 3 segundos. Se a luminosidade permanecer em nível de alerta, o buzzer volta a soar.

## Componentes Necessários na Montagem do Projeto

- Arduino Uno (ou similar)
- LDR (Light Dependent Resistor)
- 3 LEDs (Verde, Amarelo e Vermelho)
- Buzzer
- Resistor de 10k ohms (para o LDR)
- Resistor de 220 ohms (para cada LED)
- Breadboard e fios jumper

## Montagem do Circuito
1. Conecte o LDR e o resistor de 10k ohms em série.
2. Conecte o ponto de junção do LDR e do resistor ao pino analógico A0 do Arduino.
3. Conecte os LEDs verde, amarelo e vermelho aos pinos digitais 8, 9 e 10 do Arduino, respectivamente.
4. Conecte o buzzer a um pino digital (por exemplo, o pino 7) do Arduino.

## Como Reproduzir o Projeto
1. Clone ou faça o download deste repositório.
2. Monte o circuito conforme descrito na seção "Montagem do Circuito".
3. Crie e abra o arquivo "monitoramento_luminosidade.ino" utilizando a IDE do Arduino.
4. Faça o upload do código para o Arduino.
5. Observe a sinalização dos LEDs e a sinalização sonora do buzzer de acordo com a luminosidade do ambiente.

## Observações
- Certifique-se de que os LEDs e o buzzer estejam devidamente conectados aos pinos corretos do Arduino, conforme especificado no código.
- Este projeto foi desenvolvido e testado utilizando o software Tinkercad para simulação de circuitos Arduino.

Este **projeto** foi desenvolvido como parte de um exercício de aprendizado e pode ser modificado e expandido conforme necessário. Sinta-se à vontade para contribuir e adaptar o código conforme suas necessidades.
