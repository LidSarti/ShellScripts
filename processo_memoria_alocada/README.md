# Script de Monitoramento de Processos por Uso de Memória

EEste repositório contém um script em Bash que foi desenvolvido durante o curso de shell scripting da Alura. O objetivo do script é realizar o monitoramento do uso de memória dos processos em execução no sistema. Ele identifica os 10 processos que estão utilizando mais memória e salva essa informação em arquivos de log.

O script obtém os 10 processos com maior uso de memória, classificados pelo tamanho em ordem decrescente.
Para cada processo selecionado, o script registra a data e hora atual, bem como o tamanho do processo em megabytes, em um arquivo de log específico para o processo.
Os arquivos de log são salvos no diretório log/, com o nome do arquivo correspondente ao nome do processo.

## Pré-requisitos

    - Sistema operacional Linux ou macOS.

## Uso
O script irá identificar os 10 processos com maior uso de memória e salvar as informações em arquivos de log individuais, dentro do diretório log/. Cada arquivo de log conterá a data e hora atual, juntamente com o tamanho do respectivo processo em megabytes.
Observações
Lembre-se de que este script tem como objetivo fornecer uma funcionalidade básica de monitoramento de uso de memória de processos. Caso necessite de recursos mais avançados ou precisos, considere utilizar ferramentas específicas para esse propósito.

## Alura
Esse script foi feito durante o curso *Shell Scripting parte 1: scripts de automação de tarefas*, da formação _Shell Scripting: automatize tarefas_. Você pode conferir meu certificado clicando [aqui](https://cursos.alura.com.br/certificate/ddb75fb2-b2d7-4c84-a87e-2495f4245ca3).