# API de beneficiários de plano de saúde

**Status: planejamento — implementação ainda não iniciada.**

Repositório de estudo de [José Carlos](https://github.com/carlos0ff), organizado a partir da [seleção de desafios de Matheus Leandro](https://www.matheusleandro.com.br/desafios).

## Objetivo

Construir uma API para gerenciar beneficiários de um plano de saúde e os documentos associados a cada cadastro.

## Escopo do desafio

- Criar o beneficiário e seus documentos na mesma operação.
- Consultar a lista de beneficiários.
- Buscar documentos vinculados a um beneficiário.
- Alterar os dados cadastrais.
- Excluir um beneficiário.
- Seguir o diagrama disponibilizado no enunciado.

## Tecnologias indicadas

Java 17, Spring Boot 3+, Spring Data JPA, H2 e Maven. A referência também sugere arquivos `.http` para chamadas de teste e OpenAPI/Swagger como opção.

## Critérios de conclusão

- [ ] Conferir os campos e relacionamentos do diagrama.
- [ ] Implementar entidades, persistência e operações REST.
- [ ] Definir validações, respostas e tratamento de cadastro inexistente.
- [ ] Testar o vínculo entre beneficiário e documentos.
- [ ] Documentar build, execução e exemplos de chamadas.

## Decisões pendentes

Os caminhos dos endpoints, os códigos de resposta e a política de exclusão dos documentos serão definidos durante a implementação.

## Relação com os outros desafios

A plataforma também lista uma versão atribuída à empresa Kan. Ela está organizada separadamente em [desafio-beneficiarios-kan](https://github.com/carlos0ff/desafio-beneficiarios-kan), preservando a referência de cada proposta.

## Como executar

Este repositório contém apenas a documentação inicial. Ainda não há aplicação, scripts de execução ou testes executáveis. Os comandos serão adicionados junto com a implementação.

## Referências e créditos

- [Enunciado na plataforma](https://www.matheusleandro.com.br/desafios/desafio-de-vaga-junior-api-de-gestao-de-beneficiarios-de-plano-de-saude)
- [Referência original indicada pela plataforma](https://github.com/matheuslf/com-rocketseat-desafio-junior)

Este README resume a proposta e registra um plano de trabalho. Os créditos do enunciado pertencem aos autores das referências; a solução será desenvolvida neste repositório.
