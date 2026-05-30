# 💡 Piano de LED com MicroPython

## 🧠 Sobre o Projeto

Este projeto foi desenvolvido utilizando MicroPython com o objetivo de controlar LEDs conectados a um microcontrolador. Ele simula um efeito sequencial, acendendo e apagando LEDs em ordem.

## 📄 Descrição

O sistema controla três LEDs conectados aos pinos digitais do dispositivo:

* LED 1 → pino 12
* LED 2 → pino 13
* LED 3 → pino 14

O programa executa um loop infinito, onde:

1. Acende o primeiro LED
2. Aguarda meio segundo
3. Apaga o LED
4. Repete o processo com os próximos LEDs

Isso cria um efeito visual contínuo de luz em sequência.

O projeto utiliza conceitos como:

* Controle de hardware com `machine.Pin`
* Estrutura de repetição infinita (`while True`)
* Temporização com `time.sleep()`

## ▶️ Execução
![imagempiano](https://github.com/laysacferreira/PIANO-LED-/blob/main/piano.png)

## 🎯 Conclusão

Este projeto é ideal para iniciantes em eletrônica e programação embarcada, pois demonstra de forma prática como controlar componentes físicos utilizando Python.


