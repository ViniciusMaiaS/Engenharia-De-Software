# Estudo de Viabilidade

## Índice

1. [Identificação](#1-identificação)
2. [O Sistema](#2-o-sistema)
3. [Viabilidade Técnica](#3-viabilidade-técnica)
4. [Viabilidade Econômica](#4-viabilidade-econômica)
5. [Viabilidade Operacional](#5-viabilidade-operacional)
6. [Conclusão](#6-conclusão)

---

## 1. Identificação

| Campo | Preencher |
|---|---|
| Grupo | Equipe 3 |
| Integrantes | Vinicius Maia Silva, Yarlei Aguiar, Carlos Italo |
| Disciplina | Engenharia de Software I |
| Semana | 2 |
| Data | 18/09/2026 |

## 2. O Sistema

O aplicativo de delivery de comida caseira possui porte entre pequeno e médio, pois envolve o gerenciamento de clientes, estabelecimentos (Fornecedores de Comida), entregadores, pedidos, pagamentos e entregas.

| ID | Descrição |
|---|---|
| RF-01 | O sistema deve enviar uma notificação ao usuário confirmando o pedido. |
| RF-02 | O sistema deve enviar notificações atualizando o status do pedido. |
| RF-03 | O sistema deve exigir autenticação do usuário/lojista por meio de um email válido. |
| RF-04 | o sistema deve armazenar os dados de cadastro e pagamento do usuário para pedidos futuros. |
| RF-05 | O sistema deverá calcular o frete de acordo com a localidade, limite até 10km. |
| RF-06 | O sistema deverá aceitar a de novos itens ao cardápiod digital. |
| RF-07 | O sistema deverá está em confomidade com a Nota Técnica Decreto nº 35.061/2022,emissão nota fiscal modelo 65. |

| ID | Categoria | Descrição |
|---|---|---|
| RNF-01 | Desempenho | A atualização de localização do entregador no mapa deve ocorrer com latência máxima de 5 segundos. |
| RNF-02 |  |  |
| RNF-03 |  |  |
| RNF-04 |  |  |
| RNF-05 |  |  |
| RNF-06 |  |  |

---

## 3. Viabilidade Técnica

A equipe possui conhecimentos sólidos em desenvolvimento mobile e na construção que cobre a maior parte das necessidades do sistema. O banco de dados e a autenticação não fogem do padrão de mercado.

O principal desafio técnico está ligado ao RNF-01 (rastreamento em tempo real). Essa funcionalidade requer o consumo contínuo e otimizado do GPS dos dispositivos dos entregadores para não drenar as baterias rapidamente. Além disso, a integração com serviços de mapas pode ser complexa.

**Risco identificado:** está ligado ao RF-05 (calcular frete). Essa funcionalidade requer a implementação do google maps para calcular a distância real das ruas, e não a distância em linha reta. 
**Solução:** APIs de geolocalização e roteamento como Google Maps.

## 4. Viabilidade Econômica

_O benefício de construir esse sistema justifica o custo de construí-lo?_

- Quais custos principais o grupo imagina (desenvolvimento, manutenção, infraestrutura)?
- Qual o benefício esperado para quem vai usar ou pagar pelo sistema?
- O benefício parece compensar o investimento?

> _(escrever aqui)_

## 5. Viabilidade Operacional

_O sistema seria de fato aceito e usado pelas pessoas envolvidas, no dia a dia real?_

- Os usuários finais têm familiaridade com esse tipo de sistema, ou vai exigir adaptação grande?
- O sistema muda algum processo atual de um jeito que pode gerar resistência?
- Existe algum grupo de stakeholders que provavelmente vai resistir à mudança? Como lidar com isso?

> _(escrever aqui)_

---

## 6. Conclusão

Marquem uma opção e justifiquem em 2 a 3 frases.

- [ ] Viável
- [ ] Viável com ressalvas
- [ ] Não viável

> _(justificativa aqui)_
