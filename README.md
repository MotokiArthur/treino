# Treino ABC

Aplicativo web simples para registrar e acompanhar treinos no esquema **Leg / Push / Pull** (ciclo ABC duplo).

## O que faz

- Navega entre os 6 treinos do ciclo: Leg 1, Push 1, Pull 1 → descanso → Leg 2, Push 2, Pull 2
- Registra **carga e repetições** de duas séries por exercício, com campo de observação
- **Salva automaticamente** o rascunho enquanto você digita (via `localStorage`)
- **Histórico por treino**: salve sessões com data e consulte registros anteriores expandindo/recolhendo
- Funciona como **arquivo local** — basta abrir o `treino.html` no navegador, sem servidor

## Como usar

1. Baixe ou clone o repositório
2. Abra `treino.html` diretamente no navegador
3. Preencha as cargas e repetições
4. Clique em **Salvar treino no histórico** ao terminar

> **iPhone/Safari:** abrir arquivos locais (`file://`) bloqueia o `localStorage` no iOS. Nesse caso, o app funciona durante o uso mas os dados são perdidos ao fechar. Para persistência no iPhone, sirva o arquivo via algum servidor local ou hospede em GitHub Pages.

## Treinos incluídos

| # | Treino | Exercícios |
|---|--------|------------|
| 1 | Leg 1 | Panturrilha, Flexor sentado, Flexor deitado, Agachamento, Extensor, Stiff |
| 2 | Push 1 | Supino inclinado, Supino reto, Crucifixo máquina, Tríceps polia, Desenvolvimento, Elevação lateral halteres |
| 3 | Pull 1 | Remada curvada, Remada baixa triângulo, Remada aberta, Puxada fechada, Rosca scott, Lombar banco |
| 4 | Leg 2 | Panturrilha, Flexor sentado, Agachamento, Leg 45, Abdutor, Stiff |
| 5 | Push 2 | Supino inclinado, Supino declinado, Crucifixo polia baixa, Tríceps francês, Elevação lateral máquina |
| 6 | Pull 2 | Remada curvada, Puxada aberta, Remada triângulo, Puxada fechada, Bíceps no banco 45, Lombar banco |

## Tecnologias

HTML · CSS · JavaScript puro — sem dependências externas.
