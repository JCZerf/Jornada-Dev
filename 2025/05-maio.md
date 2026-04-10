# Maio 2025 - Brapp (valoraresoftware)

> Infraestrutura de mapas e Firestore

## SITUAÇÃO

Foco em infraestrutura do projeto: migração de serviço Firestore, melhorias nos mapas com marcadores e atualização de APIs de mapas.

## PRINCIPAIS ENTREGAS

### Infraestrutura Firestore
- Criação de Firestore Service para troca de database
- Backup de indexes do Firestore
- Configuração de database padrão

### Sistema de Mapas
- Marcadores para pontos de início e fim das trilhas
- Atualização do raio do mapa para 20km
- Migração de Map Tiler para ArcGIS
- Limite de maxZoom nos mapas

### Melhorias de Trilhas
- Capitalização de nomes de trilhas e rotas
- Reload de trilhas ao atualizar dados
- Suporte a circuitos e múltiplas voltas no compareGeohashes

### Correções
- Filtro de dados em queries de rankings
- Tratamento de usuário nulo no perfil
- Ajuste de geo query por setores

## COMMITS RELEVANTES

```
2025-05-07 | feat: Update map tiler api key and version
2025-05-09 | fix: Reload trails when update trail data
2025-05-13 | feat: Create firestore service to change database
2025-05-13 | feat: Create indexes backup
2025-05-13 | fix: Change firestore instance to firestore Service
2025-05-15 | fix: add default firestore database
2025-05-16 | feat: Add markers for trail start and end points
2025-05-16 | fix: Update map radius to 20km
2025-05-16 | Update app version to 2.0.3
2025-05-20 | fix: Capitalize trail and route names
2025-05-20 | fix: Update Map Tiler URL to ArcGIS
2025-05-26 | feat: improve compareGeohashesWithTolerance for circuits
2025-05-26 | fix: Add data filtering in rankings query
2025-05-26 | fix: Limit maxZoom in maps
2025-05-27 | update version to 2.0.5
```

## RESULTADO

- Infraestrutura de Firestore modularizada
- Sistema de mapas melhorado com marcadores
- Suporte a múltiplas voltas em trilhas
- App evoluiu para v2.0.5

---

### Stack Técnico
- **Firebase Firestore** - Service pattern, indexes, backup
- **Maps** - ArcGIS, marcadores, geohashes
- **Dart** - Padrões de serviço, queries

### Aprendizados
- Migração de serviços Firebase
- Trabalho com APIs de mapas
- Algoritmos de geohash para trilhas
