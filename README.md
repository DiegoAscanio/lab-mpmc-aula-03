<link rel="stylesheet" type="text/css" href="style.css"></link>

# Laboratório de Microcontroladores e Microprocessadores
## Aula 03 — Interrupções e Timers no Arduino

### Objetivos

- Fazer práticas com o uso de interrupções no Arduino;
- Fazer práticas com o uso de contadores no Arduino.

### Exercícios

1. **Contador de Interrupções Externas:** 
   - **Objetivo:** Crie um programa que use uma interrupção externa para contar o número de vezes que um botão é pressionado. 
   - **Detalhes:** O contador deve ser incrementado a cada pressionamento de botão e o valor atual deve ser exibido no Serial Monitor. Utilize o pino 2 do Arduino UNO para a interrupção.

2. **Medidor de Tempo de Interrupção:** 
   - **Objetivo:** Desenvolva um programa que meça o tempo entre duas interrupções externas em milissegundos. 
   - **Detalhes:** O início e o fim do tempo devem ser disparados por dois botões diferentes, cada um conectado a seu próprio pino de interrupção (pino 2 e pino 3, por exemplo). Mostre o tempo decorrido no Serial Monitor.

3. **Alarme de Interrupção com Cancelamento:** 
   - **Objetivo:** Faça um sistema de alarme onde uma interrupção externa ativada por um sensor de movimento (_pushbutton_, conectado ao pino 2) ligue um LED e emita um som através de um buzzer e mantenha o alarme ligado.
   - **Detalhes:** Adicione uma funcionalidade para desligar o alarme pressionando um botão, que também deve funcionar através de uma interrupção externa (conectado ao pino 3).

4. **Alarme com Função Soneca:** 
   - **Objetivo:** Faça um alarme que, ao ser disparado, emite um som e, se a função soneca for ativada, silencia por um período de tempo antes de soar novamente. 
   - **Detalhes:** Utilize um buzzer para o som do alarme e botões para disparar (desligar) o alarme a ativar a função soneca. Se o alarme não for desligado pelo botão, ele deve desligar sozinho após 30 segundos de funcionamento.

### Entrega

- Você deve entregar no AVA um relatório feito em formato Markdown e salvo em pdf com os códigos, capturas de tela dos exercícios realizados e os links para os projetos Wokwi de cada exercício. 
- O trabalho pode ser feito em dupla.

### Valor:

10 Pontos relativos ao TP1 e 5 pontos relativos ao TP2.
