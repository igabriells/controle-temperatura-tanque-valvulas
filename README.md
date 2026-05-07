O sistema opera na faixa de 0°C a 150°C. Através de três potenciômetros, o operador define o limite de temperatura para cada uma das três válvulas (representadas por LEDs).

Lógica:
  - Se a temperatura do tanque >= temperatura regulada: a válvula fecha (Led desliga).
  - Se a temperatura do tanque <= temperatura regulada: a válvula abre (Led liga).
  - Interface: Um display LCD exibe a temperatura do tanque e das válvulas.

 Hardware e Programação
  - Linguagem/Ide: Mikrobasic.
  - Microcontrolador: PIC16F690
  - Simulação: Proteus (Circuito desenvolvido via software).
  - Hardware: Circuito físico montado e testado em laboratório durante as aulas
Componentes:
  - 3x Potenciômetros (Reguladores para as válvulas e para o tanque)
  - 3x Leds (Representando as válvulas)
  - 1x Display LCD
