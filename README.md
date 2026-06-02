Camunda DEV - Backup BPMN e DMN

Repositório destinado ao armazenamento dos arquivos BPMN e DMN extraídos do ambiente DEV do Camunda.

Objetivo

Este repositório centraliza os backups dos fluxos BPMN e decisões DMN exportados do Camunda DEV, preservando suas versões, datas de deploy, metadados e arquivos auxiliares para consulta histórica.

Contém os processos BPMN extraídos do Camunda DEV.

Cada processo possui uma pasta própria, e dentro dela existem subpastas por versão. Cada versão contém:

Arquivo .bpmn original.
Arquivo metadata.json com informações da versão.
Arquivo tasks.csv com as tasks identificadas no fluxo.
Pasta dmn

Contém as decisões DMN extraídas do Camunda DEV.

Cada decisão possui uma pasta própria, e dentro dela existem subpastas por versão. Cada versão contém:

Arquivo .dmn original.
Arquivo metadata.json com informações da versão.
Arquivo elementos_dmn.csv com os elementos identificados na decisão.
Arquivos de controle
manifesto_exportacao.csv

Arquivo consolidado com o registro dos itens exportados, incluindo nome, key, versão, data de deploy e caminho do arquivo salvo.

resumo_exportacao.json

Resumo geral da extração realizada, contendo totais e informações de controle.

tasks_todos_os_bpm.csv

Arquivo consolidado com todas as tasks identificadas nos arquivos BPMN.

elementos_todos_os_dmn.csv

Arquivo consolidado com todos os elementos identificados nos arquivos DMN.

Observações
Todas as versões disponíveis no ambiente DEV foram preservadas.
Os arquivos foram organizados por tipo, nome e versão.
Os nomes dos arquivos e pastas preservam caracteres especiais sempre que permitido pelo sistema operacional.
Caracteres inválidos para nomes de arquivos no Windows foram substituídos automaticamente durante a exportação.
Este repositório tem finalidade de backup, consulta e preservação histórica dos artefatos BPMN e DMN.
Ambiente de origem
Camunda DEV
Aviso

Este repositório contém artefatos exportados do ambiente de desenvolvimento. Antes de utilizar qualquer arquivo para redeploy ou comparação, valide se ele corresponde à versão desejada.
