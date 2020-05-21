# ISEC - Sistemas Operativos 2018 / 2019

  O trabalho pratico de sistemas operativos consiste na implementação de um editor de texto multiutilizador aqui denominado MEDIT. O editor exibira uma interface em modo consola (modo texto), e não envolvera questões de formatação de texto (justificarão, alinhamento, etc. - nada disso esta envolvido aqui). A complexidade do trabalho estará essencialmente na parte relacionada com os mecanismos Unix.

  O editor e composto por uma aplicação cliente, invocada por cada um dos utilizadores, e uma aplicação servidor, langada pelo administrador do sistema, responsável por coordenar o processo de edição. O servidor e os vários clientes residem na mesma máquina Unix. A troca de informação entre os clientes e o servidor e assegurada exclusivamente por mecanismos de comunicação inter-processo dados nas aulas. Este trabalho não envolve mecanismos de comunicação em rede. A utilização por vários utilizadores envolvera apenas consolas (terminals) diferentes, uma por utilizador. Dado que uma maquina dispõe apenas de um teclado e um ecrã, a utilização de sessões remotas (recorrendo ao PuTTY, por exemplo) simplificara bastante a utilização e teste em cenário de multi-utilizador, para a mesma maquina, na qual residirão as aplicações cliente e servidor que ira desenvolver.


# Trabalho feito por:
# - Ricardo Belinha
# - Sarah Cunha
