# Junho 2025 - Brapp (valoraresoftware)

> Primeiro mês de estágio - Integração e primeiras funcionalidades

## SITUAÇÃO

Início do estágio na Pluritech com integração ao projeto Brapp (aplicativo mobile Flutter/Firebase para gestão de trilhas e rankings). Necessidade de compreender arquitetura existente e começar a contribuir com funcionalidades reais.

## PRINCIPAIS ENTREGAS

### Sistema de Ranking e Categorias
- Correção de bugs no ranking de usuários
- Implementação de filtros por categoria (Iron, Gold, Silver)
- Sistema de compartilhamento de ranking por categoria
- Captura de tela do ranking usando RepaintBoundary

### Melhorias de Interface
- Botão para retornar à posição atual no mapa
- Scroll automático para trilha selecionada
- Melhorias na sliding-box e ranking widget
- Remoção de SVG, aplicação de PNG no ranking
- Background visual aprimorado

### Validações e Correções
- Correção de bug de tempo "maior" no ranking
- Validação de economia de bateria
- Ajustes na detecção de movimento do dispositivo
- Avisos para usuário na hora de gravar tempo
- Melhoria na comparação de similaridade de trilhas

### Infraestrutura
- Configuração de Firestore instance
- Atualização de Android build tools e Gradle
- Remoção de plataformas não utilizadas (Linux, macOS, Windows)
- Setup de notas para dev database e JDK path

## COMMITS RELEVANTES

```
2025-06-10 | Correção do bug ranking usuario
2025-06-10 | adicao botao retorna a posicao atual e pin
2025-06-13 | Png_print_ranked
2025-06-13 | Create_print_ranking
2025-06-13 | update version to 2.0.7
2025-06-16 | Correção bug tempo "maior"
2025-06-17 | Melhorias na tela printRanked e Sliding_box
2025-06-17 | Alteração da msg compartilhamento
2025-06-17 | Verificação economia de bateria
2025-06-18 | permitir usuario android mudar email
2025-06-18 | Adicionando background svg
2025-06-23 | fix: improve trail similarity comparison and add background SVG asset
2025-06-24 | feat: filtros e categorias no ranking
2025-06-24 | Adicionando trazer a trilha clicando no container, onde exibi o nome da trilha
2025-06-25 | Remoção de SVG, aplicação de PNG no ranking, delay ajustado e remoção de medalhas
2025-06-26 | Adicionado avisos para o usuário na hora de gravar tempo
2025-06-30 | IMPL Print categoria
2025-06-30 | print categoria/arquivo duplicado
2025-06-30 | IMPL compartilhar ranking por categoria
2025-06-30 | IMPL ellipsis na slidingbox e ranking_widget
```

## RESULTADO

- App evoluiu de v2.0.6 para v2.0.11
- Sistema completo de filtros por categoria implementado
- Compartilhamento de ranking funcionando
- Primeira funcionalidade major entregue end-to-end
- Integração completa ao fluxo de desenvolvimento da equipe

---

### Stack Técnico
- **Flutter** - Widgets, setState, RepaintBoundary, captureFromWidget
- **Firestore** - Queries, configuração de instância
- **Dart** - Lógica condicional, manipulação de listas
- **Git/GitHub** - PRs, branching, code review

### Aprendizados
- Fluxo de trabalho profissional com Git/GitHub
- Manipulação de estado em Flutter
- Captura de widgets para compartilhamento
- Importância de validações de UX
