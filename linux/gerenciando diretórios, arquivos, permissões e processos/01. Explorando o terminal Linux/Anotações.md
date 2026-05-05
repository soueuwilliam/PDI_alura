# 3. USANDO O TEMRINAL


## Comandos Linux importantes

```bash
    ls # List -> Lista o arquivos e pasta dentro do diretório atual

    cd # Change Directory -> Muda para a pasta que o usuário deseja
```

Atalhos importantes:

TAB -> Auto Complete

# 5. Navegando entre diretórios

```bash
    PWD # Print WORKING DIRECTORY -> Exibe na tela o caminho dentro do sistema na pasta que o usuário se encontra
```

Linux é um Kernel é um núcleo de um sistema operacional que é open source 

# 6. FHS

## Diretórios importantes Linux
 o linux ultiliza uma organização de pastas chamada Filesystem Hierarchy Standard
- root: Onde tem todos os arquivos de configurações e bibliotecas  

- usr: Onde tem os arquivos e aplicativos e bibliotecas do usários do sistema

- bin: armazenamento de arquivo binários importantes essenciais no sistema 

- boot: armazenamento de arquivos necessarios para inicialização do sisetma, incluido carregador de inicialização e o kernel

- dev: armazenamento de arquivos de dispositivos(device file) que representam dispositivos de hardware, como disco rigidos, terminais e outros periféricos

- etc: aramazenam arquivos de de configurações do sistema

- home: armazenam diretórios pessoas dos usários 

- lib: armazenamento de bibliotecas compartilhadas essenciais para binários localizados nos diretórios /bin e /sbin

- media: ponto de montagens temporária para midias removiveis(dirvers uSB,por exemplo)

- mnt: ponto de montagem temporaria para sistemas de arquivos durante a adminstração de sistemas

- opt: armazenamento de apcionais e pacotes de software adicionais que não fazem parte da instalação padrão do sistema

- proc: sistema de arquivo virtuais que armazenam informações sobre processos em execuções e o estado do kernel 

- root: diretório pessoal do usuário root(superusuário)

- run: armazenamento de informações voláteis sobre o sistema desde a última inicialização, como PID files e sockets.

- sbin: armazenamento de binários essenciais para a administração do sistema, necessários para o boot e recuperação do sistema.

- srv: armazenamento de dados específicos de serviços fornecidos pelo sistema.

- sys: sistema de arquivos virtual que fornece informações e interfaces para o kernel do Linux.

- tmp: armazenamento de arquivos temporários criados por aplicativos e pelo sistema. Esses arquivos geralmente são excluídos ao reiniciar o sistema.

- usr: armazenamento de dados de usuário mais instalados pelo sistema, incluindo binários adicionais, bibliotecas e arquivos de cabeçalho.

- var: armazenamento de arquivos variáveis, como logs, filas de email e arquivos de spool

# 7. Usando SUDO

```bash 
    sudo # Abreviação de "SUPER USER DO" onde o usuario começar a ter privilégios administrativos
```

sudo só funcionam para comandos externos do shell, comando internos(shell built-in command) ele não consegue usar o sudo, para usar isso teria que iniciar uma sessão com o super usuario como mostrado abaixo

```bash 
    sudo -i # sessão com privilégios administrativos com o usuário
```


```bash 
    ls -a # Mostra arquivos ocultos no sistema
```

```bash 
    cat # concatenar arquivos, adicionar informações a arquivos existentes e exibir o conteúdo de arquivos diretamente no terminal 
```







