# Abril 2026 - AgendaLuz + VivaFit

> Evolução do projeto pessoal e continuação do projeto acadêmico

## SITUAÇÃO

Retomada do projeto AgendaLuz com foco em melhorias de UX e dashboard financeiro. Continuação do projeto VivaFit da PUC Minas com arquitetura e documentação.

## PRINCIPAIS ENTREGAS

### AgendaLuz - Dashboard Financeiro
- Implementação de tela de dashboard financeiro
- Integração de estatísticas financeiras
- Visualização de dados de faturamento

### AgendaLuz - Gestão de Clientes
- Busca do próximo agendamento do cliente
- Exibição do último atendimento realizado
- Tags de clientes na interface
- Modal de detalhes do cliente com layout melhorado
- Info cards substituindo detail rows
- Draggable scrollable sheet para melhor navegação

### AgendaLuz - Melhorias de Interface
- Refatoração da app bar na AgendaScreen
- Background gradiente para melhor visual
- Reorganização de elementos para acessibilidade
- Seleção de mês/ano com dropdowns
- Refatoração de cores usando AppColors utility class

### VivaFit (PUC Minas)
- Atualização de imagens BPMN
- Modelo ER documentado
- Arquitetura da solução definida
- Refatoração de código para legibilidade

## COMMITS AgendaLuz

```
2026-04-10 | Add financial dashboard screen and integrate financial statistics retrieval
2026-04-10 | Add functionality to fetch the next scheduled appointment for a client and update UI accordingly
2026-04-10 | Add functionality to fetch the last completed appointment for a client and update client tag display in the UI
2026-04-10 | Refactor client details modal to improve layout and usability, replacing detail rows with info cards and adding a draggable scrollable sheet.
2026-04-10 | Refactor app bar in AgendaScreen to enhance layout and usability, introducing a gradient background and reorganizing elements for better accessibility.
2026-04-10 | Refactor date selection in Agenda and Atendimentos screens to use month/year dropdowns
2026-04-10 | Refactor color usage across screens to utilize AppColors utility class
2026-04-10 | Refactor backup service to use debugPrint for error logging and improve backup process flow
```

## COMMITS VivaFit

```
2026-04-04 | Remove Lucidchart links for BPMN processes to streamline documentation
2026-04-04 | Update BPMN process images for improved clarity
2026-04-04 | Update ER model description and links for clarity and accuracy
2026-04-04 | Update ER model image
2026-04-04 | Update ER model image link in documentation
2026-04-04 | Update 05-Arquitetura da Solução.md
2026-04-04 | Refactor code structure for improved readability and maintainability
```

## PRs RELEVANTES

```
2026-04-10 | JCZerf/Agenda_luz_app#1 | Refactor UI components and enhance appointment and financial features
```

## RESULTADO

- Dashboard financeiro funcional no AgendaLuz
- Gestão de clientes mais completa
- Interface mais moderna e acessível
- VivaFit com arquitetura e documentação atualizadas
- Projetos acadêmico e pessoal em paralelo

---

### Stack Técnico
- **Flutter** - Draggable sheets, gradients, custom widgets
- **Dart** - Utility classes, async data fetching
- **BPMN** - Processos de negócio
- **UI/UX** - Info cards, dropdowns, acessibilidade
- Padrões de UX para apps de gestão
- Implementação de dashboards financeiros
- Draggable scrollable sheets para mobile
