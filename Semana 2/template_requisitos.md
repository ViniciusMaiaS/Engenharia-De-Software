# Documento de Requisitos

> Preencham as seções abaixo transcrevendo a consolidação final dos requisitos discutidos pelo grupo. Usem os IDs (RF-01, RNF-01...) como referência, vocês vão precisar deles de novo mais adiante, na matriz de rastreabilidade.

## Índice

1. [Identificação](#1-identificação)
2. [O Sistema](#2-o-sistema)
3. [Requisitos Funcionais](#3-requisitos-funcionais)
4. [Requisitos Não-Funcionais](#4-requisitos-não-funcionais)
5. [Requisitos Relacionados](#5-requisitos-relacionados)

---

## 1. Identificação

| Campo | Preencher |
|---|---|
| Grupo | Equipe 03 |
| Integrantes | Vinicius Maia Silva , Yarley Aguiar de Sousa , Carlos Italo | 
| Disciplina | Engenharia de Software I |
| Semana | 2 |
| Data | 16 /09/2026 |

## 2. O Sistema

 aplicativo de delivery de comida caseira possui porte entre pequeno e médio, pois envolve o gerenciamento de clientes, estabelecimentos (Fornecedores de Comida), entregadores, pedidos, pagamentos e entregas.

## 3. Requisitos Funcionais

| ID | Descrição |
|---|---|
| RF-01 | O sistema deve enviar uma notificação ao usuário confirmando o pedido.|
| RF-02 | O sistema deve enviar notificações atualizando o status do pedido.|
| RF-03 | O sistema deve  exigir autenticação do usuário/lojista por meio de um email válido.|
| RF-04 | o sistema deve armazenar os dados de cadastro e pagamento do usuário para pedidos futuros.|
| RF-05 | O sistema deverá calcular o frete de acordo com a localidade, limite até 10km.|
| RF-06 | O sistema deverá aceitar a  de novos itens ao cardápiod digital.|
| RF-07 | O sistema deverá está em confomidade com a Nota Técnica Decreto nº 35.061/2022,emissão nota fiscal modelo 65.|

## 4. Requisitos Não-Funcionais

| ID | Categoria | Descrição |
|---|---|---|
| RNF-01 | Desempenho | A atualização de localização do entregador no mapa deve ocorrer com latência máxima de 5 segundos. |
| RNF-02 | | |
| RNF-03 | | |
| RNF-04 | | |
| RNF-05 | | |
| RNF-06 | | |

**Categorias possíveis:** Desempenho · Confiabilidade · Usabilidade · Segurança · Manutenibilidade · Portabilidade

<!--
Exemplo de como preencher (apagar esta linha e o exemplo abaixo depois):
RNF-01 | Desempenho | A confirmação da reserva deve ser processada em no máximo três segundos, mesmo em horário de pico.
-->

---

## 5. Requisitos Relacionados

Indiquem, quando fizer sentido, qual requisito não-funcional qualifica qual requisito funcional (nem todo RNF precisa estar amarrado a um único RF, alguns se aplicam ao sistema como um todo).

| RF | RNF relacionado(s) |
|---|---|
| RF-01 | |
| RF-02 | |

---

### Checklist antes de entregar

- [ ] Cada requisito é **verificável** (dá pra testar se foi atendido ou não)
- [ ] Cada requisito é **não ambíguo** (só uma leitura possível)
- [ ] Cada requisito é **atômico** (descreve uma coisa só)
- [ ] Nenhum requisito descreve uma **solução de projeto** (tecnologia, banco de dados, biblioteca específica)

