# controle-de-nivel-de-água
# Simulador de Automação Hidráulica

Este projeto é uma simulação de um sistema hidráulico automatizado que utiliza boias para detectar o nível de água e controlar o registro e a bomba de água. Ele foi desenvolvido em C# e utiliza um loop para simular o comportamento dos sensores em diferentes condições.

## O que foi Utilizado

- **Linguagem de Programação**: C#
- **Bibliotecas/Classes**:
  - `System`: para funcionalidades básicas de input/output e manipulação de strings.
  - `Random`: para gerar números aleatórios e simular o estado das boias.
- **Estruturas de Controle**: `if-else` e `while` para controle de fluxo baseado nas condições dos sensores.
- **Entrada/Saída**: Utilização de `Console.WriteLine` para exibir o estado dos sensores e ações do sistema, e `Console.ReadLine` para capturar a entrada do usuário.

## Etapas Implementadas

1. **Geração de valores aleatórios para simular o estado das boias** (ligadas/desligadas).
2. **Lógica de decisão**:
   - Definição de condições baseadas nos estados das boias para decidir as ações (ligar registro, ligar bomba, detectar erros).
3. **Exibição de mensagens ao usuário**: Exibição de mensagens de estado do sistema e instruções de ações com base nas leituras dos sensores.
4. **Repetição da simulação**: O loop permite que o usuário simule o sistema várias vezes até decidir parar.
## Execução do projeto
<img src=Projeto.png" alt="Print execção">

## Backlog

- **Interface Gráfica**: Substituir a interface de console por uma interface gráfica mais amigável ao usuário.
- **Simulação Visual**: Adicionar elementos gráficos para mostrar o nível de água nos tanques e o funcionamento da bomba e do registro.
- **Integração com Sensores Reais**: Integrar a simulação a sensores físicos para monitorar o nível de água em um sistema real.
- **Relatório de Manutenção**: Criar uma função que gera automaticamente um relatório de manutenção quando há detecção de erro nos sensores.
- **Logs de Sistema**: Adicionar a funcionalidade de gerar logs automáticos de cada simulação, incluindo o estado das boias e as ações tomadas.

## Conclusão

Este projeto é um exemplo prático de como simular a automação de um sistema hidráulico usando sensores de boia. Ele permite entender a lógica de controle de sistemas automatizados em condições de operação normais e de erro. O código pode ser expandido para incluir mais funcionalidades, como a visualização gráfica, integração com sensores físicos e registro de logs para monitoramento mais detalhado.
