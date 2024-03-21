# MemoryManager
Simulador de memoria RAM.

Esse programa simula a forma que os processos são alocados dentro da memoria RAM usando três estratégias:

- First Fit: aloca o primeiro espaço livre que seja grande o suficiente para atender às necessidades do processo solicitante.

- Worst Fit: aloca o maior espaço livre disponível para alocar um processo. Ao contrário do "First Fit", prioriza espaços maiores, potencialmente reduzindo a fragmentação de memória.

- Best Fit: aloca o espaço livre mais próximo do tamanho necessário para alocar um processo. Ele visa minimizar a fragmentação de memória, mas pode resultar em mais fragmentação interna.
