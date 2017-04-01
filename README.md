# QuestoesSO

1) Quais são as diferenças essenciais entre um aplicativo comum (por exemplo, o

Microsoft Word) e um sistema operacional?

O Sistema operacional é responsável pelo funcionamento do computador, ele controla

os aplicativos como por exemplo o Microsoft Word

2) Por que um sistema operacional é necessário?

Para permitir o compartilhamento dos recursos de hardware por diversas aplicações.

Para facilitar o desenvolvimento de novas aplicações, deixando o gerenciamento dos

recursos de hardware a cargo do sistema operacional.

3) Que nome é dado às chamadas realizadas pelas aplicações aos serviços

disponibilizados pelo sistema operacional? Mencione como exemplo duas destas

chamadas.

Chamadas de sistema

Accept / access

4) O que é um processo?

Processo é um &quot;trabalho &quot; em execução em um sistema computacional.

5) Um processador com um único núcleo executa vários processos simultaneamente?

Explique sua resposta.

Não, na verdade ele chaveia entre processos e da a impressão de que ele faz isso

simultaneamente

6) O que ocorre quando o sistema operacional faz o chaveamento entre processos?

Ele coloca um em espera e executa o outro,

7) Qual é a diferença entre thread e processo?

Thread é uma linha de execução de um processo, um processo pode ter varias Threads

8) Qual é a diferença entre escalonamento preemptivo e não-preemptivo.

Versão não-preemptiva: uma vez que o processo recebe tempo de CPU, não pode ser

interrompido até que utilize o tempo de CPU alocado.

Versão preemptiva: se um novo processo chega e possui um tempo de CPU menor que

o tempo restante do processo em execucão, este será interrompido. Esta forma é

conhecida como Shortest-Remaining- TimeFirst (SRTF).

9) Cite 2 algoritmos de escalonamento de processos e explique o funcionamento de cada

um.

Escalonamento First-Come, First-Served (FCFS)

Funciona como fila

Escalonamento Shortest Job First (SJF)

Ele pega os processos mais rapidos de serem finalizados e faz

10) Cite 2 recursos disponibilizados pelo sistema operacional para ajudar o programador a

implementar programas concorrentes sem interferência entre threads, e diga em qual situação

é mais conveniente utilizar cada recurso.
