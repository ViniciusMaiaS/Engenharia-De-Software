# Projeto Final

> Este arquivo funciona como o índice do projeto. Ele não repete o conteúdo de cada artefato, só resume e aponta o caminho. Preencham os resumos e ajustem os links para os arquivos reais do repositório de vocês.

## Índice

1. [Identificação](#1-identificação)
2. [Visão Geral do Sistema](#2-visão-geral-do-sistema)
3. [Fundamentos do Sistema (Semana 1)](#3-fundamentos-do-sistema-semana-1)
4. [Requisitos e Viabilidade (Semana 2)](#4-requisitos-e-viabilidade-semana-2)
5. [Modelagem UML (Semana 3)](#5-modelagem-uml-semana-3)
6. [Modelo de Processo (Semana 4)](#6-modelo-de-processo-semana-4)
7. [Cenário de Mudança](#7-cenário-de-mudança)

---

## 1. Identificação

| Campo | Preencher |
|---|---|
| Grupo | Equipe 03 |
| Tema | Delivery |
| Integrantes | Vinicius Maia Silva , Yarley Aguiar de Sousa , Carlos Italo |
| Disciplina | Engenharia de Software I |

## 2. Visão Geral do Sistema

O App de Delivery de comida caseira é um sistema de pequeno a médio porte que envolve o gerenciamento de clientes, estabelecimentos (fornecedores de comida), entregadores, pedidos, pagamentos e entregas.
O sistema foi desenvolvido considerando a necessidade de organizar essas atividades e lidar com problemas relacionados a pedidos, pagamentos, entregas e manutenção.

## 3. Fundamentos do Sistema (Semana 1)

O sistema exige Engenharia de Software devido à necessidade de organizar seu desenvolvimento e reduzir problemas como falhas em pedidos, inconsistências de pagamento, dificuldade de manutenção e atrasos. A modularidade é aplicada pela divisão do sistema em módulos de autenticação, clientes, estabelecimentos, pedidos, pagamentos, entregas e administração. A qualidade é considerada por meio de atributos como funcionalidade, confiabilidade, usabilidade, eficiência, manutenibilidade e portabilidade. A manutenibilidade permite realizar evoluções no sistema, como adicionar avaliações, novos meios de pagamento, mapa com GPS e favoritos. As boas práticas incluem documentar decisões, utilizar Git/GitHub com branches e mensagens claras, além de padronizar nomes e formatação.

🔗 [semana1/](Semana%201/README.md)

## 4. Requisitos e Viabilidade (Semana 2)

Na Semana 2 foram definidos os requisitos funcionais e não-funcionais do sistema, abrangendo funcionalidades como notificações de pedidos, autenticação, cadastro de estabelecimentos, cálculo da taxa de entrega, gerenciamento do cardápio e emissão de NFC-e. Entre os requisitos não-funcionais estão desempenho, segurança, confiabilidade, manutenibilidade, usabilidade e portabilidade. O estudo de viabilidade concluiu que o sistema é viável nas dimensões técnica, econômica e operacional, destacando como principal desafio técnico o rastreamento da localização do entregador em tempo real e o cálculo da distância por rotas.

🔗 [semana2/requisitos.md](Semana%202/template_requisitos.md) · [semana2/viabilidade.md](Semana%202/viabilidade.md)

## 5. Modelagem UML (Semana 3)

O diagrama de casos de uso apresenta os principais atores envolvidos no sistema, como Cliente, Lojista e Entregador, além das interações entre esses atores e as funcionalidades do sistema.
🔗 [casos_de_uso.png](Semana%203/casos_de_uso.png)

O diagrama de classes representa as principais entidades do sistema e seus relacionamentos, incluindo Cliente, Pedido, Pagamento, Lojista, Cardápio e Entregador, além de seus principais atributos e métodos.
🔗 [diagrama_classes.png](Semana%203/diagrama_classes.png)

O diagrama de sequência de Realizar Pedido representa a sequência de interações envolvidas na realização de um pedido no sistema. Esse diagrama foi elaborado por Italo.
🔗 [sequencia_realizar_pedido.png](Semana%203/sequencia_realizar_pedido.png)

O diagrama de sequência de Atualizar Status representa a interação entre o Lojista, o PedidoController, o Pedido e o NotificacaoService para a atualização do status de um pedido. Esse diagrama foi elaborado por Vinicius.
🔗 [sequencia_atualizar_status.png](Semana%203/sequencia_atualizar_status.png)

O diagrama de sequência de Cadastrar Item representa a sequência de interações relacionada ao cadastro de um novo item no cardápio. Esse diagrama foi elaborado por Yarlei.
🔗 [sequencia_cadastrar_item.png](Semana%203/sequencia_cadastrar_item.png)

## 6. Modelo de Processo (Semana 4)

Resumo curto do modelo de processo escolhido (cascata, incremental ou ágil) e por quê. A justificativa deve considerar pelo menos a estabilidade dos requisitos e o perfil da equipe, e mencionar brevemente por que os outros modelos foram descartados. Se o grupo optou por uma abordagem ágil, indiquem também qual framework usariam (Scrum, Kanban ou XP), por que ele se adequa ao sistema e como lidariam com o cenário de mudança dentro dele.

> _(escrever aqui)_

🔗 [semana4/](semana4/)

---

## 7. Cenário de Mudança

### O cenário recebido

Colem aqui o cenário correspondente ao tema do grupo.

> _(colar aqui)_

### Tipo de manutenção

Identifiquem e nomeiem o tipo de manutenção que esse cenário representa (corretiva, adaptativa, perfectiva ou preventiva) e justifiquem a classificação com base no conteúdo estudado.

> _(escrever aqui)_

### Análise de impacto

Expliquem, em texto corrido, como essa mudança afeta o que vocês já construíram ao longo da disciplina, rastreando quais artefatos das semanas anteriores são atingidos. Vocês são livres para tocar nas áreas que julgarem necessárias, princípios, stakeholders, requisitos, viabilidade, diagramas, ou o modelo de processo, mas justifiquem o raciocínio por trás de cada ajuste, inclusive quando a conclusão for que uma determinada parte não precisa mudar.

> _(escrever aqui)_
