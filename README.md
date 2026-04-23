# Case Profissional - Plataforma de Consulta e Analise de Dados Publicos

## Sobre o projeto

Este repositorio apresenta um case profissional baseado em uma aplicacao full stack desenvolvida em contexto corporativo para consulta, normalizacao e analise de dados publicos.

Por questoes de confidencialidade, o codigo-fonte nao pode ser publicado. O objetivo deste material e documentar o problema resolvido, a arquitetura da solucao, a stack utilizada e minha atuacao tecnica no projeto.

## Aplicacao em producao

O sistema pode ser acessado publicamente em:

https://consultatce-dev.ssinformatica.net/

## Contexto

O projeto foi concebido para apoiar rotinas operacionais que dependem de consulta, consolidacao e validacao de informacoes publicas. A solucao centraliza diferentes fluxos em uma unica interface, reduz o esforco manual de consulta e melhora a consistencia do tratamento dos dados exibidos e exportados.

## O que a solucao entrega

- consulta de dados com filtros operacionais
- integracao com fonte externa de dados publicos
- padronizacao das respostas para consumo interno
- exportacao de resultados em CSV
- analise de arquivos CSV para apoio a identificacao de inconsistencias
- interface web para pesquisa e acompanhamento operacional

## Stack utilizada

- Ruby on Rails 8
- PostgreSQL
- Preact
- TypeScript
- Vite
- Docker

## Arquitetura em alto nivel

A aplicacao foi estruturada em dois blocos principais:

- backend em Ruby on Rails responsavel por expor endpoints, integrar dados externos, padronizar respostas, paginar resultados e apoiar fluxos de analise
- frontend em Preact + TypeScript responsavel pela experiencia de consulta, filtros, exibicao de resultados e exportacao

O ambiente tambem foi preparado para execucao conteinerizada com Docker, facilitando padronizacao de setup e execucao entre ambientes.

## Principais funcionalidades

- consulta paginada de dados
- filtros por municipio e outros criterios operacionais
- integracao com APIs externas
- exibicao estruturada dos resultados
- exportacao de dados para CSV
- processamento de arquivos CSV para validacao e conferencia

## Minha atuacao

Atuei no desenvolvimento full stack da solucao, incluindo:

- implementacao e evolucao de funcionalidades no backend
- construcao e manutencao da interface web
- integracao com servicos externos
- tratamento e normalizacao de dados para consumo na interface
- implementacao de filtros e fluxos de exportacao
- apoio a rotinas de analise de inconsistencias em arquivos processados

## Desafios tecnicos envolvidos

- organizar a integracao com dados externos de forma consistente
- garantir respostas padronizadas para consumo no frontend
- estruturar filtros e resultados para uso operacional
- tratar importacao e leitura de arquivos CSV
- equilibrar experiencia de uso com necessidades tecnicas de consulta e analise

## Resultados percebidos

- centralizacao do fluxo de consulta em uma unica aplicacao
- ganho de produtividade em rotinas operacionais
- melhor consistencia na exibicao e exportacao dos dados
- apoio tecnico a validacao de inconsistencias em arquivos analisados

## Confidencialidade

Este repositorio documenta um projeto profissional real, mas nao inclui codigo proprietario, detalhes internos de negocio, credenciais, dados sensiveis ou implementacoes exclusivas da empresa.

## Tecnologias e temas

`Ruby on Rails` `Preact` `TypeScript` `PostgreSQL` `Docker` `APIs REST` `Integracao de Sistemas` `CSV` `Full Stack`
