# Conversor de Arquivo CSV para JSONL

Este script converte um arquivo CSV contendo colunas de perguntas e respostas em diferentes formatos JSONL, 
utilizados para ajuste fino de modelos de IA.

## O que é Ajuste Fino?
Ajuste fino (fine-tuning) é o processo de treinamento adicional de um modelo de IA já existente 
com dados específicos, permitindo que ele aprenda padrões e contextos mais específicos para determinada aplicação.

## Formato de Entrada e Saída:
O arquivo CSV deve conter duas colunas:
- `input:` -> Pergunta do usuário
- `output:` -> Resposta correspondente

Os dados serão convertidos para diferentes formatos JSONL para serem utilizados em treinamentos de IA.
