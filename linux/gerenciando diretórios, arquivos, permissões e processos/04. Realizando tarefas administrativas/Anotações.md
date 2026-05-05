# Analisando processos em execuções

## Comando TOP 

```bash

top # TABLE OF PROCESS

```
Serve para monitorar processos em tempo real


| Campo  | Descrição                                                                 |
|--------|---------------------------------------------------------------------------|
| PID    | Número de identificação do processo (único)                               |
| USER   | Usuário que está executando o processo                                    |
| PR     | Prioridade do processo (quanto maior o valor, maior a prioridade)         |
| NI     |                         |
| VIRT   | Quantidade de memória virtual utilizada                                   |
| RES    | Quantidade de memória residente (RAM)                                     |
| SHR    | Memória compartilhada                                                     |
| S      | Estado do processo (S: sleep, R: running, T: stopped)                     |
| %CPU   | Uso de CPU pelo processo                                                  |
| %MEM   | Uso de memória RAM pelo processo                                          |


## Filtrando processsos

## Comando PS

Mostra o procesos que está em execução no momento que o comando é dado, é como se fosse um foto do processo atual

```bash
ps # PROCESS STATUS
```

```bash
ps aux # Mostar todos os procesos do sistema, um fotografia do momento que o comando foi feito
```

| Campo   | Descrição                                                                                  |
|---------|--------------------------------------------------------------------------------------------|
| VSZ     | Quantidade de memória virtual utilizada pelo processo                                      |
| RSS     | Quantidade de memória realmente alocada na RAM                                             |
| TTY     | Terminal associado ao processo (ou “?” quando não está ligado a um terminal)              |
| STAT    | Estado do processo (indica se está rodando, dormindo, etc.)                               |
| START   | Momento em que o processo foi inicializado                                                 |
| COMMAND | Comando ou programa que iniciou o processo                                                 |


```bash
    pstree  # Visualiza processo em formato de arvore
```

o que é o bash? ferramena de interação que é usado no terminal, é ele que interpreta os comandos do linux

```bash
    ps aux --sort=-%mem  # --sort orderna pro um paremetro especifico neste caso por memorio
```


Para parar o projeto

```bash

    kill PDI # Mata um processos

    pkill nome_processo # Mata processo pelo nome

    kill -9 # Mata de maneira abrupta

    kill -stop # Em alguns caso conseguimos pausar o processo

```