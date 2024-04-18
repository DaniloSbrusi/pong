# Jogo Pong

Desenvolvido como projeto final da disciplina de Sistemas Digitais Experimental no IFC Luzerna

Software: [Digital by Hneemann](https://github.com/hneemann/Digital)

## Instruções

- Abra o arquivo **jogo.dig**
- O botão S inicia ou reinicia o jogo
- Os botões A e D movem a barra

*Objetivo do jogo: impedir que a bolinha toque a lateral direita do display*

*Os botões estão mapeados para o teclado*

---
![Imagem do jogo](/pong.png)
--- 

Foram utilizados os seguintes componentes que são exportáveis, pelo software, em VHDL:

- Botões
- Sinal de clock (16 Hz)
- Portas lógicas (NOT, OR, AND)
- Flip-flops tipo D (síncrono e assíncrono)
- Flip-flops tipo K
- Contadores (74193 e genérico)
- Codificador
- Decodificador
- Multiplexador
- Comparador
- RAM
- ROM
- Matriz de LEDs
