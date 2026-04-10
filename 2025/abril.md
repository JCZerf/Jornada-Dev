# Abril 2025 - Brapp (valoraresoftware)

> Início da contribuição no projeto Brapp

## SITUAÇÃO

Primeiras contribuições no projeto Brapp, focando em melhorias de UI/UX e correções iniciais no sistema de ranking e mapas.

## PRINCIPAIS ENTREGAS

### Melhorias de Interface
- Aumento do tamanho da fonte no MapWidget e MapSearchWidget
- Atualização de estilos de container para melhor visibilidade
- Remoção de data do SlidingBox e RankingWidget

### Sistema de Ranking
- Ajuste de timestamp no ranking de usuários
- Avatar padrão para usuários sem foto
- Correção na verificação de URL de foto do usuário

### Autenticação e Navegação
- Verificação de autenticação antes de criar trilha
- Lógica de navegação para atividades do usuário
- Informações de debug do userID

### Otimização
- Cache de resultados em geo queries
- Processamento otimizado de trilhas

## COMMITS RELEVANTES

```
2025-04-07 | fix: Adjust user timestamp ranking
2025-04-07 | fix: Increase font size in MapWidget and MapSearchWidget
2025-04-07 | fix: Remove date from SlidingBox and RankingWidget
2025-04-07 | fix: Update container styling for better visibility
2025-04-07 | update: Increment version to 2.0.1+40
2025-04-23 | feat: Add authentication check before creating a trail
2025-04-23 | feat: Add default avatar display for users without photo
2025-04-23 | feat: Add navigation logic for user activities
2025-04-23 | feat: Optimize geo query by caching results
2025-04-23 | fix: Fix user photo URL check in avatar display
```

## RESULTADO

- Primeiras contribuições aceitas no projeto
- Melhorias de UX no mapa e ranking
- Otimização de queries de geolocalização
- Familiarização com o codebase

---

### Stack Técnico
- **Flutter** - Widgets de mapa, avatares, navegação
- **Firebase** - Auth, geo queries
- **Dart** - Cache, otimização

### Aprendizados
- Estrutura do projeto Brapp
- Padrões de código da equipe
- Fluxo de trabalho com PRs
