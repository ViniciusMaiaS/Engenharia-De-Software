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

Vamos então ao nosso resumo o grupo optou por utilizar o modelo de processo ágil que a gente achou ser mais adequado ao desenvolvimento do nosso sistema de delivery de comida caseira nesse primeiro momento.  essa nossa escolha Ela acabou sendo motivada pelo fato da Necessidade desses nossos requisitos poderem sofrer necessariamente a atualizações ou alterações ao longo do tempo de desenvolvimento do projeto e esse modelo de processo ágil ele acaba tendo muita praticidade em relação a comunicação entre os integrantes da equipe e a possibilidade de realizar entregas incrementais e melhorias no projeto.

Agora dentro da modelagem que a gente escolheu como framework e o SCRUM, que vai permitir a nossa equipe  (1 desenvolvedor full stack, 1 assurance quality e 1 Product manager ) mesmo que pequena, organizar o trabalho em três sprints cada uma de 15 dias, E acompanhar a evolução do projeto e adaptar o planejamento de acordo com as novas necessidades identificadas durante o desenvolvimento do projeto.

Justificando assim o modelo que não foi escolhido Os outros dois como o Cascata e o creme Mental é porque a gente acabou pressupondo que que tornaria um pouco um pouco mais difícil a questão de de adaptação a mudanças futuras não que não seriam possíveis, porém mais pelo fato da abordagem ágil acabar sendo mais adaptativa. Enquanto há o modelo incremental ele também poderia ser utilizado, porém a gente vê no Scan a maior facilidade para planejar não planejamento mas o gerenciamento da equipe e acompanhamento das atividades.

E justificando mais um pouco a escolha da modelagem e do Scan nós vemos como os novos casos de exigências que surgiram em relação a leis na Prefeitura vai nos permitir organizar melhor as prioridades e atender às mudanças sem necessidade de realizar todo o planejamento novamente.


🔗 [semana4/](semana4/)

---

## 7. Cenário de Mudança

### O cenário recebido

A prefeitura aprovou uma nova lei de mobilidade urbana que exige que empresas de entrega registrem e comprovem o tempo máximo que um entregador permanece em rota contínua, sob pena de multa.

### Tipo de manutenção

O cenário representa uma manutenção adaptativa, pois o sistema precisa ser modificado para atender a uma nova exigência legal externa. Não é corretiva, pois não existe um erro no sistema; nem perfectiva ou preventiva, pois a mudança não surgiu para melhorar ou prevenir problemas, mas para adequar o sistema à nova legislação.

### Análise de impacto

A mudança afeta principalmente os requisitos relacionados às entregas e aos entregadores. Será necessário adicionar uma funcionalidade para registrar o início e o fim da rota, calcular o tempo de permanência e armazenar esses dados para comprovação.
Nos requisitos não funcionais, será necessário garantir a confiabilidade, segurança e integridade dos registros, evitando alterações indevidas.

No diagrama de classes, a classe ENTREGADOR poderá ser relacionada a uma nova classe ROTAENTREGA, contendo informações como horário de início, horário de término e duração da rota.

Nos casos de uso, será necessário adicionar ou adaptar funcionalidades relacionadas ao início, encerramento e consulta das rotas. Os casos de uso de cadastro de cliente, pagamento e cadastro de itens do cardápio não são afetados diretamente.

Nos diagramas de sequência, o fluxo de entrega poderá ser ajustado para registrar automaticamente os horários de início e término da rota. Os diagramas de realizar pedido e cadastrar item não precisam de alterações significativas.

A viabilidade do sistema continua mantida, pois o projeto já previa rastreamento da localização dos entregadores. Será necessário apenas ampliar essa funcionalidade para controlar o tempo de rota.

Por fim, o Scrum continua adequado, pois a nova exigência pode ser adicionada ao Product Backlog e priorizada em uma Sprint, sem necessidade de refazer todo o planejamento.

Assim, a mudança afeta principalmente os requisitos, as funcionalidades de entrega, o diagrama de classes, parte dos casos de uso e o backlog, enquanto outras partes do sistema permanecem inalteradas por não terem relação com a nova exigência.