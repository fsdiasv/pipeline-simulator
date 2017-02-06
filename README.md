# Pipeline Simulator
Simulador que apresenta as soluções da execução de instruções em pipeline de forma gráfica, desenvolvido para a disciplina de Arquitetura de Computadores II - DCC/UFLA.

## Descrição do Simulador
O simulador comtém seis (6) unidades funcionais que podem ter conflito estrutural:
* [Unidade de Ponto Flutuante de Add/Subtract]
* Unidade de Ponto Flutuante de Multiply
* Unidade de Ponto Flutuante de Divide
* Unidade de Inteiro Add/Subtract
* Unidade de Inteiro Multiply
* Unidade de Inteiro Divide

As seguintes instruções serão implementadas:
* ADD.D, SUBD, MULTD, DIV.D, L.D, S.D, 
* ADD, DADDUI, SUBI, MULT, DIV, LW, SW, BEQ, BNEZ.

Características:
* O simulador possui uma entrada para definir o número de instruções do bloco básico.
* As latências das instruções podem ser escolhidas pelos usuários antes de sua execução.
* Dois modos para execução das instruções: com unidades de adiantamento e sem unidades de adiantamento.
