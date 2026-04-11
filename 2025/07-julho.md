# Julho 2025

Primeiro mês de trabalho intenso no Brapp.

## Resumo

| Métrica | Valor |
|---------|-------|
| Commits | 45 |
| PRs Merged | 13 |
| Projetos | 2 |

## Projetos

### 1. Brapp Life (Valorare Software)

App de corrida e trilhas.

| Área | Implementações |
|------|----------------|
| Categorias | Implementação nas telas |
| Cidades | JSON com todas as cidades do Brasil |
| Ranking | Validação de tempo, bestTime handling |
| Performance | Carregamento assíncrono, debug logs desativados |
| Busca | Normalização de texto em trilhas e cidades |
| Perfil | Campo categoria obrigatório |
| Mapas | NetworkTileProvider para OSM |
| Firestore | Transações para operações atômicas |
| UX | Bloqueio de navegação durante salvamento |
| Tolerâncias | Sistema dinâmico (20M, 50M) |
| Detalhes | Data/hora e username na tela |

PRs Merged: 13

### 2. AgendaLuz (Projeto Pessoal)

| Campo | Valor |
|-------|-------|
| Repositório | [JCZerf/Agenda_luz_app](https://github.com/JCZerf/Agenda_luz_app) |
| Commits | 2 |

MVP de app de gestão para profissionais autônomos.

| Área | Implementações |
|------|----------------|
| Agenda | Sistema personalizado |
| Financeiro | Módulo básico |
| Clientes | Gestão |
| Notificações | Sistema robusto |

## PRs Merged

```
2025-07-16 | brapp-life#32 | Perf/improve trail loading speed
2025-07-16 | brapp-life#33 | ensure trails are saved only after processing
2025-07-17 | brapp-life#37 | block user from leaving screen before saving
2025-07-21 | brapp-life#43 | Adjust fonts and spacing
2025-07-23 | brapp-life#48 | Adjust/tolerance in meter to 20
2025-07-29 | brapp-life#52 | display message for incomplete lap
2025-07-30 | brapp-life#57 | new tolerance 50M
```

## Stack

- Flutter/Dart
- Firebase/Firestore
- OpenStreetMap
