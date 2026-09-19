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

O sistema ele acaba se tornando viável porque no dia a dia na rotina de todos os digamos assim os usuários desse tipo de aplicativo de delivery, ele funciona diariamente e reduz bem assim a necessidade de Treinamento até mesmo para utilização da plataforma então ele é muito viado pela tratamento pela alta usabilidade que ele tem 

Esse nosso tipo de sistema é os clientes usuários clientes poderão realizar pedidos poderá acompanhar a sua entrega é receber notificação do status das do seu das suas compras idêntico ao que acontece já no seu aplicativo conhecidos do mercado Além do mais o segundo tipo de usuário os Lojistas ou estabelecimento também poderão gerenciar seus cardápios e pedidos de maneira centralizada 

É alguns requisitos funcionais que especificamos aqui como o 01 e 02 eles vão até auxiliar na comunicação que os usuários tem com sua com sua entrega durante o processo né e o 06, queremos dizer que ele vai acabar facilitando principalmente a atualização de produtos disponíveis evitando que sejam feito é pedidos para produtos desatualizados é dessa forma não nesta dessa forma e peso que já foi comentado da grande usabilidade que tem o sistema cremos que clientes e fornecedores e nem mesmo os entregadores terão problema em não saber utilizar o sistema.

Como todo o grande app de delivery a gente sabe que pode enfrentar sim desafios operacionais né como por exemplo dificuldade um fornecedor mesmo que somente Inicial na utilização da sociedade até mesmo do não sei do próprio do próprio entregador também mas é assim que a gente vai procurar mitigar isso e reduzir a bem próximo de zero com uma  interface simples e intuitiva e que tenha já algo parecido no mercado para utilizar a questão do que os clientes de pedido fornecedores também entregadores  já estão acostumados


## 6. Conclusão

Marquem uma opção e justifiquem em 2 a 3 frases.

- [ ] Viável
- [ ] Viável com ressalvas
- [ ] Não viável

> _(justificativa aqui)_
