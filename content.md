# Introdução

O projeto \brz tem por finalidade acionar um ventilador
baseado na temperatura do ambiente.

Para isso será necessário um sensor de temperatura, um Arduino para
a verificação da variação de temperatura e o acionamento de um relé.
Quando estiver com baixa temperatura o circuito que alimenta o ventilador
é desligado, e quando a temperatura alcançar um certo valor o indutor
é acionado mudando o estado do relé e ligando o ventilador.

# Material

* Arduino
* Relé
* Sensor de Temperatura
* Diodo
* Transistor
* Tomada fêmea

# Circuito (Draft)

\begin{figure}[h]
	\includegraphics[scale=0.7]{img/breeze-diagram-1.jpg}
	\caption{Circuito (Draft)}
\end{figure}
