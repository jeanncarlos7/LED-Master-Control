## LED Master Control 

É um projeto Arduino que demonstra o controle de LEDs usando botões e um potenciômetro. Este projeto é ideal para aprender sobre leitura de entradas digitais e analógicas, controle de LEDs, e programação de lógica condicional em Arduino.

## Componentes

Arduino Uno: Placa de microcontrolador.
4 LEDs: Vermelho, Amarelo, Verde e Roxo.
3 Botões: Branco (esquerda), Cinza (central) e Preto (direita).
1 Potenciômetro: Para ajuste de valores analógicos.
Resistores: 560 ohms para limitar a corrente dos LEDs.

## Conexões

# LEDs

LED Vermelho: Pino 2
LED Amarelo: Pino 4
LED Verde: Pino 6
LED Roxo: Pino 8

# Botões

Botão Branco: Pino 10
Botão Cinza: Pino 11
Botão Preto: Pino 12

# Potenciômetro

Pino de Sinal (SIG): A0

# Conexões de Alimentação

Potenciômetro: VCC para 5V, GND para GND.

# Funcionalidades

1 - Controle dos LEDs com Botões:

    Botão da Esquerda: Pisca o LED roxo.
    Botão Central: Acende todos os LEDs.
    Botão da Direita: Pisca alternadamente os LEDs amarelo e verde.
    Controle dos LEDs com Potenciômetro:

2 - O LED verde acende quando o valor do potenciômetro está baixo.

    LEDs verde e amarelo acendem em valores intermediários.
    LEDs verde, amarelo e vermelho acendem em valores altos.
    Todos os LEDs piscam quando o valor está no máximo.

3 - Controle de Piscar dos LEDs:

    LEDs roxo e azul piscam quando qualquer botão é pressionado.

## Montagem

Conecte os LEDs, botões e o potenciômetro conforme as conexões descritas. 
Certifique-se de que os resistores estão corretamente posicionados para limitar a corrente dos LEDs e evitar danos.

## Uso

1 - Inicie o Arduino: Conecte o Arduino ao seu computador e carregue o código.
2 - Teste os Botões: Pressione os botões e observe a resposta dos LEDs.
3 - Ajuste o Potenciômetro: Mova o potenciômetro e veja como os LEDs respondem aos diferentes valores analógicos.

## Licença

Este projeto é fornecido sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.
